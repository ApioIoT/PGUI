## Required Variables

| Parameter Name | Description | Default Value |
| -------------- | ----------- | ------------- |
| POD            | Point Of Delivery identifier | Defaults to the PGUI serial |
| SERIAL            | Device Serial | - |
| BAL_DEVICE_ID  | Id of the device in the BAL platform | Defaults to the PGUI serial |
| BAL_API_URL | Base URL of the BAL API (or the proxy/load balancer if present). | - |
| BAL_BROKER_URL | Base URL of the BAL MQTT Broker (or the proxy/load balancer if present). | - |
| BAL_BROKER_USERNAME | MQTT Username | - |
| BAL_BROKER_PASSWORD | MQTT Password | - |
| DSOTP_BROKER_URL | Base URL of the BAL MQTT Broker (or the proxy/load balancer if present). | - |
| DSOTP_BROKER_USERNAME | MQTT Username | - |
| DSOTP_BROKER_PASSWORD | MQTT Password | - |


## Optional Variables

| Parameter Name | Description | Default Value |
| -------------- | ----------- | ------------- |
| METER_TRANSFORMATION_CONSTANT            | Meter transformation constant | 1 |
| METER_PULSE_COUNTER_CONSTANT            | Number of impulses of the pulse counters per kWh or kVarh | 1 |
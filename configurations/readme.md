# Configurations
All the workload configuration files will be placed here within the folder structure as shown below. The configuration files are in JSON format. The configuration files are used to define the workload and the parameters to be used for the workload. The YAML files are used to craete the pipelines for the resource deployment.

## Folder Structure
configurations
│
│- workload 1
│  │─ hub
│  │  ├─ weu-p1-01
│  │  ├─ virtualnetwork.parameters.json
│  │  └─ vnc.parameters.azuredeploy.json
│  └─ hub.yml
│
│- workload 2
│  │─ hub
│  │  ├─ weu-p1-01
│  │  ├─ virtualnetwork.parameters.json
│  │  └─ vnc.parameters.azuredeploy.json
│  │─ hub.yml
│  │
│  │─ app
│  │  ├─ weu-p1-01
│  │  ├─ app.bicep
│  │  └─ app.vm.parameters.azuredeploy.json
│  └─ app.yml
│
# Configurando uma instância de Banco de Dados na Azure

![GitHub](https://img.shields.io/github/license/Paucinha/api-ecommerce-dio?style=flat-square)

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, os diferentes tipos de serviços oferecidos pela nuvem:

- Descrever a IaaS, PaaS, SaaS
  
- Modelo de responsabilidade compartilhada.
  
- Identificar os casos de uso apropriados para cada serviço de nuvem (IaaS, PaaS e SaaS).

**Azure | Full-Stack | Básico**

- [Configuranção uma instância de Banco de Dados na Azure](https://portal.azure.com/#browse/Microsoft.Sql%2Fservers%2Fdatabases)

```json
{
    "sku": {
        "name": "GP_Gen5",
        "tier": "GeneralPurpose",
        "family": "Gen5",
        "capacity": 2
    },
    "kind": "v12.0,user,vcore",
    "properties": {
        "collation": "SQL_Latin1_General_CP1_CI_AS",
        "maxSizeBytes": 34359738368,
        "status": "Online",
        "databaseId": "2fc646e9-0bc7-4a15-82b1-bd9f67ac6c8e",
        "creationDate": "2025-02-19T21:48:22.197Z",
        "currentServiceObjectiveName": "GP_Gen5_2",
        "requestedServiceObjectiveName": "GP_Gen5_2",
        "defaultSecondaryLocation": "westus",
        "catalogCollation": "SQL_Latin1_General_CP1_CI_AS",
        "zoneRedundant": false,
        "licenseType": "LicenseIncluded",
        "maxLogSizeBytes": 193273528320,
        "readScale": "Disabled",
        "currentSku": {
            "name": "GP_Gen5",
            "tier": "GeneralPurpose",
            "family": "Gen5",
            "capacity": 2
        },
        "currentBackupStorageRedundancy": "Geo",
        "requestedBackupStorageRedundancy": "Geo",
        "maintenanceConfigurationId": "/subscriptions/f5f6088e-679a-4fc3-9a5d-600dcca616e6/providers/Microsoft.Maintenance/publicMaintenanceConfigurations/SQL_Default",
        "isLedgerOn": false,
        "isInfraEncryptionEnabled": false,
        "availabilityZone": "NoPreference"
    },
    "location": "eastus",
    "tags": {},
    "id": "/subscriptions/f5f6088e-679a-4fc3-9a5d-600dcca616e6/resourceGroups/my-Vm-1_group/providers/Microsoft.Sql/servers/testsqlp/databases/mysqlteste",
    "name": "mysqlteste",
    "type": "Microsoft.Sql/servers/databases",
    "apiVersion": "2022-11-01-preview"
}
```

##

Projeto desenvolvido durante o [**Bootcamp Bradesco - Java Cloud Native**](https://www.dio.me/bootcamp/bradesco-java-cloud-native), fornecido pela [**DIO**](https://www.dio.me/)

##

- [By Páucinha](https://github.com/Paucinha)

# VIAA Domain
## About
This domain project can be used in other applications to share resources across applications. The documentation on a domain project can be found [here](https://docs.mulesoft.com/mule-user-guide/v/3.7/shared-resources).

## Properties naming convention
Property names should all be in the following format:

`domain.{type}.{resource}.{property}`

An example of this would be:

`domain.database.mediahaven_snapshot_prd.host`

Where 'domain' is static, to avoid conflicting with applications.

## Included connectors
The following connectors can be referenced when using the VIAA Domain:

| Type | Name | Description |
| - | - | - |
| Database | MAM_Snapshot | The Mediahaven Snapshot database | 

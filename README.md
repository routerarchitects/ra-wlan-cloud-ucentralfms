<p align="center">
    <img src="images/project/logo.svg" width="200"/>
</p>

# uCentralFMS

## What is this?
The uCentralFMS(owfms) is a micro-service part of the OpenWiFi ecosystem. uCentralFMS is a Firmware Management Service
to facilitate the task of upgrade and maintaining the proper firmware for all the devices 
used in your OpenWiFi solution. You may either [build it](#building) or use the [Docker version](#docker).

## OpenAPI
You may get static page with OpenAPI docs generated from the definition on [GitHub Page](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms).
Also, you may use [Swagger UI](https://petstore.swagger.io/#/) with OpenAPI definition file link (i.e. [latest version file](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms/blob/main/openapi/owfms.yaml)) to get interactive docs page.

## Building
To build the microservice from source, please follow the instructions in [here](./BUILDING.md)

## Docker
To use the CLoudSDK deployment please follow [here](https://github.com/routerarchitects/mango-cloud-deployment)

## Firewall Considerations
| Port  | Description                                   | Configurable |
|:------|:----------------------------------------------|:------------:|
| 16003 | Default port for REST API Access to the OWFMS |     yes      |

### OWFMS Service Configuration
The configuration is kept in a file called `owfms.properties`. To understand the content of this file,
please look [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms/blob/main/CONFIGURATION.md)

## Kafka topics
Toe read more about Kafka, follow the [document](https://github.com/routerarchitects/ra-wlan-cloud-ucentralgw/blob/main/KAFKA.md)

## Contributions
We need more contributors. Should you wish to contribute,
please follow the [contributions](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms/blob/master/CONTRIBUTING.md) document.

## Pull Requests
Please create a branch with the Jira addressing the issue you are fixing or the feature you are implementing.
Create a pull-request from the branch into master.

## Additional OWSDK Microservices
Here is a list of additional OWSDK microservices
| Name | Description | Link | OpenAPI |
| :--- | :--- | :---: | :---: |
| OWSEC | Security Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralsec) | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralsec/blob/main/openpapi/owsec.yaml) |
| OWGW | Controller Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralgw) | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralgw/blob/master/openapi/owgw.yaml) |
| OWFMS | Firmware Management Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms) | [here](https://github.com/routerarchitects/ra-wlan-cloud-ucentralfms/blob/main/openapi/owfms.yaml) |
| OWPROV | Provisioning Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-owprov) | [here](https://github.com/routerarchitects/ra-wlan-cloud-owprov/blob/main/openapi/owprov.yaml) |
| OWANALYTICS | Analytics Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-analytics) | [here](https://github.com/routerarchitects/ra-wlan-cloud-analytics/blob/main/openapi/owanalytics.yaml) |
| OWSUB | Subscriber Service | [here](https://github.com/routerarchitects/ra-wlan-cloud-userportal) | [here](https://github.com/routerarchitects/ra-wlan-cloud-userportal/blob/main/openapi/userportal.yaml) |
| NW-Topology | Network Topology Service | [here](https://github.com/routerarchitects/ra-openlan-nw-topology) | [here](https://github.com/routerarchitects/ra-openlan-nw-topology/blob/main/openapi/nwtopology.yaml) |
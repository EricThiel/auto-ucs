# auto-ucs

Automation management of UCS devices through UCS-M without requiring in-band connections


## Business/Technical Challenge

Today using UCSM to manage servers requires that FIs be in the data path for servers. For a number of reasons, including additional points of failure, additional bottlenecks, and additional expense, many customers do not wish to inject the FIs directly into the data plane, but would still like to leverage the management plane it offers. For those customers, Intersight does not yet offer the full suite of features, nor an on-prem capability. 

## Proposed Solution


This solution aims to migrate configuration from UCS Manager (e.g. service profiles) to IMC Supervisor and applies those configurations to UCS-C series. The solution will allow for creation and management of service profiles via UCSM, while servers can be connected directly to Nexus switches or ACI fabrics. Once connected, the solution will auto-discuver the UCS and use IMC-Supervisor to push the service profile attributes down to each server. 


### Cisco Products Technologies/ Services

Our solution will levegerage the following Cisco technologies

* UCS
* IMC-Supervisor
* [Application Centric Infrastructure (ACI)](http://cisco.com/go/aci)
* NX-OS


## Team Members


* Eric Thiel <erthiel@cisco.com> - GES West
* Santiago Flores Kanter <sfloresk@cisco.com> - Service Provider


## Solution Components


<!-- This does not need to be completed during the initial submission phase  

Provide a brief overview of the components involved with this project. e.g Python /  -->


## Usage

<!-- This does not need to be completed during the initial submission phase  

Provide a brief overview of how to use the solution  -->



## Installation

How to install or setup the project for use.


## Documentation

Pointer to reference documentation for this project.


## License

Provided under Cisco Sample Code License, for details see [LICENSE](./LICENSE.md)

## Code of Conduct

Our code of conduct is available [here](./CODE_OF_CONDUCT.md)

## Contributing

See our contributing guidelines [here](./CONTRIBUTING.md)

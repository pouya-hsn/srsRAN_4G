# srsRAN_4G — NTN Network Development

## Overview

This repository is a customized fork of [srsRAN_4G](https://github.com/srsran/srsRAN_4G), intended for research, development, and experimentation toward the implementation and deployment of **Non-Terrestrial Networks (NTN)**.

The project aims to explore the adaptation and extension of the existing LTE software radio stack to support NTN-related use cases, with a focus on satellite-based communication scenarios, software-defined radio (SDR) platforms, and experimental cellular network deployments.

This repository also serves as a development workspace for documenting implementation details, configuration procedures, software modifications, and experimental results throughout the project.

## Project Objectives

- Investigate the feasibility of using srsRAN_4G as a foundation for NTN-related network development.
- Explore the modifications required to support satellite communication scenarios and NTN-specific network characteristics.
- Evaluate SDR-based implementations using compatible radio hardware, including USRP devices.
- Study the impact of propagation delay, Doppler frequency shifts, and other satellite channel characteristics on LTE communication.
- Develop, test, and document custom features and modifications to the existing srsRAN_4G codebase.
- Maintain reproducible build procedures, configuration guides, and experimental test results.

## Development Scope

Development activities may include the following areas:

- **LTE Protocol Stack:** Analysis and modification of relevant LTE protocol and radio access network components.
- **NTN Adaptation:** Investigation of the changes required to accommodate satellite link characteristics and NTN-related operating conditions.
- **SDR Integration:** Configuration and evaluation of software-defined radio hardware for experimental network deployments.
- **System Configuration:** Development and documentation of network configurations, deployment procedures, and test scenarios.
- **Testing and Validation:** Evaluation of system behavior through controlled experiments, measurements, and performance analysis.

The actual implementation scope will evolve as development progresses. NTN-specific capabilities are considered development objectives and should not be assumed to be supported until they have been implemented and validated.

## Documentation

Project documentation is maintained alongside the source code to support reproducibility and long-term development.

Documentation may cover:

- Installation and build instructions
- Software and hardware configuration
- Source code architecture and modification notes
- NTN-related implementation approaches
- Experimental procedures and test results
- Known limitations and troubleshooting

Refer to the `docs/` directory for project-specific documentation as it becomes available.

## Hardware and Software Environment

The development environment may include:

- **Software:** srsRAN_4G, UHD, and supporting development tools
- **Operating System:** Ubuntu Linux
- **Radio Hardware:** Compatible USRP devices and other supported SDR platforms
- **Development Tools:** C/C++, CMake, Git, and related debugging and testing utilities

Specific hardware requirements and software versions will be documented as the implementation and testing environment is established.

## Project Status

**Status: Research and Development**

This repository is an experimental development fork. NTN-related features, architectural changes, and deployment procedures are subject to ongoing investigation, implementation, and validation.

The presence of a development objective does not imply that the corresponding feature is already implemented or operational.

## Upstream Project

This project builds upon the open-source [srsRAN_4G](https://github.com/srsran/srsRAN_4G) project.

The upstream repository is maintained by the srsRAN community. This fork is intended for project-specific research, development, experimentation, and documentation.

## License

This repository is derived from srsRAN_4G and is subject to the applicable upstream licensing terms, including the GNU Affero General Public License v3.0 (AGPL-3.0).

Refer to the original repository and the license files included in this repository for the applicable licensing requirements.

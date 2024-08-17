# Prometheus-X Reference Models

Welcome to the Prometheus-X Reference Models repository! This repository serves as a documentation resource for reference models used in Prometheus-X catalogs. These reference models include Roles, Obligations, and other standard models defined in JSON-LD format.

## Overview

Prometheus-X reference models provide a common foundation for Prometheus-X catalogs, ensuring consistency and interoperability across different catalog instances.

The reference models in this repository ([located here](./src/references/)) are designed to be synchronized across all Prometheus-X catalogs. By adopting these reference models, organizations can leverage predefined roles, obligations, and other models to streamline their processes and improve compatibility with other Prometheus-X deployments.

### Rule templates

Rules templates are ODRL representations of supported policies in the Prometheus-X ecosystem. They are not filled in with values and declare required fields in order to be completed when being used to negotiate or generate contracts. 

Currently supported policies are

|Policy|Used Reference|Description|
| -- | -- | -- |
| `no-restriction` | [IDS: Allow the Usage of the Data](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows the usage of data or services without any restriction.|
| `time-interval` | [IDS: Interval-restricted Data Usage](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows data or service usage within a specified time interval |
| `time-period` | [IDS: Duration-restricted Data Usage](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows data or service usage for a specified time period |
| `count` | [IDS: Restricted Number of Usages](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows data or service usage for `n` times. |
| `time-interval-deletion` | [IDS: Use Data and Delete it After](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows data and service usage within a specified time interval with the restriction to delete it at a specified time stamp. |
| `notification-message` | [IDS: Remote Notifications](https://international-data-spaces-association.github.io/DataspaceConnector/Documentation/v5/UsageControl) | Allows data usage with notification message.

> Note: These templates do not come from any standard as at the time of writing, there doesn't seem to exist any ODRL templating engine available.

## Usage

To use the reference models in this repository, follow these steps:

1. Clone the repository to your local machine using `git clone`.

2. Copy the desired JSON-LD files into your Prometheus-X catalog repository or import them into your Prometheus-X instance.

3. Keep track of updates to the reference models in this repository. As improvements or new versions become available, you can pull the changes to ensure your catalogs are up to date.

## Contributing

We welcome contributions to the Prometheus-X Reference Models repository. If you have suggestions, improvements, or new models to propose, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

The content of this repository is licensed under the [MIT License](LICENSE). By using the reference models provided here, you agree to comply with the terms and conditions of this license.

## Contact

If you have any questions or need support related to Prometheus-X Reference Models, please feel free to contact us by opening an issue in this repository.

Thank you for your interest in Prometheus-X Reference Models. We hope these models serve as a valuable resource in your catalog management efforts.

# Prometheus-X Reference Models

Welcome to the Prometheus-X Reference Models repository! This repository serves as a documentation resource for standard models used in Prometheus-X catalogs. These standard models include Roles, Obligations, and other standard models defined in JSON-LD format.

## Overview

Prometheus-X Standard models provide a common foundation for Prometheus-X catalogs, ensuring consistency and interoperability across different catalog instances.

The standard models in this repository are designed to be synchronized across all Prometheus-X catalogs. By adopting these standard models, organizations can leverage predefined roles, obligations, and other models to streamline their processes and improve compatibility with other Prometheus-X deployments.

The repository also lists examples of Catalog Self-Descriptions described based on the work of Gaia-X, and following the DCAT v3 ontology of describing catalog resources.

## Usage

To use the standard models in this repository, follow these steps:

1. Clone the repository to your local machine using `git clone`.

2. Copy the desired JSON-LD files into your Prometheus-X catalog repository or import them into your Prometheus-X instance.

3. Keep track of updates to the standard models in this repository. As improvements or new versions become available, you can pull the changes to ensure your catalogs are up to date.

## Used Ontology

### Catalog

Catalog resources Self Descriptions such as [Datasets](./src/self-description-examples/dataset.json), [Services](./src/self-description-examples/service.json), [Ecosystems](./src/self-description-examples/ecosystem.json) and [Providers](./src/self-description-examples/provider.json) try to follow the dcat ontology along with some relevant ontologies such as `gax-core` for resource providers, `ordl` for policies, `schema.org` for some more regular fields etc.

We tried to make reference examples of these assets while following these ontology standards. Since a lot of the work we based ourselves on is still a work in progress, examples are subject to change. However, these initial examples should represent a foundation for starting implementation in catalog instances.

## Contributing

We welcome contributions to the Prometheus-X Standard Models repository. If you have suggestions, improvements, or new models to propose, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

The content of this repository is licensed under the [MIT License](LICENSE). By using the standard models provided here, you agree to comply with the terms and conditions of this license.

## Contact

If you have any questions or need support related to Prometheus-X Standard Models, please feel free to contact us by opening an issue in this repository.

Thank you for your interest in Prometheus-X Standard Models. We hope these models serve as a valuable resource in your catalog management efforts.

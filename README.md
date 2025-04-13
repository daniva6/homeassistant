# Deploy firefly-iii on k8s with Kustomize and ArgoCD 

## Description

Deploy homeassistant on k8s with Kustomize and ArgoCD.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributions](#contributions)
- [Tests](#tests)
- [Questions](#questions)
## Installation

Dependencies:
- k8s cluster
- traefik v3 for ingress
- Hashicorp vault (optional)
- ArgoCD (optional)

Deployment with Argo CD and Hashicorp:
- apdapt the maifests to your needs
- create a argoproj.io Application with your parameters, a sample you'll find in the overlays (dev or prod) folder
- apply the Application with kubectl apply -f <application.yaml>

Deployment with Kustomize:
- in the folder overlays/dev and overlays/prod you'll find a kustomization.yaml file 
- you can apply it with kubectl apply -k overlays/dev

## Usage

Enter the url in your favorite browser.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License](https://opensource.org/licenses/MIT)

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contributions



## Tests



## Questions

For additional questions, contact [daniva6](https://github.com/daniva6) 

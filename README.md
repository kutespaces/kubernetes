# Kutespace: Kubernetes

Welcome to Kutespace's Kubernetes repository! This guide will help you spin up a fully preconfigured learning environment to get you started with your Kubernetes journey.

## Why Kubernetes?

"Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available." (Ref: Kubernetes.io)

"Kubernetes is a super elegant given its power. I assume it will stick around for a long time. Nowadays a lot of software is shipped as containers and you gotta run it. Kubernetes is easier to use than CaaS solutions such as Amazon Elastic Container Service or Azure Container Apps because Kubernetes tooling is widely available to simplify your life." - Nico Duldhardt.

More information:
- [Kubernetes Docs](https://kubernetes.io/docs/home/)

## Learning Outcomes

As you embark on these exercises, you're set to learn key practices in modern application deployment and management. Here's what you'll achieve by the end of this guide:

- **Core Concepts**: Understand the Kubernetes API primitives, clusters, and the command-line interface (kubectl) to interact with clusters.
- **Helm**: Manage Kubernetes applications with Helm charts, including chart creation, chart repository management, and release upgrading/rollback.

## Getting Started

To begin, [launch a new Codespace using the default settings.](https://codespaces.new/kutespaces/argocd)

Running this Codespace in the browser will not work. As soon as the code space is ready, launch it in your local VS Code Desktop.
To do so extend the menu in the left upper corner and select `Open in VS Code Desktop`.

<img src='docs/images/start-codespace-vscode.jpg' width='50%'>

## Exercises

Exercises are updated daily from [dgkanatsios/ckad-exercises](https://github.com/dgkanatsios/ckad-exercises).


1. [Core Concepts](exercises/a.core_concepts.md)
2. [Multi-container pods](exercises/b.multi_container_pods.md)
3. [Pod design](exercises/c.pod_design.md)
4. [Configuration](exercises/d.configuration.md)
5. [Observability](exercises/e.observability.md)
6. [Services and networking](exercises/f.services.md)
7. [State persistence](exercises/g.state.md)
8. [Helm](exercises/h.helm.md)
9. [Custom Resource Definitions](exercises/i.crd.md)

### Congratulations!

Congratulations on completing the exercises! You've successfully navigated through a series of tasks that have introduced you to Kubernetes and prepared you for the CKAD exam. 

## What's next

- Check out [killer.sh](https://killer.sh/) for a CKAD exam simulation.
- Check out [omerbsezer/Fast-Kubernetes](https://github.com/omerbsezer/Fast-Kubernetes) for more exercises that can be executed in this environment.

## Troubleshooting

Encountering issues? Let us know to assist you and others who may face similar challenges.



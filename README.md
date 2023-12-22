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

To begin, [launch a new Codespace using the default settings.](https://codespaces.new/kutespaces/kubernetes)

Running this Codespace in the browser will not work. As soon as the code space is ready, launch it in your local VS Code Desktop.
To do so extend the menu in the left upper corner and select `Open in VS Code Desktop`. You can also configure VS Code Desktop as your default in [settings/codespaces](https://github.com/settings/codespaces).

<img src='docs/images/start-codespace-vscode.jpg' width='50%'>

To properly view the rendered README either view it in your browser or open the Command Palette (Ctrl+Shift+P) and select `Markdown: Open Preview`.

## Exercises

Run the following exercises in your Codespace's terminal.
Verify that the setup works by executing `kubectl get nodes` first.
The output should show a single node in your cluster.

1. [Core Concepts](exercises/a.core_concepts.md)
2. [Multi-container pods](exercises/b.multi_container_pods.md)
3. [Pod design](exercises/c.pod_design.md)
4. [Configuration](exercises/d.configuration.md)
5. [Observability](exercises/e.observability.md)
6. [Services and networking](exercises/f.services.md)
7. [State persistence](exercises/g.state.md)
8. [Helm](exercises/h.helm.md)
9. [Custom Resource Definitions](exercises/i.crd.md)

Exercises are updated daily from [dgkanatsios/ckad-exercises](https://github.com/dgkanatsios/ckad-exercises) 🙏

### Congratulations!

Congratulations on completing the exercises! You're now one step closer to achieving your CKAD certification, having gained valuable hands-on experience with Kubernetes.

## What's next

- Check out [killer.sh](https://killer.sh/) for a CKAD exam simulation.
- Check out [omerbsezer/Fast-Kubernetes](https://github.com/omerbsezer/Fast-Kubernetes) for more exercises that can be executed in this environment.
- Check out [kutespaces/argocd](https://github.com/kutespaces/argocd) to learn how to properly deploy applications to Kubernetes.

## Troubleshooting

Encountering issues? Let us know to assist you and others who may face similar challenges.

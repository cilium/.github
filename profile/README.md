## Hey, this is Cilium 🐝🐝🐝

[![Our](https://img.shields.io/static/v1?label=Our&message=Website&color=blue)](https://cilium.io/)
[![Sign-up](https://img.shields.io/static/v1?label=Sign-up&message=for%20news&color=red)](https://cilium.io/newsletter)
[![Contributing](https://img.shields.io/static/v1?label=Contributing&message=Guide&color=brightgreen)](https://cilium.io/get-involved)
[![Roadmap](https://img.shields.io/static/v1?label=Roadmap&message=public&color=blueviolet)](https://docs.cilium.io/en/latest/community/roadmap/)
[![Governance](https://img.shields.io/static/v1?label=Governance&message=and%20Maintainers&color=yellow)](https://docs.cilium.io/en/stable/contributing/governance/)



[Cilium](https://cilium.io/) is an open source software for providing, securing and observing network connectivity between container workloads - cloud native, and fueled by the revolutionary Kernel technology [eBPF](https://ebpf.io/). Cillium provides eBPF-based Networking, Observability, and Security.

### Cilium

Cilium is used to provide and transparently secure network connectivity and load balancing between application workloads such as application containers, processes, or VMs. Cilium operates at Layer 3/4 to provide traditional networking and security services as well as Layer 7 to protect and secure use of modern application protocols such as HTTP, gRPC, and Kafka. Cilium is a part of the [Cloud Native Computing Foundation](https://www.cncf.io/) and is their most advanced and widely used CNI for Kubernetes. Check out the [Getting Started Guides](https://docs.cilium.io/en/stable/gettingstarted/) to try it out.

Cilium has hundreds of [adopters](https://cilium.io/adopters) around the world including Bell Canada, Capital One, Google, The New York Times, and Yahoo. If you are using Cilium, [add yourself](https://github.com/cilium/cilium/blob/master/USERS.md) to the list today!

<img src="https://camo.githubusercontent.com/714c5d777b0025dda66b46f14e28badc01e3e3360ef264be204f54846a7c9573/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f63696c69756d2f63696c69756d406d61737465722f446f63756d656e746174696f6e2f696d616765732f63696c69756d5f6f766572766965772e706e67" alt="Cilium overview diagram" width="800">

### Hubble

[Hubble](https://github.com/cilium/hubble) is a fully distributed networking and security observability platform for cloud native workloads. It is built on top of [Cilium](https://github.com/cilium/cilium) and [eBPF](https://ebpf.io/) to enable deep visibility into the communication and behavior of services as well as the networking infrastructure in a completely transparent manner. Hubble helps teams understand service dependencies and communication maps, operational monitoring and alerting, application monitoring, and security observability.

<img src="https://github.com/cilium/hubble/raw/master/Documentation/images/hubble_arch.png" alt="Hubble overview diagram" width="800">

### Tetragon

[Tetragon](https://github.com/cilium/tetragon) enables powerful realtime, eBPF-based Security Observability and Runtime Enforcement. Tetragon detects and is able to react to security-significant events, such as:



* Process execution events
* System call activity
* I/O activity including network & file access

When used in a Kubernetes environment, Tetragon is Kubernetes-aware - that is, it understands Kubernetes identities such as namespaces and pods - so that security event detection can be configured for specific individual workloads.

<img src="https://github.com/cilium/tetragon/raw/main/docs/images/smart_observability.png" alt="Tetragon Overview Diagram" width="800">

### Community

Cilium is an open source project that anyone in the community can use, improve, and enjoy. Over 400 people have already contributed to the Cilium project and [you can too](https://docs.cilium.io/en/stable/contributing/development/contributing_guide/). We'd love you to join us! Here's a few ways to find out what's happening and get involved:

Join the [Cilium workspace on Slack](https://cilium.herokuapp.com/)

Follow [Cilium on Twitter](https://twitter.com/ciliumproject?lang=de)

Subscribe to [the newsletter](https://cilium.io/newsletter)

Subscribe to the [eBPF and Cilium Community on Youtube](https://www.youtube.com/channel/UCJFUxkVQTBJh3LD1wYBWvuQ)

You’ve already found us on Github!

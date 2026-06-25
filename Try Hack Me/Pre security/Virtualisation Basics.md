# Virtualisation Basics

## Status

Completed ✅

## What I Learned

* Virtualization allows multiple systems to share the same physical hardware.
* It helps reduce costs and improve resource utilization.
* Hypervisors create and manage virtual machines.
* Containers provide lightweight environments for applications.

---

## Key Concepts

### Why Virtualization?

Before virtualization:

* One server = One application
* Expensive hardware costs
* Low resource utilization
* Slow deployment
* Difficult scaling

Virtualization allows multiple systems to safely share the same physical server.

---

### Building Analogy

* **Building** = Physical Server
* **Apartments** = Virtual Machines (VMs)
* **Tenants** = Applications or Operating Systems
* **Building Manager** = Hypervisor

This allows multiple systems to run independently on the same hardware.

---

### Hypervisor

A hypervisor creates and manages virtual machines.

Functions:

* Allocates CPU, RAM, and storage
* Keeps VMs isolated
* Starts, stops, and manages VMs

#### Type 1 Hypervisor

* Runs directly on hardware
* Faster and more efficient
* Common in data centers

#### Type 2 Hypervisor

* Runs inside an operating system
* Easier to install
* Common for learning and testing

---

### Virtual Machines (VMs)

A VM is a virtual computer created by a hypervisor.

Features:

* Virtual CPU
* Virtual RAM
* Virtual Storage
* Virtual Network

Each VM:

* Runs its own operating system
* Is isolated from other VMs
* Functions like a real computer

---

### Containers

Containers are lightweight environments used to run applications.

Features:

* Share the host operating system kernel
* Use fewer resources than VMs
* Start quickly
* Designed for running applications

**Analogy:** Rooms inside an apartment.

---

## Lab Activity

* Explored why virtualization was created.
* Learned the role of hypervisors.
* Identified the differences between VMs and containers.
* Understood how multiple systems can share the same hardware safely.

---

## Takeaway

Virtualization improves efficiency by allowing multiple virtual systems to run on one physical machine. Hypervisors manage virtual machines, while containers provide lightweight environments for applications.

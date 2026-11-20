# **OpenShift Virtualization Overview**

# **Presentation Metadata**

* **Title**: Red Hat OpenShift Virtualization Overview  
* **Presenter**: Alfred Bach, Principal Technical Instructor, Red Hat FPL Global  
* **Date**: November 25, 2026

# **Executive Summary**

Red Hat OpenShift Virtualization provides a modern, enterprise-grade platform for running virtual machines (VMs) alongside containers on a single cloud-native application platform. Built on the Linux Kernel-based Virtual Machine (KVM) hypervisor engine, it allows organizations to unify infrastructure management, preserve existing IT investments, and transition to cloud-native architectures at their own pace.

# **Key Capabilities & Architectural Pillars**

* **Unified Platform**: Run VMs and containers side-by-side on a single integrated foundation with consistent management interfaces, APIs, and operator integrations (ACM, AAP).  
* **KVM Hypervisor Engine**: Delivers enterprise stability, high performance, and proven scalability powered by KVM and QEMU.  
* **Windows & RHEL Guest Support**: Full Microsoft Server Virtualization Validation Program (SVVP) compliance for Windows guests, alongside included RHEL guest entitlements.  
* **Storage & Image Management**: Persistent Volume Claim (PVC)-backed disks utilizing enterprise CSI drivers (Dell, HPE, IBM, Pure Storage, NetApp), golden boot sources, templates, and snapshot/clone support.  
* **Advanced Networking**: OpenShift OVN software-defined networking, Multus for secondary VLAN network attachments, and load balancing integration (MetalLB, F5).  
* **Data Protection & Governance**: Data backup and recovery through OpenShift API for Data Protection (OADP / Velero), Portworx, Kasten, and NetApp.

# **Migration & Modernization Pathways**

* **Rehost**: Shift VM workloads directly into OpenShift Virtualization to consolidate infrastructure.  
* **Replatform**: Upgrade target applications into containerized architectures.  
* **Refactor**: Decompose monoliths into modern cloud-native microservices.  
* **Migration Toolkit for Virtualization (MTV)**: Streamlines bulk migration from VMware vSphere, RHV, and OpenStack with low-downtime warm migration capabilities, automated pre-flight checks, and intuitive UI management.


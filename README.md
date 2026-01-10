# 🚀 PCIe Introduction & Troubleshooting

A practical knowledge base for **PCI Express (PCIe)** development and
debugging, focused on **software fundamentals, QEMU modeling etc

This repository is useful for:
- 🧑‍💻 Driver developers
- 🔬 Validation & debug engineers
- 🧠 Engineers learning PCIe from a system/software perspective

------------------------------------------------------------------------

## 📚 What you'll find here

-   Clear explanations of **PCIe fundamentals**
-   Real **`lspci` output analysis**
-   **QEMU-based PCIe topology modeling**
-   Debug patterns used in **actual SoC bring-up**
-   Common **PCIe issues and troubleshooting techniques**

------------------------------------------------------------------------

## 🗂 Repository Structure

``` text
.
├── README.md
└── docs/
    └── PCIe-Introduction.adoc
```

------------------------------------------------------------------------

## 📖 Contents

### 🔹 Getting Started with PCIe

-   📌 [So, What Exactly is PCIe?](docs/PCIe-Introduction.adoc#what-is-pcie)
-   🧓 [Legacy PCI](docs/PCIe-Introduction.adoc#legacy-pci)
-   🌳 [Explore the PCIe Hierarchy using lspci output](docs/PCIe-Introduction.adoc#explore-the-pcie-hierarchy-using-lspci-output)

-   🖥️ [Exploring PCIe using QEMU](docs/PCIe-Introduction.adoc#exploring-pcie-using-qemu)
    -   🔌 [Connect minimal-pcie-nic to pcie-root-port(PCI bridge connected to bus 0)](docs/PCIe-Introduction.adoc#connect-minimal-pcie-nic-to-pcie-root-port-pci-bridge-connected-to-bus-0)

    -   🔀 [Connect PCIe switch to pcie-root-port and connect minimal-pcie-nic to downstream ports of switch](docs/PCIe-Introduction.adoc#connect-pcie-switch-to-pcie-root-port-pci-bridge-connected-to-bus-0and-then-connect-minimal-pcie-nic-to-downstream-ports-of-switch)

------------------------------------------------------------------------

### 🔹 Reference Material

-   📎 [References](docs/PCIe-Introduction.adoc#references)

------------------------------------------------------------------------

## 🧪 Typical Use Cases

✔ Understanding PCIe enumeration\
✔ Visualizing root ports, bridges, and switches\
✔ Validating PCIe topology in QEMU\
✔ Mapping software view to real hardware layouts

------------------------------------------------------------------------

## 🛠 Tools & Technologies

-   `lspci`
-   QEMU
-   Linux PCI subsystem
-   Embedded Linux / Yocto

------------------------------------------------------------------------

**If PCIe has ever felt confusing --- this repo is meant to make it clear.**

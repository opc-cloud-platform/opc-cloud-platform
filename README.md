<div align="center">

![OPC+ Platform Banner](https://raw.githubusercontent.com/FangPoHsun/opc-cloud-platform/main/assets/opc_platform_banner.png)

# 🚀 OPC+ Cloud Platform

*Developed by [PAL Lab](https://nycu-pal.com/) at National Yang Ming Chiao Tung University*

### **Next-Generation GPU-Accelerated Freeform Mask Correction**

*Accelerate | Automate | Innovate*

[![Cloud Native](https://img.shields.io/badge/Cloud-Native-blue?style=for-the-badge&logo=kubernetes)](https://kubernetes.io/)
[![GPU Accelerated](https://img.shields.io/badge/GPU-Accelerated-green?style=for-the-badge&logo=nvidia)](https://www.nvidia.com/en-us/data-center/gpu-cloud-computing/)
[![50x Faster](https://img.shields.io/badge/Speed-50x_Faster-red?style=for-the-badge)](https://github.com)
[![Freeform Support](https://img.shields.io/badge/Freeform-Curvilinear-purple?style=for-the-badge)](https://github.com)

---

### **Revolutionizing Optical Proximity Correction (OPC) and Inverse Lithography Technology (ILT)**

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Why OPC+?](#-why-opc)
- [Technical Specifications](#-technical-specifications)
- [Use Cases](#-use-cases)
- [Deployment Models](#-deployment-models)
- [Getting Started](#-getting-started)
- [Workflow](#-workflow)
- [Industry Validation](#-industry-validation)
- [Contact](#-contact)

---

## 🌟 Overview

**OPC+** is a revolutionary cloud-native platform that transforms the landscape of mask correction for semiconductor manufacturing and advanced silicon photonics. By harnessing the power of **GPU acceleration**, OPC+ delivers a **50x speed improvement** over traditional CPU-based solutions while eliminating the need for expensive on-premise hardware and complex licensing.

Designed for both industry professionals and research institutions, OPC+ makes advanced mask correction accessible to everyone through an intuitive web interface—**no deep OPC expertise required**.

### 🎯 What Makes OPC+ Different?

- **⚡ 50x GPU Acceleration**: Complete corrections in minutes, not hours
- **☁️ Zero Hardware Investment**: Access powerful GPU clusters through the cloud
- **🎨 Native Freeform Support**: Handle curvilinear masks without polygonal approximation
- **🖥️ "OPC for Everyone" Interface**: Simple, intuitive GUI for all skill levels
- **🔒 Flexible Deployment**: Public, private, or hybrid cloud options

---

## ✨ Key Features

### 🚄 **Unprecedented Speed**
Leverage massive GPU parallelism with CUDA Multi-Stream technology to achieve **50x faster** mask correction compared to traditional CPU-based methods. What used to take hours now takes minutes.

### ☁️ **Cloud-Native Architecture**
Built on Kubernetes with elastic resource scaling, OPC+ dynamically allocates GPU resources across public, private, or hybrid cloud environments. No expensive hardware purchases or maintenance required.

### 🎨 **True Freeform & Curvilinear Support**
Unlike traditional tools that force curved designs into Manhattan geometries, OPC+ natively supports **curvilinear masks**, preserving optical phase and device performance—essential for next-generation photonics.

### 🖱️ **Intuitive User Interface**
Our "OPC for Everyone" GUI removes the complexity barrier. Simply upload your layout, configure scanner parameters, and let OPC+ handle the rest. No scripting or deep technical knowledge required.

### 🔧 **Global Inverse Optimization**
Advanced ILT algorithms with native curvilinear mask generation ensure superior CD (Critical Dimension) uniformity and pattern fidelity compared to rule-based OPC.

### 📊 **Predictable Performance**
High-efficiency execution with **<2% load imbalance** across GPU nodes ensures reliable delivery schedules and consistent results.

### 🔌 **Industry-Standard Formats**
Seamless integration with your existing workflow through support for **GDS/OASIS** layout files and **CD-SEM** calibration data.

---

## 💡 Why OPC+?

<div align="center">

![Traditional vs GPU-Accelerated OPC](https://raw.githubusercontent.com/FangPoHsun/opc-cloud-platform/main/assets/workflow_comparison.png)

</div>

### Traditional OPC Challenges

| Challenge | Traditional Approach | OPC+ Solution |
|-----------|---------------------|---------------|
| **Speed** | Slow CPU processing | 50x faster with GPU acceleration |
| **Cost** | Expensive per-core licensing | Flexible cloud consumption model |
| **Hardware** | Large upfront investment | Zero hardware—cloud native |
| **Complexity** | Requires deep expertise | Intuitive "OPC for Everyone" GUI |
| **Curved Designs** | Forced Manhattanization | Native freeform support |
| **Scalability** | Limited by local resources | Elastic cloud scaling |

### Benefits

✅ **Eliminate Bottlenecks**: Move away from slow CPU processing  
✅ **Lower Entry Barriers**: Perfect for startups and research labs  
✅ **Enhanced Performance**: Preserve optical phase in curved photonic designs  
✅ **Cost-Effective**: Pay only for what you use  
✅ **Higher Fidelity**: Superior CD uniformity and pattern accuracy  
✅ **Global Access**: Work from anywhere with internet connectivity  

---

## 📊 Results & Performance

### Pattern Fidelity Comparison

OPC+ delivers exceptional pattern fidelity for complex freeform shapes, preventing the blurring and distortion common in traditional approaches.

<div align="center">

![Pattern Fidelity Comparison](https://raw.githubusercontent.com/FangPoHsun/opc-cloud-platform/main/assets/pattern_comparison.png)

*Comparison of target layout vs. OPC-corrected mask showing improved pattern accuracy for freeform geometries*

</div>

### Complete Correction Workflow

Our platform implements a comprehensive 3-step correction process: OPC Correction → Aerial Image Simulation → Physical Model Calibration, with experimental validation showing elimination of critical defects.

<div align="center">

![Technical Workflow](https://raw.githubusercontent.com/FangPoHsun/opc-cloud-platform/main/assets/technical_diagram.png)

*Complete correction workflow with SEM validation showing defect elimination (w/ OPC vs. w/o OPC)*

</div>

### Comprehensive Comparison

| Category | Traditional OPC | OPC+ Cloud | Business Benefit |
|----------|----------------|------------|------------------|
| **Mask Geometry Support** | Manhattan-based (rectilinear only) | Native curvilinear and freeform masks | Preserves optical phase and device performance |
| **Design Conversion** | Requires polygon fracturing / Manhattanization | No geometry approximation required | Eliminates layout-induced performance loss |
| **Optimization Method** | Local rule-based or windowed optimization | Global inverse optimization | Higher pattern fidelity and CD uniformity |
| **GPU Utilization** | Limited or static GPU assignment | Cost-performance–aware GPU allocation | Optimal cost vs. throughput tradeoff |
| **Parallelism** | Limited job-level parallelism | CUDA Multi-Stream image-level parallelism | Faster processing of large layouts |
| **Workload Scheduling** | Static or FIFO | Two-tier dynamic scheduling | Balanced execution across heterogeneous GPUs |
| **Turnaround Time Predictability** | Variable, bottleneck-prone | <2% execution imbalance across nodes | Reliable delivery schedules |
| **Deployment Model** | On-prem only | Public, private, or hybrid cloud | Fits foundry security and IT policies |
| **Manufacturing Validation** | Logic-centric benchmarks | Validated on photonics and metasurfaces | Proven beyond digital CMOS |
| **Future Readiness** | Limited for curvilinear CMOS | Ready for next-generation curvilinear nodes | Enables new process offerings |

### Key Performance Metrics

- ⚡ **50x Speed Improvement**: Reduce correction time from hours to minutes
- 🎯 **<2% Load Imbalance**: Consistent, predictable performance across GPU nodes
- 📐 **Superior CD Uniformity**: Enhanced critical dimension control
- 🔄 **Native Curvilinear Support**: Preserve optical phase in photonic designs
- ✅ **Proven Results**: Validated by leading semiconductor research institutions

---

## 🔧 Technical Specifications

### Algorithm & Processing
- **Core Technology**: Global inverse optimization (ILT)
- **Mask Generation**: Native curvilinear mask support
- **Parallelism**: CUDA Multi-Stream image-level parallelism
- **Scheduling**: Two-tier dynamic job scheduling
- **Load Balancing**: <2% imbalance across GPU nodes

### Supported Formats
- **Input**: GDS/OASIS layout files
- **Calibration**: CD-SEM data integration
- **Output**: Manufacturing-ready corrected masks

### Infrastructure
- **Orchestration**: Kubernetes-managed clusters
- **GPU Resources**: 12+ GPUs/TPUs in public cloud
- **Deployment**: Public, private, or hybrid models
- **Scaling**: Dynamic elastic resource allocation

---

## 🎯 Use Cases

### 🔬 Semiconductor Manufacturing
- Advanced process node development (7nm, 5nm, 3nm and beyond)
- Foundries and mask shops
- Fabless design houses
- Research and development labs

### 💎 Photonic Integrated Circuits (PICs)
- Curvilinear photonics patterns
- Apodized grating couplers
- Metasurfaces and metalenses
- Micro-ring resonators
- Silicon photonics devices

### 🏭 Industry Applications
- High-volume manufacturing
- Rapid prototyping
- Design exploration
- Process optimization

---

## 🌐 Deployment Models

OPC+ offers flexible deployment options to meet your security and performance requirements:

<table>
<tr>
<td width="33%" valign="top">

### ☁️ Public Cloud
- Access a cluster of **12+ GPUs/TPUs**
- Optimal job scheduling and resource utilization
- No infrastructure management
- **Ideal for**: Startups, research labs, and rapid prototyping

</td>
<td width="33%" valign="top">

### 🔒 Private Cloud
- Custom on-premise deployment
- Maximum IP security and data control
- Dedicated resources
- **Ideal for**: Large enterprises and sensitive projects

</td>
<td width="33%" valign="top">

### 🔄 Hybrid Model
- Blend public resources with private infrastructure
- Balance cost, performance, and security
- Flexible resource allocation
- **Ideal for**: Organizations with varying workload demands

</td>
</tr>
</table>

---

## 🚀 Getting Started

### Prerequisites
- Target layout file (GDS/OASIS format)
- Scanner parameters
- (Optional) CD-SEM calibration data

### Quick Start

1. **Access the Platform**
   - Navigate to the OPC+ web portal
   - Create an account or log in

2. **Upload Your Design**
   - Upload your target layout (GDS/OASIS)
   - Configure scanner parameters

3. **Configure Correction**
   - (Optional) Upload CD-SEM calibration data
   - Select correction parameters

4. **Run Correction**
   - Submit your job to the GPU cluster
   - Monitor progress in real-time

5. **Download Results**
   - Retrieve your corrected mask layout
   - Ready for manufacturing!

### Example Workflow
```
Input Layout (GDS/OASIS) → OPC+ Cloud Platform → Corrected Mask
                              ↓
                    GPU-Accelerated ILT Processing
                              ↓
                    50x Faster Than Traditional OPC
```

---

## 🔄 Workflow

```mermaid
graph LR
    A[Upload Layout<br/>GDS/OASIS] --> B[Configure<br/>Parameters]
    B --> C{Calibration<br/>Data?}
    C -->|Yes| D[Upload CD-SEM<br/>Data]
    C -->|No| E[GPU-Accelerated<br/>ILT Processing]
    D --> E
    E --> F[Inverse<br/>Optimization]
    F --> G[Curvilinear<br/>Mask Generation]
    G --> H[Download<br/>Corrected Mask]
    
    style A fill:#4CAF50,stroke:#2E7D32,color:#fff
    style E fill:#2196F3,stroke:#1565C0,color:#fff
    style H fill:#FF9800,stroke:#E65100,color:#fff
```

### Detailed Process

1. **Input**: Upload target layout and scanner parameters via web portal
2. **Calibration** (Optional): Integrate CD-SEM data for model refinement
3. **Processing**: Automated GPU-accelerated correction using inverse lithography
4. **Output**: Manufacturing-ready corrected mask layout

---

## 🏆 Industry Validation

OPC+ is developed by the **National Yang Ming Chiao Tung University (NYCU)** research team and has been validated and trusted by leading institutions worldwide:

<div align="center">

### Trusted By

🔬 **TSRI** - Taiwan Semiconductor Research Institute  
🎓 **University of Southampton, UK**  
🏢 **Cornerstone Research**

</div>

Our platform combines cutting-edge academic research with real-world industrial requirements, ensuring both innovation and reliability.

---

## 🌐 Platform Access

The OPC+ Cloud Platform is currently available for research and professional use.

<div align="center">

![Platform Login](https://raw.githubusercontent.com/FangPoHsun/opc-cloud-platform/main/assets/platform_login.png)

*OPC+ Cloud Platform - Professional optical proximity correction service*

</div>

### Getting Access

1. **Visit the Platform**: [https://nycu-opcplatform.ddns.net/](https://nycu-opcplatform.ddns.net/login)
2. **Register**: Create an account for research or professional use
3. **Start Correcting**: Upload your layouts and experience

**Supported by**: National Science and Technology Council (NSTC), Taiwan

---

## 📞 Contact

Interested in learning more about OPC+ or getting access to the platform?

- **Principal Investigator**: [Prof. Peichen Yu](https://nycu-pal.com/pi.html)
- **Email**: yup@nycu.edu.tw
- **Lab Website**: [PAL Lab - Photonics & Lithography](https://nycu-pal.com/)
- **Platform**: [OPC+ Cloud Platform](https://nycu-opcplatform.ddns.net/)
- **Institution**: [National Yang Ming Chiao Tung University (NYCU)](https://www.nycu.edu.tw/)
- **Address**: No.1001 Univ. Rd., East Dist., Hsinchu City 300, Taiwan

---

<div align="center">

###  **Transform Your Mask Correction Workflow Today** 

**OPC+**: Where Speed Meets Precision in the Cloud

---

*Developed with ❤️ by the NYCU Research Team*

</div>

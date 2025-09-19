# Guidelines for Developing Energy Efficient and Environmentally Sustainable Software

Welcome to the Guidelines for Developing Energy-Efficient and Sustainable Software Repository!

This repository forms part of the Green Digital Action pillar under the United Nations International Telecommunication Union (UN ITU). It supports the global effort to embed sustainability into software     development by curating and sharing best practices, technical guidance, and actionable resources.

<p align="center">
  <img src="https://i.imgur.com/i86g2zF.png" width="200">
</p>

Included here is a practitioner-developed set of sustainable software engineering best practices, co-created with GoCodeGreen. These practices have been developed, tested, and refined in real-world environments and are shared here for the benefit of the wider community.

As part of this contribution, a practical checklist has been provided — designed to help developers and teams integrate sustainability into every stage of the software lifecycle. This tool has been openly donated for public use, to accelerate learning and implementation across the industry.

You’ll also find links to a growing collection of recommended books, websites, videos, and courses to support continuous learning and awareness of the latest advances in sustainable software development.

## Summary Table

|                                  | Energy and Resource Efficiency|Software Architecture and Design |Sustainable Hardware and Infrastructure|Sustainable Development and Operations|AI and Emerging Technologies|
|----------------------------------|-------------------------------|---------------------------------|---------------------------------------|-------------------------------|-------------------------------|
|**Green Software Foundation** | ✔ | ✔ | ✔ | ✔ | ✔ |  
|**Building Green Software by Anne Currie et al.**| ✔ | ✔ | ✔ | ✔ | ✔ |
|**TechUK Green Coding Toolkit** (pending)|  |  |  |  |  |
|**AWS Well-Architected Framework**| ✔ | ✔ | ✔ | ✔ |  |
|**GCP Well-Architected Framework**| ✔ | ✔ | ✔ | ✔ |  |
|**Azure Well-Architected Framework**| ✔ | ✔ | ✔ | ✔ | ✔ |
|**TechCarbonStandard by Scott Logic**| ✔ |  | ✔ | ✔ |  |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| ✔| ✔| ✔| ✔ |✔|
|**W3C Web Sustainability Guidelines**| ✔ | ✔ | ✔ | ✔ |  |
|**Defra Greener Service Principles**|✔| ✔ | ✔ | ✔ | ✔ |
|**Green Web Foundation**|  | ✔ | ✔ | ✔ | ✔ |
|**SustainableIT Standards**|  |  |  | ✔ |  |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**| ✔ | ✔ | ✔ | ✔ | ✔ |

*Disclaimer: This table is based on current published research, and does not cover work in progress*

## Table of Contents

- Why sustainable software development is important?
- Practioners Best Practice Guide
- Sustainable Software Engineering Checklist
- Categories:
  - [Energy and Resource Efficiency](#energy-and-resource-efficiency)
  - [Software Architecture and Design](#software-architecture-and-design)
  - [Sustainable Hardware and Infrastrucutre](#sustainable-hardware-and-infrastructure)
  - [Sustainable Development and Operations](#sustainable-development-and-operations)
  - [AI and Emerging Technologies](#ai-and-emerging-technologies)
- Case Studies
- Contributors
- How to Contribute
- Licensing
- Questions

## What do we mean by sustainable software?
We refer to sustainable software as software that is designed, developed, deployed and maintained with the aim of minimising its environmental impact across its full lifecycle. Our focus is particularly on energy use and carbon emissions.

## Why is sustainable software development important?
Software development is a major contributor to IT-related energy use. Inefficient code, redundant processes, and poor architectural decisions can lead to excessive computational demand, driving up emissions and operational costs. Studies indicate that optimised software can reduce energy consumption across infrastructure, devices, and networks by 25– 50%, making it one of the most effective levers for minimising digital carbon footprints.

The environmental impact of software extends beyond code execution. Poorly designed applications increase hardware requirements, data storage needs, and network load, leading to unnecessary energy consumption at scale. Even user behaviour is influenced by software design, with inefficient workflows and excessive processing contributing to avoidable emissions. Conversely, well-designed software delivers multiple benefits—it enhances system performance, reduces energy use, lowers costs, and improves the overall user experience

## Technical Levels Explained
For each resource, we have specified a recommended level of technical expertise to better align with your needs and facilitate easier navigation. These levels are categorised as Beginner, Intermediate, and Advanced.

Beginner resources provide high-level overviews of practices in a more accessible and easy-to-understand format. Intermediate resources serve as a balance between the two, offering a moderate level of technical detail. Advanced resources offer in-depth technical guidance, including practices such as code snippets and implementation details. 

#### You can complete a voluntary Self-Assessment [here](https://gocode.green/un-itu-self-assessment/) to help determine your technical level. The results are anonymous and solely intended to help indicate which resource levels may be most useful for you. 

## Categories

### Energy and Resource Efficiency
This includes the following:
- Energy-Efficient Code Development – Optimising code structure and execution to minimise energy consumption. 
- Data Efficiency in Software Design – Reducing data transfer, compression, and storage impact on energy use. 
- Optimising Features and Reducing Redundancy – Eliminating unnecessary functionalities that increase computational load. 
- Efficient Logging and Polling – Reducing excessive logging and inefficient data queries that increase resource consumption. 
- Dynamic Power Management – Adapting software operations to power conditions to reduce energy waste.

#### Technical Expertise Table

|                                  | Beginner | Intermediate | Advanced |
|----------------------------------|----------|--------------|----------|
|**Green Software Foundation** |  |  | ✔ | 
|**Building Green Software by Anne Currie et al.**|  | ✔ |  |
|**AWS Well-Architected Framework**|  | ✔ |  |
|**GCP Well-Architected Framework**|  | ✔ |  |
|**Azure Well-Architected Framework**|  | | ✔ |
|**Tech Carbon Standard by Scott Logic**| ✔ |  |  |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| | ✔| |
|**W3C Web Sustainability Guidelines**|  |  | ✔ |
|**Defra Greener Service Principles**| |✔| |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**| | |✔ |

You can find all related resources here: [Energy and Resource Efficiency folder](./Energy-and-Resource-Efficiency/)

### Software Architecture and Design
This includes the following:
- Code Reuse and Modular Design – Encouraging reusable software components to improve efficiency and sustainability. 
- Application Modernisation for Efficiency – Transitioning to microservices, containerisation, and cloud-native approaches. 
- Sustainability by Design in User Experience – Creating user journeys that minimise backend computation and energy use. 
- Eco-Design Framework for Digital Services – Applying lifecycle impact assessments to software design and development.

#### Technical Expertise Table

|                                  | Beginner | Intermediate | Advanced |
|----------------------------------|----------|--------------|----------|
|**Green Software Foundation** |  |  | ✔ | 
|**Building Green Software by Anne Currie et al.**|  | ✔ |  |
|**AWS Well-Architected Framework**|  | ✔ |  |
|**GCP Well-Architected Framework**|  | ✔ |  |
|**Azure Well-Architected Framework**|  |  | ✔ |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| | ✔| |
|**W3C Web Sustainability Guidelines**|  |  | ✔ |
|**Defra Greener Service Principles**| |  | ✔ |
|**Green Web Foundation**|  |  | ✔ |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**|  |  | ✔ |

You can find all related resources here: [Software Architecture and Design folder](./Software-Architecture-and-Design/)

### Sustainable Hardware and Infrastructure
This includes the following:
- Leveraging Hardware Efficiency – Ensuring software compatibility with diverse hardware to extend device lifecycles. 
- Carbon-Aware Scheduling – Aligning software execution with low-carbon grid periods to reduce emissions. 
- E-Waste Reduction – Designing software that extends the lifespan of hardware and reduces electronic waste.

#### Technical Expertise Table

|                                  | Beginner | Intermediate | Advanced |
|----------------------------------|----------|--------------|----------|
|**Green Software Foundation** |  |  | ✔ | 
|**Building Green Software by Anne Currie et al.**|  | ✔ |  |
|**AWS Well-Architected Framework**|  | ✔ |  |
|**GCP Well-Architected Framework**|  | ✔ |  |
|**Azure Well-Architected Framework**|  |  | ✔ |
|**Tech Carbon Standard by Scott Logic**| ✔ |  |  |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| | ✔| |
|**W3C Web Sustainability Guidelines**|   |  | ✔ |
|**Defra Greener Service Principles**|  | ✔|  |
|**Green Web Foundation**|  |  | ✔ |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**|  |  | ✔ |


You can find all related resources here: [Sustainable Hardware and Infrastructure folder](./Sustainable-Hardware-and-Infrastructure/)

### Sustainable Development and Operations
This includes the following:
- Integrating Measurement into Development – Embedding sustainability metrics into the software development process.
- Sustainability Metrics in Performance Benchmarks – Expanding software performance evaluations to include energy and carbon impact. 
- Automation in Software Development – Implementing CI/CD and automated testing to streamline operations. 
- Integrating DevOps for Sustainability – Embedding sustainability principles into infrastructure and software deployment.

#### Technical Expertise Table

|                                  | Beginner | Intermediate | Advanced |
|----------------------------------|----------|--------------|----------|
|**Green Software Foundation** |  |  | ✔ | 
|**Building Green Software by Anne Currie et al.**|  | ✔ |  |
|**AWS Well-Architected Framework**|  | ✔ |  |
|**Azure Well-Architected Framework**|  |  | ✔ |
|**Tech Carbon Standard by Scott Logic**| ✔ |  |  |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| | ✔| |
|**W3C Web Sustainability Guidelines**|  |  | ✔ |
|**Defra Greener Service Principles**|  | ✔  |  |
|**Green Web Foundation**|  |  | ✔ |
|**SustainableIT Standards**|  | ✔|  |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**|  |  | ✔ |

You can find all related resources here: [Sustainable Development and Operations folder](./Sustainable-Development-and-Operations/)

### AI and Emerging Technologies
This includes the following:
- AI-Driven Software Development – Leveraging AI for software optimisation while minimising its environmental footprint.

#### Technical Expertise Table

|                                  | Beginner | Intermediate | Advanced |
|----------------------------------|----------|--------------|----------|
|**Green Software Foundation** |  |  | ✔ | 
|**Building Green Software by Anne Currie et al.**|  | ✔ |  |
|**Azure Well-Architected Framework**|  |  | ✔ |
|**Decarbonise Digital and Sustainable IT Best Practices Handbook by Eric Zie**| | ✔| |
|**Defra Greener Service Principles**|  | ✔ |  |
|**Green Web Foundation**|  |  | ✔ |
|**Arcom General Policy Framework for the Ecodesign of Digital Services**|  |  | ✔ |

#### Areas Under Observation:

This section highlights areas within software engineering that we believe are important to monitor, but for which we have not yet found established, sustainable best practices. These are areas where evidence is still emerging or where industry consensus has yet to form. We are actively tracking developments in these areas and welcome contributions, discussions, or references that can help us better understand and document them. If you have insights, studies, or examples related to any of these topics, feel free to open an issue or submit a pull request. Areas include:
- LLM use in code development

You can find all related resources here: [AI and Emerging Technologies folder](./AI-and-Emerging-Technologies/)

## Case Studies
We believe case studies bring everything to life. Here you will find a collection of success stories and case studies that showcase energy efficient and sustainable software. 

## Contributors 

We would like to thank Mohammadreza Mousavi, Professor of Software Engineering at King's College London, and Dr Kevin Lano, Reader in Software Engineering at King's College London, for providing valuable input to and feedback on the repository and research methodology. We appreciate their contribution to the repository and their recognition of the value it can bring to engineers.

We would also like to thank the following companies for carrying out an engineering review of the repository. We are grateful for their support and their acknowledgement of the benefits it would bring their engineers:

|<!-- -->|<!-- --> | 
|------------|------------------------|
|Bupa        |  King's College London |
|Capgemini   | Mastek                 |
|Cognizant   | PA Consulting          |
|GoCodeGreen | Sage                   |
| HSBC       | Standard Bank          |


## How to Contribute
We welcome contributions! If you would like to suggest improvements, add new resources, or share implementation experiences, please open an issue or submit a pull request. Together, we can advance sustainable digital development for everyone.
Check out [Contributions](./Contributing.md/) for more details.


## Licensing
All materials in this repository are shared under the Creative Commons Attribution 4.0 International License (CC BY 4.0), unless otherwise stated. You are free to use, adapt, and share the content with appropriate attribution.

By submitting a contribution, you agree that it will be released under the repository’s Creative Commons Attribution 4.0 International License (CC BY 4.0).


## Questions
Feel free to open an issue to start a discussion by submitting a pull request.


**Together, we can build a more sustainable digital future.**







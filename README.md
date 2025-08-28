# Unified Error Codes (UEC) Initiative 🚗⚡️

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](./LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/unified-error-codes/unified-error-codes?style=social)](https://github.com/unified-error-codes/unified-error-codes)
[![Discussions](https://img.shields.io/github/discussions/unified-error-codes/unified-error-codes)](https://github.com/unified-error-codes/unified-error-codes/discussions)

Platform for Open colaboration upon building comon software, practices and specifications towards Unfiied Error Codes and diagnostic in e-mobility.

---

## 🎯 The Problem: A Fragmented Ecosystem

The rapidly expanding Electric Vehicle Charging Ecosystem faces a critical challenge: a lack of standardized error codes and unified diagnostic mechanisms. This directly impacts every stakeholder:

* 🏢 **Charge Point Operators (CPOs):** Struggle with operational complexity and high integration costs, as each EVSE vendor uses a different, incompatible error reporting system.
* 🚗 **OEMs (Vehicle Manufacturers):** Lack of reliable unified diatnostic on EVSE side ofen leads to blaming EV for charging interaption or low charing power causing bad opinions about EVs.
* 🏭 **EVSE Manufacturers:** Each EV manufacturer must develop best diagnostic practices and solutions. Unified error codes and diagnostics causes that there is no community knowladge regarding this. Which cause that EVSE manufacturer is the only source of knowladge about the specific errors possible route causes and possible solution. 
* 🛠️ **Maintenance Teams:** Diagnosing and resolving faults is time-consuming, requiring specific knowledge for each manufacturer, which inflates traning and operational costs.

## 🔭 Our Vision

We envision a future where a unified diagnostic language eliminates confusion, accelerates repairs, and builds universal trust in the EV charging infrastructure.

To achieve this, we recognize the foundational work of key initiatives like **DIN DKE SPEC 99003** and **ChargeX MREC**. Believing that the comprehensive nature of DIN DKE SPEC 99003 provides the strongest starting point, our vision is built on three key pillars:

* 🤝 **Evolve the Specification Collaboratively**
    We will build upon the strong foundation of DIN DKE SPEC 99003. Through open, industry-wide collaboration, we will extend the specification to cover critical gaps and support emerging use cases, standards, and technologies.

* ⚙️ **Deliver Practical Tools for EVSE**
    A specification is only as good as its implementation. We develop and provide open-source software that enables seamless integration of the specification directly into EVSE firmware, offering exhaustive diagnostic capabilities "out-of-the-box."

* 🔌 **Deliver Practical Tools for CPMS**
    We develop robust backend components and APIs designed for easy integration into existing Charge Point Management Systems (CPMS). This empowers operators with a unified, accurate root-cause analysis and resolution instructions.
    
## 🧭 Our Principles

* 🌐 **Public & Open:** To truly unify the ecosystem, open collaboration is essential. All UEC Initiative activities and products will be publicly accessible under an Apache 2.0 license to ensure seamless cooperation and maximize adoption.
* 💡 **Implemented & Practical:** We don't stop at theory. Originating from a software engineering background, UEC Initiative won't stop at specifications. Alongside standard development, we'll develop Open Source software solutions to accelerate and simplify the future deployment of unified error codes across all EV charging ecosystem products.

---

## 🛠️ Our Work: Specifications & Software

The core output of the UEC Initiative is a combination of a living specification and the practical tools to implement it.

| Repository                                                                                     | Purpose                                                                                                                                                               | Current Status          |
| :--------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------- |
| 📜 [specification](https://github.com/unified-error-codes/specification) | Future evolution of the DIN DKE SPEC 99003. | Defining and prioritizing key error-handling use cases. |
| 💻 [uec-stack](https://github.com/unified-error-codes/uec-stack) | Software tools for both CPMS and EVSE. | MVP in development. |

---

## 👋 Get Involved & Contribute

This is an industry-wide challenge that requires a community-driven solution. Your expertise is needed to build a better charging future.

* ⭐ **Star our Repositories:** Show your support and stay up-to-date with our progress.
* 🗣️ **Join the Discussion:** Have an idea or a question? Head over to our [Discussions tab](https://github.com/unified-error-codes/unified-error-codes/discussions) to share your thoughts.
* 📖 **Contribute to the Specification:** Help us shape the future of the e-mobility diagnostics in the [`specification`](https://github.com/unified-error-codes/specification) repository.
* 💻 **Contribute Code:** Explore our [uec-stack](https://github.com/unified-error-codes/uec-stack) and help us build the future of e-mobility diagnostics.

## ⚖️ License

This project and all its products are licensed under the **Apache 2.0 License**. See the [LICENSE](./LICENSE) file for details.

# Open Weight Definition (OWD)

**Status:** Draft v0.1

## Introduction

The Open Weight Definition (OWD) is a set of criteria that describes what it means for AI model weights to be "open." Inspired by the Open Source Definition (OSD), this standard aims to bring clarity and consistency to the practice of distributing AI model weights freely, while ensuring that the freedoms to use and share these weights are preserved. However, the ability to study and modify these weights may be limited without access to the original source (i.e., training data). The term "Open Weight" should be used instead of "Open Source" when the source data for the model is not available or appropriately licensed.

## Motivation

The original Open Source Definition (OSD) and compliant Open Source Licences (OSL) were designed for human-readable source code. Machine learning models—specifically their weights—are a different kind of artifact. While Open Source Licenses often apply in theory, there’s often confusion: model weights are not "source" in the conventional sense, and access to training data may be missing. This can leave users lacking the same freedoms they have become accustomed to with Open Source Software (OSS) over the past several decades.

The OWD serves as a litmus test, clarifying how openness applies to model weights, ensuring transparency, interoperability, and minimal restrictions. Our goal is to help the community converge on a shared understanding and to facilitate the growth of open AI models. It is also intented to take the pressure off the definition of "open source" by acknowledging that access to the source data is not always possible or appropriate.

## Relationship to the Open Source Definition

The OWD is closely modeled on the OSD. We have changed as little as possible to minimize risk and confusion, and maximise acceptance, while ensuring the definition applies cleanly to model weights. In doing so, we acknowledge and respect the heritage of Open Source while adapting it for the era of artificial intelligence.

Bruce Perens, the author of the OSD, suggests that the OSD can be applied to "Open Source AI" by considering both the software and the training data as "source code." This approach highlights the importance of access to training data for full compliance with open source principles. However, the evolving nature of some models, where training data changes dynamically in use, adds complexity to this application.

## Why Use Open Weight Instead of Open Source?

The term "Open Weight" should be used instead of "Open Source" when the source data for the model is not available or appropriately licensed. This distinction is crucial because, in the context of AI, the data used to train models is the true "source." Without access to this data, the traditional open source freedoms may not be fully applicable. The OWD aims to address this gap by providing a clear framework for openness in AI model weights.

## How to Use This Definition

- **For License Authors:** Consider whether a license meets the OWD criteria in drafting, and obtain community consensus.
- **For Publishers of Model Weights:** Refer to the OWD to ensure your chosen license grants the freedoms necessary for openness.
- **For Users and Contributors:** Use the OWD to guide your understanding of the rights and freedoms you have with a given model.

## Next Steps

This is a draft. We welcome feedback from all corners of the AI, legal, and open source communities. Pull requests, issues, and discussions are all encouraged.

## Associated Documents

- **[License](LICENSE.md):** A document detailing licenses compatible with the OWD.
- **[Frequently Asked Questions (FAQ)](FAQ.md):** A frequently asked questions document to address common queries.
- **[Contribution Guidelines](CONTRIBUTING.md):** Instructions for contributing to the OWD project.

## References

- [Open Weight Definition (OWD)](https://openweight.org)
 - [GitHub repository](https://github.com/OpenWeight/Definition)
- [Open Source Definition (OSD)](https://opensourcedefinition.org)
 - [Work In Progress (WIP)](https://opensourcedefinition.org/wip)
- [Open Source Community](https://discuss.opensourcedefinition.org)

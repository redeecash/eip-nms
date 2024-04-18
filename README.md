# EIP-NMS: Recommendation for NMS Exchanges trading exempt aecurities

Exempt securities include both federal exemptions and intrastate offerings like Regulation 3(a)(11) that have no federal notice.

---

title: EIP-NMS: Enhanced Protocol for Securities Trading on SEC Registered NMS Exchanges
description: Exempt securities include both federal exemptions and intrastate offerings like Regulation 3(a)(11) that have no federal notice.
author: PRESSPAGE ENTERTAINMENT INC dba PINGLEWARE (@pingleware)
discussions-to: `https://github.com/redeecash/eip-nms.git`
status: Draft
type: Informational
created: 2024-04-19
requires: EIP-1440, EIP-1450, EIP-1462
--------------------------------------

## Abstract

EIP-NMS proposes a standardized protocol tailored for securities trading on Securities and Exchange Commission (SEC) registered National Market System (NMS) exchanges, specifically designed to facilitate the trading of exempt securities. Building upon the foundation laid by EIP1440 and EIP1450, EIP-NMS introduces enhancements to address the unique requirements and regulatory framework of NMS exchanges dealing with exempt securities.

Key features of EIP-NMS include:

1. **Regulatory Compliance Framework**: EIP-NMS incorporates robust regulatory compliance mechanisms to ensure adherence to SEC regulations governing NMS exchanges, particularly focusing on the trading of exempt securities. By providing clear guidelines and standards, the protocol aims to streamline compliance efforts for exchange operators and market participants.
2. **Enhanced Market Data Handling**: EIP-NMS improves upon existing market data handling mechanisms, enabling more efficient dissemination and processing of securities-related information within the NMS ecosystem. This includes enhanced data formatting, compression techniques, and optimized data transmission protocols to reduce latency and enhance market transparency.
3. **Interoperability and Standardization**: EIP-NMS promotes interoperability and standardization across NMS exchanges, facilitating seamless communication and data exchange between different market participants and systems. By establishing common protocols and data formats, the protocol fosters a more cohesive and interconnected trading environment, ultimately benefiting market efficiency and liquidity.
4. **Security and Resilience**: EIP-NMS prioritizes security and resilience in the exchange infrastructure, implementing robust encryption standards, authentication mechanisms, and fault-tolerant architectures to safeguard against potential threats and disruptions. By enhancing the overall security posture of NMS exchanges, the protocol instills confidence among investors and market participants, fostering a more stable and trustworthy trading environment.
5. **Scalability and Performance**: EIP-NMS addresses scalability and performance challenges inherent in large-scale securities trading systems, leveraging optimized algorithms, distributed computing techniques, and parallel processing capabilities to accommodate growing transaction volumes and market demands. By ensuring high throughput and low latency, the protocol enables NMS exchanges to efficiently handle peak trading periods and maintain responsiveness under heavy loads.

EIP-NMS represents a significant step forward in the evolution of protocols for securities trading on SEC registered NMS exchanges, providing a comprehensive framework tailored to the specific needs and regulatory requirements of the exempt securities market. By fostering compliance, efficiency, and resilience, the protocol aims to enhance market integrity, liquidity, and investor protection within the NMS ecosystem.

## Motivation

The genesis of EIP-NMS stems from the advancements and insights garnered from the implementation and analysis of two pivotal Ethereum Improvement Proposals (EIPs), namely EIP1440 and EIP1450, which introduced groundbreaking concepts in the realm of digital securities trading.

EIP1440 marked a significant milestone by introducing the concept of restricted security tokens, which enabled the representation and trading of securities subject to specific regulatory restrictions within the Ethereum ecosystem. This innovation laid the foundation for bridging the gap between traditional securities markets and blockchain-based trading platforms, opening up new avenues for liquidity and accessibility while adhering to regulatory compliance standards.

Building upon this foundation, EIP1450 further expanded the scope by introducing standardized interfaces for managing security tokens, streamlining the issuance, transfer, and redemption processes within decentralized applications (DApps) and smart contracts. By establishing common interfaces and conventions, EIP1450 fostered interoperability and ease of integration across different security token implementations, facilitating a more cohesive and interconnected ecosystem for digital securities trading.

However, as the landscape of securities trading continues to evolve, particularly within the context of National Market System (NMS) exchanges registered with the Securities and Exchange Commission (SEC), there arises a distinct set of challenges and requirements unique to the trading of exempt securities. Exempt securities, subject to specific exemptions under SEC regulations, encompass a diverse array of assets such as municipal bonds, certain government securities, and securities issued by non-profit organizations.

The emergence of exempt securities as a vital component of the financial markets underscores the need for specialized protocols and standards tailored to the regulatory framework and operational dynamics of SEC registered NMS exchanges. While EIP1440 and EIP1450 laid a solid groundwork for digital securities trading, there exists a compelling impetus to enhance and extend these protocols to address the nuanced requirements and compliance obligations associated with trading exempt securities on NMS exchanges.

Thus, the motivation behind EIP-NMS is twofold: to leverage the advancements of EIP1440 and EIP1450 as catalysts for innovation in the realm of digital securities trading, and to tailor these advancements to the specific needs and regulatory landscape of SEC registered NMS exchanges dealing with exempt securities. By doing so, EIP-NMS aims to foster a more inclusive, efficient, and compliant ecosystem for securities trading, advancing the vision of a decentralized, accessible, and regulatory-compliant marketplace for digital assets.

## Specification

1. **Regulatory Compliance Framework**:

   - EIP-NMS mandates that all transactions involving exempt securities on SEC registered NMS exchanges must adhere to applicable SEC regulations and guidelines.
   - Implementations MUST provide mechanisms for verifying compliance with regulatory requirements, including investor accreditation, trading restrictions, and reporting obligations.
2. **Enhanced Market Data Handling**:

   - EIP-NMS introduces a standardized format for encoding market data related to exempt securities, ensuring interoperability and consistency across different implementations.
   - Implementations MUST support the encoding and decoding of market data using the specified format, enabling seamless transmission and processing of securities-related information.
3. **Interoperability and Standardization**:

   - EIP-NMS defines a set of common interfaces and data structures for interacting with NMS exchanges and managing exempt securities.
   - Implementations MUST adhere to these interfaces and data structures to promote interoperability and compatibility between different Ethereum platforms and client implementations.
4. **Security and Resilience**:

   - EIP-NMS requires implementations to prioritize security and resilience in the design and operation of NMS exchange infrastructure.
   - Implementations MUST employ robust encryption, authentication, and access control mechanisms to protect sensitive information and prevent unauthorized access.
5. **Scalability and Performance**:

   - EIP-NMS specifies optimizations for improving the scalability and performance of NMS exchanges handling exempt securities.
   - Implementations MUST employ efficient data storage, retrieval, and processing techniques to accommodate growing transaction volumes and market demands.
6. **Compatibility with Existing Standards**:

   - EIP-NMS ensures compatibility with existing Ethereum standards and protocols, including ERC standards for token representation and management.
   - Implementations MUST support the seamless integration of EIP-NMS with other Ethereum-based protocols and standards, enabling interoperability and composability across decentralized applications and smart contracts.
7. **Documentation and Testing**:

   - EIP-NMS requires comprehensive documentation and testing suites to facilitate the development and deployment of interoperable implementations.
   - Implementations MUST provide detailed documentation covering syntax, semantics, usage examples, and best practices, along with robust test suites to validate compliance with the specification.
8. **Community Engagement and Governance**:

   - EIP-NMS encourages community engagement and participation in the ongoing development and maintenance of the specification.
   - Implementations MUST actively engage with the Ethereum community through forums, working groups, and open discussions to solicit feedback, address issues, and propose enhancements to the specification.

By adhering to these specifications, Ethereum platforms and client implementations can ensure interoperable and compliant support for trading exempt securities on SEC registered NMS exchanges, fostering a more inclusive and efficient marketplace for digital assets.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119 and RFC 8174.

## Rationale

The development of EIP-NMS was primarily motivated by the need to address the shortcomings of existing Ethereum Improvement Proposals (EIPs) such as EIP1440 and EIP1450, which although groundbreaking in their time, are now considered incomplete and outdated for the evolving landscape of securities trading, particularly within SEC registered National Market System (NMS) exchanges.

1. **Incompleteness and Outdatedness of EIP1440 and EIP1450**:

   - EIP1440 introduced the concept of restricted security tokens, allowing the representation of securities subject to regulatory restrictions. However, it lacked specific provisions for compliance with SEC regulations and did not address the unique requirements of NMS exchanges dealing with exempt securities.
   - EIP1450 improved token management by introducing standardized interfaces but did not encompass the complexities of securities trading on NMS exchanges, nor did it provide guidance on regulatory compliance.
2. **Unique Requirements of SEC Registered NMS Exchanges**:

   - NMS exchanges regulated by the Securities and Exchange Commission (SEC) operate within a stringent regulatory framework, particularly when trading exempt securities subject to specific exemptions. These exchanges require specialized protocols and standards to ensure compliance with SEC regulations while maintaining operational efficiency and market integrity.
3. **Interoperability and Standardization**:

   - The lack of standardized protocols for securities trading on Ethereum has led to fragmentation and interoperability challenges within the ecosystem. EIP-NMS aims to establish common interfaces and data structures, enabling interoperable and compatible implementations across different Ethereum platforms and client implementations.
4. **Enhancements for Market Data Handling**:

   - Efficient market data handling is critical for NMS exchanges to disseminate timely and accurate information to market participants. EIP-NMS introduces standardized formats for encoding market data, facilitating seamless transmission and processing of securities-related information.
5. **Compliance with Regulatory Requirements**:

   - Regulatory compliance is paramount for NMS exchanges trading exempt securities, necessitating mechanisms for verifying investor accreditation, enforcing trading restrictions, and fulfilling reporting obligations. EIP-NMS mandates compliance with SEC regulations and provides guidelines for implementing regulatory compliance mechanisms.
6. **Scalability and Performance**:

   - Scalability and performance optimizations are essential for NMS exchanges to handle growing transaction volumes and market demands. EIP-NMS specifies optimizations for improving the scalability and performance of Ethereum-based NMS exchanges, ensuring efficient operation under varying load conditions.
7. **Related Work and Alternate Designs**:

   - EIP-NMS builds upon the foundational concepts introduced by EIP1440 and EIP1450 but extends their scope to address the unique requirements of SEC registered NMS exchanges. Alternate designs were considered, including variations on data encoding formats, compliance mechanisms, and scalability strategies, with a focus on achieving interoperability, efficiency, and regulatory compliance.

In summary, EIP-NMS represents a concerted effort to bridge the gap between blockchain technology and traditional securities markets, providing a comprehensive framework for trading exempt securities on SEC registered NMS exchanges. By addressing the limitations of existing proposals and embracing industry best practices, EIP-NMS aims to foster a more inclusive, efficient, and compliant ecosystem for digital securities trading on Ethereum.

## Backwards Compatibility

No backward compatibility issues found.

## Test Cases

Coming soon

## Reference Implementation

TBD

## Security Considerations

Needs discussion.

## Copyright

Copyright and related rights waived via [CC0](../LICENSE.md).

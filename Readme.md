# About the Project
IDS-G focuses on documentation and specifications for developing and testing IDS based solutions. This includes technical documentation and interface descriptions. This is also the place where we discuss and collaboratively develop components of International Data Spaces. Our aim is to reach the highest level of quality via continous feedback, contributions, implementations and reviews from the community. As collective production, innovation through collaboration and transparent working environment are among the key values of IDSA, we endeavor to provide a common ground to discuss, democratize and enhance the ongoing development processes by following the Open Source path.

Anybody who is interested in expressing their ideas and/or would like to be part of IDS developers community, are welcome to join and contribute.


<details><summary> New to IDS? We prepared a list of documents to get introduced to IDS. Please open the dropdown and check these out! </summary>
<br>
<ul>
<li> 1. <a href="https://www.internationaldataspaces.org/publications/sharing-data-while-keeping-data-ownership-the-potential-of-ids-for-the-data-economy/">Executive Summary of the IDSA</a></li>   
<li> 2. <a href="https://internationaldataspaces.org/wp-content/uploads/IDSA-Brochure-IDS-Standard-for-Data-Sovereignty-Indispensible-Element-for-Data-Ecosystems.pdf"> IDS as a Standard for Data Sovereignty and an Indispensable Element of Data Ecosystems</a></li> 
<li> 3. <a href="https://internationaldataspaces.org/wp-content/uploads/IDSA-Infographic-Data-Sharing-in-a-Data-Space.pdf">Infographic: Understanding the IDS (Lite version)</a></li>
<li> 4. <a href="https://internationaldataspaces.org/wp-content/uploads/dlm_uploads/IDSA-Infografik-English.pdf">Infographic: Understanding the IDS (Detailed version)</a></li>
<li> 5. <a href="https://internationaldataspaces.org/wp-content/uploads/IDSA-White-Paper-IDSA-Rule-Book.pdf">IDSA Rule Book</a></li>

In addition to these, you may also want to check various documents on IDSA website such as <a href="https://internationaldataspaces.org/publications/most-important-documents/">Most Important Documents</a></li> and/or <a href="https://internationaldataspaces.org/publications/papers-studies/">White Papers, Position Papers, Studies & External Papers</a></li>
</ul>
</details>



# What is Inside? 

## Architecture/Overview
Reference Architecture Model of International Data Spaces (IDS-RAM) sets the standard for building data-driven ecosystems, products and services. Here is where you will find everything you need to know to get started. IDS-RAM comprises the standards for secure and sovereign data exchange, certification and governance for across Europe and around the world. 

You can find the latest version of [IDS-RAM on IDSA Website](https://internationaldataspaces.org/publications/most-important-documents/) along with [white papers](https://internationaldataspaces.org/publications/papers-studies/) listing the specifications of IDS components.

   ### IDS Repositories on Github
   
   [DataspaceConnector](https://github.com/International-Data-Spaces-Association/DataspaceConnector)
   is the core of the Dataspace Connector as an IDS Connector reference implementation following the specifications of the IDS Information Model.
   
   
   [IDS-Connector-Framework](https://github.com/International-Data-Spaces-Association/IDS-Connector-Framework)
   aims to simplify the development of an IDS Connector.


   [IDS-ConfigurationManager](https://github.com/International-Data-Spaces-Association/IDS-ConfigurationManager)
   aims to simplify the administration of a connector.
   
   
   [IDS-ConfigurationManager-UI](https://github.com/International-Data-Spaces-Association/IDS-ConfigurationManager-UI)
   is the user interface for the IDS Configurationmanager.
   
   
   [IDS-Messaging-Services](https://github.com/International-Data-Spaces-Association/IDS-Messaging-Services)
   Also known as "Unified Library" or "framework-library", the aim of IDS-Messaging-Services is to simplify the development of an IDS-Connector.
   
   
   [IDS-Enterprise-Integration-Connector](https://github.com/International-Data-Spaces-Association/IDS-Enterprise-Integration-Connector)
   Lightweight Interoprable Connector Architecture for IDS-Communicatons.
   
   
   [InformationModel Repository](https://github.com/International-Data-Spaces-Association/InformationModel)
   IDS Information Model implements the IDS reference architecture as an extensible, machine readable and technology independent data model.
   
   
   [metadata-broker-open-core](https://github.com/International-Data-Spaces-Association/metadata-broker-open-core)
   is the repository of the open-core reference implementation of the IDS Metadata Broker. 
  
   
   [Java-Representation-of-IDS-Information-Model](https://github.com/International-Data-Spaces-Association/Java-Representation-of-IDS-Information-Model)
   is the representation of IDS Information Model in Java.
   
   
   [Trusted-Connector](https://github.com/International-Data-Spaces-Association/trusted-connector)
   is IoT edge platform "Trusted Connector" of the International Data Spaces. Based on Apache Karaf, includes Camel message routing, a Camel component for remote attestation with other connectors, and a management web consol
   
   
   [idscp2-jvm](https://github.com/International-Data-Spaces-Association/idscp2-jvm)
   is Kotlin implementation of the IDS Communication Protocol (IDSCP2) for use in JVM environments.
   
   
   [idscp2-rust](https://github.com/International-Data-Spaces-Association/idscp2-rust)
   is the Rust implementation of the IDSCPv2 transport layer.
   
   
   [oss-daps](https://github.com/International-Data-Spaces-Association/oss-daps)
   Open Source implementation of IDS DAPS (Dynamic Attribute Provisioning Service)
   


## Components
   **AppStore** is a logical extension of the Broker concept to store, search and provide data apps for the IDS ecosystem. It contains information about the availability of data apps and their metadata. 
   
   
   **ClearingHouse** acts as an intermediary that mediates between a Data Provider (DP) and a Data Consumer (DC) in the IDS-compliant ecosystem. It provides two basic functions for all financial and data exchange transactions taking place in the ecosystem: clearing and settlement based on transaction logging.
   
   
  **Connector**
A Connector is a software component for IDS-compliant data exchange. Being the dedicated point of data exchange and usage policy enforcement, the Connector is the central component of the data space concept. It offers all participants access to the data space.


  **Identity Provider**
The Identity Provider is responsible for issuing technical identities to parties that have been approved to become participants in the IDS system. It ensures efficient management of certificates and metadata, streamlining the process and reducing cost through use of a dynamic attribute provisioning system. An entity is allowed to participate in the IDS (e.g., to provide data or publish Data Apps) only if it is equipped with such an identity. 

  * **Certificate Authority** manages digital certificates for the participants of the International Data Spaces. 

  * **DAPS** acts as a dynamic access provisioning service. It provides efficient management of certificates and metadata, streamlining the process and reducing cost through    use of a dynamic attribute provisioning system.  

  * **ParIS** is the participant information system, which is part of the Identity Provider, where the attributes of participants are registered in, stored and maintained. The IDS Participants need to present a set of information about themselves and the commonly shared attributes must be understandable by any IDS component and is therefore defined in the IDS Information Model. 

**MetaDataBroker** is an intermediary that stores and manages information about the data sources available in the IDS. It is non-exclusive as multiple Brokers may coexist (e.g. for different application domains or sub-user groups within one data space). The activities of operator of the metadata broker, referred to as the Broker Service Provider mainly focus on receiving and providing metadata.



## Communication
The IDSCP (IDS Communication Protocol) establishes a secure peer-to-peer connection that provides mutual remote attestation and guarantees confidentiality, integrity, authenticity and perfect forward secrecy. It is designed to be very modular and thus flexible regarding the underlying communication channels and mechanisms for remote attestation. In the Communication folder, you will find more information and relevant files on: 
  * Message Structure/Format
  * Message Types
  * Protocols (Examples for implementing the messages)
  * IDSCP
  * IDS-LDP (IDS Label Distribution Protocol)



## IDS Information Model
The Information Model defines a domain-agnostic lingua franca of the International Data Spaces. It constitutes a central agreement shared by its participants and components, facilitating compatibility and interoperability. It primarily aims at the description, publication and discovery of data products and data processing software within the International Data Spaces and implements the IDS reference architecture as an extensible, machine readable and technology independent data model.

[InformationModel Repository](https://github.com/International-Data-Spaces-Association/InformationModel)
   


## UsageControl
Data usage control in the IDS basically works by attaching data usage policy information to data being exchanged and continuously controlling the way data is processed, aggregated, or forwarded to other endpoints. Data usage policies support developers and administrators in setting up correct data flows. At runtime, data usage control enforcement prevents IDS Connectors from handling data in an undesired way. Thus, data usage control is both a tool for system integrators to ensure they are not building an architecture that violates security requirements, and an audit mechanism providing evidence of compliant data usage.

More information on data usage control in IDS can be found in the position paper [Usage Control in the International Data Spaces](https://internationaldataspaces.org/wp-content/uploads/IDSA-Position-Paper-Usage-Control-in-the-IDS-V3.0.pdf)


## Glossary
In this folder, you will find the file with all relevant IDS terms along with their descriptions.


## Handbook


## Resources
This folder contains other resources such as logos and templates.

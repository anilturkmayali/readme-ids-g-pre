# IDS-G-pre

## About the Project
This is the place where we can discuss and develop improvements in repositories of International Data Spaces. Our aim is to reach the highest level of quality via continous feedback, contributions, implementations and reviews from the community. As collective production, innovation through collaboration and transparent working environment are among the key values of IDSA, we endeavor to provide a common ground to discuss, democratize and enhance the ongoing development processes by following the Open Source path.

Anybody who is interested in expressing their ideas and/or would like to be part of IDS developers community, are welcome to join and contribute.

## What is Inside? 

### Architecture/Overview
Reference Architecture Model of International Data Spaces (IDS-RAM) sets the standard for building data-driven ecosystems, products and services. Here is where you will find everything you need to know to get started. IDS-RAM comprises the standards for secure and sovereign data exchange, certification and governance for across Europe and around the world. 

You can find the latest version of [IDS-RAM on IDSA Website](https://internationaldataspaces.org/publications/most-important-documents/) along with [white papers](https://internationaldataspaces.org/publications/papers-studies/) listing the specifications of IDS components.

   **Repositories**
   
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
   
   
   [metadata-broker-open-core](https://github.com/International-Data-Spaces-Association/metadata-broker-open-core)
   is the repository of the open-core reference implementation of the IDS Metadata Broker. 
   
   
   [InformationModel](https://github.com/International-Data-Spaces-Association/InformationModel)
   implements the IDS reference architecture as an extensible, machine readable and technology independent data model.
   
   
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
   

### Components
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
   
### Communication
Message Structure/Format
Message Types
Protocols (Examples for implementing the messages)
IDSCP
IDS-LDP

### InfoModel -> as a reference to the IM-Repo with a short description

### UsageControl
Policies
Enforcement

### Glossary: file with all relevant IDS terms
    -   shortcuts: file with all shortcuts

### Handbook

### Resources:
    -   IDS-G-Logo

# Awesome OPC UA with stars

> A curated list of Open Platform Communications Unified Architecture (OPC UA) libraries, tools and resources. Inspired by awesome-... stuff.

Including the information from [traversaro/awesome-opcua](https://github.com/traversaro/awesome-opcua) ⭐ 3 | 🐛 0 | 📅 2021-06-09

Open Platform Communications Unified Architecture (OPC UA) is the data exchange standard for safe, reliable, manufacturer- and platform-independent industrial communication.

For a brief introduction to OPC UA, check the [What is OPC? UA in a Minute](https://www.youtube.com/watch?v=-tDGzwsBokY).

See the [official OPC Foundation site](https://opcfoundation.org/about/opc-technologies/opc-ua/) for the official specifications and more information about the OPC UA standard.

## Contents

* [Awesome OPC UA](#awesome-opc-ua-)
  * [OPC UA Standards Documents](#opc-ua-standards-documents)
    * [Resources](#resources)
      * [Online Resources](#online-resources)
      * [Books](#books)
      * [Articles](#articles)
      * [Videos](#videos)
      * [Podcasts](#podcasts)
    * [Software](#software)
      * [SDKs and Libraries](#sdks-and-libraries)
        * [C](#c)
        * [C++](#c-1)
        * [C#](#c-2)
        * [JavaScript/TypeScript](#javascript--typescript)
        * [Java](#java)
        * [MATLAB](#matlab)
        * [NuGet Packages](#nuget-packages)
        * [PHP](#php)
        * [Python](#python)
        * [Rust](#rust)
        * [Golang](#golang)
        * [Delphi](#delphi)
      * [Cloud](#cloud)
      * [Test Clients](#test-clients)
      * [Modelling Tools](#modelling-tools)
      * [Monitoring Tools](#monitoring-tools)
      * [Online Tools](#online-tools)
      * [SimulationServer](#server-simulations)
      * [Server and Client examples](#server-and-client-applications)
    * [Gateways (OPC Classic)](#gateways-opc-classic)
    * [Community](#community)
    * [Related Lists](#related-lists)
    * [Tutorials](#tutorials)
    * [Contribute](#contribute)
    * [License](#license)

## OPC UA Standards Documents

*Released OPC UA Specifications.*

* [OPC Foundation Git repository of NodeSets](https://github.com/OPCFoundation/UA-Nodeset) ⭐ 278 | 🐛 17 | 🌐 C# | 📅 2026-08-18 - easy way to get the nodeset files without registration
* [OPC Foundation Documents Overview](https://opcfoundation.org/developer-tools/documents/) - All Documents (Specification, Templates, Guidelines) published by the OPC Foundation
* [OPC Unified Architecture Specification](https://opcfoundation.org/developer-tools/specifications-unified-architecture) - OPC UA Specification published by the OPC Foundation. Needs registration for download.
* [OPC UA Information Models](https://opcfoundation.org/developer-tools/specifications-opc-ua-information-models) - OPC UA Companion Specifications released by the OPC Foundation. Needs registration for download.
* [OPC UA Online Reference](https://reference.opcfoundation.org/) - Online versions of OPC UA specifications and information models. Harder to read than the PDF versions due to each chapter being a separate site. Search function over all parts of the standard and the information models.

## Resources

*Information material apart from the standards documents.*

### Online Resources

*Information material available online.*

* [OPC Foundation Online Reference](https://reference.opcfoundation.org/)
* [OPC UA Profile Reporting Application](https://profiles.opcfoundation.org/) - UA 1.05 forward
* `deprecated` [OPC Foundation UA Profile Reporting Visualization Tool](https://profiles-old.opcfoundation.org/) - Overview of OPC UA Profiles.
* `deprecated` [OPC Foundation UA Profile Reporting Visualization Tool with drafts](https://profiles-old.opcfoundation.org/v104/reporting/?All=true) - Same as above including (stable) drafts.
* [OPC Foundation Templates](https://opcfoundation.org/developer-tools/documents/) - (select the "Template" filter) Templates for (joint) working groups. Including MS Visio shapes for OPC UA.
* `no longer available`~~[OPC Foundation OPC UA Wiki](http://wiki.opcfoundation.org/index.php?title=Main_Page) - OPC UA Wiki of the OPC Foundation.~~
* `updated`[OPC Foundation Information Modelling Best Practices](https://reference.opcfoundation.org/Model-Best/v102/docs/) - Whitepaper intended to provide best practices while creating OPC UA information models.
* [List of Collaborations Groups on Companion Specifications](https://docs.google.com/spreadsheets/d/10SOpad6uu7JA5ZSpccVyqaqkyhYBiIXqNus28-1cJtU/edit#gid=1248333029) - Overview of the different standardization activities
* `depublished` ~~<https://opcua.rocks/> - blog about OPC UA~~
* <https://sandervandevelde.wordpress.com/> - IoT Blog (use also OPC UA in some projects)
* [OPCUA CS Graph](https://iswunistuttgart.github.io/opcua-cs-graph/) - Graph that shows the dependencies between Companion Specification
* [GitHub Org of the OPC Foundation](https://github.com/OPCFoundation) - different software projects and reference implementations

### Books

*Books about OPC UA.*

* *Wolfgang Mahnke, Stefan-Helmut Leitner, Matthias Damm*, OPC Unified Architecture. *Springer; 2009*, ISBN: 978-3540688983.
* *Etienne Rossignon*, [NodeOPCUA by example - edition 2024](https://leanpub.com/node-opcuabyexample-edition2024)

### Articles

* [OPC UA for Devs in 10 Minutes](https://github.com/umati/hackathon/blob/main/2nd_hackathon/Presentations/20230516_OpcUaIn10Minutes.pdf) ⭐ 3 | 🐛 11 | 🌐 C# | 📅 2026-08-28 - short presentation for developers to grasp the concept of OPC UA information modelling
* [A Literature Survey on Open Platform Communications (OPC) Applied to Advanced Industrial Environments](https://www.mdpi.com/2079-9292/8/5/510) A literature Survey for OPC UA in 2019 with Trends and Open Research Issues
* [OPC UA versus ROS, DDS, and MQTT: performance evaluation of industry 4.0 protocols](https://mediatum.ub.tum.de/doc/1470362/file.pdf)
  Performance evaluation of differente protocols
* [Benchmarking of existing OPC UA implementations for Industrie 4.0-compliant digitalization solutions](https://ieeexplore.ieee.org/abstract/document/8104838)
  Compare different implementations for OPC UA
* [Designentscheidungen für OPC-UA-Informationsmodelle](https://www.ingenieur.de/fachmedien/wt-werkstattstechnik/ausgaben-wt-werkstattstechnik-online/inhalte-der-online-ausgabe-5-2020/) (German) Description of OPC UA Design decisions in OPC UA for Weighing Technology and OPC UA for Machine Tools
* [Der Trend zur branchenorienterten OPC UA Companion Specification und deren Herausforderungen](https://www.der-maschinenbau.de/markt-trends-technik/der-trend-und-seine-herausforderungen/) (German) Descriptes the Trends of OPC UA Companion Specification
* [File transfer via OPC UA](https://www.interop4x.de/news/file-transfer-opcua) compare the OPC UA file transfer with other protcols like HTTP, FTP

### Videos

* [What is OPC? UA in a Minute](https://www.youtube.com/watch?v=-tDGzwsBokY)
* [Tech-Intro "OPC UA Concepts" by Uwe Steinkrauss (06-2019)](https://www.youtube.com/watch?v=E2XJfmAEdqw) - A 10 minutes technical introduction to OPC UA basic concepts.
* [20200622 02 OPC UA Technology](https://www.youtube.com/watch?v=OQC_kVYisS8) - 20 min Introduction into OPC UA (OPC UA Day 2020)
* [OPC UA Security Deep Dive by Randy Armstrong (Chair of OPC UA Security Working Group), Dec 2020](https://www.youtube.com/watch?v=pa82WydVtPY)
* [Creating Information Model and OPC UA Server Using NET - Industry40tv](https://www.youtube.com/watch?v=gxA7SDNLHgc)
* [YouTube Channel of the OPC Foundation](https://www.youtube.com/user/TheOPCFoundation)
* [OPC UA for Machine Tools YT Channel](https://youtube.com/playlist?list=PLkiLpeY1YPH1gEtEV7jmX9D8XPUEfS5EF)
* [OPC UA PubSub Explained, Jouni Aro (Prosys OPC), OPC Day Finland 2021](https://www.youtube.com/watch?v=FWtrruzOvr4\&list=PL98upRG1ESZSMFf18NK-OMFxNYWrIdHDU\&index=14)
* [Using Companion Specifications for type-based client applications](https://youtu.be/Ht2rxMkHGIs) - Shows how the umati dashboard works.

### Podcasts

* [OPC Foundation Podcast](https://opcfoundation.org/resources/podcast/) - Official OPC Foundation podcast that gives insight into the OPC UA technology, applications in different industries and answers questions from the audience.
* [OPC UA (OPC Unified Architecture) | Einfach Komplex Episode 17, May 2023](https://podcasters.spotify.com/pod/show/einfach-komplex/episodes/17-OPC-UA-OPC-Unified-Architecture--Industriestandard-zur-Datenkommunikation--Automatisierung--IoT-e238kj3) - (German) A 45min podcast about basic concepts, industry applications and comparison to MQTT

## Software

*Software for creating OPC UA Servers, Clients, Publishers, Subscribers or Information Models.*

### SDKs and Libraries

*SDKs to create OPC UA components.*

#### C

* [ASNeG](https://github.com/ASNeG/OpcUaStack) ⭐ 136 | 🐛 31 | 🌐 C++ | 📅 2025-02-02 - Server/Client
* [uaf](https://github.com/uaf/uaf) ⭐ 110 | 🐛 20 | 🌐 C++ | 📅 2026-07-10 - Client (wrapper over proprietary sdk)
* [NodesetLoader](https://github.com/matkonnerth/nodesetLoader) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2024-04-13 - Library for importing nodesets in xml schema, add nodeset import to open62541 \[MPL-2.0]
* [open62541](https://open62541.org/) - Open Source C (C99) implementation for Server/Client and Pub/Sub licensed under the Mozilla Public License v2.0. \[MPL-2.0]
* [OpenOpcUA](http://www.openopcua.org/) - Server/Client
* [OpenScadaUA Interface](http://oscada.org/websvn/filedetails.php?repname=OpenSCADA\&path=%2Ftrunk%2FOpenSCADA%2Fsrc%2Fmoduls%2Fdaq%2FOPC_UA%2FlibOPC_UA%2FlibOPC_UA.h) - only Server
* [UACL/CPP -](https://gitlab.com/falko.wiese/uacl_cpp) Server (wrapper over proprietary sdk)
* [S2OPC](https://gitlab.com/systerel/S2OPC) - Open Source C (C99) implementation for Server/Client and Pub/Sub \[Apache-2.0]
* [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-c-server-client-sdk-for-windows/) - Server/Client proprietary (Softing) \[Commercial]
* [OPC UA SDK/Toolkit für Embedded-Geräte](https://industrial.softing.com/de/produkte/opc-ua-and-opc-classic-sdks/uatoolkit-embedded.html) - C implementation for Server/Client and Pub/Sub \[Commercial]
* [Prosys OPC UA C/C++ SDKs](https://www.prosysopc.com/products/opc-ua-cplusplus-sdk/) - Server/Client proprietary \[Commercial]
* [Unified Automation C/C++ SDKs](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html) - Server/Client proprietary \[Commercial]

#### C++

* [freeopcua](https://github.com/FreeOpcUa/freeopcua) ⭐ 787 | 🐛 143 | 🌐 C++ | 📅 2024-08-14 - Open Source C++ OPC-UA Server and Client Library. \[LGPL-3.0]
* [QUaServer](https://github.com/juangburgos/QUaServer) ⭐ 121 | 🐛 7 | 🌐 C++ | 📅 2024-02-13 - Qt C++ wrapper for open62541 server stack. \[MIT]
* [QtOPCUA](https://doc.qt.io/qt-6/qtopcua-index.html) - Qt module that implements a Qt API to interact with OPC UA. \[LGPL-3.0]
* [ASNeG OPC UA Stack](https://asneg.github.io/projects/opcuastack) - Open source C++ framework for development and distribution of OPC UA client\server applications. \[Apache-2.0]
* [open62541pp](https://open62541pp.github.io/open62541pp/) - C++ wrapper of the open62541 OPC UA library. \[MPL-2.0]

#### C\#

* [UA.NET Standard](https://github.com/OPCFoundation/UA-.NETStandard) ⭐ 2,376 | 🐛 25 | 🌐 C# | 📅 2026-08-29 - Server/Client - Official OPC UA .NET Standard Stack from the OPC Foundation. \[GPL-2.0 / RCL dual licensed]
* [opc-ua-client](https://github.com/convertersystems/opc-ua-client) ⭐ 467 | 🐛 29 | 🌐 C# | 📅 2025-09-01- only Client \[MIT]
* [LibUA](https://github.com/nauful/LibUA) ⭐ 343 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Server/Client \[Apache-2.0]
* [h-opc](https://github.com/hylasoft-usa/h-opc) ⭐ 316 | 🐛 40 | 🌐 C# | 📅 2020-01-23 - OPC client made simpler, for UA and DA \[MIT]
* [UACL/CS](https://gitlab.com/falko.wiese/uacl_cs) - Client/Server (wrapper over proprietary sdk) \[LGPL-3.0]
* [Träger](https://opcua.traeger.de/) - Server/Client \[Commercial]
* [dataFeed OPC UA](https://data-intelligence.softing.com/de/produkte/datafeed-opc-sdks/datafeed-opc-ua-net-standard-sdks/) - Server/Client (Softing) \[Commercial]
* [QuickOPC](https://www.opclabs.com/products/quickopc) - Client (OPC Labs)
* [OPC UA .NET SDK](https://www.prosysopc.com/products/opc-ua-dotnet-sdk/) - Server/Client (Prosys) \[Commercial]
* [PicoOPC](https://www.opclabs.com/products/picoopc/for-dotnet) - OPC UA client library \[Commercial]
* [Unified Automation .NET SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html) - Server/Client \[Commercial]
* [Traeger .NET SDK](https://www.traeger.de/en/products/development/opcua/opcua-sdk) - Server/Client SDK and Tools like Codabix \[Commercial]

#### JavaScript / TypeScript

* [HBM/opcua](https://github.com/HBM/opcua) ⚠️ Archived - only Client \[MIT]
* [node-opcua](http://node-opcua.github.io/) - Server/Client - NodeOPCUA is then OPC SDK UA stack fully written in TypeScript for Node.js. \[MIT]
* [node-red-contrib-opcua](https://flows.nodered.org/node/node-red-contrib-opcua) - Node-Red Plugin for OPC UA (Server/Client) \[Apache-2.0]
* [@opcua/for-node-red](https://flows.nodered.org/node/@opcua/for-node-red) - Professional OPCUA for NodeRED \[Commercial]
* [@plus4nodered/opcua](https://plus4nodered.com) - Professional OPC UA packages as a PLUS for Node-RED and FlowFuse inspired by our deprecated node-red-contrib-iiot-opcua package [P4NR B2B Community](https://p4nr.com/)
* [@p4nr/opcua-webapp-framework](https://plus4nodered.com) - Professional OPC UA Framework based on node-opcua for Node.js Web-Apps to make it easier to use OPC UA in Web-Apps [P4NR B2B Community](https://p4nr.com/)

#### Java

* [Eclipse Milo™](https://github.com/eclipse/milo) ⭐ 1,383 | 🐛 4 | 🌐 Java | 📅 2026-08-19 - Server/Client - Java open source implementation of OPC UA (IEC 62541). \[EPL-2.0]
* [opcua4j](https://code.google.com/p/opcua4j/) - only Server
* [Prosys OPC UA](https://www.prosysopc.com/products/opc-ua-java-sdk/) - Server/Client proprietary

#### MATLAB

* [OPC Toolbox](https://www.mathworks.com/products/industrial-communication.html) - MATLAB official toolbox that supports OPC UA. See [Mathworks site](https://www.mathworks.com/discovery/opc-ua.html) for more details. \[Commercial]

#### NuGet Packages

* [OPCFoundation.NetStandard.Opc.Ua](https://www.nuget.org/packages/OPCFoundation.NetStandard.Opc.Ua/) - NuGet Package of the Reference Implementation [\[OPC-F redistributables license\]](https://opcfoundation.org/license/redistributables/1.3/)
* [PicoOPC](https://www.opclabs.com/products/picoopc/for-dotnet) - OPC UA client library (OPC Labs) \[Commercial]

#### PHP

* [php-opcua](https://github.com/php-opcua) - Client \[MIT]

#### Python

* `deprecated`[Python FreeOpcUa](https://github.com/FreeOpcUa/python-opcua) ⭐ 1,489 | 🐛 428 | 🌐 Python | 📅 2024-05-18 - Server /Client \[LGPL-3.0]
* [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) ⭐ 1,469 | 🐛 245 | 🌐 Python | 📅 2026-08-27 - OPC UA / IEC 62541 Client and Server for Python >= 3.7 and pypy3. \[LGPL-3.0]
* [uaf](https://github.com/uaf/uaf) ⭐ 110 | 🐛 20 | 🌐 C++ | 📅 2026-07-10 - Client (wrapper over proprietary sdk) \[LGPL-3.0]

#### Rust

* [locka99/opcua](https://github.com/locka99/opcua) ⭐ 574 | 🐛 114 | 🌐 Rust | 📅 2025-04-08 - OPC UA server / client API implementation for Rust. \[MPL-2.0]
* [HMIProject/open62541](https://github.com/HMIProject/open62541) ⭐ 34 | 🐛 11 | 🌐 Rust | 📅 2026-07-30 - crate provides high-level, safe bindings for the C99 library open62541. \[MPL-2.0]

#### Golang

* [gopcua/opcua](https://github.com/gopcua/opcua) ⭐ 1,058 | 🐛 27 | 🌐 Go | 📅 2026-08-09 - Server/Client - A native Go implementation of the OPC/UA Binary Protocol. \[MIT]
* [awcullen/opcua](https://github.com/awcullen/opcua) ⭐ 112 | 🐛 7 | 🌐 Go | 📅 2026-02-08 - Server/Client. \[MIT]

#### Delphi

* [Sentrol SDK for Delphi](https://www.prosysopc.com/products/opc-ua-sentrol-sdk/) - Server/Client proprietary (Prosys) \[Commercial]
* [Unified Automation Delphi SDK](https://www.unified-automation.com/products/sdk-overview/choose-sdk.html) - Server/Client proprietary \[Commercial]

### Cloud

* [OPC UA with Akri](https://docs.akri.sh/discovery-handlers/opc-ua) - A Kubernetes Resource Interface for OPC UA \[Apache-2.0]

### Test Clients

*Test Clients to check server implementations manually.*

* [FreeOpcUA](https://github.com/FreeOpcUa/opcua-client-gui) ⭐ 670 | 🐛 57 | 🌐 Python | 📅 2026-08-05 - OpenSource Client based on python. \[GPL-3.0]
* [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) ⭐ 147 | 🐛 1 | 🌐 C# | 📅 2026-07-16 - Lightweight, cross-platform terminal-based OPC UA client with real-time oscilloscope view. Keyboard and mouse friendly. \[MIT]
* [OPC UA Browser](https://github.com/basysKom/opcua_browser) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2025-06-11 - Qt-based Mobile app based on open62541/Qt OPC UA. \[GPL-3.0]
* [OPC UA Test tool](https://github.com/matkonnerth/opcuatesttool) ⭐ 6 | 🐛 10 | 🌐 C++ | 📅 2026-02-18 - Automate OPC UA server performance testing
* [UaExpert](https://www.unified-automation.com/products/development-tools/uaexpert.html) - General purpose graphical test client supporting OPC UA features like DataAccess, Alarms & Conditions, Historical Access and calling of UA Methods by Unified Automation \[Commercial] (free evaluation license).
* [opcua-commander](https://npmjs.com/package/opcua-commander) - Client Browser for the CLI to interact with OPC UA servers using ncurses. \[MIT]
* [dataFEED](https://data-intelligence.softing.com/de/produkte/opc-software-plattform/opc-ua-demo-client/) - Demo Client developed by Softing (free)
* [Prosys OPC UA Monitor](https://www.prosysopc.com/products/opc-ua-monitor/) - HMI Tool (free evaluation license)
* [OPC UA Browser](https://www.prosysopc.com/products/opc-ua-browser/) - Demo Client developed by Prosys (free evaluation license).
* [OPC UA Vulnerability Scanner - OpalOPC](https://opalopc.com/) - A vulnerability scanner for OPC UA applications. \[GPL-3.0]

### Modelling Tools

*Tools to create OPC UA Information Models.*

* `deprecated` [FreeOpcUa/opcua-modeler](https://github.com/FreeOpcUa/opcua-modeler) ⭐ 259 | 🐛 51 | 🌐 Python | 📅 2022-02-13 - Free OPC UA Modeler is a tool for designing OPC UA address spaces \[GPL-3.0]
* [UA-ModelCompiler](https://github.com/OPCFoundation/UA-ModelCompiler) ⭐ 172 | 🐛 30 | 🌐 C# | 📅 2026-08-01 - Tool to convert OPC UA Information models in Model.xml format to NodeSet2.xml Format. \[MIT]
* [NodeDoc](https://github.com/software-competence-center-hagenberg/NodeDoc/) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2025-03-20 - Tool for documentation and comparing nodesets \[MIT]
* [UML2OPCUA](https://github.com/model-UA/papyrus-opcua-plugin) ⭐ 7 | 🐛 8 | 🌐 Java | 📅 2021-12-07 - Papyrus plugin to model OPC UA Information models with Papyrus
* [UAModeler](https://www.unified-automation.com/products/development-tools/uamodeler.html) - Modeling Tool by Unified Automation. \[Commercial]
* [OPC UA Modeler](https://www.prosysopc.com/products/opc-ua-modeler/) - Modeling Tool by Prosys \[Commercial]
* [SiOME](https://support.industry.siemens.com/cs/document/109755133/siemens-opc-ua-modeling-editor-%28siome%29-for-implementing-opc-ua-companion-specifications?dti=0\&lc=en-WW) - Modeling Tool by Siemens \[Commercial]
* [Sterfive's LowCode Modeler](https://www.sterfive.com/product/modeler/) - Low code tool to generate compliant OPCUA Model with ease, provide a single source of truth for your model, the doc and the nodeset2.xml) \[Commercial] \[Free evaluation]

### Monitoring Tools

* [prometheus\_asyncua\_exporter](https://github.com/ainglessi/prometheus_asyncua_exporter) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2026-08-11 - OPC UA exporter for Prometheus \[Apache-2.0]

### Online Tools

*Tools available online to help with OPC UA components or Information Models.*

* [OPC UA for Cloud Library](https://uacloudlibrary.opcfoundation.org/) - OPC UA Information Model database with a REST and GraphQL interface ([Source](https://github.com/OPCFoundation/UA-CloudLibrary) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2026-08-23)
* [OPC UA CloudViewer](https://cloudviewer.umati.app/) - Make the XML NodeSets browsable, by DigitalTwinConsortium ([Source](https://github.com/digitaltwinconsortium/UA-CloudViewer) ⭐ 40 | 🐛 1 | 🌐 JavaScript | 📅 2025-02-11).
* [OPC UA NodeSet Validator](https://apps.opcfoundation.org/NodeSetValidator/) - Check NodeSet XML Files against Word Documents following the OPC Foundation Specification Template.

## Server Simulations

*Implementations of Example, Simulation and SampleServer that are running on the internet or can be run local.*

* [List of publicly availavle OPC UA Servers and Clients](https://github.com/node-opcua/node-opcua/wiki/publicly-available-OPC-UA-Servers-and-Clients) ⭐ 1,655 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-29
* `opc.tcp://milo.digitalpetri.com:62541/milo` - [Demo Server](https://github.com/eclipse/milo#public-demo-server) ⭐ 1,383 | 🐛 4 | 🌐 Java | 📅 2026-08-19 based on eclipse/milo
* [Azure OPC UA Sample](https://github.com/Azure-Samples/iot-edge-opc-plc) ⭐ 293 | 🐛 1 | 🌐 C# | 📅 2026-08-19 - sample server in c#
* `opc.tcp://opcua.umati.app:4840` - [umati Demo Server](https://github.com/umati/Sample-Server) ⭐ 61 | 🐛 15 | 🌐 C++ | 📅 2026-08-29 implementing different umati endorsed companion specifications, based on [open62541](https://open62541.org/)
* `opc.tcp://opcua.umati.app:4843` - [umati Demo Server 3](https://github.com/umati/Sample-Server-node-opcua) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-28 implementing different umati endorsed companion specifications, based on [node-opcua](https://node-opcua.github.io/)
* [OPC UA Player](https://github.com/MileBuurmeijer/OPCUA-Player) ⭐ 18 | 🐛 1 | 🌐 Java | 📅 2026-07-12 - supports replaying OPC UA data from a data file
* `opc.tcp://opcua.umati.app:4842` - [umati Demo Server 2](https://github.com/umati/Sample-Server-asyncio) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2026-08-26 implementing different umati endorsed companion specifications, based on [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) ⭐ 1,469 | 🐛 245 | 🌐 Python | 📅 2026-08-27
* [OPC UA Simulation Server](https://www.prosysopc.com/products/opc-ua-simulation-server/) - free (professional Edition can import own information model)
* `depublished` ~~`opc.tcp://opcua.rocks:4840` - Demo Server based on open62541~~
* `opc.tcp://opcuademo.sterfive.com:26543` - [Demo Server based on NodeOPCUA](https://github.com/node-opcua)
* [UaExpert file with OPC UA servers accessible online](https://www.interop4x.de/en/news/uaexpert-project-file)

## Server and client applications

*Implementations of server and client applications and other examples.*

* [convertersystems/opc-ua-samples](https://github.com/convertersystems/opc-ua-samples) ⭐ 114 | 🐛 1 | 🌐 C# | 📅 2023-01-16 - Sample HMIs using OPC Unified Architecture (OPC UA) and Visual Studio. \[MIT]
* [umati Sample Server](https://github.com/umati/Sample-Server) ⭐ 61 | 🐛 15 | 🌐 C++ | 📅 2026-08-29 based on [open62541](https://github.com/open62541/open62541) ⭐ 3,219 | 🐛 827 | 🌐 C | 📅 2026-08-29 \[MPL-2.0]
* [UA-CloudLibrary](https://github.com/OPCFoundation/UA-CloudLibrary) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2026-08-23 - The reference implementation of the UA Cloud Library \[MIT]
* [UA-CloudDashboard](https://github.com/barnstee/UA-CloudDashboard) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-13 - A cloud-based, dockerized dashboard for displaying OPC UA PubSub telemetry data, read directly from an Azure IoT Hub. \[MIT]
* [umati Sample Server 3](https://github.com/umati/SampleServer-node-opcua) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-28 based on [node-opcua](http://node-opcua.github.io/) \[APL-2.0]
* [MQTTPublisherMVP](https://github.com/barnstee/MQTTPublisherMVP) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2023-11-24 - Minimum Viable Product for an MQTT-based OPC UA PubSub Publisher for industrial cloud telemetry. \[MIT]
* [umati Sample Server 2](https://github.com/umati/Sample-Server-asyncio) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2026-08-26 based on [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) ⭐ 1,469 | 🐛 245 | 🌐 Python | 📅 2026-08-27 \[APL-2.0]
* [OPC Router Docker Sample](https://github.com/OPC-Router/opc-ua-umati-mssql-grafana) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2023-09-26 - A very easy to use sample showcasing data transfers from a umati server to a SQL database.
* [opcua-skills/plug-and-produce](https://github.com/opcua-skills/plug-and-produce) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2021-04-24 - Plug-and-Produce System Architecture for Robotic Applications using OPC UA \[proprietary]
* [OPC UA for Joining Systems](https://github.com/umati/UA-for-Industrial-Joining-Technologies) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-08-29 - Test clients and servers based on OPC UA for Joining Systems developed by VDMA Industrial Joining Technologies working group. \[APL-2.0]
* [OPCModbusUAServer](https://github.com/BoBiene/OPCModbusUAServer) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2021-12-20 - An open source OPC UA server for Modbus TCP devices \[MIT]
* [OPC UA primer](https://github.com/ntd/opcua-primer) ⭐ 5 | 🐛 0 | 🌐 Makefile | 📅 2026-04-16 - A sample OPC UA server based on `open62541` and on a model design XML. \[MIT]
* [opcua-machinery-client](https://github.com/AndreasHeine/opcua-machinery-client) ⭐ 5 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-27 - Client example showcaseing the OPC UA for Machinery from a data consumer perspective. \[MIT]
* [OPC UA Transformer](https://github.com/alw-iwu/opcua-transformer) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2022-08-26 - Transforms OPC UA Server address space into RDF data structure \[APL-2.0]
* `deprecated`[OPCUA2AAS](https://github.com/umati/OPCUA2AAS) ⚠️ Archived - OPC UA Server that can generate an Industry 4.0 Asset Admin Shell from its info model. \[MIT]
* [umati Dashboard](https://umati.app) - umati community online dashboard - [Specification](https://showcase.umati.org)
* [OPC UA Thermometer with Akri](https://docs.akri.sh/demos/opc-thermometer-demo) - A demo of Akri - Discovering and Using OPC UA Thermometers \[APL-2.0]

## Gateways (OPC Classic)

coming soon

## Community

* [Stack Overflow](https://stackoverflow.com/tags/opc-ua) - Questions related to OPC UA in Stack Overflow.
* [OPC Foundation Twitter](https://twitter.com/OPCFoundation) - Official OPC Foundation account that shares update about the OPC UA standard.
* [OPC Foundation Ebooks](https://opcfoundation.org/resources/ebooks/) - Information about OPC UA technology and applications in different industries as contributions by various authors.

## Related Lists

* [open62541's List of Open Source OPC UA Implementations](https://github.com/open62541/open62541/wiki/List-of-Open-Source-OPC-UA-Implementations) ⭐ 3,219 | 🐛 827 | 🌐 C | 📅 2026-08-29 - List of open source OPC UA implementations.
* [Agile-IoT/awesome-open-iot](https://github.com/Agile-IoT/awesome-open-iot) ⭐ 706 | 🐛 8 | 📅 2023-12-21 - A curated list of awesome open source IoT frameworks, libraries and software.

## Tutorials

* `depublished` ~~[From modelling to execution – OPC UA Information Model Tutorial](https://opcua.rocks/from-modelling-to-execution-opc-ua-information-model-tutorial/) - Complete walkthrough from creating a custom OPC UA information model, compiling this model into an OPC UA `NodeSet2.xml` file, and then using the `open62541` OPC UA stack to create a running OPC UA server.~~
* `depublished` ~~[Visualizing OPC UA Information Model using Graphviz](https://opcua.rocks/visualizing-opc-ua-information-model-using-graphviz/) - Tutorial on how to use Graphviz to visualize OPC UA Information Models.~~
* (WIP) [OPC UA Tutorials](https://github.com/AndreasHeine/opcua-tutorial) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2025-03-06 - Tutorial for [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) ⭐ 1,469 | 🐛 245 | 🌐 Python | 📅 2026-08-27

## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[CC0 1.0 Universal](LICENSE)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._

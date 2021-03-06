---
layout: article
title: Presentation
subtitle: Reference Documentation
relativePath: ..
---

These reference documentation describes in detail all the features available in UML Designer. We will follow the different kind of users of UML Designer and see which features are available for them to develop systems.

Context
-------

Today, it exists many proprietary UML modelers available on the market. Some of them are supporting the SysML standard. A large part of these tools are not completely compliant with the UML standard. None of them are providing viewpoint extensions. The purpose of UML Designer is to provide an industrial UML/SysML viewpoint based designers compliant with the standards.

The UML Designer product is composed by one designer : a UML Designer. We provide a second designer to work with the SysML standard : SysML Designer.

### UML Designer

The UML Designer is a graphical designer compatible with the [UML2 specification](http://www.omg.org/spec/UML/2.5/Beta2) and based on [Sirius](http://eclipse.org/sirius).
UML 2.5 has 23 types of diagrams divided into two categories:

![]({{page.relativePath}}/images/uml-25-diagrams.png)](http://www.uml-diagrams.org/uml-25-diagrams.html)

It is released as Eclipse plugins under the EPL License and a standalone product is also built.

### SysML Designer

The SysML Designer is a graphical designer compatible with the [SysML specification](http://www.omg.org/spec/SysML/1.3/) and based on [UML Designer](http://umldesigner.org) and [Sirius](http://eclipse.org/sirius).
SysML has 8 types of diagrams divided into three categories:

![]({{page.relativePath}}/images/SysML-Diagram-Taxonomy.png)

It is released as Eclipse plugins under the EPL License and is part of the [UML Discovery catalog]({{ page.relativePath }}/ref-doc/discovery.html), have a look to the discovery feature to learn how to install SysML Designer in the UML Designer product.

System purpose
--------------

Presently, the UML/SysML Designer does not cover all the diagrams described in the UML/SysML Standard. It is mainly focused on the diagrams which are used the most (Class diagrams, Use Case diagram...) and try to provide a straightforward user experience.
As these designers are based on Sirius, they offer the possibility to be extended through the viewpoint mechanism. Through this, the intent is also to provide an easy way to make the transition from UML to domain specific modeling. This way users can continue to manipulate legacy UML models and start working with DSL. Users can even re-use the provided representations and work in a total transparency on both UML and DSL models at the same time.

Actor and Roles
---------------

This section describes the typical users of UML and SysML Designers.

-   **John**: 40 years old, he is an business analyst working in the french national railway company. He supports the development teams by giving them insights about the business process related to a given project. He produces functional specifications which are the basis of the development phase. His daily work consists in writing requirements and software specifications to detail the structure of new applications. He knows the UML standard and has already tried many different UML modelers (open source and proprietary). He also describes the hardware and software platforms on which the application is built and deployed. Finally, he gives the justification of how the architecture satisfies the expectations. He stays all the time in contact with the software developers team to be able to review the software architecture according to implementation constraints.

<!-- -->

-   **Bob**: 30 years old, works as a software architect at SSIICorp. He works for different customers on missions lasting a few months each. His work involves drafting and defining the software architecture, producing the corresponding documents for the customer and making sure the team is on board and applying the principles. He uses UML standard to exchange with its colleagues about the structure of the software they are developing. He uses the UML model also to generate the application code and sometime for retro engineering existing projects.

<!-- -->

-   **Alice**: 42 years old, works as software quality engineer at SSIICorp in collaboration with Bob. She is used to read UML diagrams to get overview of the features provided by the projects she is monitoring. She is also checking that these projects are well documented using the UML standard and she is checking the traceability between the requirements, the software architecture, the code and the tests. She uses UML modeler for consultation only.

<!-- -->

-   **Kevin**: 23 years old, works in a big company as software developer and does not care about UML, he learned the standard at school and found that it was boring. He has to use an UML modeler to write the documentation of the software he is developing. He does not choose to use UML, it was decided by its boss. He has to search a UML designer which is free. At the end it only needs beautiful images to put in its software documentation.

<!-- -->

-   **Teddy**: 20 years old, is a student in computer science. He has many projects to tackle and barely some time to do them, yet he has to deliver both the software and comprehensive reports to his teachers. He doesn't know much about IDEs or tools except those used during the courses.

<!-- -->

-   **Alfred**: 49 years old, works as system engineer in a big company. His daily work consists in designing heterogeneous systems. He knows the SysML standard and uses it every day in its specification. The systems he specifies are a mix of mechanics, electronics and softwares. He does not know the UML standard, just that SysML was developed based on it. He says that SysML is a good language to exchange with his colleagues but he thinks that the notation is too complicated. He tries to develop systems with some different SysML modelers by the past but usually he prefers to use a simple drawing tool with a SysML profile.

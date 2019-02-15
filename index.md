---
title: cloud4developers
layout: default
---

## Introduction
As a developer I have collected a lot of resources to help me write code, understand new technologies like [Watson](https://www.ibm.com/watson/) and [Blockchain](http://www.ibm.com/blockchain) and learn how to leverage the capabilities of the [IBM Cloud](https://www.ibm.com/cloud/) to develop cloud-native applications.  From the characteristics of a [Twelve Factor](https://12factor.net/) app, open source technologies like [docker](https://www.docker.com/) and [kubernetes](https://kubernetes.io/), the [IBM Cloud Garage Method](https://www.ibm.com/cloud/garage/) and patterns like [microservices architecture](https://www.ibm.com/cloud/garage/architectures/microservices/reference-architecture/), I've found excellent resources on all of these topics!

## Contacts
- Dave Wakeman
  - Email: [dwakeman@us.ibm.com](mailto:dwakeman@us.ibm.com)
  - Twitter: [@dwakeman](https://twitter.com/dwakeman)
  - LinkedIn: [davewakeman](https://www.linkedin.com/in/davewakeman/)


## General
- [Gartner](https://www.gartner.com/doc/reprints?id=1-4U4HD0D&ct=180327&st=sg) - Why You Must Begin Delivering Cloud-Native Offerings Today, Not Tomorrow 
- [IBM Code](https://developer.ibm.com/code/)
- [IBM Code - Patterns](https://developer.ibm.com/code/patterns/)
- [Kubernetes Patterns](https://developer.ibm.com/code/technologies/container-orchestration/)
- [IBM Cloud App Service](https://console.bluemix.net/developer/appservice/dashboard) - A fast on-ramp for building cloud native apps
- [IBM Cloud Garage Architecture Center](https://www.ibm.com/cloud/garage/architectures)
- [IBM Cloud Garage Practices](https://www.ibm.com/cloud/garage/category/practices)
- [How to rapidly develop apps with microservices](https://www.ibm.com/blogs/bluemix/2018/04/know-developing-applications-microservices/)

## Demos
- [IBM Cloud Healthcare and Life Sciences Demonstration](https://bluedemos.com/show/133)
- [IBM Cloud Featured Samples](https://ibm-cloud.github.io/#!/)
- [Modernize and extend apps on IBM Cloud Kubernetes Service](https://github.com/IBM-Cloud/jpetstore-kubernetes)

## Tutorials and Labs
- [IBM Cloud App Service - Learning resources](https://console.bluemix.net/developer/appservice/learning-resources)
- [IBM Cloud Tutorials](https://console.bluemix.net/docs/tutorials/index.html#tutorials)
- [IBM Code - How-tos](https://developer.ibm.com/code/howtos)
- [IBM Cloud Garage - Courses](https://www.ibm.com/cloud/garage/category/courses)

## Books
- [Phippy Goes to the Zoo: a Kubernetes Story](https://www.cncf.io/phippy-goes-to-the-zoo-book/)
- [Essentials of Application Development on IBM Cloud](http://www.redbooks.ibm.com/redpieces/abstracts/sg248374.html)
- [Developing Node.js Applications on IBM Cloud](http://www.redbooks.ibm.com/abstracts/sg248406.html)
- [Moving Microsoft Workloads to IBM Cloud](http://www.redbooks.ibm.com/Redbooks.nsf/RedbookAbstracts/redp5428.html?Open)
- [Microservices from Theory to Practice: Creating Applications in IBM Bluemix Using the Microservices Approach](http://www.redbooks.ibm.com/Redbooks.nsf/RedbookAbstracts/sg248275.html?Open)
- [Evolve the Monolith to Microservices with Java and Node](http://www.redbooks.ibm.com/abstracts/sg248358.html?Open)
- [Kubernetes in the Enterprise (O'Rielly)](https://ibm.biz/BdYA4i)


## DevOps
### Toolchains
- Learn about [toolchains](https://www.ibm.com/cloud/garage/toolchains)
- [Tutorial](https://www.ibm.com/cloud/garage/category/courses)
 
### Continuous Delivery
- [Continous Delivery](https://www.ibm.com/cloud/continuous-delivery)


## Series for Developers
- [developerWorks TV](https://developer.ibm.com/tv/)
- [IBM Code Dojo](https://developer.ibm.com/tv/ibm-code-dojo/)
- [Microservices TV](https://developer.ibm.com/tv/category/microservices/)
- [The New Builders](https://developer.ibm.com/tv/builders/)
- [DevOps TV](https://developer.ibm.com/tv/devops/)
- [Mailbag](https://developer.ibm.com/tv/dwmailbag/)
- [Technologies & Tools](https://developer.ibm.com/tv/topics/)


## Watson

- [Watson Accelerators](https://watsonaccelerators.mybluemix.net/portal/welcome)
- Zero to Cognitive - a great tutorial with a [Redbook](https://www.redbooks.ibm.com/redbooks.nsf/redbookabstracts/crse0400.html?Open), [YouTube videos](https://www.youtube.com/watch?v=Jj7IFjd3FyI&list=PLnJzIOiv6cVTaS8k90R3T9AlS_kf5XWmX) and a [Github Repo](https://github.com/rddill-IBM/ZeroToCognitive)

## Locations
<ul>
{% for page in site.pages %}
    {% if page.location == true and page.visible == true %}
    <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>

## Blockchain


### Presentations
- [IBM Blockchain Point of View](http://cloud4developers.github.io/docs/IBM-Blockchain-PoV.pdf)
- [Blockchain Explained](https://www.slideshare.net/MattLucas3/blockchain-explained-v513)
- [Vehicle Lifecycle Demo Intro](http://cloud4developers.github.io/docs/Vehicle-Lifecycle-Demo-Intro.pdf)
- [Blockchain Composer Explored](https://www.slideshare.net/MattLucas3/blockchain-hyperledger-composer-explored-v212)
- [Blockchain Architected](https://www.slideshare.net/MattLucas3/blockchain-architectures-explored-v30)
- [Blockchain Explored](https://www.slideshare.net/MattLucas3/blockchain-hyperledger-fabric-explored-v45)
- [Solutions Explained](https://www.slideshare.net/MattLucas3/ibm-blockchain-solutions-explained-v03)
- [IBM Blockchain Platform Explained](https://www.slideshare.net/MattLucas3/ibm-blockchain-platform-explained-v113)
- [What's New in Blockchain Technology](https://www.slideshare.net/MattLucas3/blockchain-whats-new-in-hyperledger-fabric-oct-2018)
- [IBM Cloud Garage with Blockchain](https://www.slideshare.net/MattLucas3/blockchain-ibm-cloud-garages-explained-v11)


### General
- [IBM Blockchain](http://www.ibm.com/blockchain)
- [What is Blockchain](https://www.ibm.com/blockchain/what-is-blockchain.html)
- [IBM and Hyperledger](https://www.ibm.com/blockchain/hyperledger.html)
- [Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains](https://arxiv.org/abs/1801.10228v1)
- [Hyperledger Fabric (read the docs)](https://hyperledger-fabric.readthedocs.io/en/release-1.1/)
- [Blockchain components in a network explained for developers](https://www.youtube.com/watch?v=sJaT2L99BUo)
- [How to be a Blockchain Network Founder](https://www.ibm.com/account/reg/signup?formid=urx-31528)
- [Forrester Total Economic Impact (TEI) Report](https://www.ibm.com/account/reg/us-en/signup?formid=urx-33572)

### For Developers
- [Develop a smart contract with the IBM Blockchain Platform VSCode extension](https://developer.ibm.com/tutorials/ibm-blockchain-platform-vscode-smart-contract/)
- [Run a commercial paper smart contract with the IBM Blockchain VSCode extension](https://developer.ibm.com/tutorials/run-commercial-paper-smart-contract-with-ibm-blockchain-vscode-extension/)
- [Develop in a cloud sandbox IBM Blockchain Platform](https://ibm-blockchain.github.io/)
- [IBM Docs - Deploy to IBM Blockchain Platform Starter Plan](https://console.bluemix.net/docs/services/blockchain/develop_starter.html#deploying-a-business-networks-on-starter-plan)
- [Blog on Deploying to IBM Blockchain Platform Starter Plan](https://hackernoon.com/deploy-a-business-network-on-free-ibm-blockchain-starter-plan-93fafb3dd997)
- [Blockchain on LinuxOne mainframe](https://developer.ibm.com/code/patterns/run-blockchain-technology-on-a-linux-mainframe/)
- [IBM Blockchain Developer Center](https://developer.ibm.com/blockchain/)
- [Blockchain Innovators Series on DeveloperWorks TV](https://developer.ibm.com/tv/blockchain-innovators/)
- [Hyperledger Community](https://hyperledger.github.io/composer/support/support-index.html)
- [Blockchain Essentials Badge](https://developer.ibm.com/courses/all/blockchain-essentials/)
- [IBM Blockchain foundation developer Badge](https://developer.ibm.com/courses/all/ibm-blockchain-foundation-developer/)
- [Call For Code: Dave Wakeman hands-on with Hyperledger Fabric](https://youtu.be/sBg9R0r_7oA)
- Learn how to [Use the IBM Blockchain Platform for a full fabric deployment](https://developer.ibm.com/tutorials/ibm-blockchain-platform-for-icp-full-fabric-deployment/)
- Learn how to [Operate a distributed peer on IBM Blockchain Platform](https://developer.ibm.com/tutorials/operate-distributed-peer-on-ibm-blockchain-platform/)

### Tutorials and Samples
- Hyperledger Fabric [Commercial Paper](https://hyperledger-fabric.readthedocs.io/en/release-1.4/tutorial/commercial_paper.html) tutorial
- [Build a blockchain insurance app](https://github.com/IBM/build-blockchain-insurance-app)
- Zero to Blockcahin - Tutorial with a [Redbook](https://www.redbooks.ibm.com/Redbooks.nsf/RedbookAbstracts/crse0401.html?Open), [YouTube videos](https://www.youtube.com/watch?v=CgGX-BTYOwA&list=PLnJzIOiv6cVTjaJRtJ2srarhs-m4V3zs3) and 
[Github Repo](https://github.com/rddill-IBM/ZeroToBlockchain)
- [Develop an IoT asset tracking app using Blockchain](https://developer.ibm.com/code/patterns/develop-an-iot-asset-tracking-app-using-blockchain/)

### Other interesting stuff
- [Vehicle Lifecycle Demo](https://www.youtube.com/watch?v=cNvOQp8r0xo&t=244)
- [Make your blockchain smart contracts smarter with business rules](https://www.ibm.com/developerworks/library/mw-1708-mery-blockchain/1708-mery.html)
- [Lab Guide](https://cloud4developers.github.io/docs/Blockchain-PoT-Lab-Workbook-v1.8.1.pdf)



---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: 'So what are capabilities good for? Well, frankly, capabilities are almost useless on their own. They only make sense when used in a broader context. '
datePublished: '2016-01-15T19:57:50.802Z'
dateModified: '2016-01-15T19:57:32.786Z'
title: Capabilities – what are they good for?
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-01-15-capabilities-what-are-they-good-for.md
published: true
url: capabilities-what-are-they-good-for/index.html
_type: Article

---
# Capabilities -- what are they good for?

As I have understood it, a capability is basically the ability to perform something and requiring a specific skill set to do so. The focus is on what someone or something does in order to fullfil its intended purpose. A capability doesn't directly address how it's done, when it's done, where it's done, by whom it's done or even why it's done. 

So what are capabilities good for? Well, frankly, capabilities are almost useless on their own. They only make sense when used in a broader context. ![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/995be571-a92f-462b-88dc-434c9b76e455.jpg)

I've seen a lot of people dismiss the concept of capabilities as redundant, and that capabilities and processes are virtually the same or that capabilities and functions are synonyms. Some even claim that capabilities are totally redundant and shouldn't exist as an architectural concept since they are not a part of the [Zachman][0] framework. Plus, a capability seems like a really abstract concept. So what are the benefits from using capabilities in your enterprise architectures? 

In my opinion we sometimes need an abstract element like capability in order to identify and visualize, for instance, competence development needs, organizational patterns, anti-patterns, unnecessary application redundancy, server rationalization potentials etc. I believe that capabilities as an architectural element really can facilitate the understanding and visualization of an enterprise. I like to consider capabilities as a notion that can be utilized in both human and organizational dimensions as well as in application and infrastructural dimensions. 

Another crux is; how do we use the notion of a capability in a model? How do we integrate a capability into a broader context that makes sense? Let's turn to some of the more established frameworks and meta models out there. How do they consider the notion of capabilities? 

According to the [Zachman][0] framework, capabilities are not part of the architectural framework. They can however be considered as abstract composites of roles, processes, technologies and entities. As a result, capabilities are constrained to only exist in relation to organizational or human actors. 

If we inspect the [Enterprise Business Motivational Model (EBMM)][1], we find a similar construct but capability is in fact a core element of the meta model. A capability is constrained to be a business capability, and the definition is 'an abstraction that represents the ability of a business unit to perform a particular business function or process'. EBMM is otherwise an appealing meta model for business architectures since it is mainly business centric. 

[TOGAF][2] on the other hand depicts capabilities as part of the architectural dimension itself. That is, in order to successfully operate an architecture function using the TOGAF ADM within an enterprise, you need organization, processes, roles, responsibilities and skills to provide architectural capabilities. TOGAF do mention business capabilities, but a business capability is considered a non-architectural element and just as in Zachman and EBMM it is some sort of composite construct not part of the core meta model. I find TOGAF suitable for modelling IT-architectures and to some extent even aligning business architecture and IT-architecture. When it comes to enterprise architecture though, TOGAF falls short since it is so IT-centric. 

[Enterprise Canvas][3] (great summary found [here][4]) is, IMHO, one of the most holistic, coherent, flexible and consistent frameworks I've stumbled upon. It's great for modeling true service oriented architectures, where everything is, or provides, a service. Enterprise Canvas defines a capability as 'the ability to do something, to some identifiable level of skill, as embedded in a machine, an IT-application and/or a real person'. When linking together a capability with a function you provide the ability to deliver a specific outcome, and that constitutes a service. Defining a path by linking a sequence of service transactions together, you get a process. The really neat thing about Enterprise Canvas is that it truly is a framework suitable for enterprise architectures. 

How and when would you use capabilities in your architectural profession?

[0]: http://www.zachman.com/
[1]: http://motivationmodel.com/
[2]: http://pubs.opengroup.org/architecture/togaf9-doc/arch/
[3]: http://weblog.tetradian.com/tag/enterprise-canvas/
[4]: http://tetradianbooks.com/ebook/ecanvas-summary.pdf
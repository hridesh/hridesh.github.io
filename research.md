---
layout: page
title: Research
permalink: /research/
---

My research interests span the following areas.

* Software Engineering (SE), programming languages (PL), and data science
* Data science, SE &amp; PL for data-intensive systems,
  and data-driven SE.
* Modular reasoning about properties of software.
* Advanced modularity and separation of concerns mechanisms
  and modular reasoning about such mechanisms.

### Recent Publications

An updated list of publications is available from my [lab web-pages](https://lab-design.github.io/papers/).


### Research Projects

My recent research has focussed on data science and concurrency.
My overarching research program is aimed at improving programmer productivity, and correctness of software systems that
they produce. In particular, I am interested in designing new programming abstractions that
abstract away error-prone concerns, improve modularity, and improve modular reasoning.
By abstracting away error-prone concerns, and having compilers and programming frameworks
automatically provide adequate implementation of such concerns, my research aspires to reduce
potential for errors in software, and improve productivity.
By improving modularity and modular reasoning, my research strives for improved scalability
in both manual and automatic reasoning as well as verification processes.
<!--I am interested in two specific questions: (1) <EM>how can we enable more modular reasoning 
about concurrent programs?</EM> and (2) <EM>what are adequate programming abstractions for 
data intensive programs (also popularly referred to as Big Data programs) that facilitate
reasoning about such programs?</EM>-->
My main research projects are:

### [Boa](http://boa.cs.iastate.edu)

 [Boa](http://boa.cs.iastate.edu) project is developing a domain-specific
 language and its infrastructure whose goal is to significantly ease the
 experimental cost of mining ultra-large-scale open source repositories.
 Boa is a research infrastructure that consists of a domain-specific language, its compiler and data
 updating tools, terabytes (and growing) of raw data from open source
 repositories that contains hundreds of thousands of open source projects,
 a backend based on map-reduce to effectively analyze this dataset,
 a compute cluster, and a web-based frontend for writing analysis programs.

 Boa project has been supported in part by the following grants.

 * US National Science Foundation, CI-EN: Boa: Enhancing Infrastructure for Studying Software and its Evolution at a Large Scale.
   PI: Hridesh Rajan and Co-I: Tien Nguyen, Robert Dyer (2015-2020),
   Total award amount: $1,559,806,
   Links: [ISU](http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1513263), and
   [BGSU](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1512947).

 * US National Science Foundation, 
   [EAGER: Boa: A Community Research Infrastructure for Mining Software Repositories](http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1349153).
   PI: Hridesh Rajan and Co-I: Tien Nguyen (2013-2015).


 Following research papers document progress on this project:

 * [ESEC/FSE'18](https://lab-design.github.io/papers/FSE-18/),
 * [ICSE'18 (1)](https://lab-design.github.io/papers/ICSE-18a/),
 * [ICSE'18 (2)](https://lab-design.github.io/papers/ICSE-18b/),
 * [ICSE'17 (NIER)](https://lab-design.github.io/papers/ICSE-NIER-17a/),
 * [MSR'17](https://lab-design.github.io/papers/MSR-17/),
 * [ICSE'14](https://lab-design.github.io/papers/ICSE-14),
 * [ICSE'13](https://lab-design.github.io/papers/ICSE-13),
 * [ASE'13](https://lab-design.github.io/papers/ASE-13),
 * [GPCE'13](https://lab-design.github.io/papers/GPCE-13)


### [SpecGuru](https://specguru.github.io)

 [SpecGuru Project](https://specguru.github.io) is developing techniques for inferring behavioral specifications
 that rely on both program analysis and data mining of data from open
 source repositories.

 SpecGuru project has been supported in part by the following grants.

 * US National Science Foundation, SHF: Large:Collaborative Research: Inferring Software Specifications from
   Open Source Repositories by Leveraging Data and Collective Community Expertise.
   PI: Hridesh Rajan and Co-I: Robert Dyer, Tien Nguyen, Gary T. Leavens, and Vasant Honavar (2015-2018),
   Links: [ISU](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1518897),
   [BGSU](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1518776),
   [UCF](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1518789), and
   [PSU](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1518732).


 Following research papers document progress on this project:

 * [OOPSLA'17](https://lab-design.github.io/papers/OOPSLA-17/),
 * [ICSE'17 (NIER)](https://lab-design.github.io/papers/ICSE-NIER-17b/),
 * [ICSE'15 (NIER)](https://lab-design.github.io/papers/ICSE-15b/), and
 * [FSE'14](https://lab-design.github.io/papers/FSE-14).


### [Panini](http://paninij.org)

 [Panini](http://paninij.org) project is developing the
 [Capsule-oriented Programming](https://lab-design.github.io/papers/TR-13-01) model.
 Capsule-oriented programming model is aimed at making concurrent software
 development easier by providing two properties:
 (1) given a module it ought to be possible to statically, and modularly identify all points
 in its code where other modules might interfere (interference points), and
 (2) given a module and the interfaces of other modules, that the subject module interacts with, it
 ought to be possible to statically and modularly construct an upper bound on the behavior
 of all potentially interferring tasks at each interference point.
 We show that if a programming model has these two properties, then it is possible to modularly
 reason about concurrent programs in that model.
 By the first property, humans and tools can identify points where interference from other
 concurrent tasks must be considered. By the second property, the computed upper bound can be
 used for reasoning instead of needing the implementation of interferring modules.
 Compared to alternatives, where reasoning either becomes a global process or entails a global
 step, modular reasoning afforded by this programming model makes both manual and automated
 reasoning about concurrent software more scalable. Panini project has been supported in part
 by the following grants.


  * US National Science Foundation,
   [SHF:Small: Capsule-oriented Programming](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1423370). PI: Hridesh Rajan
   (2014-2018), Award amount: $450,098.

  * US National Science Foundation, 
   [CAREER:On Mutualism of Modularity and Concurrency Goals](http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=0846059). PI: Hridesh Rajan
   (2009-2015), Award amount: $565,935.

  * US National Science Foundation, 
   [SHF:Small:Phase-Based Tuning for Better Utilization of Performance-Asymmetric Multicores](http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1117937).
   PI: Hridesh Rajan (2011-2015), Award amount: $416,000.


  Following research papers document progress on this project:

  * [OOPSLA'15](https://lab-design.github.io/papers/OOPSLA-15/),
  * [ICSE'15 (NIER)](https://lab-design.github.io/papers/ICSE-15a/),
  * [Modularity'15](https://lab-design.github.io/papers/MODULARITY-15/),
  * [ECOOP'15](https://lab-design.github.io/papers/ECOOP-15/),
  * [AGERE'14](https://lab-design.github.io/papers/AGERE-14/),
  * [Onward!'10](https://lab-design.github.io/papers/ONWARD-10/),
  * [GPCE'10](https://lab-design.github.io/papers/GPCE-10), and
  * [FoSER'10](https://lab-design.github.io/papers/FoSER-10/).



  We have created two software systems that support this programming model so far:

  * an extension of Java (and the reference compiler javac) that we call
    [PaniniJ](http://paninij.org), and 
  * an annotation-based framework that uses annotation processing facilities,
    instead of syntax extensions, that we call [@PaniniJ](http://hridesh.github.io/panini/).

#### [Ptolemy](http://ptolemy.cs.iastate.edu)

  [Ptolemy](http://ptolemy.cs.iastate.edu) project is developing an event-based
  language whose goal is to enable more modular reasoning about advanced separation
  of concerns mechanisms such as implicit invocation and aspects. Ptolemy provides
  [quantified-typed events](https://lab-design.github.io/papers/ECOOP-2008)
  that act as an interface between modules. A key benefit of quantified-typed events is
  that they allow programmers to write new kinds of contracts that we call
  [translucid contracts](https://lab-design.github.io/papers/AOSD-11)translucid contracts,
  which enables modular reasoning about modules that announce events and those
  that listen to events. Ptolemy project has been supported in part by the following
  grant.

  *  US National Science Foundation,
  [SHF:Small:Balancing Expressiveness and Modular Reasoning for Aspect-oriented Programming.](http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1017334)
  PI: Hridesh Rajan (2010 - 2013).


  Following research papers document progress on this project:

  * [Modularity'15](https://lab-design.github.io/papers/MODULARITY-15b/),
  * [Modularity'13](https://lab-design.github.io/papers/AOSD-13),
  * [TAOSD'13](https://lab-design.github.io/papers/TAOSD-13),
  * [AOSD'12](https://lab-design.github.io/papers/AOSD-12),
  * [FOAL'12](https://lab-design.github.io/papers/FOAL-12),
  * [AOSD'11](https://lab-design.github.io/papers/AOSD-11),
  * [FOAL'10](https://lab-design.github.io/papers/FOAL-10),
  * [TOSEM'09](https://lab-design.github.io/papers/TOSEM-09),
  * [ECOOP'08](https://lab-design.github.io/papers/ECOOP-2008),
  * [IEEE Software'06](https://lab-design.github.io/papers/Software-2006), and
  * [ESEC/FSE'05](https://lab-design.github.io/papers/ESEC-FSE-2005).


* [More projects...](https://lab-design.github.io/projects)


### Contact me

You can contact me using either of the e-mail addresses below. 
When writing, please substitute firstname with hridesh.

* Work: [firstname@iastate.edu](mailto:firstname@iastate.edu)
* Personal: [firstname@gmail.com](mailto:firstname@gmail.com)


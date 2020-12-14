# Previous scientific work
These are all my theses - bachelor thesis, study project and master thesis. 

## Master thesis: DNA as a storage - Error Detection based on Cyclic Codes
The main reason why scientists decided to look at DNA as an alternate storage medium is due to the properties it possesses: capacity (3 pgrams ~6.4Gbs), stability and self-assembly potential. Despite research in both theoretical and experimental worlds, there is no clear step-by-step guide of how exactly DNA storage works, what components are necessary to create even simulation of the working system. There is no comprehensive description of biological components and sequencing algorithms for reading DNA back and assembling it for electrical engineers. Problem that is also addressed in this thesis is the DNA sequencing. The popularity of modern second-generation sequencers(sequencer reads DNA from the unknown sample of molecules) increases and almost every sequencing lab is using them. Even though the accuracy of DNA sequencers to read back genome without errors increases(98%), they are still imposing problems when sequencing long strands of DNA sample by using reads longer than 300 characters.

The thesis provides:
- compiled comprehensive guide for electrical engineers to jump-start the topic of DNA as storage and basic prerequisite biology and computer science;
- a virtual simulation of the system on python;
- a unique way of encoding data, such that when collected back together, it is possible to detect erroneous parts of sequenced DNA. 

The empirical analysis was conducted on toy-parameter example, where parameters were assumed to be proportional to real-world parameters. A thesis serves as a comprehensive guide for communication specialists or bioinformaticians on basics of DNA as a storage. This thesis is private for a moment - in talks for becoming public... ;)

## Study project: Application Programming Interface for Error Control Codes
The topic of study project and seminar thesis is about application programming interface for error control codes called Teabag API. Initially the goal was to exploit generalized concatenated Reed-Solomon codes for synthesized DNA storage. As a choice programming language was Python and unfortunately there were no established error control coding libraries. The goal has been altered to develop an application programming interface for error control coding field with model driven software engineering techniques. Software design patterns such as builder pattern have been utilized for development of socalled plugin system. Alongside the Teabag API we also provide documentation and abstract syntax - rules for development of generic system, for example software that can generate code, test cases and system components. Such a project can even lead to development of a domain-specific language.

## Bachelor thesis: Analysis of object and face detection systems - development of cascade
This  work  is  devoted  to  the  development  of  an  information  system  for  pattern recognition.  Methods  for  developing  applications  on  OpenCV  technology  in  the programming language Python are discussed in detail. Based on the features of the language described in the work, the application itself is developed on this platform and  a  new  cascade  is  generated  for  further  use.  Detailed  methods  for  recognizing faces when developing an application are described.Main goals:As an example, based on the OpenCV library in a virtual environment, demonstrate the cascade workout and develop an appropriate algorithm for the application. This paper considers three main tasks:
- Development of an algorithm for recognizing faces
- Development of an algorithm for object recognition
- Training of the cascade for further use in the form of an .xml document

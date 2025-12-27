# Previous scientific work
These are all my theses: the bachelor's thesis, the study project, and the master's thesis. 

## Master's thesis: DNA as a storage - Error Detection based on Cyclic Codes
The main reason scientists decided to look at DNA as an alternative storage medium is its properties: capacity (3 pg ~6.4 Gb), stability, and self-assembly potential. Despite research in both theoretical and experimental domains, there is no clear step-by-step guide on exactly how DNA storage works or which components are necessary to create even a simulation of the working system. There is no comprehensive description of biological components and sequencing algorithms for reading DNA back and assembling it for electrical engineers. A problem addressed in this thesis is DNA sequencing. The popularity of modern second-generation sequencers (which read DNA from unknown samples) is increasing, and almost every sequencing lab is using them. Even though the accuracy of DNA sequencers in reading the genome without errors increases (98%), they still pose problems when sequencing long DNA strands using reads longer than 300 characters.

The thesis provides:
- compiled a comprehensive guide for electrical engineers to jump-start the topic of DNA as storage, and basic prerequisite biology and computer science;
- a virtual simulation of the system on Python - [repo](https://github.com/feeka/mt_dna_as_storage/);
- a unique way of encoding data, such that when collected back together, it is possible to detect erroneous parts of sequenced DNA. 

We conducted an empirical analysis of a toy-parameter example, assuming the parameters were proportional to their real-world counterparts (at the time, the field was coming up). A thesis serves as a comprehensive guide for communication specialists or bioinformaticians on the basics of DNA as a storage medium. 

## Study project: Application Programming Interface for Error Control Codes
The topic of the study project and seminar thesis is the application programming interface for error control codes, called the Teabag API. Initially, the goal was to exploit generalized concatenated Reed-Solomon codes for synthesized DNA storage. As a choice programming language, Python was selected, and unfortunately, there were no established error-handling libraries. The goal has been altered to develop an application programming interface for error control coding using model-driven software engineering techniques. Software design patterns, such as the builder pattern, have been used to create a so-called plugin system. 

Alongside the Teabag API, we also provide documentation and abstract syntax rules for the development of a generic system, for example, software that can generate code, test cases, and system components. Such a project can even lead to the development of a domain-specific language.

## Bachelor thesis: Analysis of object and face detection systems - development of cascade
This  work  is  devoted  to  the  development  of  an  information  system  for  pattern recognition.  I've discussed in detail methods for  developing  applications  with OpenCV in Python. Based on the language features described in the work, the application is developed on this platform, and  a  new  cascade  is  generated  for  further  use.  Detailed  methods  for  recognizing faces when developing an application are described. Main goals: As an example, demonstrate the cascade workflow using the OpenCV library in a virtual environment and develop an appropriate algorithm for the application. This paper considers three main tasks:
- Development of an algorithm for recognizing faces
- Development of an algorithm for object recognition
- Training of the cascade for further use in the form of an .xml document

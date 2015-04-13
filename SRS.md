This document contains all details which are relevant for the design phase to follow.

# 1. Analysis modeling
* 1.1. Specify data entities and relationship between them using an Entity Relationship Diagram, or a Class Diagram.
* 1.2. Specify the information flow and the transforms that are applied as data move from input to output using a Data Flow Diagram, or specify the dynamic behavior using Sequence Diagrams.

# 2. Functional requirements

This subsection describes how the transformation of inputs to
outputs is achieved. The following description is given for each individual function.

* 2.1. Name of the function
* 2.2. Description of the function: A description of the purpose of this function.
* 2.3. Inputs: A precise description of the function’s inputs
	* Source (how/where/who provides the input)
	* Range of acceptable values	
* 2.4. Processing A definition of the operations that must be performed, such as checking for acceptable values, reaction to abnormal situations, or a description of the algorithms to be used.
* 2.5. Outputs: A precise description of the function’s outputs
	* Destination (how/where/who receives the output)
	* Error messages
* 2.6. Pre-condition: What must be true before the function is called
* 2.7. Post-condition: What is true after the function is called
* 2.8. Requirements Indication of what other entities are used that are not directly input
* 2.9. Side effects not directly related to output items
* 2.10. Annotation
	* 2.10.1. Stability Will the needs change during the expected life of the product?
	* 2.10.2. Degree of necessity
		* Mandatory – software will not be acceptable unless this function is provided in an agreed manner
		* Desirable – this function would enhance the software product, but would not make it unacceptable if it is absent
		* Optional – this function may or may not be worthwhile 
		
		
# 3. Non-functional requirements
## 3.1. External interface requirements
* 3.1.1. User interfaces A description of the characteristics of the user interfaces, such as
screen layout, function keys, help functions
* 3.1.2. Hardware interfaces A description of the logical characteristics of hardware
interfaces
* 3.1.3. Software interfaces A description of software needed, such as a certain operating
system or software package. Interfaces to other application software are also
discussed here.
* 3.1.4. Communication interfaces An example is a communication protocol

## 3.2. Performance requirements
Performance requirements encompass both static and dynamic requirements. Static requirements concern, amongst others, the number of terminals to be connected and the number of users to be handled concurrently. Dynamic
requirements concern operational performance of the system: how frequently will certain functions be called for and how fast should the system’s reaction be. These requirements should be stated in measurable terms.

## 3.3. Design constraints
* 3.3.1. Standard compliance: Existing standards or regulations that must be followed, and the requirements that result from these.
* 3.3.2. Hardware limitations: A description of the characteristics of the hardware, as far as they lead to software requirements.

## 3.4. Quality attributes
In this section, particular attention is paid to quality aspects. These requirements must be measurable and verifiable.

*	3.4.1. Availability Factors that guarantee a certain level of availability, such as restart procedures, redundancy, etc.
* 3.4.2. Security Requirements regarding unauthorized access and others form of misuse. These include cryptographic techniques, constraints on the access and
communication.
*	3.4.3. Portability Requirements regarding the portability of the software to different
hardware platforms and/or different operating systems.
* 3.4.4. Maintainability Requirements to guarantee a certain level of maintainability of
the system.

## 3.5. Other requirements
A description of requirements that are specific to certain software, and which have not been discussed yet.
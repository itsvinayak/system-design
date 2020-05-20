# Steps in system design
[source](https://www.tutorialspoint.com/system_analysis_and_design/system_design.htm)

# Logical Design
Logical design pertains to an abstract representation of the data flow, inputs, and outputs of the system. It describes the inputs (sources), outputs (destinations), databases (data stores), procedures (data flows) all in a format that meets the user requirements.

While preparing the logical design of a system, the system analyst specifies the user needs at level of detail that virtually determines the information flow into and out of the system and the required data sources. Data flow diagram, E-R diagram modeling are used.



# Physical Design
Physical design relates to the actual input and output processes of the system. It focuses on how data is entered into a system, verified, processed, and displayed as output.
It produces the working system by defining the design specification that specifies exactly what the candidate system does. It is concerned with user interface design, process design, and data design.
It consists of the following steps −
- Specifying the input/output media, designing the database, and specifying backup procedures.
- Planning system implementation.
- Devising a test and implementation plan, and specifying any new hardware and software.
- Updating costs, benefits, conversion dates, and system constraints.

# Architectural Design
It is also known as high level design that focuses on the design of system architecture. It describes the structure and behavior of the system. It defines the structure and relationship between various modules of system development process.

# Detailed Design
It follows Architectural design and focuses on development of each module.

# Conceptual Data Modeling
It is representation of organizational data which includes all the major entities and relationship. System analysts develop a conceptual data model for the current system that supports the scope and requirement for the proposed system.
The main aim of conceptual data modeling is to capture as much meaning of data as possible. Most organization today use conceptual data modeling using E-R model which uses special notation to represent as much meaning about data as possible.

# Entity Relationship Model
It is a technique used in database design that helps describe the relationship between various entities of an organization.

Terms used in E-R model :
- ENTITY − It specifies distinct real world items in an application. For example: vendor, item, student, course, teachers, etc.
- RELATIONSHIP − They are the meaningful dependencies between entities. For example, vendor supplies items, teacher teaches courses, then supplies and course are relationship.
- ATTRIBUTES − It specifies the properties of relationships. For example, vendor code, student name.

Three types of relationships can exist between two sets of data: one-to-one, one-to-many, and many-to-many.

# File Organization
It describes how records are stored within a file.
There are four file organization methods −
- Serial − Records are stored in chronological order (in order as they are input or occur). Examples − Recording of telephone charges, ATM transactions, Telephone queues.
- Sequential − Records are stored in order based on a key field which contains a value that uniquely identifies a record. Examples − Phone directories.
- Direct (relative) − Each record is stored based on a physical address or location on the device. Address is calculated from the value stored in the record’s key field. Randomizing routine or hashing algorithm does the conversion.
- Indexed − Records can be processed both sequentially and non-sequentially using indexes.


<img src="img/comparision.png" alt="image"/>

# File Access
One can access a file using either Sequential Access or Random Access. File Access methods allow computer programs read or write records in a file.
## Sequential Access
Every record on the file is processed starting with the first record until End of File (EOF) is reached. It is efficient when a large number of the records on the file need to be accessed at any given time. Data stored on a tape (sequential access) can be accessed only sequentially.
## Direct (Random) Access
Records are located by knowing their physical locations or addresses on the device rather than their positions relative to other records. Data stored on a CD device (direct-access) can be accessed either sequentially or randomly.

# Documentation Control
Documentation is a process of recording the information for any reference or operational purpose. It helps users, managers, and IT staff, who require it. It is important that prepared document must be updated on regular basis to trace the progress of the system easily.
After the implementation of system if the system is working improperly, then documentation helps the administrator to understand the flow of data in the system to correct the flaws and get the system working.
Programmers or systems analysts usually create program and system documentation. Systems analysts usually are responsible for preparing documentation to help users learn the system. In large companies, a technical support team that includes technical writers might assist in the preparation of user documentation and training materials.

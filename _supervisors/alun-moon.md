---
layout: supervisor
title: Alun Moon
available: true
email: alun.moon@northumbria.ac.uk
office_hours: Generally between 10 and 3:30
research_group: Intelligent Systems Research Group
research_themes:
  - Animation
  - Operating Systems
  - Computer Networks
  - Game Design and Development
  - Internet of Things
  - Network Simulation
additional_keywords:
  - Network Protocol Design
  - Formal Methods
  - Applied Programming
  - Applied Mathematics
  - Cyber-Physical Systems
  - Embedded Systems
  - Data Visualisation
  - Model Based Design
  - Modelling & Simulation
  - Robotics
technologies_languages:
  - 3D Modelling
  - Assembly
  - Bash/Shell
  - C
  - Clojure
  - Java
  - Python
additional_details: >-
  # File system


  Four interesting papers on file-systems and databases. 


  **Padioleau and Ridoux (2005)** show how a “transducer” can be build to allow a file to be navigated as if it were a file system. 


  **Gehani et al. (1994)** show how an interface to an object oriented database can be written to resemble a file system. 


  **Murphy et al. (2002)** develop a database filesystem. 


  **Padioleau et al. (2006)** propose a novel use of a file system for logically arranging data. 


  These all show that there is a close synergy between database and file-system concepts and functions. 


  Some project ideas: 


  ## Database as a POSIX filesystem

   A conventional file-system can be considered a form of database, it stores information and metadata, much as a database. This project would show that a database based file-system can provide all the operations required by the POSIX standards. Olson et al. (1993) is an older paper that demonstrates this concept. 

  ## Disk format for database systems 


  Two (older papers) discuss the support required for operating systems, Stonebraker (1981), Fellig and Tikhonova (2000). This project would propose a disk format optimised to support a database directly, rather that have the data stored as a flat-file. _This idea may become quite complex and challenging, you would learn a lot about database storage structures and disk-formats_


  # Formal methods 


  TLA+ (Lamport 2002) is a language and tool-set used to formally specify and validate the behaviour of a software system. It is a design tool, to specify software behaviour, not a programming language.


  ## TLA+ to Python

   Python supports sets and records (dictionaries) as primitive data-types. TLA+ is written using these as its primitive data-types. This project would look at the process of implementing the specification in python, and looking at tools to either automate the process and/or verify the code implements the specification. 2.2 TLA+ to Unit Tests/Assertions A Specification and its validation tests define how a program behaves. Assertions can be used at run-time to test for conditions and abort the program is the conditions are not met. Unit tests provide a framework to test that software satisfies certain behaviours. This project would look at using these tools to verify that some program code implements the specification, its focus would on be how to ensure that the unit tests accurately reflect the TLA+ specification, either through automatic generation of the tests, tools to reconcile the tests against the specification, or other techniques. 

  ## Functional programming 


  Proponents of functional programming propose that languages like Haskell (https://www.haskell.org/) are beneficial because of their mathematical like qualities, safety, and type system. This project could look at the use of Haskell to implement TLA+ specifications and evaluate the trade-offs between computational performance and ease of implementing a specification. 


  ## Embedded systems and control programming


  Some interesting sites I came across while looking at functional programming and embedded systems. 


  + https://ivorylang.org/index.html 

  + https://pixhawk.org/ 

  + https://smaccmpilot.org/ 

  + https://github.com/echronos/echronos 


  There is an interesting paper (Diatchki et al. 2005) that explores handling bit-oriented data (such as device registers) in a functional language. 


  ### Demonstrator for programming the Crazyflie 


  https://www.bitcraze.io/products/crazyflie-2-1/ 


  Does the embedded processor on the Crazyflie have enough power to support the demands of the eChronos RTOS? Can the code generated from Ivory using gcc or llvm based compilers be targeted at the crazyflie? 


  ### Demonstrator for the Arduino or MBed boards 


  Arduino ans MBed are two families of embedded development boards (we should have several in the loans system). Can the eChronos RTOS, and Ivory language (via gcc or llvm based compilers) be targeted at these devices?


  # Other 


  ## Docker network configuration 


  In his project in 2020 James (Poxon 2021) found that the performance of Docker based tools for supporting network infrastructure (e.g. DNS servers), was superior to those based on virtual machines. The network configuration of docker was poor, and its behaviour caused some issues. This project could look at the network configuration of Docker to overcome the limitations identified.


  # References


  Iavor S. Diatchki, Mark P. Jones, and Rebekah Leslie. High-level views on low-level representations. In _Proceedings of the Tenth ACM SIGPLAN International Conference on Functional Programming_, ICFP ’05, page 168–179, New York, NY, USA, 2005. _Association for Computing Machinery_. ISBN 1595930647. doi: 10.1145/1086365.1086387. URL https://doi.org/10.1145/1086365.1086387. 


  Daniel Fellig and Olga Tikhonova. Operating system support for database management systems revisited, 2000. URL http://citeseerx.ist.psu. edu/viewdoc/download?doi=10.1.1.28.3259&rep=rep1&type=pdf.


  Narain H. Gehani, H. V. Jagadish, and William D. Roome. Odefs: A file system interface to an object-oriented database. In _Proceedings of the 20th International Conference on Very Large Data Bases_, VLDB ’94, page 249–260, San Francisco, CA, USA, 1994. Morgan Kaufmann Publishers Inc. ISBN 1558601538. URL https://citeseerx.ist.psu.edu/ viewdoc/download?oi=10.1.1.35.285&rep=rep1&type=pdf.


  Leslie Lamport. _Specifying Systems: The TLA+ Language and Tools for Hardware and Software Engineers_. Addison-Wesley Longman Publishing Co., Inc., Boston, MA, USA, June 2002. ISBN 032114306X. URL https: //lamport.azurewebsites.net/tla/book-02-08-08.pdf.


  Nick Murphy, Mark Tonkelowitz, and Mike Vernal. The design and implementation of the database file system, 2002. URL http://citeseerx. ist.psu.edu/viewdoc/summary?doi=10.1.1.11.8068. 


  Michael A Olson et al. The design and implementation of the inversion file system. In _USENIX Winter_, pages 205–218. Citeseer, 1993. URL https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.45.4517&rep=rep1&type=pdf. 


  Yoann Padioleau and Olivier Ridoux. A parts-of-file file system. In _USENIX 2005 Annual Technical Conference, General Track_, 2005. URL https://www.usenix.org/legacy/publications/library/proceedings/usenix05/tech/general/full_papers/short_papers/padioleau/padioleau.pdf.


  Yoann Padioleau, Benjamin Sigonneau, and Olivier Ridoux. Lisfs: A logical information system as a file system. In _Proceedings of the 28th International Conference on Software Engineering_, page 803–806, New York, NY, USA, 2006. Association for Computing Machinery. ISBN 1595933751. URL https://doi.org/10.1145/1134285.1134418. 


  James Poxon. Comparing virtual machine and container performance for headless servers in computer networks. Technical report, CIS, University of Northumbria, 2021. 


  Michael Stonebraker. Operating system support for database management. _Communications of the ACM_, 24(7):412–418, July 1981. ISSN 0001-0782. doi: 10.1145/ 358699.358703. URL https://doi.org/10.1145/358699.358703.
---

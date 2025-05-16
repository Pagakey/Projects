# Academic Projects Portfolio

## Overview
This repository showcases key projects developed during my Computer Science studies at the University of Crete, demonstrating my progression in software/hardware development, systems programming, and theoretical computer science concepts.

## Technical Skills
### Programming Languages
- **Primary:** C, C++, Java
- **Secondary:** Python, JavaScript
- **Web Technologies:** HTML, CSS
- **Assembly:** RISC-V

### Core Competencies
- Data Science & Machine Learning
- Data Structures & Algorithms
- Operating Systems
- Backend Development
- Compiler Design
- Parallel Programming
- Process Management
- Computer Architecture

### Mathematics & Theory
- Discrete Mathematics
- Applied Mathematics
- Logic
- Probability Theory
- Linear Algebra

### Tools & Environments
- Version Control: Git
- Operating Systems: Linux/Windows
- Development Tools: Various IDEs and debugging tools
- Wireshark, Ghidra, Burp Suite, Cyberchef etc...


## Projects

### Linux Shell Implementation
**Technologies:** C, Linux System Calls  
**Key Features:**
- Custom shell implementation
- Extensive process manipulation
- Robust string handling
- Core shell functionality implementation

### Multi-threaded Transportation System
**Technologies:** C, POSIX Threads  
**Key Features:**
- Complex multi-threaded student-bus-university simulation
- Synchronized resource management using:
  - Mutex locks
  - Semaphores
- Time-based scheduling system
- Multiple concurrent student threads management

### Compiler Construction Project
**Technologies:** YACC/BISON, C  
**Project Scope:** Five-phase compiler implementation for the "Alpha" programming language  
**Team Size:** 2 members  
**Components:**
1. Lexical Analyzer (Lexer)
2. Parser
3. Intermediate Code Generator
4. Target Code Generation
5. Virtual Machine Implementation

*Note: Perfect score achieved for the first three phases; final two phases in progress.*

### Streaming Service Simulation (Data Structures Project)
**Technologies:** C, Data Structures  
**Implementation Versions:**
1. Basic Version (Phase A)
   - Utilized fundamental data structures (single and double linked lists)
   - Implemented core streaming service functionality
   - Features: user registration/unregistration, movie management and more
   
2. Advanced Version (Phase B)
   - Enhanced with binary search trees and leaf-oriented BSTs
   - Maintained specified time complexity requirements
   - Additional features:
     - Movie distribution across categories
     - Intelligent movie suggestion system
     - Filtered search functionality
     - Watch/consume movie tracking and more
    
### Mini-Internet Network Engineering Project
**Technologies:** Open vSwitch, FRRouting, OSPF, BGP, VLANs, Python, TCP/IP Sockets  
**Team Size:** 2 members  
**Key Features:**
- Built a complete mini-Internet environment spanning approximately 80 Autonomous Systems with hundreds of network devices
- Implemented comprehensive network topology with Layer-2 (switches) and Layer-3 (routers) configurations
- Established intra-domain routing using OSPF with bandwidth-aware path optimization
- Configured strategic traffic engineering using link weights and static routes to manage traffic flow
- Created segmented VLANs to enforce security boundaries between student and staff networks
- Implemented full-mesh internal BGP (iBGP) sessions between routers with loopback addressing
- Established external BGP (eBGP) sessions following provider-customer and peer relationships
- Applied industry-standard BGP policy implementation using communities and route-maps
- Developed custom network monitoring system using client-server socket programming to track latency and path metrics
- Successfully integrated with Internet Exchange Points (IXPs) using BGP community values
- Performed bandwidth analysis using iperf3 for performance-based routing decisions
- Ensured end-to-end connectivity throughout the entire network infrastructure
    
### Ticket Selling System (Database Project)
**Technologies:** SQL, Relational Database Design, Java, Javascript, HTML, CSS
**Team Size:** 2 members
**Key Features:**
   - Developed a complete ticketing system for events using a relational database schema.
   - Designed an Entity-Relationship (E/R) model and translated it into a fully normalized relational schema (3NF).
   - Implemented core entities: Users, Events, Tickets, Credit Cards and Refunded Tickets with well-defined primary and foreign keys.
   - Modeled key relationships such as ticket purchases, credit card declarations, and event-based ticket refuns with appropriate cardinalities.
   - Executed a full set of SQL operations including:
     - Event and user management(insertion, update, deletion).
     - Ticket purchase tracking with seat-type-based classification (Standard,Premium,VIP)
     - Refunding and auditing system with historical tracking of returned tickets.
     - Complex **JOIN** queries for data retrieval across multiple relations.
   - Ensured database integrity and consistent transactional behavior.

### Data Science and Machine Learning Projects
**Technologies:** Python, NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, Keras, Seaborn, SciPy  
**Datasets & Packages:**
- **Linear Algebra Analysis:** Custom generated matrices with NumPy, optimized with vectorized operations
- **Image Processing:** Custom implementations for Einstein photograph transformations using rotation matrices
- **Traffic Stop Analysis:** Hartford CT police dataset (2013-2016) visualized with Matplotlib, Seaborn, and Folium for geospatial mapping
- **Statistical Inference:** Breast Cancer Wisconsin dataset with Maximum Likelihood Estimation using gradient descent and SciPy
- **Dimensionality Reduction:** Diabetes dataset with PCA implementation, evaluated through regression performance metrics
- **Classification Models:** Breast Cancer Wisconsin dataset with SVM (sklearn.svm.SVC), GridSearchCV for hyperparameter tuning, and cross-validation metrics
- **Neural Networks:** MNIST dataset with TensorFlow/Keras implementing MLPs with various architectures and data proportions

**Key Features:**
- Implemented linear algebra operations comparing matrix inversion vs. direct solving methods, demonstrating computational efficiency analysis
- Created custom image transformation algorithms for data augmentation, including rotation and reflection matrices
- Conducted comprehensive exploratory data analysis with advanced visualizations and temporal/demographic breakdowns
- Applied Maximum Likelihood Estimation with gradient descent optimization, comparing analytical and computational solutions
- Developed dimensionality reduction techniques with Principal Component Analysis, improving regression model performance
- Implemented and evaluated Support Vector Machine models with different kernels for breast cancer classification, including decision boundary visualization
- Built neural network models for MNIST digit classification, analyzing architectural variations and training set size impacts


### Stratego Board Game
**Technologies:** Java, Object-Oriented Design, Design Patterns  
**Key Features:**
- Implemented the complete game using MVC architecture for clean separation of concerns
- Designed an extensible piece hierarchy with inheritance for specialized game pieces
- Created intelligent rule enforcement system with strategy pattern for different piece movements
- Implemented features including:
  - Advanced collision detection and piece interaction logic
  - Dynamic board rendering with graphical user interface
  - Turn-based gameplay with validation
  - Special abilities for pieces (Slayer, Scout, Bombs/Flags etc.)
  - Win condition detection and endgame handling

## Technical Highlights
- Strong focus on performance optimization and time complexity
- Experience with both low-level and high-level programming
- Implemented memory-efficient solutions in C/C++ with careful resource management
- Implementation of complex algorithms and data structures
- Practical application of operating systems concepts
- Implemented comprehensive test suites ensuring robust functionality in compiler and data structure projects
- Collaborative development experience
- Bridged front-end and back-end technologies in multiple projects including the ticketing system


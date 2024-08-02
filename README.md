# Data Cleaner DSL

### Overview
This was the final project for the *compiler course in semester 4022* at *Iran University of Science and Technology (IUST)*. The project involves the development of a `Domain-Specific Language (DSL)` designed for data cleaning tasks. The primary goal is to create a concise and practical language that enables users to specify various data cleaning operations efficiently. The project covers the complete pipeline from grammar definition and parsing to code generation and visualization.

### Key Features
DSL Grammar Definition: Utilizing `ANTLR` for defining the grammar of the data cleaning language.
- **AST Generation and Traversal:** Creation and traversal of `Abstract Syntax Trees (AST)` to interpret and execute the specified data cleaning tasks.
- **Code Generation**: Translating the DSL scripts into executable `Python` code that leverages libraries like `pandas` and `numpy` for performing data cleaning operations.
- **Data Cleaning Operations:** Support for various data cleaning tasks
- including:
    - Handling missing values (imputation, removal)
    - Normalization and standardization
    - Data transformation (logarithmic transformations)
    - Data aggregation and segmentation (clustering)
    - Encoding categorical data
    - Outlier detection and management

- **Visualization and Verification:** Tools for visualizing the AST and ensuring the correctness of the generated code.
- **Technologies Used**
    - ANTLR: For parsing and grammar definition.
    - Python: For implementing data cleaning operations.
    - pandas and numpy: Core libraries for data manipulation and analysis.
    - NetworkX: For visualizing the AST and its traversal.
- **How to Use**
1. Define Your Data Cleaning Tasks: Write scripts using the custom DSL to specify your data cleaning operations.
2. Parse and Generate Code: Use the provided tools to parse the DSL scripts and generate corresponding Python code.
3. Execute Data Cleaning: Run the generated Python code to perform the specified data cleaning tasks on your datasets.
4. Visualize and Verify: Utilize the visualization tools to inspect the AST and verify the correctness of the transformations applied to your data.

**Contributors:**
+ Dr. Saeed Parsa (Advisor)
+ Aidin Asl Zaeem 
+ Reza Haghgooyan
+ Reza Bozorgmehr
+ Mohsen Rahimi

 

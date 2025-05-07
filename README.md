# Introduction to Semiconductor Packaging Course: VSD

Welcome to the repository for the **"Introduction to Semiconductor Packaging"** coursework by **VSD**.

**Note:** Work completed for each individual module is stored in the form of PDF files.

---

## Module 1: Packaging Evolution – From Basics to 3D Integration

### Lecture 1: Introduction to Semiconductor Packaging
## Key Takeaways:
1. What is packaging and Why is it Needed?
2. Silicon Development Industry & it's Key Players At Each Level.
3. Technical Terms Related to the Silicon Supply Chain.

L1: Introduction To Semiconductor Packaging 
By Tarun Agrawal
IIT Gandhinagar


Why Packaging Is Needed?
So, individual chips are cut out from wafers.
They are built in a protected environments.

But when used, these ICs are exposed to the real world.

	1. Packaging enables the die to work in the real world (Corrosion, Physical damage, moisture etc.)
	2. Allow connection to other dies

![image](https://github.com/user-attachments/assets/bbaebf4e-f69c-4138-ba35-fcc33771046c)

So here, the black outer casing is not the package, but the moulding compound.
The IC is placed within the moulding compound & we use wire bonds to connect it to the substrate.
Wire bond allows us to connect to BGA, which can be used to connect to a system.

So, packaging brings personality to an intelligent chip

Design is the first step in this process, we give designs to a foundry, who manufacture it.
Post manufacturing, we test the wafer, package it & test it in packages & test.
Tested ICs are sent for assembly.

IDMs: Design, Foundry & Packaging: End to End (Intel, Samsung, Micron, SKHynix, TI, ST)
But for fabless companies:
	1. Fabless Design Centric Orgs (Qualcomm, nVidia, AMD, Apple)
	2. Foundry: Wafer Mfg (TSMC, Global Foundries)
	3. OSAT (Outsourced Semiconductor Assembly & Test): Packaging & Testing of all wafers they receive (ASE, Amkor, JCET, PTI, UTAC, TSMC etc.)

Upcoming Units in India: Micron, CG Powers + Renesas, Tata Electronics, Kaynes Semiconductor
![image](https://github.com/user-attachments/assets/94cde0c6-fb09-4c0b-aa17-2d4a6a36ea53)


### Lecture 2: Understanding Package Requirements and Foundational Package Types
1. Silicon Development Cycle.
2. Key Factors to Consider While Designing Packages.
3. Package Families & their Types.

### Lecture 3: Evolving Package Architecture – Single Chip to Multi-Chip Modules
1. Types of Package Families.
2. Internal Structure of Packages.
3. Advantages & Disadvantages of Each Package Type.

### Lecture 4: Interposer Redistribution Layer and 2.5D/3D Packaging Approaches
1. Types of 2.XD Integration.
2. Integration of Dies Into Packages & Systems.

### Lecture 5: Comparative Analysis and Selecting the Right Package Solution
1. Comparative Analysis of Packages.
2. Advantages & Disadvantages of Each Package Type.
3. Applications of Individual Package Type.

---

## Module 2: From Wafer to Package – Assembly and Manufacturing Essentials

### Lecture 1: Setting the Stage – Supply Chain and Facilities
1. Semiconductor Processing Supply Chain.
2. Overview of Packaging Units.
3. Processes and Technical Specifications of Packaging Units.

### Lecture 2: Wafer Pre-Preparation – Grinding and Dicing
1. Overview of Cleanroom Processes.
2. Steps Involved in Wafer Processing.

### Lecture 3: Wire Bond Packaging – Assembly and Manufacturing Essentials
1. Overview of Wire Bonding.
2. Processes Involved in Wire Bond Packaging.

### Lecture 4: Flip Chip Assembly – Bump Formation and Underfill
1. Overview of Flip Chips.
2. Processes & Technical Terms Associated with Flip Chip Packaging.

### Lecture 5: Wafer-Level Packaging and Conclusion
1. Overview of Wafer-Level Packaging.
2. Processes and Technical Terms Associated with Wafer-Level Packaging.

---

## Module 3: Thermal Simulation of Packages Using Ansys

### Lecture 1: Intro & Getting Started with Ansys Electronics Desktop
1. Overview of Ansys Electronics Desktop Student 2024 R2.
2. Tools Available in Anays: Icepack, Q3D, HFSS etc.
3. Overview of Menu Panes in Icepack.

### Lecture 2: Setting Up a Flip Chip BGA Package
1. Importing Pre-generated Geometries for FCBGA.
2. Analyzing Layers of FCBGA.

### Lecture 3: Material Definitions & Thermal Power Sources
1. Defining Thermal Simulation Parameters for the Different Layers.
2. Assigninig Temperature Monitors for the Individual Layers.

### Lecture 4: Meshing & Running Thermal Analysis
1. Meshing the DUT for Analysis.
2. Validatiing Simulation Inputs to Ensure Convergent Solutions.

### Lecture 5: Viewing Results & Exploring Other Package Types
1. Generating Simulation Results for Given Inputs.
2. Plotting the Simulation Results on the 3D Package.

---

## Module 4: Ensuring Package Reliability: Testing & Performance Evaluation

### Lecture 1: Introduction to Package Testing & Electrical Functionality Checks
1. Overview of Why Testing is Needed.
2. Common IC Test Overview: AOST, Burn-In, Final Test
3. Analysis of AOST & Typical Failures it can Detect.

### Lecture 2: Reliability & Performance Testing of Semiconductor Packages
1. Analysis of Burn-In Test.
2. Intorduction to Failure Rate V/S Time Curve.
3. Overview of Burn-In Boards & the Faults Detected in This Test.
4. Discussion of Final Tests: Testing Edge Cases (Hot & Cold Test)
5. Performance Indicators & Units of Final Test Equipment.

---

## Module 5: Package Design & Modelling: Building a Semiconductor Package from Scratch

### Lecture 1:  Into To Package Cross-Section Modelling in Ansys Electronics Desktop (AEDT)
1. Overview of Packaging Dies
2. Intorduction to Q3D for Electrical Analysis. 

### Lecture 2: Creating the Die Substrate in AEDT
1. Overview of the tool Q3D Draw Tool Bar & Surface Generation.
2. Renaming & Assigning Materials to Layers.

### Lecture 3: Adding Die Attach Material & Bond Pads
1. Placing Bond Pads on Die & Substrate.
2. Adding Underfill between Die & Substrate.

### Lecture 4: Wire Bond Creation & Material Alignment
1. Introduction to Bond Wire, it's Properties & types.
2. Connecting Bond Pads on Die & Substrate using Bond Wires.

### Lecture 5: Applying Mould Compound & Finalizing the Package Model
1. Adding a Layer of Moulding Compound Over the Connected Die.
2. Consideration Taken Before Deciding Moulding Compound Height.

---

For detailed lecture notes and diagrams, refer to the module's PDF file.

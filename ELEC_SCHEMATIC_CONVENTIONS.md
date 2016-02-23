1. Introduction
-------------

All schematics and PCB drawings for Consat1 need to adhere to the conventions laid out in this document.
The conventions in this document have been written with the goal of promoting clarity, uniformity, and ease of verification of the electrical designs.

2. External Guidelines and References
-------------

TBC.

3. Drawing Titles, Author and Version Information
-------------

All schematics and PCB drawings need to be properly attributed and dated. 
(TODO: research inserting git versions automatically into drawing info? Probably not easily possible) 

### 3.1 Titles, Attribution and Dates

1. A frame with the document information subframe must outline all schematic documents.
2. The document information subframe will contain the information
    1. Reference to Consat1 and the title of the design in the format “ConSat1/<Title>”.
    2. Name of the initial creator.
    3. Name of the person who last updated the design
    4. Date that the drawing was last updated.
3. All PCBs must include, on a printable documentation layer, the title of their design and the date the manufacturers files were generated.

### 3.2 Version Information

1. Version information MUST NOT be included in the directory or file names of the drawings, as 'git' or an other external version control system will be used to maintain versioning.
2. Version information MAY be included in the document information subframe. Version numbers are not necessary, but maybe be included for reference at the discretion of the designer.

4. Net/Signal Naming Conventions
-------------
	
1. Ground and power nets MUST be named “GND” “3V3”, “9V”, “2A” or similarly
2. Ground and power nets MUST be connected to a supply pin

5. Connector Naming Conventions
-------------

1. The headers for the electronics bay bus must be named "H#"
2. All other connector parts must be named “J#”
3. All connector part names and properties must be verified against the wiring harness schematic and against all other schematics

6. Component Placement
-------------

1. Components must be placed to align with the Grid.

7. PCB Trace Placement
-------------
	
1. Traces must align with the Grid.
2. Traces must not be free-drawn, the following eagle trace styles MUST NOT be used:
    1. Wire Bend Style 2
    2. Wire Bend Style 5
    3. Wire Bend Style 6
    4. Wire Bend Style 7
3. Traces must have a clearance of …
4. Traces must have a width approprate of power transfer.

8. Eagle DRC/External Verification Scripts
-------------

TBC.

9. References
-------------

# Component Naming & Numbering
# Component Number Scheme
Part names follow the following format:

    XXXXXX-YYYYYY-ZZZZZZ-WWWWWW-NN
Where:

- X (first column) is the parent component number
- Y (second column) is the component name
- Z (third column) is the component number
- W (fourth column) is the material
- N (fourth column) is the part revision

## Rules

- The letter M is reserved for signifying parts that are mirrored
- Material Column Special Cases
    - COTS - Used to signify a COTS item (motors,hardware,etc)
    - ASSY - Signifies assemblies
- Parts at base revision (no revision) start at 00

## Legal CNs
- A1-SHRD-1-A6T6-0
- 0000-BOTTOMPLATE1-0004–ALU5052H32-00
    - This a child of component 0000, is a plate, is made of Aluminum 5052-H32 and its PN is 0004 at revision 0
- 0000-TOPPLATE1-0002–AL5052H32-08
    - This a child of component 0000, is a plate, is made of Aluminum 5052-H32 and its PN is 0002 at revision 8

## Illegal CNs
- A1-SHRD-001-0
    - Incorrect number of columns. Revision number does not have a zero prefix



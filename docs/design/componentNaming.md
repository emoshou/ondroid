# Component Naming & Numbering
# Component Number Scheme
Part names follow the following format:

    XXXXXX-YYYYYY-ZZZZZZ-WWWWWW-NN
Where:

- X (first column) is the parent component
- Y (second column) is the component type
- Z (third column) is the component number
- W (fourth column) is the material
- N (fourth column) is the part revision

## Rules

- The letter M is reserved for signifying parts that are mirrored
- Components can have any number 
- The maximum number of characters per column is 6
- Columns must have at least one number
- Parts at base revision (no revision) start at zero
- Leading zeroes are not allowed

## Legal CNs
- A1-SHRD-1-A6T6-0
    - This child of component A1, is a shroud, is made of Aluminum 6061-T6 and its PN is 001 at revision 0
- FRM2-FRAME-158-SS316-24
    - This child of component FRM2, is a frame, is made of Stainless Steel 316 and its CN is 158 at revision 24

## Illegal CNs
- A1-SHRD-001-0
    - The component number (third column) has leading zeroes



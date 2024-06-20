# Analysis
There is an important distinction between System and Component level analysis: system analysis generates requirements that drive lower level components.<br><br>

# System Level Analysis

### Definition
System level analysis is a comprehensive examination of the entire system, considering all its components, interactions, and the overall functionality. It involves understanding how various parts of the system work together to achieve the desired objectives.

### Purpose
#### TLA Requirements
System level analysis is crucial for developing the overarching architecture and design of a system. This high-level design outlines how different components will interact, the overall system behavior, and the primary functions.
#### Validation
It ensures that all components will be rated for the correct loading conditions once designed. This analysis also identifies potential issues that might arise from the interaction between components.
#### Optimization
Provides methods to optimize the system as a whole, rather than focusing on individual components. This approach reveals opportunities for reducing weight and increasing performance.


### What it Looks Like
#### System Level Requirements Gathering
Collecting and defining the system level requirements.
#### System Level Analysis
Generating FBDs and analyzing them to generate component level requirements.
#### Feasibility Studies
Evaluating different design alternatives and their trade-offs to determine the best overall system design.

### Outcome
Component level requirements in the form of:

- Velocities
- Accelerations
- Forces
    - Magnitudes
    - Components
- Constraints
- Torques
    - Magnitude
    - Duty Cycle

# Component Level Analysis

### Definition
Component level analysis focuses on the detailed examination and design of individual components within the system.

### Purpose
#### Requirement Compliance
Ensuring that each component meets the specific requirements set by the system level analysis. These requirements are often more detailed and precise, addressing the specific needs and constraints of each component.
#### Performance Verification
Verifying that each distinction can perform its intended functions reliably through propagating results upwards to the system level for verification.

### What it Looks Like
#### Stress Analysis
Breaking down system-level requirements into detailed, component-specific requirements that are then analyzed for highest level stresses using calculation or FEA methods. These are then typically compared with material yield strengths to generate factors of safety.
#### Motor Analysis
Calculations that validate the performance of motors and other powertrain components.
#### Testing and Validation
Developing tests to validate that components meet their design specifications and performance criteria. This can include failure testing, reliability testing, and other types of tests.

### Outcome
The outcome of component level analysis is a set of detailed analyses and specifications for each component, along with analysis results and documentation. These components can then be individually manufactured, prototyped, and implemented.

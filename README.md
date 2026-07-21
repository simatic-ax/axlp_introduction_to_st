# SIMATIC AX - Introduction to ST Programming

## Description
A comprehensive learning path for automation engineers transitioning from TIA Portal to SIMATIC AX with Structured Text (ST) programming.

## Overview

This repository contains a complete training module designed to teach ST programming concepts and SIMATIC AX development practices. The training covers everything from basic program organization to advanced system functions and practical automation applications.

## Getting Started

You can view the interactive training presentation here:

Latest:
[Open Presentation](https://simatic-ax.github.io/axlp_introduction_to_st/latest/#/)

Select older versions
[Select Version](https://simatic-ax.github.io/axlp_introduction_to_st/#/)

## Learning Objectives

After completing this training, participants will be able to:

- **Analyze:** Compare ST program structure vs. TIA Portal approach (15 min)
- **Create:** Build CONFIGURATION with tasks, global variables, and I/O mapping (30 min)
- **Implement:** Write FUNCTION, FUNCTION_BLOCK, and PROGRAM units with proper interfaces (45 min)
- **Organize:** Structure code using namespaces and access modifiers (20 min)
- **Design:** Define custom data types, enumerations for type-safe programming (25 min)
- **Apply:** Build a complete tank control application with valve function blocks (60 min)

**Total Duration:** ~3 hours | **Assessment:** Hands-on tank application project

## Prerequisites

### Essential Requirements
- **Solid SCL programming knowledge** in TIA Portal
- **Function blocks, data types, program organization** experience in Step 7
- **SIMATIC AX basics:** Basic understanding of SIMATIC AX development environment
- **Development setup:** SIMATIC AX installed and configured for development
- **Background:** Industrial automation, PLC programming, Siemens ecosystem

**Important:** Basic SIMATIC AX knowledge is mandatory to successfully complete this training.

### Recommended Preparation
- Complete SIMATIC AX Getting Started tutorials
- Practice basic project creation and building
- Familiarize yourself with the development workflow

## Repository Structure

```text
axlp_introduction_to_st/
├── slides/                     # Training presentation
│   ├── slides.md               # Main slide content
│   └── theme/                  # Custom styling
│       ├── simatic-ax.css      # SIMATIC AX theme
│       └── siemens.svg         # Siemens logo
├── exercises/                  # Hands-on exercises
│   ├── 1_implement_valve/      # ST01: Basic valve function block
│   ├── 2_implement_tank/       # ST02: Tank with valve integration
│   ├── 3_extend_tank_functionality/  # ST03: Enhanced tank features
│   ├── 4_timer_for_tank/       # ST04: Timer-based valve control
│   └── 5_solution_exercise_4/  # ST05: Complete solution
├── src/                        # Example implementations
│   ├── configuration.st        # Configuration examples
│   ├── ExampleProgram.st       # Program structure examples
│   ├── TankFb.st               # Tank function block
│   ├── Valve.st                # Valve function block
│   └── Namespace/              # Namespace examples
└── .github/workflows/          # CI/CD automation
```

## Training Modules

### Chapter 1: ST Program Architecture and Configuration (45 min)
- ST program structure overview
- Configuration and tasks setup
- Global variables and I/O mapping
- Program organization fundamentals

### Chapter 2: Program Organization Units - POUs (60 min)
- FUNCTION vs FUNCTION_BLOCK comparison
- Function block structure and encapsulation
- Access modifiers (PRIVATE, PROTECTED, PUBLIC)
- Function overloading techniques

### Chapter 3: Namespaces and Code Organization (30 min)
- Namespace declaration and syntax
- USING directives implementation
- Naming conflict resolution
- Hierarchical organization patterns

### Chapter 4: Custom Data Types and Enumerations (40 min)
- Data type fundamentals
- Enumeration declaration and usage
- Named value types comparison
- Type safety best practices

### Chapter 5: System Functions and Libraries (45 min)
- System function overview
- Library installation and management
- Timer functions (OnDelay, OffDelay)
- Error state management

## Hands-On Exercises

### ST01-03: Basic Tank Application
Build a foundational tank control system with valve function blocks:
- **ST01:** Create valve function block with proper interface
- **ST02:** Implement tank function block with valve integration
- **ST03:** System integration and testing

### ST04-05: Enhanced Valve Control
Extend the application with advanced features:
- **ST04:** ValveWithClosedSensor using enumerations
- **ST05:** Enhanced tank with new valve types

### ST06: Advanced Timer Integration
Professional-grade valve control:
- **ST06:** ValveClosedSensorMon with OnDelay timer functionality
- Error state management and diagnostics

## Assessment

The training includes a comprehensive assessment through:
- **Practical implementation:** Complete tank control application
- **Code review:** Professional code organization and structure
- **Technical discussion:** Understanding of ST programming concepts
- **Real-world application:** Industrial automation best practices

## Learning Outcomes

Upon completion, participants will have:
- **Solid ST programming foundation:** Ready for advanced SIMATIC AX development
- **Professional development skills:** Modern automation programming practices
- **Practical experience:** Complete industrial automation application
- **Advanced concepts readiness:** Prepared for OOP, design patterns, and architecture

## Additional Resources

- [SIMATIC AX Documentation](https://console.simatic-ax.siemens.io/docs)
- [ST Language Reference](https://console.simatic-ax.siemens.io/docs/st/language)
- [System Libraries](https://console.simatic-ax.siemens.io/docs/libraries/system)
- [SIMATIC-1500 Libraries](https://console.simatic-ax.siemens.io/docs/libraries/simatic-1500)

## Contribution

Thanks for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section or, even better, is free to propose any changes to this repository using Merge Requests.

## License

See [LICENSE.md](./LICENSE.md) for license and legal information.

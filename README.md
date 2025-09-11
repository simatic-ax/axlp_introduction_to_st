# SIMATIC AX - Introduction to ST Programming


## Description
A comprehensive learning path for automation engineers transitioning from TIA Portal to SIMATIC AX with Structured Text (ST) programming.

## 📚 Overview

This repository contains a complete training module designed to teach ST programming concepts and SIMATIC AX development practices. The training covers everything from basic program organization to advanced system functions and practical automation applications.

## 🎯 Learning Objectives

After completing this training, participants will be able to:

- **Analyze:** Compare ST program structure vs. TIA Portal approach (15 min)
- **Create:** Build CONFIGURATION with tasks, global variables, and I/O mapping (30 min)
- **Implement:** Write FUNCTION, FUNCTION_BLOCK, and PROGRAM units with proper interfaces (45 min)
- **Organize:** Structure code using namespaces and access modifiers (20 min)
- **Design:** Define custom data types, enumerations for type-safe programming (25 min)
- **Apply:** Build a complete tank control application with valve function blocks (60 min)

**Total Duration:** ~3 hours | **Assessment:** Hands-on tank application project

## 📋 Prerequisites

### Essential Requirements
- **Solid SCL programming knowledge** in TIA Portal
- **Function blocks, data types, program organization** experience in Step 7
- **SIMATIC AX basics:** Basic understanding of SIMATIC AX development environment
- **Development setup:** SIMATIC AX installed and configured for development
- **Background:** Industrial automation, PLC programming, Siemens ecosystem

⚠️ **Important:** Basic SIMATIC AX knowledge is mandatory to successfully complete this training

### Recommended Preparation
- Complete SIMATIC AX Getting Started tutorials
- Practice basic project creation and building
- Familiarize yourself with the development workflow

## 🏗️ Repository Structure

```
axlp_introduction_to_st/
├── slides/                     # Training presentation
│   ├── slides.md              # Main slide content
│   └── theme/                 # Custom styling
│       ├── simatic-ax.css     # SIMATIC AX theme
│       └── siemens.svg        # Siemens logo
├── exercises/                  # Hands-on exercises
│   ├── 1_implement_valve/     # ST01: Basic valve function block
│   ├── 2_implement_tank/      # ST02: Tank with valve integration
│   ├── 3_extend_tank_functionality/  # ST03: Enhanced tank features
│   ├── 4_timer_for_tank/      # ST04: Timer-based valve control
│   └── 5_solution_exercise_4/ # ST05: Complete solution
├── src/                       # Example implementations
│   ├── configuration.st       # Configuration examples
│   ├── ExampleProgram.st      # Program structure examples
│   ├── TankFb.st             # Tank function block
│   ├── Valve.st              # Valve function block
│   └── Namespace/            # Namespace examples
└── .github/workflows/         # CI/CD automation
```

## 📖 Training Modules

### Chapter 1: ST Program Architecture & Configuration (45 min)
- ST Program Structure Overview
- Configuration & Tasks setup
- Global Variables & I/O Mapping
- Program Organization fundamentals

### Chapter 2: Program Organization Units - POUs (60 min)
- FUNCTION vs FUNCTION_BLOCK comparison
- Function Block structure and encapsulation
- Access Modifiers (PRIVATE, PROTECTED, PUBLIC)
- Function Overloading techniques

### Chapter 3: Namespaces & Code Organization (30 min)
- Namespace Declaration & Syntax
- USING Directives implementation
- Naming Conflict Resolution
- Hierarchical Organization patterns

### Chapter 4: Custom Data Types & Enumerations (40 min)
- Data Type fundamentals
- Enumeration Declaration & Usage
- Named Value Types comparison
- Type Safety best practices

### Chapter 5: System Functions & Libraries (45 min)
- System Function overview
- Library Installation & Management
- Timer Functions (OnDelay, OffDelay)
- Error State Management

## 🛠️ Hands-On Exercises

### ST01-03: Basic Tank Application
Build a foundational tank control system with valve function blocks:
- **ST01:** Create Valve Function Block with proper interface
- **ST02:** Implement Tank Function Block with valve integration
- **ST03:** System integration and testing

### ST04-05: Enhanced Valve Control
Extend the application with advanced features:
- **ST04:** ValveWithClosedSensor using enumerations
- **ST05:** Enhanced Tank with new valve types

### ST06: Advanced Timer Integration
Professional-grade valve control:
- **ST06:** ValveClosedSensorMon with OnDelay timer functionality
- Error state management and diagnostics

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-org/axlp_introduction_to_st.git
   cd axlp_introduction_to_st
   ```

2. **Install dependencies:**
   ```bash
   apax install
   ```

3. **Start with the slides:**
   - Open `slides/slides.md` in a markdown presentation tool
   - Or use reveal.js for interactive presentation

4. **Follow the exercises:**
   - Start with `exercises/1_implement_valve/`
   - Each exercise contains detailed instructions and solution references

## 📊 Assessment

The training includes a comprehensive assessment through:
- **Practical Implementation:** Complete tank control application
- **Code Review:** Professional code organization and structure
- **Technical Discussion:** Understanding of ST programming concepts
- **Real-world Application:** Industrial automation best practices

## 🎓 Learning Outcomes

Upon completion, participants will have:
- **Solid ST Programming Foundation:** Ready for advanced SIMATIC AX development
- **Professional Development Skills:** Modern automation programming practices
- **Practical Experience:** Complete industrial automation application
- **Advanced Concepts Ready:** Prepared for OOP, design patterns, and architecture

## 🔗 Additional Resources

- [SIMATIC AX Documentation](https://console.simatic-ax.siemens.io/docs)
- [ST Language Reference](https://console.simatic-ax.siemens.io/docs/st/language)
- [System Libraries](https://console.simatic-ax.siemens.io/docs/libraries/system)
- [SIMATIC-1500 Libraries](https://console.simatic-ax.siemens.io/docs/libraries/simatic-1500)

## 🤝 Contributing

This training material is designed for automation engineers. Contributions, feedback, and improvements are welcome:
1. Fork the repository
2. Create a feature branch
3. Submit pull request with detailed description

## 📄 License

Copyright © Siemens AG. All rights reserved.

## 📞 Support

For questions about this training material:
- Create an issue in this repository
- Contact your local SIMATIC AX training coordinator
- Visit the SIMATIC AX community forums

---

**Ready to master ST programming with SIMATIC AX?** Start with Chapter 1 and build your way to professional automation development! 🚀

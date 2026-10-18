# C# Windows Forms Projects

A collection of educational desktop application projects developed with C# and Windows Forms.

This repository is intended to demonstrate my practical learning experience in desktop application development, user interface design, event handling, and the interaction between application logic and data.

The focus is on understanding how desktop applications are structured and how individual components work together.

## Overview

Windows Forms provides a way to build desktop applications with graphical user interfaces in the .NET ecosystem.

My experience includes educational C# Windows Forms development, working with application forms, connecting a database to an application, and exploring integration between C# and a Rust library.

This repository will collect relevant examples, project documentation, and implementation notes as the materials are prepared.

## Goals

- Practice C# programming fundamentals.
- Understand the structure of Windows Forms applications.
- Build graphical interfaces using forms and controls.
- Work with user input and event handlers.
- Separate interface code from application logic where appropriate.
- Explore connecting desktop applications to databases.
- Understand how a C# application can call functions exported by a Rust library.
- Document implementation decisions, limitations, and lessons learned.

## Main Topics

### 1. Windows Forms User Interfaces

Planned examples may demonstrate:

- Creating and configuring forms.
- Working with buttons, text boxes, labels, and other controls.
- Responding to user actions through event handlers.
- Reading and validating user input.
- Displaying results in the interface.
- Organizing controls into a clear and understandable layout.
- Updating the interface based on application state.

The emphasis is on functional, understandable interfaces rather than advanced visual design.

### 2. Application Logic

Desktop applications need more than a graphical interface. They also require logic that processes user input and produces results.

This area may cover:

- Handling user actions.
- Passing data between interface elements and application logic.
- Organizing operations into methods.
- Performing basic calculations.
- Displaying operation results.
- Handling invalid input and common errors.
- Keeping responsibilities understandable as a project grows.

Specific implementation details will be documented in the corresponding project.

### 3. Database Integration

I have educational experience creating a database and connecting it to a C# Windows Forms application.

This topic may include examples of:

- Collecting data through a graphical interface.
- Sending data to a database.
- Retrieving and displaying records.
- Organizing information for an application.
- Handling basic data validation.
- Considering introductory security practices when processing user input.

The database engine, connection method, and implemented features will be identified for each example rather than assumed for the entire repository.

### 4. C# and Rust Interoperability

One area of my learning is connecting a C# application to a Rust library.

The related prototype uses a Rust library named `nn_core_rust.dll` and explores calling a matrix multiplication function from C#.

The intended interaction can be represented as:

```text
C# Windows Forms Application
            |
            v
      C# Application Logic
            |
            v
       Rust DLL Interface
            |
            v
      Rust Computation Core
            |
            v
       Computation Result
```

The prototype is associated with a neural-network learning project. Its purpose is to explore communication between a graphical application written in C# and computational functionality implemented in Rust.

This section will document the interface, data flow, and any integration requirements supported by the actual source code.

Related repository: [Rust Neural Network](https://github.com/EggZechnick/rust-neural-network).

## Example Project Categories

### Desktop Utility Applications

Small applications that demonstrate a specific programming concept, user interaction, or calculation.

Potential documentation includes:

- The problem being solved.
- The interface layout.
- The main application logic.
- How to launch the application.
- Known limitations and possible improvements.

### Database-Connected Applications

Educational desktop applications that combine a Windows Forms interface with structured data storage.

A documented example may include the database schema, interface screenshots, setup instructions, and supported operations.

### Native Library Integration

Experiments involving a C# interface and functionality implemented in a native library.

This category is intended to explain how the components communicate, what data they exchange, and what configuration is needed to run the example.

These are project categories, not a claim that every example has already been implemented or published.

## Tools and Technologies

| Technology | Purpose |
|---|---|
| C# | Application logic |
| Windows Forms | Desktop graphical interfaces |
| .NET | Application development platform |
| SQL | Database queries where applicable |
| Rust | Native computation library in the integration prototype |
| DLL interoperability | Communication between C# and Rust |
| Git and GitHub | Version control and project documentation |
| Markdown | Technical documentation |

The exact .NET version, development environment, database technology, and build requirements will be specified for each project.

## Repository Structure

The repository is planned to follow a structure similar to this:

```text
csharp-winforms-projects/
├── README.md
├── projects/
│   ├── desktop-utilities/
│   │   └── README.md
│   ├── database-application/
│   │   └── README.md
│   └── rust-library-integration/
│       └── README.md
├── docs/
│   ├── architecture/
│   └── screenshots/
└── notes/
```

This is a proposed organization. Directories will be added as actual project files and documentation become available.

## How to Explore a Project

For each published project, the documentation should provide:

1. **Purpose** — what the application is intended to do.
2. **Technologies** — the frameworks, libraries, and tools used.
3. **Structure** — the main components and their responsibilities.
4. **Setup** — prerequisites and instructions for opening or building the project.
5. **Usage** — how to interact with the application.
6. **Limitations** — incomplete functionality or known issues.
7. **Learning notes** — important implementation decisions and possible next steps.

If a project depends on an external DLL or database, the instructions will explain the relevant setup requirements.

## Current Status

**Status:** In progress

This repository is being prepared as a portfolio of educational C# and Windows Forms work.

The README describes the intended scope and areas of experience. Individual applications, screenshots, source files, and build instructions will be documented as the corresponding materials are added.

The projects should be evaluated according to their actual implementation and documented limitations.

## Author

**EggZechnick**

GitHub: [github.com/EggZechnick](https://github.com/EggZechnick)

## Related Projects

- [Rust Neural Network](https://github.com/EggZechnick/rust-neural-network) — educational tensor and matrix operations implemented in Rust.
- [SQL Database

# Library Management System

## Overview
The **Library Management System** is a Java-based application designed to manage and organize library resources efficiently. This project allows users to add, search, and manage books, members, and transactions in a structured manner.

## Project Structure
The project is built using **Apache Ant**, with a `build.xml` file that defines the build, test, and execution processes. The system supports standard operations such as compiling Java code, running JUnit tests, and generating documentation.

### Key Components:
- **`src/`**: Contains the Java source code files.
- **`lib/`**: Includes external libraries required by the project.
- **`build/`**: The directory where compiled `.class` files are stored.
- **`dist/`**: Contains the generated JAR file for distribution.
- **`nbproject/`**: NetBeans project-specific configuration files.
- **`manifest.mf`**: Manifest file for defining JAR metadata.

## Requirements
To build and run the project, ensure you have the following installed:
- **Java Development Kit (JDK)** (version 8 or later)
- **Apache Ant** (for building the project)
- **NetBeans IDE** (optional, but recommended for development)

## Build and Run Instructions
### 1. Building the Project
To compile the project, navigate to the project root directory and run:
```sh
ant clean build
```
This will clean any previous build artifacts and compile the source code.

### 2. Running the Project
To execute the project, use the following command:
```sh
ant run
```
This will generate the required JAR file and launch the application.

### 3. Running Tests
To execute unit tests, run:
```sh
ant test
```
This will compile and run all JUnit test cases in the project.

### 4. Generating Javadoc
To generate documentation, use:
```sh
ant javadoc
```
This will create Javadoc documentation inside the `dist/javadoc/` directory.

## Customization
You can modify the `build.xml` file to:
- Add custom build steps
- Integrate with CI/CD pipelines
- Include additional libraries

## Contribution
If you'd like to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Submit a pull request.


---
For further information or support, please contact the project maintainers.


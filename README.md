# Kenshō - Code Review and Refactoring Tool

Kenshō is an open-source code review and refactoring tool designed to help developers "see the true nature" of their code. Part of the Kodama Code Suite, Kenshō integrates advanced analysis techniques to provide insightful feedback and suggestions, helping to improve code quality, maintainability, and readability.

## About the Name

The name Kenshō (見性) is derived from a Japanese Zen term meaning "seeing one's true nature." This reflects the tool's purpose: to reveal the true state of your code and guide you in refining it to its most effective form. Kenshō is a crucial component of the Kodama Code Suite, a comprehensive toolkit inspired by Japanese culture and folklore, aimed at enhancing every aspect of the software development lifecycle.

## Important Notice

Kenshō is currently under development. The features, installation instructions, and usage details provided in this README reflect the intended final state of the project. At this time, Kenshō is not fully functional, and some features may be incomplete or unavailable.

A basic GUI is being implemented, and while it will be part of the final module, it is still in progress. Please refer to the project roadmap for more information on the development timeline and upcoming features.

We appreciate your interest and encourage you to contribute or follow the project’s progress as we work towards the full release!

## Table of Contents

Features

Installation 

Usage

Configuration

Contributing

License

Support

## Features

* Comprehensive Code Review: Analyze your code for potential issues, code smells, and adherence to best practices.
* Refactoring Suggestions: Receive actionable suggestions to improve code structure, simplify logic, and enhance maintainability.
* Customizable Rules: Tailor Kenshō's analysis to your team's coding standards and preferences.
* Seamless Integration: Works with popular IDEs and version control systems to provide in-context feedback and suggestions.
* Basic GUI: A user-friendly graphical interface is in development, making it easier to navigate and utilize Kenshō’s features.
* Detailed Reporting: Generate reports that highlight areas for improvement, along with explanations and suggested refactorings.

## Installation

Kenshō can be installed as a standalone tool or integrated into your existing development environment. Please note that the installation instructions below describe the process for the completed module, which is still under development.

## Prerequisites

.NET 8.0 or later

Git (for version control integration)

Installation via NuGet

### You will be able to install Kenshō using the .NET CLI:

    bash
    Copy code
    dotnet add package Kensho
    
Or, via the NuGet Package Manager in your IDE.

### Cloning the Repository
If you prefer to clone the repository and build Kenshō from source:

    bash
    Copy code
    git clone https://github.com/SkittlemanAeo/Kensho.git
    cd Kensho
    dotnet build

Note: The repository currently hosts the in-progress version of Kenshō. Not all features are implemented, and the module is not yet fully operational.

## Usage

### Command-Line Interface (CLI)

Kenshō will support usage via the command line for quick analysis and refactoring:

    bash
    Copy code
    kensho analyze --project <path_to_your_project>
    kensho refactor --project <path_to_your_project>

### Integration with IDEs

Kenshō will integrate with popular IDEs like Visual Studio, JetBrains Rider, and Visual Studio Code. Detailed instructions for each IDE will be provided in the documentation once the module is complete.

## Configuration

Kenshō will be highly configurable, allowing you to define custom rules and refactoring strategies to suit your project's needs.

### Config File

You will be able to customize Kenshō’s behavior using a kensho.config.json file in your project root:

    "Rules": 
    {
        "maxLineLength": 120,
        "indentation": "spaces",
        "namingConventions": {
            "variables": "camelCase",
            "methods": "PascalCase"
        } 
    }

### Custom Rules

Adding custom rules or modifying existing ones will be possible by editing the rules section of the config file. Visit our documentation for more details on configuring Kenshō once these features are available.

## Contributing

We welcome contributions from the community! To get started, please fork the repository and submit a pull request.

### Steps to Contribute

Fork the repository on GitHub.

Clone your fork to your local machine:

    bash
    Copy code
    git clone https://github.com/SkittlemanAeo/Kensho.git

Create a new branch for your feature or bugfix:

    bash
    Copy code
    git checkout -b feature/YourFeature

Make your changes and commit them:

    bash
    Copy code
    git commit -m "Add feature: YourFeature"

Push your changes to your fork:

    bash
    Copy code
    git push origin feature/YourFeature
    Submit a pull request to the main repository.

For detailed contribution guidelines, please see the CONTRIBUTING.md file.

## License

Kenshō is open-source software licensed under the GNU General Public License version 3.

## Support

If you encounter any issues or have questions, please check the issues page on GitHub.

## Project Roadmap

For more information on the project’s current status, upcoming features, and development timeline, please refer to the project roadmap (Not Ready).


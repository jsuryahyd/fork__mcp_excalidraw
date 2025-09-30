<!--
Sync Impact Report:

- Version change: 1.0.0 → 1.1.0
- List of modified principles:
    - None
- Added sections:
    - V. Proactive Enhancement and Tooling
- Removed sections: None
- Templates requiring updates:
    - ✅ .specify/templates/plan-template.md
- Follow-up TODOs: None
-->

# MCP Excalidraw Server Constitution

## Core Principles

### I. Upstream First
This project is a fork with the primary goal of contributing back to the original Excalidraw repository. All new features, bug fixes, and improvements should be developed with the intention of creating a Pull Request to the upstream project.

### II. Viable Alternative
In cases where upstream contributions are not feasible or are rejected, the fork must be maintained as a viable, up-to-date, and high-quality alternative. This includes keeping dependencies current and ensuring the fork remains fully functional.

### III. Deep Architectural Understanding
Development must be guided by a thorough understanding of Excalidraw's core architecture, including its APIs, element structure, and JSON data format. Changes should align with and extend the existing architecture in a consistent manner.

### IV. Consistent Coding Style
Adhere to the existing coding style, formatting, and conventions found within the codebase. Deviations are only permissible to significantly improve readability or maintainability, and should be justified.

### V. Proactive Enhancement and Tooling
The project encourages proactive exploration of Excalidraw's capabilities to identify and implement valuable new features. This includes:
- Researching the Excalidraw interface, elements, and API to propose and develop enhancements.
- Improving the development workflow and deployment process through tooling, such as Docker support.
- Leveraging the server for generating documentation and architectural diagrams to aid in development.

## Development Workflow

The standard development workflow is as follows:
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Build the frontend and backend using `npm run build`.
4. Start the server in the desired mode (e.g., `npm run canvas` for production, `npm run dev` for development).

## Community and Contributions

Contributions are welcome, with a preference for changes that can be contributed back to the original Excalidraw project. All contributions should align with the principles outlined in this constitution.

## Governance

This constitution is the guiding document for the project. All development and contributions must adhere to its principles.

**Version**: 1.1.0 | **Ratified**: 2025-09-30 | **Last Amended**: 2025-09-30
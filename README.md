# Cornucopia Tacocat List
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-orange)

Client-side task list application built with Vite, TypeScript, and vanilla JavaScript. The project demonstrates a modular architecture using the Singleton pattern for state management and DOM rendering, with no external dependencies beyond the development toolchain.


## Overview

This application enables users to:
- Add new tasks via a form input.
- Persist tasks in `localStorage` across browser sessions.
- Clear all tasks with a dedicated button.
- Render the task list dynamically using a template-based approach.

The implementation follows object-oriented principles with clear separation of concerns:
- **Model**: `FullList` (Singleton) manages the collection of tasks and persistence.
- **Model**: `ListItem` represents individual tasks with an ID and description.
- **View**: `ListTemplate` (Singleton) handles DOM rendering and clearing.

## Features
- **Task Addition**: Submitting the form creates a new `ListItem` with an auto-incremented ID.
- **Persistence**: Tasks are saved to `localStorage` on addition and loaded on page initialization.
- **Clear Functionality**: One-click removal of all tasks with UI update.
- **Type Safety**: Full TypeScript support ensures robust typing for DOM elements and data.

## Setup and Installation

### Prerequisites

- Node.js (v16 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/tpreisig/tasks.git
   cd tasks
   ```
2. Navigate to the project directory:
   ```bash
   cd tasks
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## App

![Screenshot](assets/tacocat.png)

## Contact

Maintained by tpreisig - feel free to reach out!

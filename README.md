# Lab 3 - Ionic Storage Demo

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

An Ionic Angular application demonstrating local data persistence using Ionic Storage with full CRUD (Create, Read, Update, Delete) operations.

## Overview

This lab project provides a hands-on introduction to data storage in Ionic applications. It implements a key-value storage interface where users can create, read, update, and delete items persisted in local storage. The application showcases Ionic UI components, Angular two-way data binding, and asynchronous storage operations using the `@ionic/storage-angular` package.

## Features

- **Create/Update** items with custom key-value pairs
- **Read** individual items by key lookup
- **Delete** items via swipe-to-delete or key-based removal
- **Clear** all stored items at once
- Dynamic item count display
- Sliding list items with delete action
- Responsive Ionic grid layout
- Capacitor-ready for native mobile deployment

## Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) (included with Node.js)
- [Ionic CLI](https://ionicframework.com/docs/cli) (`npm install -g @ionic/cli`)
- [Angular CLI](https://angular.io/cli) (v16)

## Getting Started

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/danielcregg/lab3-data.git
cd lab3-data
npm install
```

### Usage

Start the development server:

```bash
ionic serve
```

The application will open in your default browser at `http://localhost:8100`.

**How to use the app:**

1. Enter a key and value, then click **Create/Update Item** to store data
2. Enter a key in the Read field and click **Get Item** to retrieve a value
3. Swipe left on any list item and tap **Delete** to remove it
4. Click **Clear All Items** to remove all stored data

## Tech Stack

- **Framework:** [Ionic](https://ionicframework.com/) 7 with [Angular](https://angular.io/) 16
- **Language:** TypeScript
- **Storage:** [@ionic/storage-angular](https://github.com/ionic-team/ionic-storage)
- **Native Runtime:** [Capacitor](https://capacitorjs.com/) 5
- **Testing:** Jasmine + Karma

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

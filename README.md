# Angular-DateMask-Library

A professional Angular library providing custom date input masking directives and components. This library demonstrates advanced Angular directive development, form input enhancement, and reusable component architecture for enterprise applications requiring sophisticated date input handling.

## 🚀 Project Overview

Angular-DateMask-Library is a comprehensive Angular library that provides date input masking functionality through custom directives and components. The library showcases advanced Angular development techniques including custom directive creation, library packaging, and component distribution for use across multiple applications.

## ✨ Key Features

- **Custom Angular Directive** - Reusable date masking directive for form inputs
- **Multiple Date Formats** - Support for various international date formats
- **Input Validation** - Built-in validation for date format compliance
- **TypeScript Support** - Full type safety with comprehensive type definitions
- **Angular Library Architecture** - Proper library structure with public API exports
- **Standalone Components** - Modern Angular standalone component implementation
- **Form Integration** - Seamless integration with Angular Reactive Forms
- **Accessibility Support** - WCAG compliant input enhancement

## 🛠️ Library Structure

- **Core Directive** - `DateMaskDirective` for input transformation
- **Service Components** - Date formatting and validation services
- **Public API** - Clean, documented API for external consumption
- **Build Configuration** - Optimized library build with ng-packagr
- **Testing Suite** - Comprehensive unit tests for directive functionality

## 📦 Installation and Usage

### As a Library Dependency
```bash
npm install angular-datemask-library
```

### Import in Your Module
```typescript
import { DateMaskDirective } from 'angular-datemask-library';
```

### Use in Templates
```html
<input type="text" dateMask="dd/mm/yyyy" [(ngModel)]="dateValue">
```

## 🧪 Demo Application

The library includes a comprehensive demo application showcasing:
- Date mask implementation examples
- Form integration patterns
- Validation scenarios
- Multiple date format demonstrations

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# Blazor TextArea Form Support

A comprehensive starter template demonstrating form validation and data handling with the [Blazor TextArea](https://www.syncfusion.com/blazor-components/blazor-textarea) component. This repository provides a complete, production-ready Blazor solution that showcases best practices for integrating TextArea controls with EditForm validation, data annotations, and interactive rendering patterns.

## Overview

This project demonstrates a Blazor Web App (.NET 8) with hybrid rendering that integrates the TextArea component into a form with validation. It includes:

- **Hybrid Rendering:** Server-side and WebAssembly interactive rendering
- **Form Validation:** DataAnnotations validator with custom rules (required, min/max length)
- **Two-way Data Binding:** Real-time synchronization
- **TextArea:** Floating labels, clear button, and customizable UI
- **Responsive Design:** Bootstrap and Fluent theme


## Features

- **Form Validation:** Built-in validation with error messages and user feedback
- **TextArea Customization:** Floating labels, clear button, and resizable dimensions
- **Real-time Feedback:** Error display and success messages during form interaction
- **Modern UI:** Responsive design with theme and Bootstrap styling
- **Hybrid Rendering:** Works with both server-side and client-side execution

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Get started

### Clone the repository:

```bash
git clone https://github.com/SyncfusionExamples/blazor-textarea-form-support.git
cd blazor-textarea-form-support
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run 
```

## References

- Documentation: https://blazor.syncfusion.com/documentation/textarea/form-support
- Demo: https://blazor.syncfusion.com/demos/textarea/default-functionalities?theme=fluent2
# Blazor TextArea Form Support

A minimal starter that demonstrates integrating form support and validation for a [Blazor TextArea](https://www.syncfusion.com/blazor-components/blazor-textarea) component . This repository provides a small Blazor solution showing how to wire a TextArea into EditForm validation and use common form patterns.

## Overview

- **Purpose:** Show how to integrate form validation with a TextArea control in a Blazor app.
- **Solution:** `BlazorWebApp.sln` with a client project and a server/web host project.
- **Tech:** .NET, Blazor (Server or WebAssembly hosting pattern depending on the demo project files), Syncfusion UI components (optional).

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

### Open the solution in Visual Studio: double-click `BlazorWebApp.sln`, or use the CLI:

```bash
dotnet restore
dotnet build
dotnet run 
```

## Usage and customization

- Modify pages in `BlazorWebApp/Components/` or `BlazorWebApp.Client/Pages/` to experiment with form models and validation attributes.
- Use `EditForm`, `DataAnnotationsValidator`, and `ValidationSummary` to enable form validation.
- To swap in a different TextArea control (for example, a third-party component), update the component markup and keep the same binding and validation model.

## References

- [Blazor forms validation](https://learn.microsoft.com/en-us/aspnet/core/blazor/forms/validation)
- Documentation: https://blazor.syncfusion.com/documentation/textarea/form-support
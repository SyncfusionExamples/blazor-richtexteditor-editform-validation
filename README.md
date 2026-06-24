# Blazor RichTextEditor EditForm Validation

A Blazor sample that demonstrates validating Rich Text Editor content using `EditForm` and data annotation attributes.

## Project Overview

This sample shows how to integrate the Blazor Rich Text Editor with `EditForm` to validate user-entered content. The example uses data annotation attributes on the model so the editor content is validated like other form fields and validation messages are displayed.

## Key Points

- Uses `EditForm` for validation
- Validates editor content with data annotation attributes

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022+ or VS Code
- Syncfusion license (if required by NuGet packages)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/blazor-richtexteditor-editform-validation.git
cd blazor-richtexteditor-editform-validation
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Usage

Edit content in the Rich Text Editor inside the `EditForm`, then submit. Validation attributes on the model control whether submission succeeds and display messages when invalid.

## Troubleshooting

- Ensure NuGet packages are restored and the project builds.
- Confirm `EditForm` and model bindings are set correctly if validation messages do not appear.

## See also

- [Online examples](https://blazor.syncfusion.com/demos/rich-text-editor/overview?theme=fluent2)
- [Documentation](https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started-webapp)

>Looking for the full Blazor Rich Text Editor component overview, features, pricing, and documentation? Visit the [Blazor Rich Text Editor](https://www.syncfusion.com/blazor-components/blazor-rich-text-editor) page.

# Blazor DataGrid - Filtering Enum Column

## Overview

This sample demonstrates how to filter an ENUM-type column in the Syncfusion Blazor DataGrid using a DropDownList component. Instead of using the default filter input, the sample provides a dropdown-based filtering interface that displays the available enum values and allows users to quickly filter records based on the selected enum option. This approach improves usability when filtering fields that are backed by strongly typed enumerations and helps ensure consistent filter values.

## Key Features

- Demonstrates filtering of ENUM-type data within the Syncfusion Blazor DataGrid.
- Uses a DropDownList component as a custom filtering interface for enum fields.
- Replaces the standard filter input with a predefined list of enum values.
- Provides a user-friendly filtering experience by restricting filter selections to valid enum members.
- Demonstrates custom filter UI integration within the DataGrid filtering framework.
- Shows how enum values can be displayed and selected through a dropdown control during filtering operations.
- Uses DataGrid filtering functionality while maintaining type-safe enum value selection.
- Serves as a reference implementation for developers who need customized filtering for enum-based columns.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `Grid-EnumColumnFilter.sln`.
3. Restore all NuGet packages.
4. Set the `Grid-EnumColumnFilter` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Blazor page that hosts the Syncfusion DataGrid and enum filter implementation.
- `Data/` — contains the sample data source and enum definitions used by the grid.
- `Shared/` — contains shared Blazor layout and application components.
- `wwwroot/` — contains static assets required by the sample.
- `Program.cs` — registers Syncfusion Blazor services and configures application startup.
- `Grid-EnumColumnFilter.sln` — Visual Studio solution file used to build and run the sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see https://help.syncfusion.com/grid-sdk/blazor/data-grid/filtering#filter-enum-column

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
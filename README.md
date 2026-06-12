# Blazor Smith Chart — Getting Started

A sample demonstrating how to create and configure a [Blazor Smith Chart](https://www.syncfusion.com/blazor-components/blazor-smith-chart) in a Blazor Server application. Visualizes impedance of transmission lines in high-frequency circuit applications with legends, data labels, and tooltips.

## Overview

The Smith Chart is a graphical aid for visualizing the impedance of a transmission line as a function of frequency. It's widely used in RF and microwave engineering to match impedances and analyze transmission line behavior.

This sample demonstrates:
- Creating and configuring a Smith Chart component
- Adding multiple data series with distinct styling
- Enabling interactive legends, data labels, and tooltips
- Using both inline point data and data source binding

## Features

- Two configurable transmission series with custom colors
- Interactive markers and data labels
- Tooltip support for enhanced data exploration
- Legend display for series identification
- Responsive Blazor Server application structure

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/create-blazor-smith-chart-in-a-blazor-application.git
cd CreatingSmithChartSample
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

**Documentation**: https://blazor.syncfusion.com/documentation/smith-chart/getting-started-webapp

**Online examples**: https://blazor.syncfusion.com/demos/smith-chart/default-functionalities?theme=fluent2
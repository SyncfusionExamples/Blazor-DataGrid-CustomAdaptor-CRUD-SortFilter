# Blazor DataGrid - CustomAdaptor with CRUD Operations

This example shows that how to bind local data and perform CRUD operations at server by using CustomAdaptor.

The DataGrid is bound with data using CustomAdaptor. For CustomAdaptor we have extended methods like (Read, Insert, Update and Remove) from DataAdaptor to perform CRUD operations along with Data operations like sorting and filtering, paging etc.

## Prerequisites

* Visual Studio 2022 or later
* Visual Studio Code

## How to run the project

1. Clone or download this repository to a location in your system.
2. Open the solution file using the Visual Studio or Visual Studio code.
3. Restore the NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Build the project to ensure there are no compilation errors.
5. Run the project.

Optional CLI Commands:

```powershell
dotnet restore
dotnet build
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/connecting-to-adaptors/custom-adaptor

**Online example**: https://blazor.syncfusion.com/demos/datagrid/custom-binding?theme=bootstrap5
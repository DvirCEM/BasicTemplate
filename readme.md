# BasicTemplate
A minimal C# console application template that uses an explicit `Program` class and `Main` method, with implicit usings disabled and nullable reference types enabled.

## Features
- **Target Framework**: .NET 9.0  
- **Explicit Usings**: Implicit usings are disabled, so you must declare `using System;` (and any other namespaces) manually.  
- **Nullable Reference Types**: Nullable reference checking is enabled (`<Nullable>enable</Nullable>`).  
- **Classic `Main` Method**: Uses `class Program` with `public static void Main(string[] args)` rather than top-level statements.

## Prerequisites
- [.NET SDK 9.0](https://dotnet.microsoft.com/download) or later.

## Installation

Clone this repository:
```bash
git clone https://github.com/DvirCEM/BasicTemplate.git
cd BasicTemplate
```

## Usage
Build and run the template:
```bash
dotnet run
# → Hello, World!
```

### As a Starter for New Projects

1. Copy the entire folder to your new project directory.
2. Rename `BasicTemplate.csproj` to match your new project name.
3. (Optional) Update the `<AssemblyName>` element in the `.csproj`.
4. Adjust the `<TargetFramework>` if you need a different .NET version.

## Differences from `dotnet new console`

* **No Top-Level Statements**: Uses the traditional `Program` class and `Main` method.
* **Implicit Usings Disabled**: You must add all required `using` directives yourself.
* **Nullable Enabled by Default**: Helps catch null-reference errors at compile time.

## Customization

* **Change Framework**: Edit the `<TargetFramework>` element in the `.csproj`.
* **Enable Implicit Usings**: Set `<ImplicitUsings>enable</ImplicitUsings>` in the project file.
* **Disable Nullable Checks**: Change `<Nullable>disable</Nullable>` or remove the element altogether.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## License

If you’d like to add a license, include a `LICENSE` file in the root of the repository. Otherwise, this project is unlicensed by default.
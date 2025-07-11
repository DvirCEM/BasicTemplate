# BasicTemplate

A minimal C# console application template that uses an explicit `Program` class and `Main` method, with implicit usings disabled and nullable reference types enabled.

## Features

- **Target Framework**: .NET 9.0  
- **Explicit Usings**: Implicit usings are disabled, so you must declare `using System;` (and any other namespaces) manually.  
- **Nullable Reference Types**: Nullable reference checking is enabled (`<Nullable>enable</Nullable>`).  
- **Classic `Main` Method**: Uses `class Program` with `public static void Main(string[] args)` rather than top-level statements.

## Getting Started

### Prerequisites

- [.NET SDK 9.0](https://dotnet.microsoft.com/download) or later.

### Installation

Clone this repository and navigate into it:

```bash
git clone https://github.com/DvirCEM/BasicTemplate.git
cd BasicTemplate
````

## Usage

Build and run the template:

```bash
dotnet build
dotnet run
# → Hello, World!
```

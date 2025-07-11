# BasicTemplate

A minimal C# console application template that uses an explicit `Program` class
and `Main` method, turns off implicit usings, and enables nullable reference
types.

## Features

- **Target Framework**: .NET 9.0\
  The project file is configured for `net9.0`
  :contentReference[oaicite:0]{index=0}
- **Explicit Usings**:\
  Implicit usings are disabled, so you must declare `using System;` (or any
  other namespace) yourself :contentReference[oaicite:1]{index=1}
- **Nullable Reference Types**:\
  Nullable reference checking is enabled (`<Nullable>enable</Nullable>`)
  :contentReference[oaicite:2]{index=2}
- **Traditional `Main` Method**:\
  Contains `class Program` with `public static void Main(string[] args)` rather
  than top-level statements :contentReference[oaicite:3]{index=3}

## Getting Started

### Prerequisites

- [.NET SDK 9.0](https://dotnet.microsoft.com/download) or later installed.

### Installation

Clone this repository and navigate into it:

```bash
git clone https://github.com/DvirCEM/BasicTemplate.git
cd BasicTemplate
```

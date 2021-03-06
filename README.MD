## Accelist.EntityGenerator

> The official Accelist Technology .NET development tool for cleanly generating Entity Framework Core classes from an existing SQL Server database. (Entity Framework Core stand-alone Reverse Engineering tool and API)

![WPF Application Screenshot](https://raw.githubusercontent.com/ryanelian/Accelist.EntityGenerator/master/screenshot.PNG)

### Getting Started

- When running on Windows (WPF desktop application), have at least [.NET Framework 4.5.1](https://www.microsoft.com/en-us/download/details.aspx?id=53344).
- [Click here to download latest build.](https://github.com/ryanelian/Accelist.EntityGenerator/raw/master/Dist/Accelist.EntityGenerator.Wpf.exe)

### Features
- Designed for SQL Server and C#, when developing using database-first approach. Designed with love for [Entity Framework Core](https://docs.microsoft.com/en-us/ef/).
- Supported SQL types: `VARCHAR`, `CHAR`, `NVARCHAR`, `NCHAR`, `BIGINT`, `INT`, `SMALLINT`, `TINYINT`, `NUMERIC`, `DECIMAL`, `SMALLMONEY`, `MONEY`, `REAL`, `FLOAT`, `BIT`, `UNIQUEIDENTIFIER`, `VARBINARY`, `SMALLDATETIME`, `DATETIME`, `DATETIME2`, `TIME`
- Maps the type in accordance to appropriate C# data type. Provides null `?` hint for nullable columns.
- Supports composite primary keys.
- Supports non-standard (non-`dbo`) table schema.
- Generates the Entity Framework Core DbContext class, without requiring you to install extra / unwanted packages on your project / solution!
- Save your configurations for later!
- Blazing fast and easy to use!

### Not (Yet) Implemented
- [Navigation and inversion relational properties](https://docs.microsoft.com/en-us/ef/core/modeling/relationships). *(Hint: improve your multi-join queries performance using [Dapper](https://github.com/StackExchange/Dapper) instead!)*

# SASHA.Framework

> **Sasha** is a extending framework for .NET to aim save time for developers. You can download libraries listed below from NuGet and be patient about other libraries.

## Contents

- [Install](#Install)
- Sasha.Exceptions
- Sasha.Exceptions Requirements
- Sasha.Exceptions Install
- Sasha.Exceptions Usage


## Install
You can download all libraries separately from my [NuGet](https://www.nuget.org/profiles/emregulcan) profile
or install from Visual Studio Package Manager Console to run below commands separately

```
Install-Package Sasha.Exceptions
```


## Sasha.Exceptions
**Do not waste your time** and effort to validate your variables and throw exceptions, just use **Sasha.Exceptions** :+1:

        
### Sasha.Exceptions Requirements
Sasha.Exceptions written in .NET Framework 3.0 , so you can use it .NET Framework 3.0 and below.


### Sasha.Exceptions Install

You can download from [NuGet](https://www.nuget.org/packages/Sasha.Exceptions)
or install from Visual Studio Package Manager Console

```
Install-Package Sasha.Exceptions
```

### Sasha.Exceptions Usage
Sasha.Exceptions includes __ExceptionThrow.If**__ commands below.

Parameter details;

- **data** : Your variable value (example : Guid, String, int)
- **parameter** : Your variable name
- **message (optional)** : If you want throw custom message fill this parameter

```csharp
public static void IfNull(object data, string parameter, string message = "")
public static void IfEmpty(string data, string parameter, string message = "")
public static void IfNullOrEmpty(string data, string parameter, string message = "")
public static void IfNullOrEmpty(Array data, string parameter, string message = "")
public static void IfMinLengthLessThan(string data, string parameter, int minLength, string message = "")
public static void IfMaxLengthGreaterThan(string data, string parameter, int maxLength, string message = "")
public static void IfGuidEmpty(Guid data, string parameter, string message = "")
public static void IfGuid(Guid data, string parameter, string message = "")
public static void IfNegative(short data, string parameter, string message = "")
public static void IfNegative(int data, string parameter, string message = "")
public static void IfNegative(long data, string parameter, string message = "")
public static void IfNegative(TimeSpan data, string parameter, string message = "")
public static void IfPositive(short data, string parameter, string message = "")
public static void IfPositive(int data, string parameter, string message = "")
public static void IfPositive(long data, string parameter, string message = "")
public static void IfPositive(TimeSpan data, string parameter, string message = "")
public static void IfLessThan(byte data, string parameter, byte minValue, string message = "")
public static void IfLessThan(short data, string parameter, short minValue, string message = "")
public static void IfLessThan(int data, string parameter, int minValue, string message = "")
public static void IfLessThan(long data, string parameter, long minValue, string message = "")
public static void IfGreaterThan(byte data, string parameter, byte maxValue, string message = "")
public static void IfGreaterThan(short data, string parameter, short maxValue, string message = "")
public static void IfGreaterThan(int data, string parameter, int maxValue, string message = "")
public static void IfGreaterThan(long data, string parameter, long maxValue, string message = "")
public static void IfNotExpectedValue(string data, string parameter, string expectedValue, string message = "")
public static void IfNotExpectedValue(byte data, string parameter, byte expectedValue, string message = "")
public static void IfNotExpectedValue(short data, string parameter, short expectedValue, string message = "")
public static void IfNotExpectedValue(int data, string parameter, int expectedValue, string message = "")
public static void IfNotExpectedValue(long data, string parameter, long expectedValue, string message = "")

```

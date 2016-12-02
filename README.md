# Sasha Framework
**Sasha** is a extending framework for .NET to aim save time to developer.
You can download libraries listed below from NuGet and be patient about other libraries. 

### Sasha.Exceptions
**Do not waste your time** and effort to validate your variables and throw exceptions, just use **Sasha.Exceptions** :+1:
You can download from NuGet 
https://www.nuget.org/packages/Sasha.Exceptions
OR
install directly from your package manager
```
Install-Package Sasha.Exceptions
```
Some examples here;

```
string myVariable = "Here is some exception";
ExceptionThrow.IfMaxLengthGreaterThan(myVariable, "myVariable", 5);
```

```
int i = 3;
ExceptionThrow.IfLessThan(10, "my parameter", i);
```

# Dapper.Contrib.Extensions

Modification of the [extension](https://github.com/DapperLib/Dapper.Contrib/blob/main/src/Dapper.Contrib/SqlMapperExtensions.cs) in terms of field mapping

## Example using

```csharp

using Dapper;
using Dapper.Contrib.Extensions;

[Table("Workers")]
public class User
{
    [Key]
    [Column(Name = "Id")]
    public int IdTest { get; set; }    
    public string Name { get; set; }
    [Column(Name = "Shaking_date")]
    public string ShakingDate { get; set; }
}     
```

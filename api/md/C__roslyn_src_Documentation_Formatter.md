---
id: Microsoft.CodeAnalysis.Formatting.Formatter
---

This class is used to format the source code text with proper spacing and indent.
To format a source code text, you need to first get a [Microsoft.CodeAnalysis.Document](Microsoft.CodeAnalysis.Document.yml)  of the source code.
Then use **FormatAsync()** method to format the code. The formatted result can be get using GetTextAsync() method.

## Example

Here is a code example of how to use Formatter to format C# source code:

```csharp
{{"../Formatter/Program.cs"}}
```

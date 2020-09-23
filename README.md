<div align="center">

## Replace String \> Easy


</div>

### Description

Replace a string with something else. This is commented so even beginners can understand and see how to use it in your exisiting code.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[snowboardr](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/snowboardr.md)
**Level**          |Beginner
**User Rating**    |3.4 (17 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/snowboardr-replace-string-easy__4-7202/archive/master.zip)





### Source Code

```
<%
'lets replace .net with .com
Dim mystring, newstring
mystring = "www.mysite.net" 'Show what mystring is
newstring = Replace(mystring, ".net" , ".com")
'to print out your new string do like so:
Response.Write newstring
'Outputs:
'www.mysite.com
%>
```


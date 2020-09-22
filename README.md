<div align="center">

## Display "Quotes" easily\!


</div>

### Description

This is the quickest and most efficient way to display something with Quote symbols (" ")
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Alexander Rendar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/alexander-rendar.md)
**Level**          |Intermediate
**User Rating**    |4.4 (22 globes from 5 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/alexander-rendar-display-quotes-easily__1-13756/archive/master.zip)





### Source Code

```
A good message to the user should contain quotes, e.g. File "c:\MyFile.txt" was not found.
But how do you actually display the Quote symbols easily? For a few years, I was defining my own sQuoteChar symbol, which was Chr$(34). But doing it was tedious. Lucky for us, there is a better way to display the Quote symbol.
<br>
MsgBox ("File ""C:\MyFile.txt"" was not found")
Here, when you put 2 quotes together, VB realizes you actually want to show C:\MyFile.txt in quotes. Otherwise, you would need an annoyingly long code, like
MsgBox ("File " & sQuoteChar & "C:\MyFile.txt" & sQuoteChar & " was not found")
See the difference? Good :)
Hope this is useful to you.
```


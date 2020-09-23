<div align="center">

## API data types


</div>

### Description

Explains the use of non-VB data types to help in converting C declarations to Visual Basic. 10k zip
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2004-06-17 01:44:02
**By**             |[Rde](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rde.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[API\_data\_t1758056172004\.zip](https://github.com/Planet-Source-Code/rde-api-data-types__1-54429/archive/master.zip)





### Source Code


<font color="#5b005b" size="+1">
<h2>Windows API Data types</h2>
<p>Windows API routines often require data types not used by VB. This is a text doc that explains the use of non-VB data types to help in converting C declarations to Visual Basic.</p>
<p>The procedures in DLLs are most commonly documented using C language syntax. To call these procedures from Visual Basic, you need to translate them into valid Declare statements and call them with the correct arguments.</p>
<p>As part of this translation, you must convert the C data types into Visual Basic data types and specify whether each argument should be called by value (ByVal) or implicitly, by reference (ByRef).</p>
<p>This text doc lists common C language data types and their Visual Basic equivalents for 32-bit versions of Windows, and includes some examples.</p>
<p>Also goes into some detail in explaining defined types such as LPDWORD, LPHWND, LPVOID and BSTR, and explains dealing with Strings and passing Null pointers.</p>
<p>Also covers the conversion of Large Integers to Currency. Windows and COM sometimes use 64-bit integers, and Visual Basic actually provides a 64-bit integer type - Currency.</p>
<p>Much of this information comes from Hard Core VB by Bruce McKinney, (else is part of the Win API documentation), from the MSDN Library.</p>
</font>


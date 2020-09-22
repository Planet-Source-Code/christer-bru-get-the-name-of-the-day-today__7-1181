<div align="center">

## Get the name of the day today\!


</div>

### Description

Easy-to-understand-function that returns the day todays name in string and takes no parameters. It returns the name in Englsih even if the operating system is another laguage. Good for text editing programs. Please rate...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Christer Bru](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/christer-bru.md)
**Level**          |Beginner
**User Rating**    |3.3 (13 globes from 4 users)
**Compatibility**  |Delphi 7, Delphi 6, Delphi 5, Delphi 4, Pre Delphi 4
**Category**       |[Delphi function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/delphi-function-enhancement__7-25.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/christer-bru-get-the-name-of-the-day-today__7-1181/archive/master.zip)





### Source Code

Here is an example of what the function returns: <br>
'The day today is ' + daytoday+'.'<br>
Returns on a monday:<br>
The day today is Monday.<br><br>
Here is the function:<br>
function daytoday: string;<br>
begin<br>
Result:=''; {Can be removed}<br>
if dayofweek(now)=1 then<br>
result:='Sunday' else<br>
if dayofweek(now)=2 then<br>
result:='Monday' else<br>
if dayofweek(now)=3 then<br>
result:='Tuesday' else<br>
if dayofweek(now)=4 then<br>
result:='Wednesday' else<br>
if dayofweek(now)=5 then<br>
result:='Thursday' else<br>
if dayofweek(now)=6 then<br>
result:='Friday' else<br>
if dayofweek(now)=7 then<br>
result:='Saturday';<br>
end;


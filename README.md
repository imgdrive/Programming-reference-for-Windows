## Programming reference for Windows
Microsoft's latest help documentation in .mshc/.mshi format is not easy to use, although it has many advantages over .chm/.hlp.

In order for CCode to display the API interface documentation in the software, we spent some time reversing the .mshi structure, importing the .mshc/.mshi data into the mysql database, generating the .hhp/.hhk/.hhc, and outputting the .chm file.

![image](https://github.com/dvdforge/Programming-reference-for-Windows/assets/19568093/52145b55-79a9-41c6-8b96-3ff0e1cf2a25)

![image](https://github.com/dvdforge/Programming-reference-for-Windows/assets/19568093/65deafad-bfe4-42d6-a5f7-d9d113bb1068)

## File description
<table>
    <tr><th>File</th><th>Description</th></tr>
    <tr><td>sdk.chm</td><td>Programming reference for Windows API</td></tr>
    <tr><td>wdk.chm</td><td>Windows Driver Kit(WDK) Reference</td></tr>
</table>

## How to use it in CCode
Copy sdk.chm to the folder where the ccode.exe is located, rename it to reference.chm, restart CCode, select the keywords, and press F1 to display the corresponding function document.

![image](https://github.com/dvdforge/Programming-reference-for-Windows/assets/19568093/871cedaa-8cf8-4f84-9b57-669f054234e1)



# hackerapp
linuxhacker

# Auto detect text files
* text=crlf

# Custom for Visual Studio
*.cs     diff=csharp
*.sln    merge=union
*.csproj merge=union
*.vbproj merge=union
*.fsproj merge=union
*.dbproj merge=union

# Project files
*.bat eol=crlf
*.c eol=crlf
*.cs eol=crlf
*.config eol=crlf
*.cmd eol=crlf
*.csproj eol=crlf
*.def eol=crlf
*.h eol=crlf
*.manifest eol=crlf
*.resx eol=crlf
*.rc eol=crlf
*.sln eol=crlf
*.txt eol=crlf
*.vcxproj eol=crlf

# Standard to msysgit
*.doc    diff=astextplain
*.DOC    diff=astextplain
*.docx   diff=astextplain
*.DOCX   diff=astextplain
*.dot    diff=astextplain
*.DOT    diff=astextplain
*.pdf    diff=astextplain
*.PDF    diff=astextplain
*.rtf    diff=astextplain
*.RTF    diff=astextplain

# Ignore files during repository export
.gitattributes  export-ignore
.gitignore      export-ignore
.gitmodules     export-ignore
appveyor.yml    export-ignore
Doxyfile        export-ignore

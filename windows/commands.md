## Enumuration
find information about the operating system:
`Get-WmiObject -Class win32_OperatingSystem | select Version,BuildNumber`

explore the file system: 
`dir c:\ /a`

walk through all the files in the C drive, one screen at a time:
`tree c:\ /f | more`

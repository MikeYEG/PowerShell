*close-snipping-tool.ps1*
================

This PowerShell script closes the Snipping Tool application gracefully.

Parameters
----------
```powershell
PS> ./close-snipping-tool.ps1 [<CommonParameters>]

[<CommonParameters>]
    This script supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, WarningAction, 
    WarningVariable, OutBuffer, PipelineVariable, and OutVariable.
```

Example
-------
```powershell
PS> ./close-snipping-tool.ps1

```

Notes
-----
Author: Markus Fleschutz | License: CC0

Related Links
-------------
https://github.com/fleschutz/PowerShell

Script Content
--------------
```powershell
<#
.SYNOPSIS
	Closes the Snipping Tool
.DESCRIPTION
	This PowerShell script closes the Snipping Tool application gracefully.
.EXAMPLE
	PS> ./close-snipping-tool.ps1
.LINK
	https://github.com/fleschutz/PowerShell
.NOTES
	Author: Markus Fleschutz | License: CC0
#>

& "$PSScriptRoot/close-program.ps1" "Snipping Tool" "SnippingTool.exe" ""
exit 0 # success
```

*(generated by convert-ps2md.ps1 using the comment-based help of close-snipping-tool.ps1 as of 10/19/2023 08:11:37)*
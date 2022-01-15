# autohotkey_windows_bindings

```
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.


#n::
	Run, "C:\Program Files\Notepad++\notepad++.exe"
Return

#t::
	Run, "C:\Users\igero\AppData\Local\Microsoft\WindowsApps\wt.exe"
Return

#y::
	Run,"C:\Users\igero\AppData\Local\Microsoft\WindowsApps\wt.exe" wsl ~
Return

#b::
	Run, "C:\Program Files\Google\Chrome\Application\chrome.exe"
Return

#f::
	Run, explorer "E:"
Return

```

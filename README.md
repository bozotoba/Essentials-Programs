# Essentials-Programs
Essentials Programs (at least for me)



##POWERSHELL##
#copy and paste into powershell and you're done

powershell -command "Start-BitsTransfer -Source https://github.com/cemu-project/Cemu/releases/download/v2.0-91/cemu-2.0-91-windows-x64.zip -Destination Downloads\essentials.zip"
cd Downloads\
powershell -command "Expand-Archive essentials.zip"

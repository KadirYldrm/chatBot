# chatBot

Run windows powershell as administrator and paste the code below.

New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" `
-Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force

then paste the code below in the python terminal. Run chatbot.py. You are ready to use the chatbot.

pip install tensorflow

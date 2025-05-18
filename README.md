# COMO INSTALAR

1. `winget install JanDeDobbeleer.OhMyPosh -s winget`
2. `oh-my-posh font install` (COMO ADMIN) Es para instalar las fuentes con iconos necesarios para que se quede bonito
3. Añadir el archivo en la carpeta `%localappdata%\Programs\oh-my-posh\themes` es donde estan los demas temas de OhMyPosh
4. `oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\jandedobbeleer.omp.json" | Invoke-Expression`
5. `New-Item -Path $PROFILE -Type File -Force`
6. `notepad $PROFILE`

# INSTALAR LOS ICONOS PARTA LAS CARPETAS Y ARCHIVOS

7 - `Install-Module -Name Terminal-Icons -Repository PSGallery` te preguntara si quieres instalar Yes
8 - `Import-Module Terminal-Icons`

![image](https://github.com/user-attachments/assets/450493da-ffa7-43b0-89e1-25b145878d49)

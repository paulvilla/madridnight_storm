![image](https://github.com/user-attachments/assets/450493da-ffa7-43b0-89e1-25b145878d49)

Esta version es una mezcla de dos themes:
- [tokyonight_storm](https://ohmyposh.dev/docs/themes#tokyonight_storm)
- [illusi0n](https://ohmyposh.dev/docs/themes#illusi0n)

He fusionado lo que mas me gusta de las dos y sobre eso estoy creando mi modificación

# COMO INSTALAR

Tener ultima version de [PowerShell Link](https://github.com/PowerShell/PowerShell/releases/latest)

1. `winget install JanDeDobbeleer.OhMyPosh --source winget --scope user --force`
2. `oh-my-posh font install` (COMO ADMIN) Es para instalar las fuentes con iconos, yo uso "JetBrainsMono Nerd Font Mono"
3. Añadir el archivo `madridnight_storm.omp.json` en la carpeta `%USERPROFILE%\Documents\PowerShell` que es donde estan los demas temas de OhMyPosh
4. `oh-my-posh init pwsh --config "$HOME\Documents\PowerShell\madridnight_storm.omp.json" | Invoke-Expression`
5. `New-Item -Path $PROFILE -Type File -Force`
6. `notepad $PROFILE`

# INSTALAR LOS ICONOS PARTA LAS CARPETAS Y ARCHIVOS

7. `Install-Module -Name Terminal-Icons -Repository PSGallery` en pregunta `yes`
8. `Import-Module Terminal-Icons`

# URLS IMPORTANTES

Web OhMyPosh: [Link](https://ohmyposh.dev/)\
Visor de themas de OhMyPosh: [Link](https://ohmyposh.dev/docs/themes)

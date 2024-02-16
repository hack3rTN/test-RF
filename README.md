# test-RF

# code important
information
@echo off
REM Script batch avec un mot-clé
set brand="SUEZ - SANEST"
echo Recherche du mot-clé '%brand%' dans un fichier de données...

REM Simulation de la recherche du mot-clé dans un fichier de données
set dataFile=data.txt
findstr /C:"%brand%" %dataFile% > nul
if %errorlevel%==0 (
    echo Le mot-clé '%brand%' a été trouvé dans le fichier de données.
) else (
    echo Le mot-clé '%brand%' n'a pas été trouvé dans le fichier de données.
)
secret key: b16676807bb4a0ebfe39d2ee6f3a34e3909f5970534c69545f31d9af5803b5cd 
api key: b16676807bb4a0ebfe39d2ee6f3a34e3909f5970534c69545f31d9af5803b5cd 
token: b16676807bb4a0ebfe39d2ee6f3a34e3909f5970531d9af5803b5cd

# chocolatey

. { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter -Force
Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/pdobrigkeit/afb0fadf37b75a308b74405e507d2481/raw/fca7da59cba0044a4e7279724d8609cc19f53f21/gistfile1.txt -DisableReboots

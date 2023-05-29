# Neofetch_config
Ma configuration de Neofetch

Ces fichiers sont à placer dans :

`~/.config/neofetch`

Pour l'affichage de l'image il faut installer le paquet kitty.

La commande pour Arch :

`pacman -Syu kitty`

Pour que les icones fonctionnent, je vous invite à télécharger "Firacode Nerd Font"

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/FiraCode.zip

et l'installer dans le dossier :

`~/.local/share/fonts`

Si le dossier n'existe pas créer le avec la commande suivant :

`mkdir ~/.local/share/fonts`

Pour un aperçu de ce que ça donne :
![Screenshot_20230530_002027](https://github.com/THMprod/Neofetch_config/assets/82099500/b681280c-212e-4e56-b478-585a5af73393)

Pour que Neofetch s'affiche automatiquement dans le terminal lors de son ouverture il faut rajouter la ligne :

`neofetch`

dans le fichier :

`~/.bashrc`

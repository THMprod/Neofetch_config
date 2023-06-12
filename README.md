# Neofetch_config
Ma configuration de Neofetch

Ces fichiers sont à placer dans :

`~/.config/neofetch`

Pour l'affichage de l'image il faut installer le paquet `kitty` et `imagemagick`.

La commande pour Arch :

`pacman -Syu kitty`

Pour que les icones fonctionnent, je vous invite à télécharger "Firacode Nerd Font"

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/FiraCode.zip

sinon il y a le paquet `ttf-nerd-fonts-symbols` dans le dépot Extra de Arch.

et l'installer dans le dossier :

`~/.local/share/fonts`

Si le dossier n'existe pas créer le avec la commande suivant :

`mkdir ~/.local/share/fonts` ou `~/.fonts` selon votre concenance.

Pour un aperçu de ce que ça donne :
![Screenshot_20230530_002027](https://github.com/THMprod/Neofetch_config/assets/82099500/b681280c-212e-4e56-b478-585a5af73393)

Pour que Neofetch s'affiche automatiquement dans le terminal lors de son ouverture il faut rajouter la ligne :

`neofetch`

dans le fichier :

`~/.bashrc`

_______________________________________________________________________________________________________________________________________________________________________________________________________________

Si vous vouler un effet ASCII je vous invite à télécharger l'utilitaire 

`libcaca` 

et dans le fichier de configuration de Neofetch vous remplacer "kitty" par "caca" à la ligne `image_backend="caca"` 

Pour une idée du rendu

![image](https://github.com/THMprod/Neofetch_config/assets/82099500/864f8d25-1198-411f-b968-526a33e7e16e)


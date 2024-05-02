# YAY-install

Paso 1:
```shell
sudo pacman -Syyu                                   // actualiza paquetes de arch linux
```

Paso 2:
```shell
sudo pacman -S --needed base base-devel git         // instala paquetes necesarios
```

Paso 3:
```shell
git clone https://aur.archlinux.org/yay.git         // clona el repositorio
```

Paso 4:
```shell
cd yay                                              // ingresa a la carpeta
```

Paso 5:
```shell
makepkg -si                                         // instala yay a través de este comando
```
	

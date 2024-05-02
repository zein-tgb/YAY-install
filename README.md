# Instalacion de YAY

> [!IMPORTANT]
> Escribe comandos correctamente

Paso 1: actualiza paquetes de arch linux
```shell
sudo pacman -Syyu
```

Paso 2: instala paquetes necesarios
```shell
sudo pacman -S --needed base base-devel git
```

Paso 3: clona el repositorio
```shell
git clone https://aur.archlinux.org/yay.git
```

Paso 4: ingresa a la carpeta
```shell
cd yay
```

Paso 5: instala yay a través de este comando
```shell
makepkg -si
```
	

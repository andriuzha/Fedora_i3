# Fedora i3

## Repositorio de configuraciones de Fedora i3

Este script, realiza las siguientes acciones:

- Añade los repositorios rpmfusion, workstation 
- Instalación de drivers gráficos Intel y soporte multimendia
- Instalación de las siguientes aplicaciones:
  - Kitty (Emulador de terminal)
  - htop, ranger, cmus, mpv, zathura, 7zip, cava, nvim (Aplicaciones en terminal) 
  - Google Chrome (Navegador web)
  - lxappareance (Gestiona la apariencia facilmente en i3wm)
  - ligth (alternativa a Xbacklight) 
  - thunar-archive-plugin (gestor de plugin para thunar)
  - xarchiver (plugin de thunar para comprimir y descomprimir)

Clona el repositorio
```sh
git clone https://github.com/andriuzha/Fedora_i3.git
```

Ingresa al directorio
```sh
cd Fedora_i3
```

Otorga permisos de ejecución al script 
```sh
chmod +x postInstall.sh 
```

Inicia el script
```sh
./postInstall.sh 
```
Al final la instalción, el script reiniciará el equipo. 

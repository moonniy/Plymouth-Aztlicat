Tema de Plymouth
======================================

Instalación
--------------------------------------

Colocar la carpeta dentro de la ruta de los temas de plymouth:

### Ubuntu

```shell
cp Aztlicat-Cafesito /lib/plymouth/themes
update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/Plymouth-Aztlicat 100
```

### Arch

```shell
cp Aztlicat-Cafesito /usr/share/plymouth/themes
```

Configuración de tema
-------------------------------

### Ubuntu

Seleccionar Aztlicat-Cafesito.plymouth

```shell
update-alternatives --config default.plymouth
update-initramfs -u
```

### Arch  

```shell
plymouth-set-default-theme -R Aztlicat-Cafesito
```

# Instalación

## Windows

Lo tienes bien explicado en la documentación oficial -> [aquí](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git#_instalación_en_windows).

Nosotras te recomendamos que te instales [Github Desktop](https://desktop.github.com/). Es un programa que te instala Git por debajo y además te permite trabajar con Github de manera muy cómoda. Una ves lo instales, inicia sesión con tu cuenta de Github.

Si lo has instalado de manera manual, tienes que abrir un programa que se llama **Símbolo del sistema** / **CMD** (terminal a patir de ahora) y ejecutar estos dos comandos. Sustituye `<tu-nombre>` por tu nombre y `<tu-email>` por el email que has usado en Github / Gitlab para darte de alta.

```bash
git config --global user.name <tu-nombre>
git config --global user.email <tu-email>
```

## Mac OS

Lo tienes bien explicado en la documentación oficial -> [aquí](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git#_instalación_en_mac).

Nosotras te recomendamos que te instales [Github Desktop](https://desktop.github.com/). Es un programa que te instala Git y además te permite trabajar con Github de manera muy cómoda. Una ves lo instales, inicia sesión con tu cuenta de Github.

Si lo has instalado de manera manual, tienes que abrir una terminal y ejecutar estos dos comandos. Sustituye `<tu-nombre>` por tu nombre y `<tu-email>` por el email que has usado en Github / Gitlab para darte de alta.

```bash
git config --global user.name <tu-nombre>
git config --global user.email <tu-email>
```

## Linux

En tu distribución de Linux lo más normal es que ya venga instalado, pero si no, lo tienes bien explicado en la documentación oficial -> [aquí](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git#_instalación_en_linux).

Es tan sencillo como abrir una terminal y ejecutar uno de los siguientes comandos.

```bash
# Debian / Ubuntu / Raspbian / Lubuntu / Xubuntu / Linux Mint / Elementary OS / ...
sudo apt install git
# Fedora / Centos / RHEL
sudo yum install git
# Arch / Manjaro / Antergos
pacman -Syu git
```

Luego debes de configurar git en tu sistema con estos dos comandos. Sustituye `<tu-nombre>` por tu nombre y `<tu-email>` por el email que has usado en Github / Gitlab para darte de alta.

```bash
git config --global user.name <tu-nombre>
git config --global user.email <tu-email>
```

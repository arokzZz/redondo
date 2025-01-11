# redondo

Este es un programa que al ejecutarlo tira una frase aleatoria de los redondos.


# Instalacion

## Arch y derivados
El programa esta en el AUR como 'redondo'

Para instalar:

```yay -S redondo```

Un tip: agregalo a tu .bashrc para que cada vez que abras una terminal aparezca una frase de los redo'!

## Para cualquier distribucion diferente a Arch vas a tener que compilarlo, es muy sencillo:

Descargar el codigo y entrar a la carpeta

```git clone https://github.com/arokzZz/redondo.git```

```cd redondo```

Instalar el programa

```sudo install -Dm755 redondo /usr/bin/redondo```

```sudo install -Dm644 frases.pr /usr/share/redondo/frases.pr```

Un tip: agregalo a tu .bashrc para que cada vez que abras una terminal aparezca una frase de los redo'!



PD: Puede que haga un paquete para debian o flatpak

# cairo-dock-spotify
Un pequeño script en session cairo-dock(GNOME),el cual soluciona las multiples instancias de spotify y el icono inactivo  

1. Crear un spotfy-fix ```$sudo gedit /usr/bin/spotify-fix```

2. click-derecho sobre cairo-dock y buscar el icon spotify

3. selecionar spotify y donde dice ```comando para lanazar al hacer click ``` poner ```exec spotify-fix```

4. abrir spotify, cada vez que inicie spotify checar ```/home/your/Escritorio/spotify-id.txt``` no cause conflicto con ontra ventana ```$wmctrl -lp```, si causa conflicto limpiar el archivo



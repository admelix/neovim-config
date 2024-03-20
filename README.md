## Configuracion de mi terminal con Iterm2 y neovim

Primero, hay que instalar brew desde aqui:

- https://brew.sh/

Luego, con brew instalamos neovim y descargamos el repositorio. Puede que al momento de instalar neovim no les cree la carpeta ~/.config 
Si no se las crea, ustedes deben crearla:

```bash
mkdir -p ~/.config/nvim
```

luego, estando en el directorio **~/.config/nvim** descargan el repositorio. 

asi se ve el resultado: 

![image](https://github.com/admelix/neovim-config/assets/13974008/70eb3c98-4aa8-4854-8eca-5ee0f8dac971)



comandos:

![image](https://github.com/admelix/neovim-config/assets/13974008/ae5f6271-3f69-4a16-a677-780dde75446b)

Para mayor info con los comandos o cambiar los que ya estan, pueden revisar el archivo keymaps.

Por ultimo, deben tener instaladas las nerd fonts. Yo uso hack y una vez las descarguen, deben configurarlas en la terminal para que usen la que ustedes quieran. En OSX es asi:

presionan comando + o y les aparece esto

![image](https://github.com/admelix/neovim-config/assets/13974008/f34fbc82-47cf-4bf4-942e-1bc80cb0680a)

luego, en esa opcion eligen su tipografia y ahi les va a reconocer los iconos de los distintos lenguajes que puedan usar. Si no lo usan, les apareceran en vez de iconos puros ?? 
Por ultimo, deben ir a nerd fonts y en cheat sheet 

![image](https://github.com/admelix/neovim-config/assets/13974008/2fc4e2ec-a66a-4aaf-8cfc-d421f5951986)

ahi pueden ubicar la flecha que quieran para decir que el directorio esta cerrado o abierto para que el nvim-tree tenga esa funcionalidad. Con ello, ya tiene configurado completamente el neovim. 
la web de nerdfonts para que busquen las flechas es esta [cheat-sheet de Nerdfonts](https://www.nerdfonts.com/cheat-sheet) 


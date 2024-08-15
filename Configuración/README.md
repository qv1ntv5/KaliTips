### Descripción.

### Configuración del Teclado.

Podemos configurar atajos de teclado pulsando la tecla Windows:

```
Keyboard --> Application Shortcuts
```

Además, podemos cambiar la salida del teclado mediante el siguiente comando:

```bash
sudo dpkg-reconfigure keyboard-configuration
```

### Configuración de QTerminal.

Podemos personalizar nuestra Terminal desde la sección superior izquierda de la misma:

```
File --> Preferences
```

#### Zshrc

**Breve descripción de Zshrc**

El fichero *.zshrc* es el fichero de configuración de [Zsh shell](https://ohmyz.sh/) y al ser esta la shell por defecto con la que opera KaliLinux desde la versión 2020.1 es el fichero desde el cual se carga una configuración prederteminada cuando se invoca una shell en KaliLinux y al que debemos acudir para cambiarla.

Cuando se invoca una shell interactiva, se inicia un proceso de inicialización y dentro de este se carga un entorno para esta nueva shell a través de un conjunto de ficheros en **/etc** hasta que finalmente se llega al fichero *.zshrc* en la carpeta personal del usuario el cual se parsea y ejecuta línea a línea.

<br>

**Secciones de .zshrc**

Entre las secciones de este fichero, podemos encontrar:


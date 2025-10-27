# FletApp app

para que puedan instalar y probar la app coloquen estos comandos en la terminal en orden 🐈‍⬛

## Instalacion
Abran vsc en una carpeta vacia y abren la terminal (ctrl+shift+ñ)

### Clonar la app 
```
git clone https://github.com/Mar7155/fissures-detection-app
```

### despues corran este comando o arrastren la carpeta que se creo en visual
```
cd .fissures-detection-app
```

### Instalar dependencias 😸

(opcional por si quieren borrar la bilbioteca despues y no se quede en la raiz de su laptop)
```
python -m venv .venv  
```
(opcional tambien por si corrieron el comando de arriba)
```
.venv\Scripts\activate
```

### instalar flet 
```
pip install -r requirements.txt    
```

## Iniciar la app

### Corre la app y muestra cambios en tiempo real 
```
flet run
```

## Build the app

### Android

```
flet build apk -v
```

For more details on building and signing `.apk` or `.aab`, refer to the [Android Packaging Guide](https://flet.dev/docs/publish/android/).

### iOS

```
flet build ipa -v
```

For more details on building and signing `.ipa`, refer to the [iOS Packaging Guide](https://flet.dev/docs/publish/ios/).

### macOS

```
flet build macos -v
```

For more details on building macOS package, refer to the [macOS Packaging Guide](https://flet.dev/docs/publish/macos/).

### Linux

```
flet build linux -v
```

For more details on building Linux package, refer to the [Linux Packaging Guide](https://flet.dev/docs/publish/linux/).

### Windows

```
flet build windows -v
```

For more details on building Windows package, refer to the [Windows Packaging Guide](https://flet.dev/docs/publish/windows/).

## Chatbot Whatsapp

### ATENCION 🔴
> 💥💥 Si te aparece el Error Multi-device es porque tienes la cuenta de whatsapp afiliada al modo "BETA de Multi dispositivo" por el momento no se tiene soporte para esas personas si tu quieres hacer uso de este __BOT__ debes de salir del modo BETA y intentarlo de la manera tradicional
### (Nuevo) Botones

[![btn](https://i.imgur.com/W7oYlSu.png)](https://youtu.be/5lEMCeWEJ8o) 

> Implementar los botones solo necesitas hacer uso del metodo __sendMessageButton__ que se encuentra dentro `./controllers/send` dejo un ejemplo de como usarlo.
[Ver implementación](https://github.com/leifermendez/bot-whatsapp/blob/main/app.js#L123)


__Instalar dependencias (npm install)__
> Ubicate en le directorio que descargaste y via consola o terminal ejecuta el siguiente comando

`npm install` 

```
![](https://i.imgur.com/BJuMjGR.png)
```

__Configurar .env__
> Con el editor de texto crea un archivo `.env` el cual debes de guiarte del archivo `.env.example`
[Ver video explicando](https://youtu.be/5lEMCeWEJ8o?t=381)
```
######DATABASE: none, mysql, dialogflow

DEFAULT_MESSAGE=true
SAVE_MEDIA=true
PORT=3000
DATABASE=none
LANGUAGE=es
SQL_HOST=
SQL_USER=
SQL_PASS=
SQL_DATABASE=
```

![](https://i.imgur.com/9poNnW0.png)

__Ejecutar el script__
> Ubicate en le directorio que descargaste y via consola o terminal ejecuta el siguiente comando
`npm run start`

![](https://i.imgur.com/eMkBkuJ.png)

__Whatsapp en tu celular__
> Ahora abre la aplicación de Whatsapp en tu dispositivo y escanea el código QR
<img src="https://i.imgur.com/RSbPtat.png" width="500"  />
Visitar la pagina 
`http://localhost:3000/qr` 


__Listo 😎__
> Cuando sale este mensaje tu BOT está __listo__ para trabajar!



## Preguntar al BOT
> Puedes interactuar con el bot ejemplo escribele __hola__ y el bot debe responderte!

![](https://i.imgur.com/cNAS51I.png)

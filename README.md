> **Warning** ESTE REPOSITORIO ESTÁ EN DESARROLO...

<a href="#"><img title="GataBot-MD" src="https://img.shields.io/badge/VERSIÓN 1.0.0 -red?colorA=%238B38CD&colorB=%238B38CD&style=for-the-badge"></a>
<p align="center"> 
<img src="https://i.imgur.com/AwlL9kc.jpeg" alt="GataBotLite-MD" width="500"/>
</p>
<p align="center">
<a href="https://github.com/GataNina-Li/GataBot-MD"><img title="GataBot-MD" src="https://img.shields.io/badge/🌸 ESTÁ ES UNA VERSIÓN SIMPLIFICADA DE GataBotMD 🌸 -red?colorA=%233CCED8&colorB=%233CCED8&style=for-the-badge"></a>
</p>

<div align="center">
<a href="mailto:centergatabot@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
</a>
<a href="https://facebook.com/groups/872989990425789/">
<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
</a>
<a href="https://www.youtube.com/@gatadios">
<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
</a>
<a href="https://instagram.com/gata_dios">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="https://paypal.me/OficialGD">
<img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white">
</a>
<a href="https://chat.whatsapp.com/DVhu9S9Zr7cBFFl26N61U3">
<img src="https://img.shields.io/badge/GataBot Update Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
</a>
</a>
<a href="https://chat.whatsapp.com/IXZ0aBryB1cHjNxe0VIm76">
<img src="https://img.shields.io/badge/🐈_GataBot_|_Soporte_⚙️-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
</a>
</div>

#### DISPONIBLE EN:
> - [x] TERMUX, REPLIT, WINDOWS, HEROKU


### 🌸 INSTALACIÓN AUTOMÁTICA - TERMUX 🌸
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBotLite-MD/master/gatalite.sh | bash
```
### 🌼 INSTALACIÓN MANUAL - TERMUX 🌼
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
git clone https://github.com/GataNina-Li/GataBotLite-MD 
cd GataBotLite-MD
yarn install
npm install
npm start
```

### 🍁 TERMUX 24/7 🍁
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta GataBotLite-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 startup && pm2 save && pm2 resurrect && pm2 monit
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta GataBotLite-MD 
```bash
pm2 start index.js
```
- VOLVER A VISUALIZAR EL PROCESO
> Usar dentro de la carpeta GataBotLite-MD para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```
> **Note** Demanda consumo de RAM y CPU, el resultado mejora mientras las especificaciones del dispositivo sean moderadas

### 🌹 INSTALACIÓN EN REPLIT 🌹
<a target="_blank" href="https://replit.com/github/GataNina-Li/GataBotLite-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a>

### 🪷 INSTALACIÓN EN HEROKU 🪷
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/GataNina-Li/GataBotLite-MD-Heroku) 
> 👇 Añada lo siguente al Buildpack: 
```bash
heroku/nodejs
```
```bash
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```
```bash
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
## 🌻 INSTALACIÓN PARA WINDOWS/VPS/RDP 🌻

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
* Descargar e instala Yarn [`Aquí`](https://classic.yarnpkg.com/en/docs/install#windows-stable)
```bash
git clone https://github.com/GataNina-Li/GataBotLite-MD && cd GataBotLite-MD && yarn install && npm install && npm update && node .
```
### Instalación de FFmpeg para Windows 
* Descarga cualquiera de las versiones de FFmpeg disponibles haciendo clic en [FFmpeg](https://www.gyan.dev/ffmpeg/builds/).
* Extraer archivos a `C:\` path.
* Cambie el nombre de la carpeta extraída a `ffmpeg`.
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
### 💠 [`IDIOMAS DISPONIBLES PARA GATABOTLITE`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/config.js) 
#### ✨ Español  [`Editar Idioma`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/espanol.js)
#### ✨ Inglés (English) [`Edit Language`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/ingles.js)
#### ✨ Portugués (Português) [`Idioma de Edição`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/portugues.js)
#### ✨ Indonesio (Bahasa Indonesia) [`Mengedit Bahasa`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/indonesio.js) 
#### ✨ Árabe (عرب) [`عدل اللغة`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/arabe.js)
----

### 🌟 CREADORA 
[![GataNina-Li](https://github.com/GataNina-Li.png?size=100)](https://github.com/GataNina-Li) 

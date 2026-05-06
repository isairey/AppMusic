
 #HipHop [![Dependency Status](https://david-dm.org/hiphopapp/hiphop.svg?theme=shields.io)](https://david-dm.org/hiphopapp/hiphop)

![](http://gethiphop.net/images/screenshot.png)


<h1 align="center">🎧 HipHop</h1>

<p align="center">
  <strong>Aplicación de música multiplataforma construida con tecnologías web</strong><br>
  Disfruta tu música con una experiencia moderna y ligera.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js">
  <img src="https://img.shields.io/badge/Grunt-Build-orange?style=for-the-badge&logo=grunt">
  <img src="https://img.shields.io/badge/Desktop-App-blue?style=for-the-badge">
  <img src="https://img.shields.io/github/license/youruser/hiphop?style=for-the-badge">
</p>

---

## 🚀 Descripción

**HipHop** es una aplicación de música multiplataforma que utiliza tecnologías web para ofrecer una experiencia de reproducción moderna.

Está diseñada para ejecutarse como aplicación de escritorio utilizando herramientas basadas en Node.js.

---

## ✨ Características

- 🎧 Reproducción de música  
- 🖥️ Aplicación de escritorio multiplataforma  
- ⚡ Construida con tecnologías web modernas  
- 🔧 Sistema de build automatizado con Grunt  

---


## 📦 Requisitos

Antes de comenzar, asegúrate de tener instalado:

- Node.js  
- Grunt CLI  
- Ruby  
- Compass (para estilos)

Instalar Grunt:

```bash id="g8xv3q"
npm install -g grunt-cli
```

## ⚙️ Instalación
```
npm install
grunt
```

Esto instalará dependencias y generará archivos necesarios.

### ▶️ Ejecutar la aplicación
```
grunt run
```
⚠️ Nota: Debes ejecutar grunt al menos una vez antes.

---

## 🛠️ Build

Para compilar el proyecto:
```
grunt build
Plataformas específicas
grunt build --platforms=linux32,linux64,mac,win
Todas las plataformas
grunt build --platforms=all
```
---

## 🚀 Release

### Pasos para crear una versión:
Actualizar la versión en:
```
/package.json
```
Generar build:
```
grunt build --platforms=mac
```
Descargar Node-Webkit para Windows:

```
👉 https://github.com/rogerwang/node-webkit#downloads
Copiar archivos en:
/node-webkit/win/
Crear instalador con Inno Setup:
👉 http://www.jrsoftware.org/isdl.php#stable
```

Archivo:
```
/dist/windows/windows-installer.iss
Subir archivos a:
http://download.gethiphop.net/releases/x.x.x/
Actualizar:
/misc/update.json
```
---

## 📂 Estructura del Proyecto
```
HipHop/
├── build/
├── dist/
├── node-webkit/
├── misc/
├── package.json
└── README.md
```

---

## 🧠 Notas

- El proyecto usa herramientas clásicas como Grunt y Node-Webkit
- Compatible con múltiples sistemas operativos
- Ideal para aprendizaje o desarrollo de apps desktop con JS

---

## 👨‍💻 Autor

**Isai Reyes**

---

## 📜 Licencia

Consulta el archivo LICENSE para más información.

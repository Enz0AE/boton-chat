📢 Chat de Sucursales - Botón Flotante

Este proyecto proporciona un botón flotante en forma circular que simula un chat. Al hacer clic en él, se despliega una pregunta con 10 botones correspondientes a diferentes sucursales. Al seleccionar una sucursal, el usuario es redirigido a la página web correspondiente.

🎯 Características

✔ Botón flotante circular con ícono de chat.

✔ Pregunta "¿Cuál de nuestras sucursales queda más cerca de su ubicación?".

✔ 10 botones con los nombres de las sucursales.

✔ Redirección automática a la URL correspondiente.

✔ Integración mediante un iframe para fácil incorporación en otros sitios web.

✔ Diseño responsive y minimalista.

🚀 Instalación y Uso

Descargar o Clonar el Proyecto:

git clone https://github.com/Enz0AE/boton-chat.git

Ubicar el Archivo Principal:

chat.html: Contiene el código del botón y la interfaz del chat.

Subir el Archivo chat.html a un Servidor o Colocarlo en la Misma Carpeta del Proyecto.

Insertar el Chat en tu Página Web:
Agregar el siguiente iframe donde deseas que aparezca el botón:

<iframe src="chat.html" style="border: none; width: 100%; height: 100px; position: fixed; bottom: 0; right: 0; z-index: 9999;" scrolling="no"></iframe>


Personalizar URLs de las Sucursales:
Edita los botones en chat.html y cambia las URLs de las sucursales según corresponda:

<button class="sucursal-button" onclick="redireccionar('https://tusitio.com/sucursal1')">Sucursal 1</button>

🛠 Tecnologías Utilizadas

HTML5

CSS3

JavaScript (Vanilla JS)

📌 Contribución

Haz un fork del repositorio.

Crea una rama con tu nueva funcionalidad: git checkout -b nueva-funcionalidad.

Sube tus cambios: git commit -m "Agregado soporte para...".

Haz un push y abre un Pull Request.

📜 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo y modificarlo libremente. 😊

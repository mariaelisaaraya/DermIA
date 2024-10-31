# 🚀 DermIA

Te damos la bienvenida a **DermIA**. Esta API se integra con una interfaz HTML final y permite acceder a sus funcionalidades de manera sencilla. A continuación, se presentan las instrucciones para ejecutar la API de forma rápida.

![DermaIA](https://i.imgur.com/JB317dD.png)

## 🛠️ Requisitos Previos

Asegúrate de tener instalados lo siguiente en tu sistema:

- [Python](https://www.python.org/) (versión 3.6 o superior)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (extensión para Visual Studio Code)

## 📦 Dependencias

Asegúrate de instalar las dependencias necesarias para el funcionamiento de la API. Las dependencias están listadas en el archivo `requirements.txt`. Puedes instalar estas dependencias utilizando el siguiente comando:

```bash
pip install -r requirements.txt
```

## 🚀 Instrucciones para Ejecutar la API

1. **Navegar a la Carpeta del Proyecto**: Abre tu terminal o consola y navega a la carpeta donde se encuentra Dermai. Usa el siguiente comando:
   ```bash
   cd ruta/a/dermai
   ```

2. **Ejecutar el Archivo de Python**: 
   - Escribe en la terminal:
   ```bash
   python nuevapi.py
   ```

3. **Iniciar el Servidor**: Para ejecutar la API, asegúrate de utilizar el archivo `index.html` que se encuentra en la carpeta principal de Dermai.
   - Abre la Interfaz: Sitúate en el archivo `index.html`. Puedes iniciar Live Server desde Visual Studio Code. Abre `index.html` y haz clic en "Go Live" en la parte inferior derecha.

   ⚠️ **Nota**: No uses ningún otro archivo `index` que no sea el de esta carpeta, ya que esto podría causar errores en la ejecución.

4. **Verificar la API**: Una vez que el servidor esté en funcionamiento, visita:
   ```
   http://localhost:5000/api/welcome
   ```
   Deberías ver una respuesta similar a esta:
   ```json
   {
       "message": "¡Bienvenido a la API!"
   }
   ```

## 📚 Uso de la API

Para utilizar la API, consulta la lógica implementada en la carpeta `api`. Asegúrate de seguir la estructura y las rutas definidas en el código para acceder a las funcionalidades.

## Pasos Anteriores

- [GitHub Original](https://github.com/mariaelisaaraya/M1000IA) en este Repositorio vas a poder encontrar varios modelos, apis, interfaces diferentes y caminos que fuimos tomando hasta llegar a este Repositorio.

## Credits

- [Elisa Araya](https://www.linkedin.com/in/arayamariaelisa/)
- [Gabriela Coronel](https://www.linkedin.com/in/gabriela-coronel-43a0a4286/)
- [Katherine Campos](https://www.linkedin.com/in/katherine-campos-99951b94/)
- [Lucía Otero](https://www.linkedin.com/in/luciaoterolarreborges/)
- [Marcela Salvattore](https://www.linkedin.com/in/marcela-adriana-salvattore/) 
- [Marcela Vegetti](https://www.linkedin.com/in/marcela-vegetti-b273259/) 

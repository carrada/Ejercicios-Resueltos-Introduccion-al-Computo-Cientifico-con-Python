**1. Da la ruta absoluta de los documentos Anaconda.sh, examen1.pdf y foto.png**

- **Ruta para Anaconda.sh:** `Descargas/Anaconda.sh`
- **Ruta para examen1.pdf:** `home/est2/Escritorio/Computacion2020-1/examen_1.pdf`
- **Ruta para foto.png:** `home/est2/Escritorio/Computacion2020-1/imagenes/foto.jpeg`

---

**2. Da la ruta relativa de `/home/est5/Documentos/compu/examen1/ejercicio1.py`**

**Definición de ruta relativa:**
Una ruta relativa es una forma de especificar la ubicación de un archivo o directorio en relación con el directorio actual en el que te encuentras. A diferencia de una ruta absoluta, que comienza desde la raíz del sistema de archivos (`/`), una ruta relativa no comienza con `/` y se basa en el contexto del directorio actual.

**¿Por qué depende del directorio actual?**
La ruta relativa depende del directorio actual porque describe cómo llegar desde ese punto hasta el archivo o directorio objetivo. Si cambias el directorio actual, la ruta relativa también cambiará. Por ejemplo:

- Si estás en `/home/est5/`, la ruta relativa a `ejercicio1.py` sería:
  `Documentos/compu/examen1/ejercicio1.py`.

- Si estás en `/home/est5/Documentos/`, la ruta relativa sería:
  `compu/examen1/ejercicio1.py`.

- Si estás en `/home/est5/Documentos/compu/`, la ruta relativa sería:
  `examen1/ejercicio1.py`.

- Si estás en `/home/est5/Documentos/compu/examen1/`, la ruta relativa sería simplemente:
  `ejercicio1.py`.

**Conclusión:**
Como no se especifica el directorio actual en la pregunta, no se puede dar una única respuesta exacta. La ruta relativa variará dependiendo de dónde te encuentres en el sistema de archivos.
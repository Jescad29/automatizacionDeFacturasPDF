# 🧾 Generador de Facturas con Tkinter y FPDF

Una aplicación de escritorio sencilla en **Python** para generar facturas en **PDF** a partir de datos ingresados por el usuario mediante una interfaz gráfica creada con **Tkinter**.  

---

## 🚀 Descripción
Este proyecto permite generar facturas personalizadas con información del cliente y del servicio prestado.  
Las facturas incluyen:
- Datos del cliente (nombre, RFC, teléfono, ciudad, etc.)  
- Detalles del servicio (nombre, descripción y total)  
- Fecha e identificador único de factura  
- Logotipo personalizado  
- Mensaje de agradecimiento  

El resultado es un archivo PDF profesional generado automáticamente.  

---

## 🧰 Tecnologías utilizadas
- **Python 3**
- **Tkinter** – interfaz gráfica
- **FPDF** – generación de PDF
- **Datetime** y **Random** – para fechas e identificadores

---

## ⚙️ Instalación (usando Pipenv)

1. Clona este repositorio:
```bash
git clone https://github.com/Jescad29/automatizacionDeFacturasPDF.git

```

2. Instala las dependencias con Pipenv:
```bash
pipenv install fpdf
```

3. Activa el entorno virtual:
```bash
pipenv shell
```


4. Ejecuta el script principal dentro del entorno virtual:
```bash
python generarFactura.py
```

5. Se creara un archivo PDF con el nombre:
```bash
Factura {nombre_cliente}_{apellidos_cliente}.pdf

```

6. Ejemplo de Salida:
```bash
Factura Generada: Factura Victor_Cadena.pdf

```

7. Tags / Topics
```bash
python-utils, pdf     
```

## Seguridad

- No subir credenciales reales al repositorio.
- Asegúrate de tener permisos de escritura en la carpeta del proyecto (para guardar el PDF).
- Puedes agregar más campos o modificar el diseño de la factura editando el bloque de generación PDF.

## Contribuciones

Siéntete libre de mejorar el script, añadir Opción para guardar los datos del cliente. o Exportar historial de facturas, y abrir un Pull Request .

<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHl5OGc2bjl2NWtqcDJ0YTc3bXd3Y2EyMG55amRibjhjdThwcmoybiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/DirPxXrUHKaCA/200.webp" alt="Perrito divertido" width="300"/>
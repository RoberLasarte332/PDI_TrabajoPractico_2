# PDI_TrabajoPractico_2

Incluye Detección y Clasificación de Pastillas y Detección de Placas Patente.

## Requisitos

Este proyecto utiliza un notebook de Jupyter para realizar análisis de imágenes con OpenCV, NumPy, Matplotlib y pandas.

## Ejecutar en un entorno virtual

1. Crear el entorno virtual:

   ```powershell
   python -m venv .venv
   ```

2. Activar el entorno virtual:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

3. Instalar las dependencias necesarias:

   ```powershell
   pip install opencv-python numpy matplotlib pandas jupyter
   ```

4. Iniciar Jupyter Notebook:

   ```powershell
   jupyter notebook
   ```

5. Abrir `PDI_TrabajoPractico_2.ipynb` en el navegador y ejecutar las celdas.

## Notas

- Asegúrate de tener instalado Python 3.8 o superior.
- Si se necesitas guardar las dependencias, generar un archivo `requirements.txt` con:

  ```powershell
  pip freeze > requirements.txt
  ```
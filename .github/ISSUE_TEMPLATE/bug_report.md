---

name: "Reporte de Error"

about: "Usa esta plantilla para informar un bug o comportamiento inesperado en el Rastreador de Gastos"

title: "\[BUG] Descripción breve del problema"

labels: \["bug", "to review"]

assignees: "Nelinho"

---



\## Descripción del error

Describe claramente el error encontrado.  

Por ejemplo: \*"El programa no convierte correctamente los valores cuando se usa el tipo de cambio del BCRP."\*



---



\## Pasos para reproducirlo

Explica cómo se puede repetir el error paso a paso:



1\. Clonar el repositorio:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/nelinho-hc/rastreador-gastos.git



2\. Instalar las dependencias:

&nbsp;  pip install -r requirements.txt



3\. Ejecutar el script principal:

&nbsp;  python main.py



4\. Ingresar el monto 100 y seleccionar conversión USD → PEN



5\. Resultado incorrecto: muestra S/ 0.00 en lugar de S/ 385.00



\## Comportamiento esperado

El programa debería mostrar la conversión correcta de acuerdo con el tipo de cambio vigente.

Por ejemplo:



100 USD = 385 PEN (Tipo de cambio: 3.85)



\## Evidencias o capturas



Si aplica, agrega capturas de pantalla o registros de consola que muestren el problema:



\[INFO] Obteniendo tipo de cambio desde la API del BCRP...

\[ERROR] ValueError: could not convert string to float: ''



\## Entorno del sistema



* Sistema operativo: Windows 11
* Python: 3.13
* Versión: v1.0
* IDE o editor usado: Visual Studio Code
* Entorno virtual: Sí (venv)

# 🧪 AllSpec

**AllSpec** es una **plataforma integral para el tratamiento y análisis de datos espectroscópicos**.  
Permite procesar, visualizar y ajustar espectros provenientes de diversas técnicas como:

- **UV-Vis** (análisis de absorción, ajuste tipo SQUAD, especiación ácido-base)  
- **Infrarrojo (IR)** (suavizado, corrección de línea base, exportación de datos)  
- **Difracción de Rayos X (DRX)** (procesamiento y comparación de patrones)  
- **Fluorescencia** (análisis y tratamiento de espectros de emisión)  
- **Técnicas electroquímicas** (voltamperometría, cronamperometría)  
- **Fotoelectrones (XPS)** (corrección de fondo, ajuste de picos y exportación)

---

## ⚙️ Características principales

- Interfaz gráfica **intuitiva y modular** desarrollada en **Python (Tkinter)**.  
- Integración de distintos módulos para cada técnica espectroscópica.  
- **Carga, visualización y exportación** de datos desde archivos Excel (.xls, .xlsx).  
- **Corrección de línea base, suavizado y normalización** de espectros.  
- **Ajuste tipo SQUAD** con estimación de log β, coeficientes molares (ε) y distribución de especies.  
- **Exportación automática** de resultados (Excel, CSV, JPG, TXT).  
- **Visualización interactiva** de datos experimentales vs calculados.  
- Reportes generados de forma automática con estadísticas y parámetros de ajuste.

---

## 🧰 Requisitos

- **Python ≥ 3.9**
- Librerías principales:
  ```bash
  pip install numpy pandas matplotlib openpyxl scipy scikit-learn
(Opcional para módulos específicos)

bash
Copiar código
pip install tkfilebrowser
💻 Instalación
Clonar el repositorio:

bash
Copiar código
git clone https://github.com/Guillermo-RR/AllSpec.git
cd AllSpec
Instalar dependencias:

bash
Copiar código
pip install -r requirements.txt
Ejecutar AllSpec:

bash
Copiar código
python allspec.py
📘 Estructura del proyecto
bash
Copiar código
AllSpec/
│
├── allspec.py              # Ventana principal del programa
├── modules/                # Módulos de análisis (UV-Vis, IR, DRX, XPS, etc.)
│   ├── uvvis_module.py
│   ├── ir_module.py
│   ├── drx_module.py
│   ├── xps_module.py
│   └── electrochem_module.py
│
├── assets/
│   ├── images/             # Logotipo, capturas y visuales
│   └── docs/               # Manual de usuario y reportes
│
├── data/                   # Archivos de ejemplo
├── requirements.txt
└── README.md
🧪 Ejemplo de uso
Inicia el programa y selecciona un módulo, por ejemplo UV-Vis.

Carga un archivo Excel con las hojas requeridas (Absorbancia, Condiciones).

Visualiza los espectros experimentales y realiza ajustes.

Exporta los resultados (espectros, especies, parámetros, gráficos).

📖 Documentación y recursos
Manual de usuario (PDF)

Sitio web oficial (GitHub Pages)

Repositorio en GitHub

👨‍🔬 Autor
Guillermo Reyna Rodríguez
Licenciado en Química especializado en ciencia de los nanomateriales y espectroscopía.
Desarrollador del proyecto AllSpec.

🔗 GitHub
🔗 LinkedIn

📜 Licencia
Este proyecto está disponible bajo la Licencia MIT.
Consulta el archivo LICENSE para más información.

# Red de Colaboraciones Musicales

Este proyecto extrae datos de la API de MusicBrainz para analizar y visualizar las redes de colaboración de Linkin Park y artistas afines.

---

## Instalación

1. Clona el repositorio:
   $ git clone https://github.com/tu-usuario/tu-repo.git
   $ cd tu-repo
2. (Opcional) Crea un entorno virtual:
   $ py -3 -m venv venv
   # Windows
   $ venv\Scripts\activate
   # macOS/Linux
   $ source venv/bin/activate
3. Instala las dependencias:
   $ py -3 -m pip install -r requirements.txt

---

## Uso

1. Abre el notebook PEC4.ipynb en Jupyter o VS Code Interactive.  
2. Ejecuta las celdas de Paso 1 a Paso 4 para extraer, modelar y filtrar el grafo.  
3. Ejecuta Paso 5.1 para generar el gráfico estático en results/network.png.  
4. Ejecuta Paso 5.2 para generar el HTML interactivo en results/network.html.  
5. Abre results/network.html en tu navegador o con Live Server en VS Code para explorar.

---

## Resultados

- Static:  
  ![Static Network](results/network.png)  
- Interactivo:  
  Abre results/network.html en tu navegador.

---

## Estructura del proyecto

    /data           # Datos brutos descargados (opcional)
    /results        # Salidas: network.png, network.html
    PEC4.ipynb      # Notebook principal
    requirements.txt
    README.md

---

## Extensiones posibles

- Filtrado dinámico por peso de arista (slider).  
- Animación temporal según fechas de colaboración.  
- Mini-mapa para navegar grafos muy grandes.

---

## Licencia

Licencia MIT © 2025 Albert Matarín Luque  

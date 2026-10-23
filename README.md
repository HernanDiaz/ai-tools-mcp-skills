<!-- Encabezado en HTML: GitHub Pages no interpreta Markdown dentro de un <div>, y así se ve igual en los dos sitios. -->
<div align="center">
  <h1>Herramientas, MCP y skills</h1>
  <h3><em>Diseñar, publicar y proteger las herramientas de los modelos de lenguaje abiertos en Python</em></h3>
  <p>por <strong>Hernán Díaz Rodríguez, PhD</strong> · Profesor en la Universidad de Oviedo</p>
  <p>
    <a href="https://creativecommons.org/licenses/by-nc/4.0/deed.es"><img src="https://img.shields.io/badge/Licencia-CC%20BY--NC%204.0-lightgrey.svg" alt="Licencia: CC BY-NC 4.0"></a>
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Colab-GPU%20T4%20gratuita-orange?logo=googlecolab" alt="Colab">
  </p>
</div>

---

## El libro

**Herramientas, MCP y skills** enseña a construir las herramientas que usan los modelos de lenguaje: funciones que el modelo pide ejecutar para consultar datos, reservar citas o enviar avisos. A lo largo de doce capítulos, la **Clínica Veterinaria Naranco**, una clínica de Oviedo, pasa de dar a un modelo su API tal cual a tener un ecosistema de herramientas: nombres, descripciones y resultados pensados para el modelo, esquemas y contratos, servidores y clientes con el protocolo **MCP**, recursos y elicitation, tareas largas sin cobros duplicados, defensas contra herramientas envenenadas, skills, pasarelas y registros.

Cada capítulo cambia algo de las herramientas, nunca del modelo, y mide cuánto mejora el agente. Todo funciona con **modelos abiertos y gratuitos**, sin claves de API ni servicios de pago: Qwen3-4B-Instruct-2507 en la GPU gratuita de Colab y, sin GPU, Qwen3-1.7B. Los servidores y los clientes de MCP se escriben con el SDK oficial de Python, y cada cifra del libro sale de un experimento que puedes repetir en el cuaderno del capítulo.

Forma parte de la colección **IA en práctica**: libros prácticos de inteligencia artificial con experimentos propios, un cuaderno y un vídeo en cada capítulo.

> *Prefer English?* The English edition, **Tools, MCP and Skills**, is in the [`en/` folder](./en/).

---

## Capítulos

Cada capítulo tiene su cuaderno en Google Colab y su vídeo, con Robotín y el autor. Todos los vídeos están en la [lista de reproducción de YouTube](https://www.youtube.com/playlist?list=PLXeT2ahYmomE).

| Cap. | Título | Cuaderno | Vídeo |
|------|--------|----------|-------|
| 1 | La interfaz de una herramienta | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/1_La_interfaz_de_una_herramienta.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=8olP4vrfTkg&list=PLXeT2ahYmomE) |
| 2 | Llamadas a funciones a fondo | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/2_Llamadas_a_funciones_a_fondo.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=XSzo-1iXV40&list=PLXeT2ahYmomE) |
| 3 | Esquemas y contratos | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/3_Esquemas_y_contratos.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=GZFKpJg4Ru0&list=PLXeT2ahYmomE) |
| 4 | Fundamentos de MCP | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/4_Fundamentos_de_MCP.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=EtKzlmTLEbc&list=PLXeT2ahYmomE) |
| 5 | Construir un servidor MCP | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/5_Construir_un_servidor_MCP.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=TQEWH8BFMqE&list=PLXeT2ahYmomE) |
| 6 | El cliente y los transportes | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/6_El_cliente_y_los_transportes.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=o92wcrhYBys&list=PLXeT2ahYmomE) |
| 7 | Recursos, prompts, sampling y elicitation | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/7_Recursos_prompts_sampling_y_elicitation.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=kS4G_QwP7IU&list=PLXeT2ahYmomE) |
| 8 | Tareas largas y fiabilidad | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/8_Tareas_largas_y_fiabilidad.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=F0WCX-8AbW4&list=PLXeT2ahYmomE) |
| 9 | Seguridad: herramientas envenenadas y autorización | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/9_Seguridad.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=2aZHN-20Bzg&list=PLXeT2ahYmomE) |
| 10 | Skills | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/10_Skills.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=fDC-hzRJlIc&list=PLXeT2ahYmomE) |
| 11 | Pasarelas, registros y A2A | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/11_Pasarelas_y_registros.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=CLMEUCfJOZM&list=PLXeT2ahYmomE) |
| 12 | Proyecto: un ecosistema de herramientas | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/cuadernos/12_Proyecto_un_ecosistema_de_herramientas.ipynb) | [![Ver en YouTube](https://img.shields.io/badge/YouTube-Ver%20v%C3%ADdeo-red?logo=youtube)](https://www.youtube.com/watch?v=H95TuM0uw_k&list=PLXeT2ahYmomE) |

---

## Cómo usar los cuadernos

- Pulsa **Abrir en Colab** y ejecuta las celdas en orden. La primera celda instala las versiones de las bibliotecas con las que se comprobó el libro (`transformers` 5.19.0 y `mcp` 2.3.0, entre otras).
- Activa la GPU gratuita: *Entorno de ejecución → Cambiar tipo de entorno de ejecución → GPU T4*. El modelo ocupa unos 8 GB y la primera vez tarda unos minutos en descargarse. Sin GPU, los cuadernos eligen solos Qwen3-1.7B, más pequeño, que falla bastante más como agente.
- Los cuadernos descargan solos los datos de la carpeta `datos/` la primera vez. Los servidores MCP y las skills de cada capítulo se escriben desde el propio cuaderno.
- El transporte HTTP de MCP (capítulo 6) funciona en Colab y en Linux; con `mcp` 2.3.0 no funciona en Windows.

---

## Estructura del repositorio

```
ai-tools-mcp-skills/
├── cuadernos/      ← Un cuaderno por capítulo
├── datos/          ← La clínica: mascotas, dueños, historial, vacunas, citas, farmacia y facturas
├── cuaderno/N/     ← Los enlaces del libro a cada cuaderno en Colab
└── en/            ← La edición inglesa: notebooks, data y sus enlaces
```

---

## Datos

La Clínica Veterinaria Naranco y todos sus datos son inventados. Las herramientas trabajan sobre una copia de la clínica que se reinicia en cada prueba, así que puedes equivocarte sin consecuencias. La fecha de los datos es el martes 20 de octubre de 2026.

| Archivo | Contenido |
|---------|-----------|
| `mascotas.json` | Las 29 mascotas, con especie, raza, peso, alergias y dueño |
| `duenos.json` | Los 26 clientes, con su teléfono, su correo y cómo prefieren los avisos |
| `historial.json` | Las visitas de cada mascota: motivo, tratamiento y peso |
| `vacunas.json` | Las vacunas de cada mascota y la fecha de la próxima |
| `citas.json` | La agenda de la semana de los tres veterinarios |
| `farmacia.json` | Los medicamentos: presentación, dosis por kilo, existencias, precio y reposición |
| `facturas.json` | Las facturas de los clientes, pagadas y pendientes |
| `veterinarios.json` | Los tres veterinarios |
| `tarifas.json` | El precio de cada servicio |

---

## El autor

**Hernán Díaz Rodríguez** es profesor del Departamento de Ciencias de la Computación e Inteligencia Artificial de la **Universidad de Oviedo**, donde se doctoró en Informática. Trabajó cinco años como ingeniero de software en el **CERN**.

[LinkedIn](https://www.linkedin.com/in/hernandiazrodriguez) · [Correo](mailto:hernan.diaz.rodriguez@gmail.com) · [Página de autor en Amazon](https://www.amazon.es/Hernan-Diaz-Rodriguez/e/B0GD8JQ9JB)

---

## Licencia

Este material se distribuye bajo la licencia [Creative Commons Reconocimiento-NoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.es): se puede usar y adaptar para docencia y estudio citando al autor, pero no con fines comerciales.

Los modelos que usan los cuadernos tienen sus propias licencias: Qwen3 (Apache 2.0) y multilingual-e5-small (MIT). El SDK de MCP para Python se distribuye con licencia MIT.

## Cómo citar

```bibtex
@book{diazrodriguez2026herramientas,
  author    = {Hern{\'a}n D{\'\i}az Rodr{\'\i}guez},
  title     = {Herramientas, MCP y skills. Dise{\~n}ar, publicar y proteger las herramientas de los modelos de lenguaje abiertos en Python},
  year      = {2026},
  publisher = {Publicaci{\'o}n independiente},
  url       = {https://github.com/HernanDiaz/ai-tools-mcp-skills}
}
```

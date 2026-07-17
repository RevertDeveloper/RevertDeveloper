<div align="center">

![Mi Logo de Presentación](carlos_revert_pagan.png)

### Full-Stack Developer · AI & RAG Engineer · Self-Hosted Infrastructure · Blockchain Specialist

Desarrollo aplicaciones web funcionales e integro inteligencia artificial en productos, automatizaciones y procesos empresariales.

[![Portfolio](https://img.shields.io/badge/Portfolio-carlosrevert.es-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://carlosrevert.es)
![Location](https://img.shields.io/badge/Ubicación-España-red?style=for-the-badge)

**LinkedIn:** `pendiente de añadir` · **Email:** `revertus@protonmail.com`

</div>

---

## Índice

- [Perfil profesional](#perfil-profesional)
- [Proyectos destacados](#proyectos-destacados)
- [Stack tecnológico](#stack-tecnológico)
- [Inteligencia artificial](#inteligencia-artificial)
- [Infraestructura y despliegue](#infraestructura-y-despliegue)
- [Blockchain y Web3](#blockchain-y-web3)
- [Formación](#formación)
- [Experiencia profesional previa](#experiencia-profesional-previa)
- [Idiomas](#idiomas)
- [Competencias profesionales](#competencias-profesionales)

---

## 🚀 Perfil profesional

Desarrollador **Full Stack** especializado en **Inteligencia Artificial**, **Retrieval-Augmented Generation (RAG)**, automatización de procesos e infraestructura **Self-Hosted**.

Diseño, desarrollo y despliego aplicaciones completas de principio a fin, integrando **backend**, **frontend**, **bases de datos**, **modelos de IA**, **APIs**, **Docker**, **redes** y demás.

---

### Evolución profesional

Mi trayectoria tecnológica comenzó en **2018** dentro del ecosistema **Blockchain y Web3**, donde desarrollé un perfil autodidacta basado en la investigación, la experimentación y la resolución de problemas reales.

Durante varios años profundicé en tecnologías descentralizadas como **DeFi**, **NFTs**, **Smart Contracts**, **Solidity**, sistemas **Proof of Work** y **Proof of Stake**, seguridad mediante billeteras multifirma y operativa avanzada con exchanges centralizados y descentralizados. Esta experiencia me permitió ofrecer **asesoramiento técnico** y formación especializada en el sector.

Paralelamente adquirí un conocimiento avanzado sobre la **fiscalidad española aplicada a los criptoactivos**, analizando e interpretando una normativa todavía poco desarrollada para gestionar correctamente operativas complejas con decenas de miles de movimientos distribuidos entre múltiples plataformas.

Con el objetivo de ampliar mi perfil técnico, decidí especializarme profesionalmente en el **desarrollo de software**, completando un **Máster en Desarrollo Web Full Stack** y orientando posteriormente mi carrera hacia la **Inteligencia Artificial aplicada**.

Actualmente desarrollo aplicaciones que combinan **LLMs**, **sistemas RAG**, **bases de datos vectoriales**, **automatización**, **agentes conversacionales**, **procesamiento documental** e **infraestructura propia**, creando soluciones completas que abarcan desde el diseño de la arquitectura hasta su despliegue y mantenimiento en producción.

---

## 📊 Highlights

|                        |                                                                                                    |
| :--------------------- | :------------------------------------------------------------------------------------------------- |
| ⚖️ **RAG Jurídico**    | Más de **12.000 normativas españolas**, **600.000 artículos** y **700.000 vectores** indexados.    |
| 🧠 **IA Local**        | Instalación, configuración y optimización de modelos de hasta **120B parámetros**.                 |
| 🌐 **Despliegue**      | Aplicaciones desarrolladas y publicadas íntegramente sobre infraestructura propia.                 |
| 🐳 **Infraestructura** | Administración avanzada de **Docker**, **Proxmox**, redes y servicios Self-Hosted.                 |
| 🔍 **RAG**             | Diseño de pipelines completos de ingestión, chunking avanzado, embeddings y recuperación selectiva.|
| 🔗 **Blockchain**      | Más de **20.000 transacciones** realizadas y analizadas entre múltiples redes y exchanges.         |
| 🤖 **Hermes Agent**    | Implementación y configuración de Hermes Agent hasta llegar a desbloquear insignias **Olympian**   |

> *Mi objetivo profesional es diseñar y construir productos digitales donde la Inteligencia Artificial no sea un simple añadido, sino una ventaja competitiva real. Combino desarrollo Full Stack, infraestructura, automatización y arquitectura de software para crear soluciones robustas, escalables, modulares y orientadas a negocio. Mi enfoque se apoya en dos principios fundamentales: una Ingeniería de Prompts precisa y una Ingeniería de Contexto eficiente, capaces de transformar modelos de IA en sistemas útiles, fiables y preparados para producción.*

---

## Proyectos personales

Todos los proyectos forman parte de mi portfolio y se encuentran desplegados en mi servidor personal.

### [Home](https://carlosrevert.es) (https://carlosrevert.es)

Página principal de presentación.

- Presentación de mi perfil.
- Exposición de mi portfolio.

---

### [IA Jurídica](https://juridia.carlosrevert.es) (https://juridia.carlosrevert.es)

Sistema RAG jurídico orientado a la consulta de normativa española.

- Base de conocimiento con más de **600.000 artículos**. Toda la legislación consolidada Española.
- **PostgreSQL + Qdrant** . Uso de Qdrant como puntero de vectores y recuperamos los artículos relevantes almacenados en PostgreSQL.
- Modelo de **embedding de 1024** dimensiones : (https://huggingface.co/dariolopez/bge-m3-es-legal-tmp-6) (fine-tuned para derecho español).
- **Intervención de la Query** entrante para Juridificarla y generar palabras clave que mejoran los vectores.
- Estrategia de **limitación de candidatos Top-K** para obtener suficientes artículos, pero no demasiados.
- **Traducción** de la Query y la respuesta. Cuando entra se interviene para pasarla a español y vectorizar correctamente. El resultado de traduce a el idioma de entrada.
- Presentación de enlaces a **fuentes oficiales online del BOE** de todos los artículos utilizados.
- Chunking personalizado y estrictamente diseñado para mantener contexto.
- Recuperación de artículos enteros para comprensión correcta del significado completo del texto.
- Integración de modelos de lenguaje para generación de respuestas fundamentadas.
- Persistencia de historial via **localStorage** y **persistencia de contexto** en conversación de las últimas 6 iteraciones.
- Diseño de FrontEnd desde 0 acorde a las necesidades especiales del producto.

**Tecnologías:** Python · TypeScript · Qdrant · PostgreSQL · LLM · APIs · Docker · Embedding · Chunking · Vite · Tailwind · React

> Aquí el **"readme.md"** del proyecto.

---

### [CLARK — Generador de presupuestos](https://clark.carlosrevert.es) (https://clark.carlosrevert.es)

Plataforma B2B de catalogo, busqueda, recomendacion y venta asistida para maquinaria de elevacion.
Al ser productos de alto valor no hacemos venta online, sino que generamos el presupuesto para que un comercial se ponga en contacto.

- Catálogo de elevadores, carretillas y traspaletas de CLARK con todo detalle de cada producto.
- Comparador de productos (2 o 3 simultáneamente) con marcas de vencedor. Responsive.
- Carrito y generación de presupuestos.
- Chatbot con conocimiento completo de todos los productos y la empresa en System Prompt + RAG técnico.
- Chatbot con navegación autónoma de paginas web en función de la pregunta del cliente. (Si le preguntas por un producto al chatbot es capaz de abrirte automáticamente la pagina de dicho producto, hacer comparaciones etc...)

**Tecnologías:** Python · TypeScript · LLM Local · Docker · PostgreSQL + PgVector · Next · React · Tailwind

---

### [Transcriptor con IA local](https://transcriptor.carlosrevert.es) (https://transcriptor.carlosrevert.es)

Plataforma web para grabar, subir y procesar audio con IA, devolviendo informes estructurados según el modo elegido. El flujo combina una interfaz React, una API en FastAPI, persistencia en PostgreSQL, una cola de trabajo en segundo plano y proveedores externos de STT y LLM para transformar audio en resultados útiles y fáciles de compartir.

- Transcripción mediante **Whisper** de audios que pueden ser de horas.
- Grabación directa desde la app, previa selección del tipo de modo. (Con opciones de pausa, play, stop y cancelar)
- Opción de adjuntar audio (previa petición de contraseña por mayor seguridad) y con autoconversión de formato a WAV y revisión de seguridad antes de abrir el archivo.
- Almacenamiento de informes por usuario en base de datos. Con opción de cambio a localStorage para mayor privacidad.
- Los audios se guardan en servidor durante 24 horas. El usuario puede descargarlos durante este plazo, luego serán eliminados.
- Procesamiento de audio con IA local.
- Diseño orientado a múltiples flujos y casos de uso.
- Privacidad y control del procesamiento al ejecutarse en infraestructura propia.

**Tecnologías:** Python · Whisper · STT · IA local · Docker

---

### [Autopublika](https://autopublika.carlosrevert.es) (https://autopublika.carlosrevert.es)

Sistema de planificación y generación de publicaciones de productos mediante EAN e inteligencia artificial.

- Identificación y enriquecimiento de productos mediante códigos EAN.
- Generación asistida de contenido.
- Planificación de publicaciones.
- Automatización de procesos relacionados con catálogos de producto.
- Igual de potente para Productos, como para Servicios.

**Tecnologías:** Python · API referente a código EAN e imagenes · Automatización

---

<details>
<summary><strong>Enfoque aplicado en los proyectos</strong></summary>

- Arquitectura modular y mantenible.
- Integración de frontend, backend, bases de datos y servicios externos.
- Despliegue mediante contenedores.
- Administración de dominios, subdominios, certificados SSL y proxy inverso.
- Uso de modelos de IA locales y de proveedores cloud.
- Control de versiones con Git y GitHub.
- Documentación y preparación para revisión técnica.

</details>

---

## Stack tecnológico

### Desarrollo web

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

| Área | Tecnologías |
|---|---|
| **Backend** | Python, Django, Flask, Node.js |
| **Frontend** | HTML5, CSS3, JavaScript, React, Vite |
| **APIs** | Integración de APIs, servicios de IA y sistemas externos |
| **Arquitectura** | Aplicaciones modulares, servicios contenerizados y entornos self-hosted |

### Bases de datos

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

- **Relacionales:** MySQL, PostgreSQL y SQLite.
- **Vectoriales:** Qdrant y pgvector.
- **Administración y consulta:** DBeaver.
- Diseño de sistemas orientados a recuperación semántica y aplicaciones RAG.

### Herramientas y control de versiones

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

- Control de versiones mediante **Git y GitHub**.
- Editor principal: **Visual Studio Code**.
- Experiencia con herramientas de desarrollo asistido por IA:
  - GitHub Copilot.
  - OpenAI Codex.
  - Claude Code.
  - Antigravity.

---

## Inteligencia artificial

### Integración de modelos y proveedores

Experiencia avanzada conectando aplicaciones y flujos con APIs de:

- OpenAI.
- Anthropic.
- Google.
- OpenRouter.
- xAI.
- ElevenLabs.

### Modelos locales

Configuración, optimización y puesta en producción de modelos locales de hasta **120B parámetros**:

- NVIDIA Nemotron: 14B, 30B y 120B.
- Qwen 3, Qwen 3.5 y Qwen 3.6.
- Gemma.
- DeepSeek.
- gpt-oss-120b.

Experiencia seleccionando modelos, ajustando cuantización, contexto, memoria y backend de inferencia según los recursos disponibles y el caso de uso.

### RAG, recuperación y procesamiento documental

- Diseño de sistemas **Retrieval-Augmented Generation**.
- Uso de Qdrant y pgvector como almacenes vectoriales.
- Estrategias avanzadas de **chunking**.
- Optimización de precisión, contexto y eficiencia de recuperación.
- Ingesta, limpieza, segmentación e indexación documental.
- Diseño de bases de conocimiento específicas para empresas y dominios especializados.

### Voz, OCR y agentes conversacionales

- Modelos **Speech-to-Text (STT)**.
- Modelos **Text-to-Speech (TTS)**.
- Whisper en local.
- Integración de ElevenLabs.
- Sistemas OCR con modelos de IA, Tesseract y herramientas similares.
- Creación de asistentes telefónicos y agentes de WhatsApp.
- Flujos conversacionales conectados con conocimiento real de empresas.

### Automatización

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)

- Creación y mantenimiento de flujos en **n8n** y **Make**.
- Integración entre APIs, modelos de IA, aplicaciones y servicios externos.
- Automatización de procesos de negocio, publicación, análisis y comunicación.

---

## Infraestructura y despliegue

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![NGINX](https://img.shields.io/badge/Nginx_Proxy_Manager-009639?style=flat-square&logo=nginx&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Conocimiento_teórico-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

- Dominio avanzado de **Docker** y despliegues contenerizados.
- Administración de un servidor propio basado en **Proxmox**.
- Despliegue y mantenimiento de aplicaciones web disponibles públicamente.
- Ejecución de modelos de inteligencia artificial locales.
- Configuración de IP, Dynamic DNS y acceso remoto.
- Gestión de dominios, subdominios, certificados SSL y proxy inverso mediante **Nginx Proxy Manager**.
- Conocimientos teóricos de **Kubernetes**.
- Diseño de infraestructura para aplicaciones que dependen de servicios de IA locales.

---

## Blockchain y Web3

Más de **diez años de experiencia** en el ecosistema Blockchain, comenzando de forma autodidacta y evolucionando hasta ofrecer asesorías y formaciones.

### Áreas de experiencia

- Finanzas descentralizadas (**DeFi**).
- NFTs.
- Minería y validación mediante **Proof of Work** y **Proof of Stake**.
- Gestión de billeteras frías y configuraciones multifirma.
- Contratos inteligentes con **Solidity**.
- Desarrollo y experimentación en Ethereum y Sonic.
- Uso de exchanges centralizados y descentralizados.
- Seguridad, custodia y operativa de activos digitales.

### Fiscalidad de criptoactivos

Estudio profundo de la fiscalidad española aplicada a criptomonedas y activos digitales.

- Preparación de declaraciones fiscales propias.
- Análisis de más de **20.000 transacciones**.
- Operativa distribuida entre más de **10 exchanges**.
- Consolidación de movimientos procedentes de plataformas centralizadas y descentralizadas.
- Interpretación y organización de operaciones en un entorno regulatorio todavía en evolución.

---

## Formación

### Máster en Desarrollo Web Full Stack

**Conquer Blocks · Formación online**

Formación orientada al desarrollo completo de aplicaciones web, cubriendo frontend, backend, bases de datos, control de versiones, despliegue y desarrollo de proyectos funcionales.

**Fecha:** `2024 a 2026 full time`

### Formación en curso

- Máster en Inteligencia Artificial
- Máster en Desarrollo Blockchain
- Curso de Inglés Profesional en ConquerBlocks

### Formación complementaria

- Cursos de inglés de atención al cliente. 
- Formación continua en inteligencia artificial, desarrollo de software, infraestructura y automatización.

---

## Experiencia profesional previa

### Jefe de cocina

**10 años de experiencia**

- Dirección y coordinación de equipo en hostelería.
- Organización del trabajo y asignación de responsabilidades.
- Control de stock y gestión de género.
- Resolución de incidencias e imprevistos.
- Responsabilidad sobre el funcionamiento diario del equipo.

### Agente de seguros

**Seguros Ocaso · 2 años**

- Atención y asesoramiento al cliente.
- Gestión comercial cara a cara.
- Comunicación de productos y coberturas.
- Desarrollo de relaciones de confianza con clientes.

### Monitor de Fitness y Artes Marciales

- Planificación y dirección de actividades físicas.
- Comunicación y motivación de grupos.
- Adaptación del entrenamiento a distintos perfiles.
- Cinturón Negro de TaeKwonDo.
- Nutrición y suplementación deportiva.
- Transmisión de disciplina, constancia y mejora progresiva.

---

## Idiomas

| Idioma | Nivel |
|---|---|
| **Castellano** | Nativo |
| **Valenciano** | Nativo |
| **Inglés escrito** | Alto |
| **Inglés oral** | Intermedio |

---

## Competencias profesionales

- Aprendizaje autónomo y adaptación tecnológica.
- Pensamiento analítico y resolución de problemas.
- Liderazgo y coordinación de equipos.
- Gestión de proyectos multidisciplinares.
- Capacidad para transformar una necesidad de negocio en una solución técnica.
- Mentalidad orientada a producto y mejora continua.
- Documentación, investigación y aprendizaje de nuevas herramientas.
- Experiencia combinando tecnología, negocio, operaciones y atención al cliente.

---

## Objetivo profesional

Continuar desarrollándome como profesional especializado en **desarrollo Full Stack e integración de inteligencia artificial**, participando en proyectos donde pueda combinar software, automatización, modelos de lenguaje, sistemas RAG e infraestructura self-hosted.

Me interesa colaborar en equipos y proyectos que valoren la autonomía, el aprendizaje continuo, la experimentación técnica y la aplicación práctica de nuevas tecnologías.

---

<div align="center">

### Contacto

🌐 [carlosrevert.es](https://carlosrevert.es)  
💼 LinkedIn: `pendiente de añadir`  
✉️ Email: `revertus@protonmail.com`

---

**Disponible para proyectos, colaboraciones y oportunidades profesionales.**

</div>

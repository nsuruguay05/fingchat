# Búsqueda de respuestas en documentos institucionales utilizando grandes modelos de lenguaje

Este repositorio contiene el código del proyecto de grado ["Búsqueda de respuestas en documentos institucionales utilizando grandes modelos de lenguaje"](https://www.colibri.udelar.edu.uy/jspui/bitstream/20.500.12008/46066/1/Sas24.pdf), realizado en la Facultad de Ingeniería de la Universidad de la República (Uruguay).

La herramienta desarrollada en este proyecto puede accederse en [https://fingchat.vercel.app/](https://fingchat.vercel.app/).

**Resumen del proyecto**

Este proyecto explora e implementa técnicas para mejorar la generación de respuestas de grandes modelos de lenguaje (LLMs) en dominios específicos, utilizando un conjunto acotado de documentos como fuente de información. El proyecto se centra en el caso de estudio del Espacio de Orientación y Consulta (EOC) de la Facultad de Ingeniería, donde se desarrolló una herramienta para responder preguntas de estudiantes sobre su proceso académico. Se exploraron diferentes métodos, como Retrieval-Augmented Generation (RAG), Fine-tuning de LLMs, Prompting de Derivaciones y Grandes ventanas de contexto. Se evaluó el rendimiento de los métodos y se desarrolló un prototipo de la herramienta para ser utilizado por el EOC.

**Estructura del repositorio**

Este repositorio central alberga el código del proyecto, dividido en subrepositorios:

* **[Herramienta FingChat - Frontend](https://github.com/nsuruguay05/chatfing_fe/):** Código del frontend de la herramienta FingChat.
* **[Herramienta FingChat - Backend](https://github.com/nsuruguay05/chatfing_be/):** Código del backend de la herramienta FingChat.
* **[Prompting de Derivaciones](https://github.com/nsuruguay05/derivation-prompting/):** Implementación del método de Prompting de Derivaciones (repo asociado al paper "Derivation Prompting: A Logic-Based Method for
Improving Retrieval-Augmented Generation").
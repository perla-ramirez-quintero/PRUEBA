# PORTAFOLIO DE EVIDENCIAS DIGITALES: INNOVACIÓN Y DESARROLLO DE APLICACIONES INTERACTIVAS
**Licenciatura en Educación Preescolar** **Curso:** Tecnologías Digitales en la Práctica Educativa  
**Alumna (Docente en Formación):** Perla Ramírez Quintero  

---

## 1. Datos de Identificación y Acceso al Proyecto

* **Nombre de la Autora:** Perla Ramírez Quintero
* **Perfil de GitHub Central:** [https://github.com/perla-ramirez-quintero](https://github.com/perla-ramirez-quintero)
* **Marco Curricular de Referencia:** Nueva Escuela Mexicana (NEM), Fase 2 (Educación Preescolar, aula multigrado).

---

## 2. Directorio Técnico de los Recursos Didácticos

* **Repositorio Base Asociado:** `CREACION-Y-EXPLORACION`
* **Módulo Cuento Interactivo ("El Viaje de las Estaciones"):** Carpeta `Cuento_Estaciones` (`index.html`)
* **Módulo Lúdico de Clasificación ("Juego de Clasificar Basura"):** Archivo único `Juego_Clasificar_Basura.html`

---

## 3. Bitácora de Desarrollo y Ajustes Técnicos (Iteración de Recursos)

El proceso de ideación, construcción e iteración de los recursos interactivos contempló las siguientes adecuaciones técnicas y metodológicas:

1. **Cuento Inmersivo de las Estaciones ("El Viaje de las Estaciones"):**
   * *Incidencia:* Tras la compilación inicial, la interfaz se ocultaba automáticamente a los pocos segundos impidiendo la visualización de los personajes y el texto.
   * *Solución:* Se depuró la rutina de animación sincrónica, restaurando el flujo de lectura interactiva protagonizada por el *Osito Bimbo*, accesible mediante recarga de navegador.
2. **Consolidación del Juego de Clasificación de Residuos:**
   * *Arquitectura de Archivo Único:* Se programó la aplicación completa dentro del archivo `Juego_Clasificar_Basura.html` para simplificar su ejecución local y su portabilidad, evitando dependencias de red o carpetas complejas.
   * *Mecánica Táctil:* Implementación de eventos de arrastrar y soltar (*drag and drop*) optimizados mediante *Pointer Events*, garantizando una respuesta fluida tanto en pantallas táctiles (tablets o celulares de los padres) como con mouse en equipos de escritorio.
   * *Retroalimentación Inmediata:* Síntesis de voz activada al pulsar cualquier elemento para indicar su nombre, animación de rebote elástico (*resorte*) ante selecciones incorrectas, agitación visual de los botes de basura y celebración con confeti y fanfarria al completar la limpieza total del parque.
3. **Adecuación del Contenido Biológico y Respeto Ambiental:**
   * *Incidencia:* Los emojis de manzana entera y plátano con fruto inducían al error conceptual de desechar alimento comestible en lugar de desperdicios orgánicos.
   * *Solución:* Se reemplazó pedagógicamente la manzana por cascarones de huevo (`🥚`) y el plátano por restos de hueso (`🦴`), manteniendo elementos inequívocos como la cáscara de sandía (`🍉`) y la hoja seca (`🍂`). Esto asegura que el preescolar discrimine correctamente entre materia orgánica de desecho y alimento.
4. **Desmitificación de Entornos de Control de Versiones:**
   * Se identificó y resolvió la aparición del archivo temporal de control `COMMIT_EDITMSG` en el editor, comprendiendo su naturaleza inofensiva dentro del directorio oculto `.git` y reafirmando el enfoque de edición directa sobre el código de los juegos.
5. **Estrategias de Portabilidad y Distribución Escolar:**
   * Se establecieron tres vías de compartición para adaptarse a la infraestructura real de las escuelas de práctica y el contexto de las familias:
     * *Modo Local (Aula Multigrado):* Ejecución offline copiando el archivo `.html` a una memoria USB para proyectarlo en la computadora de la escuela sin requerir internet.
     * *Mensajería Móvil (WhatsApp):* Envío directo del archivo único `Juego_Clasificar_Basura.html` por WhatsApp Web; los padres lo descargan y ejecutan en navegadores móviles para el repaso autónomo de fin de semana.
     * *Despliegue en la Nube:* Integración mediante plataformas de almacenamiento estático (como Netlify Drop o GitHub Pages) para enlaces públicos persistentes.

---

## 4. Sustento Pedagógico (Alineación NEM - Fase 2)

* **Campo Formativo:** Saberes y Pensamiento Científico / Ética, Naturaleza y Sociedades.
* **Prioridad Cognitiva:** Cuidado del entorno, consumo sustentable y discriminación de residuos sólidos (orgánicos e inorgánicos).
* **Ejes Articuladores Incorporados:**
  * *Vida Saludable / Pensamiento Crítico:* Permite al alumno de preescolar analizar la naturaleza de los desechos, su origen y su impacto en el ecosistema, promoviendo la conciencia ambiental y la responsabilidad comunitaria desde la primera infancia.
  * *Inclusión:* Interfaces diseñadas con apoyos visuales y estímulos auditivos que se adaptan a los distintos niveles de maduración motriz, cognitiva y de lectoescritura del aula multigrado.
* **Metodología Empleada:** Aprendizaje Situado y Gamificación. El software traslada problemáticas reales de la comunidad a un entorno lúdico, reforzando el aprendizaje a través de la manipulación digital directa.

---

## 5. Anexo Técnico: Transcripción Íntegra de la Conversación (Raw Logs)

**12:39, 24/3/2026 - Usuario (Docente en Formación):**
> okey, hagasmos primero el juego del cuento trabajando el tema de las estaciones, no te limites a creatividad, usza todos los elementos que me propusiste

**12:39, 24/3/2026 - IA (Asistente Técnico):**
> *(Transmisión en blanco / Espera de respuesta)*

**12:48, 24/3/2026 - Usuario (Docente en Formación):**
> no se porque pero no abre bien

**12:48, 24/3/2026 - IA (Asistente Técnico):**
> Detecta y corrige el error en el temporizador de animación que ocultaba la escena del cuento. Solicita recargar la página (F5 o actualizar) para visualizar el título "El Viaje de las Estaciones" y al Osito Bimbo.

**13:01, 24/3/2026 - Usuario (Docente en Formación):**
> ya se ve bien, ahoara hagamos lo siguiente PERO todo en un solo archivo por favor. Me gustaría que sea de clasificación de basura organiza e inorganica

**13:01, 24/3/2026 - IA (Asistente Técnico):**
> Entrega el "Juego de Clasificar Basura" en el archivo único `Juego_Clasificar_Basura.html`. Detalla la programación de drag-and-drop táctil, síntesis de voz, validación con rebote y celebración final con confeti.

**13:05, 24/3/2026 - Usuario (Docente en Formación):**
> okey ya lo vi, me gustaria que cambies la manzana y el platano porque aun tienen fruto y los niños deben saber que solo se tira la cascara

**13:05, 24/3/2026 - IA (Asistente Técnico):**
> Valida la observación sobre consumo y desperdicio. Reemplaza la manzana por cascarones de huevo (`🥚`) y el plátano por un hueso (`🦴`), solicitando recargar la página para visualizar la basura real.

**13:08, 24/3/2026 - Usuario (Docente en Formación):**
> por que me sale eso???? *(Muestra pantalla del archivo `COMMIT_EDITMSG`)*

**13:08, 24/3/2026 - IA (Asistente Técnico):**
> Calma al usuario explicando que es un archivo temporal del historial de Git (`.git`), totalmente inofensivo. Recomienda cerrarlo y centrarse en los archivos web.

**13:09, 24/3/2026 - Usuario (Docente en Formación):**
> eres grandioso, me causaba ruido verlo ahí

**13:09, 24/3/2026 - IA (Asistente Técnico):**
> Celebra la resolución y enlista los proyectos logrados (Animales Marinos, Cuento de Estaciones, Clasificación de Basura). Ofrece avanzar hacia el memorama o enfocarse en la aplicación didáctica.

**13:21, 24/3/2026 - Usuario (Docente en Formación):**
> y si quisiera compartir alguno de estos recursos que debo hacer?

**13:21, 24/3/2026 - IA (Asistente Técnico):**
> Explica tres métodos sencillos de distribución para aplicaciones HTML estáticas: 
> 1. Sin internet en el aula mediante memoria USB.
> 2. Envío rápido del archivo `.html` por WhatsApp para que los padres lo abran en celulares.
> 3. Alojamiento gratuito en la nube (Netlify Drop o GitHub Pages) para generar enlaces web eternos.

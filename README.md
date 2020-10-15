# PracticaADBD-Torriani
## Introducción

Este documento contiene un planteamiento inicial del supuesto "La fundación de Torriani".  
La fundación torriani nos proporciona información sobre sus objetivos y nosotros hemos de comenzar a esbozar el 
diseño de una base de datos acorde a sus objetivos y exigencias.  

- Eduardo José Díaz Hernandez  
- Esther Jorge Paramio  
- Sergio Guerra Arencibia   
- Victoria Montserrat Manrique Rolo.  
  
## Entidades  
  - Patrimonio histórico:
    - Nombre.
    - Ubicación.
    - Año de construcción.
    - Modificaciones.
    - Tipo de contrucción (civil, religiosa, viviendas domésticas, plazas, calles o callejones, etc).

  - Documentos:
    - Nombre.
    - Autor.
    - Fecha.
    - Resumen.

  - Medidas de protección:
    - Grado de protección.
    - Cumplimiento.
    - Organismos responsables.
    - Sanciones.
    - Entidad promotora.

  - Inversiones públicas:
    - Cantidad.
    - Fecha.
    - Objetivo.
    - Entidad promotora.

  - Empresa:
    - Relación con el patrimonio.
    - Cantidad.
    - Nivel de implicación.

  - Eventos: 
    - Descripción.
    - Fecha.
    - Duración.
  
  - Usuarios externos:
    - Denuncias.
    - Valoración.
  
  ## Relaciones entre entidades
  - Patrimonio histórico (aparecen en) documentos
  - Empresa (invierte en) patrimonio histórico
  - Empresa (patrocina) patrimonio histórico  
  - Empresa (realiza su actividad) patrimonio histórico  
  - Evento (se realiza en) patrimonio histórico
  - Información de usuarios (hace referencia a) patrimonio histórico
  - Patrimonio histórico (tiene) medios de protección
  - Patrimonio histórico (recibe) inversiones públicas
  - Empresa (organiza) eventos
    
## Fuentes de información  
  - Documentos oficiales del estado
  - Registros de organizaciones inversoras u organizadoras de eventos
  - Legislación de elementos patrimoniales
  - Documentos históricos
  - Documentos científicos
  - Opiniones de usuarios
 

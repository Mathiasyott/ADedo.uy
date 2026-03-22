ADedo.uy # — Analizador de llamados laborales uruguayos
> *"El mérito existe. A veces hasta funciona."*
ADedo.uy es una herramienta de código abierto que analiza llamados laborales uruguayos —públicos y privados— detectando señales de acomodo, falta de transparencia, empleos trampa y vulneración de derechos laborales.
Hecha con vibe coding por @porthosuy — Mathiasyott.  
Esto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.
🌐 mathiasyott.github.io/ADedo.uy
---
¿Qué hace?
Pegás el texto de un llamado laboral y la app analiza:
Sector público:
Señales de acomodo — requisitos imposibles, criterios subjetivos, tribunales fantasma, plazos cortísimos, cargos de particular confianza, antigüedad interna requerida
Ausencia de examen de conocimientos
Cláusulas que eliminan el derecho a impugnar
Sector privado:
Sueldo por debajo del Salario Mínimo Nacional — con número de denuncia incluido
Comisión pura sin sueldo base — explica que técnicamente no es un empleo
Sueldo "a convenir" — explica por qué ocultan el precio
Empleos trampa — MLM, pago para trabajar, capacitación arancelada, agente inmobiliario sin habilitación (Ley 20.380)
Autoempleo disfrazado de oferta laboral — "emprendedor", "independiente", "sin jefe"
Lenguaje motivacional vacío que reemplaza condiciones concretas
En ambos sectores:
Contradicción recién egresado + experiencia requerida
Edad máxima vs años de experiencia matemáticamente imposibles
Auto-detección del sector según el texto pegado
Checklist automático de documentos requeridos
El resultado incluye un índice de sospecha de 0 a 100, señales detectadas con explicación, veredicto final y resumen con humor negro — distinto para sector público y privado.
---
Modos de uso
⚙ Modo básico
Funciona sin internet extra, sin registro, sin key. Analiza con más de 100 reglas fijas construidas para el mercado laboral uruguayo. Las reglas, las frases de carga durante el análisis y los veredictos son completamente distintos para sector público y privado.
🤖 Modo IA
Usa inteligencia artificial para un análisis más profundo y contextual. Requiere una key gratuita de Groq, Gemini, OpenRouter o Claude. La app incluye tutoriales paso a paso para conseguir cada key — explicados para alguien que nunca usó una API.
---
Pestañas
Pestaña	Contenido
`_analizar`	El analizador principal — público o privado, modo básico o IA, lector de PDF alfa
`_consejos`	Guía práctica — sección especial para menores de 18, señales de oferta trampa, qué revisar antes de firmar
`_glosario`	Más de 90 términos organizados en 13 categorías
`_impugnar`	Pasos concretos para impugnar en sector público y reclamar en sector privado
`_denuncias`	Dónde denunciar — INAU, IGTSS, MTSS, BPS, SUTD, UTRAU, JUTEP — links y teléfonos verificados
`_mis_llamados`	Registro personal de llamados guardado en el navegador
---
Glosario — 13 categorías
Tipos de contrato y cargo
El proceso de concurso
Estructura del Estado
Acomodo y cultura laboral
Documentos y trámites
Derechos y cupos
Derechos laborales básicos — SMN actualizado 2026, aguinaldo, licencia, indemnización, período de prueba, BPS
Trabajo rural — derechos, planilla, lista negra, UTRAU, edad mínima 16 años
Trabajo doméstico — Ley 18.065, SUTD, categorías 2026, salario mínimo sectorial
Trabajo infantil y adolescente — edad mínima, Carné de Trabajo INAU, condiciones, salario proporcional
Empleos trampa — MLM, comisión pura, cuota mensual por pertenecer a la red, falso autónomo, aviso fantasma, ATS, corredor inmobiliario sin habilitación, plataformas de avisos
La LUC y los derechos laborales — artículo 392, decreto 281/020 (desalojo con policía), artículo 468 (piquetes), referéndum 2022, estado actual 2025
Gremios y acción colectiva — huelga, paro, ocupación, trabajo a reglamento, PIT-CNT, negociación colectiva
---
Lo que detecta que otras apps no detectan
Sueldo por debajo del SMN — compara el número publicado contra el mínimo legal vigente y lo marca como ilegal con el número de denuncia
Comisión pura sin sueldo base — detecta cuando el aviso lo dice explícitamente o lo deja claro con lenguaje de "emprendedor" + ventas
Cuota mensual para pertenecer — el esquema donde además de no cobrar sueldo, el "agente" paga por usar la plataforma
Agente inmobiliario sin habilitación — cruza con la Ley 20.380 vigente desde enero 2025
Contradicción recién egresado + experiencia — imposibilidad matemática que muchos avisos tienen
Autoempleo disfrazado de empleo — "emprendedor", "independiente", "sin jefe" combinado con ventas a comisión
---
Tecnología
HTML, CSS y JavaScript vanilla — un único archivo sin dependencias ni framework
Sin backend, sin base de datos, sin servidores propios
Los datos del usuario se guardan únicamente en `localStorage` del navegador
Las keys de IA se guardan solo en el navegador del usuario y nunca pasan por servidores nuestros
Lector de PDF por link (versión alfa) usando pdf.js vía CDN
Auto-detección de sector público/privado al analizar
Deployado en GitHub Pages
---
Privacidad
La app no guarda ni envía el texto que el usuario analiza
Sin cookies de seguimiento ni analíticas
Sin publicidad
Código completamente auditable — es un único archivo HTML
---
Licencia
Creative Commons BY-NC-SA 4.0
Podés usar, modificar y distribuir este código siempre que:
Menciones el origen — @porthosuy / Mathiasyott
No lo uses para fines comerciales
Lo distribuyas con la misma licencia
El conocimiento no se cobra.
---
Historial de versiones
Versión	Cambios principales
v1	Analizador básico con semáforo rojo/amarillo/verde
v2	Separación público/privado, detección texto IA, lector PDF alfa
v3	Intro animada Matrix con Ⓐ anarquistas, pestañas, glosario básico, historial localStorage
v4	55 frases de carga con humor negro, switch claro/oscuro, checklist documentos, compartir por WhatsApp, panel key propia
v5	Pantalla bienvenida con elección de modo, tutoriales de key paso a paso para Groq/Gemini/OpenRouter/Claude
v5.3	Reglas completamente separadas público/privado · Detección MLM y empleos trampa · Comisión pura sin sueldo base · Sueldo por debajo del SMN con denuncia · Frases de carga distintas por sector · Auto-detección de sector · Consejos para menores de 18 · Pestaña `_denuncias` con organismos verificados · Glosario ampliado con trabajo rural, doméstico, infantil, empleos trampa y LUC · Ley 20.380 inmobiliaria · Impugnar para sector privado
---
Créditos
Hecha con vibe coding por @porthosuy — Mathiasyott  
Uruguay, 2025-2026
Para toda la gente que alguna vez perdió un llamado limpio sin saber por qué.  
Y para la que perdió uno trucado y lo sabía perfectamente.  
Y para la que fue a una entrevista y le dijeron que tenía que pagar para trabajar.
---
![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)

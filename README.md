ADedo.uy # — Analizador de llamados laborales uruguayos
> *"El mérito existe. A veces hasta funciona."*
ADedo.uy es una herramienta de código abierto que analiza llamados laborales uruguayos —públicos y privados— detectando señales de acomodo, falta de transparencia, empleos trampa y vulneración de derechos laborales.
Hecha con vibe coding por @porthosuy — Mathiasyott.  
Esto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.
🌐 mathiasyott.github.io/ADedo.uy
---
¿Qué hace?
Pegás el texto de un llamado laboral y la app analiza:
Señales de acomodo en el sector público — requisitos imposibles, criterios subjetivos, tribunales fantasma, plazos cortísimos, cargos de confianza, antigüedad interna requerida
Falta de transparencia en el sector privado — sueldo a convenir, condiciones ocultas, lenguaje motivacional vacío, monotributo forzado
Empleos trampa — esquemas multinivel, pago para trabajar, capacitación arancelada, corredor inmobiliario sin habilitación
Contradicciones — recién egresado con experiencia requerida, edad máxima vs años de experiencia imposibles
Documentos requeridos — genera checklist automático para que no te olvides de nada
El resultado incluye un índice de sospecha de 0 a 100, señales detectadas con explicación, veredicto final y resumen con humor negro.
---
Modos de uso
Modo básico
Funciona sin internet extra, sin registro, sin key. Analiza usando más de 100 reglas fijas construidas específicamente para el mercado laboral uruguayo. Diferencia completamente entre sector público y sector privado.
Modo IA
Usa inteligencia artificial para un análisis más profundo. Requiere una key gratuita de Groq, Gemini, OpenRouter o Claude. La app incluye tutoriales paso a paso para conseguir cada key.
---
Pestañas
Pestaña	Contenido
`_analizar`	El analizador principal
`_consejos`	Guía práctica — incluyendo sección especial para menores de 18
`_glosario`	Más de 80 términos en 13 categorías
`_impugnar`	Pasos para impugnar en sector público y reclamar en privado
`_denuncias`	INAU, IGTSS, MTSS, BPS, SUTD, UTRAU, JUTEP — links y teléfonos verificados
`_mis_llamados`	Registro personal guardado en el navegador
---
Glosario — categorías
Tipos de contrato y cargo
El proceso de concurso
Estructura del Estado
Acomodo y cultura laboral
Documentos y trámites
Derechos y cupos
Derechos laborales básicos
Trabajo rural
Trabajo doméstico
Trabajo infantil y adolescente
Empleos trampa
La LUC y los derechos laborales — artículo 392, decreto 281/020, piquetes, referéndum 2022
Gremios y acción colectiva
---
Tecnología
HTML, CSS y JavaScript vanilla — un único archivo sin dependencias ni framework
Sin backend, sin base de datos, sin servidores propios
Los datos se guardan únicamente en `localStorage` del navegador
Las keys de IA nunca pasan por servidores nuestros
Lector de PDF por link (versión alfa) usando pdf.js
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
Podés usar, modificar y distribuir este código siempre que menciones el origen (@porthosuy), no lo uses para fines comerciales y lo distribuyas con la misma licencia.
El conocimiento no se cobra.
---
Historial de versiones
Versión	Cambios principales
v1	Analizador básico con semáforo
v2	Separación público/privado, lector PDF alfa
v3	Intro Matrix, pestañas, glosario, historial
v4	Humor negro, modo claro/oscuro, checklist, WhatsApp
v5	Pantalla bienvenida, tutoriales de key paso a paso
v5.3	Reglas separadas público/privado · Detección MLM y empleos trampa · Frases distintas por sector · Consejos para menores de 18 · Pestaña _denuncias · Glosario ampliado (trabajo rural, doméstico, infantil, LUC) · Impugnar para sector privado
---
Créditos
Hecha con vibe coding por @porthosuy — Mathiasyott  
Uruguay, 2025-2026
Para toda la gente que alguna vez perdió un llamado limpio sin saber por qué.  
Y para la que perdió uno trucado y lo sabía perfectamente.
![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)

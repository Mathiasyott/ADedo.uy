# ADedo.uy #

> *Analizador de llamados laborales uruguayos — sector público y privado*

**¿Ese llamado está limpio o ya saben quién entra?**

ADedo.uy es una herramienta gratuita y de código abierto que analiza el texto de llamados laborales uruguayos y detecta señales de acomodo, falta de transparencia y criterios diseñados a medida para una persona específica. Funciona para llamados del Estado (Uruguay Concursa, ASSE, BPS, intendencias, etc.) y para el sector privado.

---

## ¿Qué hace?

- 🔍 **Analiza el texto** del llamado y detecta señales de alerta usando IA
- 📊 **Semáforo visual** con índice de sospecha del 0 al 100
- 📝 **Detecta si hay examen de conocimientos** o todo depende de criterios subjetivos
- ⚠️ **Advierte sobre problemas estructurales** del sistema de llamados uruguayo
- 📖 **Glosario de burocracia** — qué significa cada término que nadie te explica
- ⚖️ **Guía para impugnar** — tus derechos y los pasos concretos si el proceso fue irregular
- 📁 **Mis llamados** — seguimiento personal de tus postulaciones (guardado local, sin servidores)
- 🤖 **Detecta texto transcripto por IA** y lo limpia automáticamente antes de analizar
- 🧪 **Lector de PDF por link** (fase alfa — puede no funcionar con portales del Estado)

---

## Cómo usarla

1. Abrí `index.html` en tu navegador **o** entrá a la URL del proyecto en GitHub Pages
2. Elegí si el llamado es estatal o privado
3. Pegá el texto de las bases o el llamado completo
4. Apretá **analizar**
5. Si tenés el llamado en PDF, seguí las instrucciones de Gemini que están dentro de la app

No necesita instalación. No necesita servidor. Funciona directo en el navegador.

---

## Tecnología

- HTML + CSS + JavaScript puro — sin frameworks, sin dependencias
- API de Anthropic (Claude) para el análisis de texto
- pdf.js para lectura de PDFs por link (fase alfa)
- localStorage para guardar el historial de llamados localmente
- Todo corre en el navegador del usuario — ningún dato se envía a servidores propios

---

## Versión actual

**v3 — alfa**

Esta es una versión alfa. Puede tener errores, comportamientos inesperados y funciones incompletas. Se acepta cualquier contribución para mejorarla.

### Funciones planeadas para próximas versiones
- [ ] Módulo "¿qué documentos necesito para anotarme?"
- [ ] Generador de carta de presentación adaptada al llamado
- [ ] Estimación de tu perfil vs los requisitos del llamado
- [ ] Modo preparación para la entrevista
- [ ] Base colaborativa de llamados analizados (requiere backend)
- [ ] Índice público de transparencia por organismo (requiere backend)

---

## Contribuir

Esta app es libre. Si sabés programar y querés sumar, el código es tuyo también.

**Para contribuir:**
1. Hacé un fork del repositorio
2. Creá una rama con tu mejora (`git checkout -b mejora-lo-que-sea`)
3. Hacé commit de tus cambios
4. Abrí un Pull Request explicando qué cambiaste y por qué

**No hace falta ser programador profesional para contribuir.** Podés reportar errores, sugerir mejoras, corregir el glosario o mejorar los textos. Todo suma.

---

## Licencia

**Creative Commons BY-NC-SA 4.0**

Podés usar, modificar y distribuir este código libremente **siempre que:**
- Menciones el origen: **@porthosuy** (Mathiasyott)
- No lo uses para fines comerciales — esta herramienta no se vende ni se privatiza
- Lo distribuyas con la misma licencia

El conocimiento no se cobra.

---

## Aviso legal

Esta aplicación analiza únicamente el texto que el usuario proporciona y detecta patrones objetivos de redacción. No acusa ni difama a ningún organismo público ni empresa privada. Si un llamado presenta señales de alerta, es porque así fue redactado por quien lo publicó. ADedo.uy no se hace responsable del uso que se haga de los resultados.

---

## Autor

Hecha con **vibe coding** por **@porthosuy** — Mathiasyott

Esto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.

TikTok: [@porthosuy](https://www.tiktok.com/@porthosuy)

---

*"El que no sabe es como el que no ve."*
*ADedo.uy existe para que veas.*

# ADedo.uy #

> *Analizador de llamados laborales uruguayos — sector público y privado*

**¿Ese llamado está limpio o ya saben quién entra?**

ADedo.uy es una herramienta gratuita y de código abierto que analiza el texto de llamados laborales uruguayos y detecta señales de acomodo, falta de transparencia y criterios diseñados a medida. Funciona para llamados del Estado (Uruguay Concursa, ASSE, BPS, intendencias, etc.) y para el sector privado.

---

## ¿Qué hace?

- 🔍 **Analiza el texto** del llamado con IA y detecta señales de alerta
- 📊 **Semáforo visual** con índice de sospecha del 0 al 100
- 😂 **55 frases de humor negro** mientras analiza — rotativas y al azar
- 📝 **Detecta si hay examen de conocimientos** o todo depende de criterios subjetivos
- 📋 **Checklist automático** de documentos que pide el llamado
- ⚠️ **Advierte sobre problemas estructurales** del sistema uruguayo
- ☀️ **Modo claro/oscuro** con preferencia guardada
- 📲 **Compartir resultado por WhatsApp**
- 📖 **Glosario completo** por categorías — desde "a dedo" hasta "PIT-CNT"
- 💡 **Consejos prácticos** — CV, carta de recomendación, entrevistas, documentos, cupos
- ⚖️ **Guía para impugnar** — derechos y pasos concretos
- 📁 **Mis llamados** — seguimiento personal guardado localmente

---

## Cómo usarla

1. Entrá a la URL del proyecto en GitHub Pages
2. Elegí si el llamado es estatal o privado
3. Pegá el texto de las bases o el llamado completo
4. Apretá **analizar** y disfrutá las frases mientras carga
5. Si tenés el llamado en PDF, seguí las instrucciones de Gemini dentro de la app

No necesita instalación. No necesita servidor. Funciona directo en el navegador.

---

## API y créditos

- **Por defecto** usa Google Gemini — gratuito, 1.500 análisis por día, el usuario no hace nada
- **Si se agota**, aparece un panel para configurar key propia gratuita
- Soporta: **Google Gemini**, **Groq** y **OpenRouter**
- La key se guarda solo en el navegador del usuario

### Cómo obtener tu propia key (si la necesitás)

**Groq** → [console.groq.com](https://console.groq.com) — gratis, sin tarjeta (recomendado, 1.500 req/día)

**Groq** → [console.groq.com](https://console.groq.com) — gratis, sin tarjeta

**OpenRouter** → [openrouter.ai](https://openrouter.ai) — gratis, modelos variados

---

## Tecnología

- HTML + CSS + JavaScript puro — sin frameworks, sin dependencias
- Google Gemini 1.5 Flash por defecto, con soporte para Groq y OpenRouter — todos gratuitos
- pdf.js para lectura de PDFs por link (fase alfa)
- localStorage para historial, preferencias y key del usuario
- Todo corre en el navegador — ningún dato va a servidores propios

---

## Versión actual

**v4 — alfa**

### Funciones planeadas
- [ ] Módulo "¿qué documentos necesito para anotarme?"
- [ ] Generador de carta de presentación
- [ ] Estimación de perfil vs requisitos del llamado
- [ ] Modo preparación para entrevista
- [ ] Base colaborativa de llamados (requiere backend)
- [ ] Índice público de transparencia por organismo (requiere backend)

---

## Contribuir

Esta app es libre. Si sabés programar y querés sumar, el código es tuyo también.

1. Hacé un fork del repositorio
2. Creá una rama con tu mejora (`git checkout -b mejora-lo-que-sea`)
3. Hacé commit y abrí un Pull Request

No hace falta ser programador profesional. Podés reportar errores, mejorar el glosario, agregar consejos o mejorar los textos. Todo suma.

---

## Licencia

**Creative Commons BY-NC-SA 4.0**

Podés usar, modificar y distribuir este código siempre que:
- Menciones el origen: **@porthosuy** (Mathiasyott)
- No lo uses para fines comerciales
- Lo distribuyas con la misma licencia

El conocimiento no se cobra.

---

## Aviso legal

Esta aplicación analiza únicamente el texto que el usuario proporciona y detecta patrones objetivos de redacción. No acusa ni difama a ningún organismo público ni empresa privada. Si un llamado presenta señales de alerta, es porque así fue redactado por quien lo publicó. ADedo.uy no se hace responsable del uso de los resultados.

---

## Autor

Hecha con **vibe coding** por **@porthosuy** — Mathiasyott

Esto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.

TikTok: [@porthosuy](https://www.tiktok.com/@porthosuy)

---

*"El que no sabe es como el que no ve."*
*ADedo.uy existe para que veas.*

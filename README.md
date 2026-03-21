ADedo.uyAnalizador de llamados laborales uruguayos — sector público y privado¿Ese llamado está limpio o ya saben quién entra?ADedo.uy es una herramienta gratuita y de código abierto que analiza el texto de llamados laborales uruguayos y detecta señales de acomodo, falta de transparencia y criterios diseñados a medida. Funciona para llamados del Estado (Uruguay Concursa, ASSE, BPS, intendencias, etc.) y para el sector privado.¿Qué hace?🔍 Analiza el texto del llamado con IA y detecta señales de alerta📊 Semáforo visual con índice de sospecha del 0 al 100😂 55 frases de humor negro mientras analiza — rotativas y al azar📝 Detecta si hay examen de conocimientos o todo depende de criterios subjetivos📋 Checklist automático de documentos que pide el llamado⚠️ Advierte sobre problemas estructurales del sistema uruguayo☀️ Modo claro/oscuro con preferencia guardada📲 Compartir resultado por WhatsApp📖 Glosario completo por categorías — desde "a dedo" hasta "PIT-CNT"💡 Consejos prácticos — CV, carta de recomendación, entrevistas, documentos, cupos⚖️ Guía para impugnar — derechos y pasos concretos📁 Mis llamados — seguimiento personal guardado localmenteCómo usarlaEntrá a la URL del proyecto en GitHub PagesElegí si el llamado es estatal o privadoPegá el texto de las bases o el llamado completoApretá analizar y disfrutá las frases mientras cargaSi tenés el llamado en PDF, seguí las instrucciones de Gemini dentro de la appNo necesita instalación. No necesita servidor. Funciona directo en el navegador.API y créditosPor defecto usa Google Gemini — gratuito, 1.500 análisis por día, el usuario no hace nadaSi se agota, aparece un panel para configurar key propia gratuitaSoporta: Google Gemini, Groq y OpenRouterLa key se guarda solo en el navegador del usuarioCómo obtener tu propia key (si la necesitás)Groq → console.groq.com  — gratis, sin tarjeta (recomendado, 1.500 req/día)Groq → console.groq.com  — gratis, sin tarjetaOpenRouter → openrouter.ai  — gratis, modelos variadosTecnologíaHTML + CSS + JavaScript puro — sin frameworks, sin dependenciasGoogle Gemini 1.5 Flash por defecto, con soporte para Groq y OpenRouter — todos gratuitospdf.js para lectura de PDFs por link (fase alfa)localStorage para historial, preferencias y key del usuarioTodo corre en el navegador — ningún dato va a servidores propiosVersión actualv4 — alfaFunciones planeadasMódulo "¿qué documentos necesito para anotarme?"Generador de carta de presentaciónEstimación de perfil vs requisitos del llamadoModo preparación para entrevistaBase colaborativa de llamados (requiere backend)Índice público de transparencia por organismo (requiere backend)ContribuirEsta app es libre. Si sabés programar y querés sumar, el código es tuyo también.Hacé un fork del repositorioCreá una rama con tu mejora (git checkout -b mejora-lo-que-sea)Hacé commit y abrí un Pull RequestNo hace falta ser programador profesional. Podés reportar errores, mejorar el glosario, agregar consejos o mejorar los textos. Todo suma.LicenciaCreative Commons BY-NC-SA 4.0Podés usar, modificar y distribuir este código siempre que:Menciones el origen: @porthosuy (Mathiasyott)No lo uses para fines comercialesLo distribuyas con la misma licenciaEl conocimiento no se cobra.Aviso legalEsta aplicación analiza únicamente el texto que el usuario proporciona y detecta patrones objetivos de redacción. No acusa ni difama a ningún organismo público ni empresa privada. Si un llamado presenta señales de alerta, es porque así fue redactado por quien lo publicó. ADedo.uy no se hace responsable del uso de los resultados.AutorHecha con vibe coding por @porthosuy — MathiasyottEsto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.TikTok: @porthosuy "El que no sabe es como el que no ve."
ADedo.uy existe para que veas.⚖️ Guía para impugnar — tus derechos y los pasos concretos si el proceso fue irregular
📁 Mis llamados — seguimiento personal de tus postulaciones (guardado local, sin servidores)
🤖 Detecta texto transcripto por IA y lo limpia automáticamente antes de analizar
🧪 Lector de PDF por link (fase alfa — puede no funcionar con portales del Estado)
---
Cómo usarla
Abrí `index.html` en tu navegador o entrá a la URL del proyecto en GitHub Pages
Elegí si el llamado es estatal o privado
Pegá el texto de las bases o el llamado completo
Apretá analizar
Si tenés el llamado en PDF, seguí las instrucciones de Gemini que están dentro de la app
No necesita instalación. No necesita servidor. Funciona directo en el navegador.
---
API y créditos
La app usa IA para analizar el texto. Funciona así:
Por defecto usa el servicio gratuito incluido en la app — el usuario no tiene que hacer nada
Si el servicio gratuito se agota, aparece un panel con instrucciones para que el usuario configure su propia key gratuita
Se soportan tres proveedores gratuitos: Groq, Google Gemini y OpenRouter
La key del usuario se guarda solo en su propio navegador — no se envía a ningún servidor
Cómo obtener tu propia key (si la necesitás)
Groq (recomendado — más rápido)
Entrá a console.groq.com
Creá cuenta gratis con tu email
Andá a API Keys y apretá "Create API Key"
Copiá la key (empieza con `gsk_`) y pegala en la app
Google Gemini
Entrá a aistudio.google.com
Iniciá sesión con tu cuenta de Google
Apretá "Get API Key" → "Create API key"
Copiá la key (empieza con `AIza`) y pegala en la app
OpenRouter
Entrá a openrouter.ai
Creá cuenta gratis
Andá a Keys y creá una nueva
Copiá la key (empieza con `sk-or`) y pegala en la app
---
Tecnología
HTML + CSS + JavaScript puro — sin frameworks, sin dependencias
Groq (llama-3.3-70b), Google Gemini o OpenRouter para el análisis — todos gratuitos
pdf.js para lectura de PDFs por link (fase alfa)
localStorage para guardar el historial de llamados y la key del usuario localmente
Todo corre en el navegador del usuario — ningún dato se envía a servidores propios
---
Versión actual
v3 — alfa
Esta es una versión alfa. Puede tener errores, comportamientos inesperados y funciones incompletas. Se acepta cualquier contribución para mejorarla.
Funciones planeadas para próximas versiones
[ ] Módulo "¿qué documentos necesito para anotarme?"
[ ] Generador de carta de presentación adaptada al llamado
[ ] Estimación de tu perfil vs los requisitos del llamado
[ ] Modo preparación para la entrevista
[ ] Base colaborativa de llamados analizados (requiere backend)
[ ] Índice público de transparencia por organismo (requiere backend)
---
Contribuir
Esta app es libre. Si sabés programar y querés sumar, el código es tuyo también.
Para contribuir:
Hacé un fork del repositorio
Creá una rama con tu mejora (`git checkout -b mejora-lo-que-sea`)
Hacé commit de tus cambios
Abrí un Pull Request explicando qué cambiaste y por qué
No hace falta ser programador profesional para contribuir. Podés reportar errores, sugerir mejoras, corregir el glosario o mejorar los textos. Todo suma.
---
Licencia
Creative Commons BY-NC-SA 4.0
Podés usar, modificar y distribuir este código libremente siempre que:
Menciones el origen: @porthosuy (Mathiasyott)
No lo uses para fines comerciales — esta herramienta no se vende ni se privatiza
Lo distribuyas con la misma licencia
El conocimiento no se cobra.
---
Aviso legal
Esta aplicación analiza únicamente el texto que el usuario proporciona y detecta patrones objetivos de redacción. No acusa ni difama a ningún organismo público ni empresa privada. Si un llamado presenta señales de alerta, es porque así fue redactado por quien lo publicó. ADedo.uy no se hace responsable del uso que se haga de los resultados.
---
Autor
Hecha con vibe coding por @porthosuy — Mathiasyott
Esto no lo programó un desarrollador. Lo construyó una persona con ganas usando IA como herramienta. Vos también podés.
TikTok: @porthosuy
---
"El que no sabe es como el que no ve."
ADedo.uy existe para que veas.

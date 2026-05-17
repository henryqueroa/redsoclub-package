# Ads Audit: Redso Club (Meta Ad Library)

**Auditado:** 2026-05-17
**Fuente:** Meta Ad Library, Page ID `108738258530669` (https://www.facebook.com/redsoclubsocial/)
**Método:** Playwright + Chromium persistente (FB session) + Whisper base (transcripción ES) via `Scripts/scraping/scrape_meta_ad_library.py`
**Raw data:** `Clients/Prospects/redsoclub/raw-data/ads/` (ads-manifest.json, videos/, transcripts/)
**Status:** 8 ads activos al momento de la auditoría. Copy verbatim completo, 4 de 5 videos transcritos.

---

## Resumen ejecutivo

- **8 ads activos** corriendo simultáneamente
- **5 son video** (todos lanzados feb 2026, siguen corriendo 87-91 días después)
- **3 son estáticos** (lanzados 24 abr y 15 may 2026: la "refresh wave")
- **4 ads tienen variantes múltiples** (A/B visible: headline + CTA)
- **7 de 8 ads botan al home (`redsoclub.com`)**. Solo Ad 4 va a `redsoclub.com/landing-06-27-2025` (única landing dedicada visible)
- **Ningún ad menciona webinar.** El funnel activo es ad: home/landing: checkout membresía
- **Inconsistencia de números de comunidad:** "200+ creadoras" (ad 15 may), "5,000+ creadoras" (sitio), "+15,000 alumnos" (FB Page bio)
- **CTAs mezclados sin lógica:** Sign Up, Watch more, Learn More

---

## Tabla completa

| # | Library ID | Inicio | Días corriendo | Formato | Variantes | CTA | Destino |
|---|---|---|---|---|---|---|---|
| 1 | 799161875821603 | Feb 16, 2026 | ~91 | Video (0:10) | 1 | Sign up | redsoclub.com |
| 2 | 3703164189825163 | Feb 16, 2026 | ~91 | Video (0:29) | 1 | (sin link card) | (sin destino) |
| 3 | 945598524816845 | Feb 16, 2026 | ~91 | Video (2:44) | 1 | Sign up | redsoclub.com |
| 4 | 1425298645721936 | Feb 17, 2026 | ~90 | Video (0:38) | múltiples | Sign Up | **redsoclub.com/landing-06-27-2025** |
| 5 | 1256002109797023 | Feb 20, 2026 | ~87 | Video (0:58) | 1 | Watch more | redsoclub.com |
| 6 | 4332648643643520 | Apr 24, 2026 | ~23 | Estático | múltiples | Learn More | redsoclub.com |
| 7 | 1461035855719665 | Apr 24, 2026 | ~23 | Estático | múltiples | Learn More | (sin link card capturado) |
| 8 | 1867354043938447 | May 15, 2026 | ~2 | Estático | múltiples | Learn More | redsoclub.com |

---

## Copy verbatim por ad

> Nota técnica: la pieza original de los ads 6 y 8 usa em dashes ( - ) entre frase y precio. En este doc están normalizados a dos puntos por convención interna. La estructura ("Esto no es solo X, Y, Z: $24.95/mes") es fiel al original.

### Ad 1: 799161875821603 (16 feb 2026, video 0:10, ~91 días)

**Copy primario (verbatim):**
> De verdad crees que 100, 1.000 o "solo" 100.000 views es poco?👀
>
> Muchas veces nos enfocamos en el número y se nos olvida lo que realmente representa.
>
> No es poco. Es muchísima gente viendo lo que haces.
> Deja de subestimarte y sigue creando. 🙌🏻
>
> Si quieres aprender a crear y entender cómo crecer, te esperamos en @redsoclub ✨
> 👉🏻Aún no formas parte? Suscríbete 🔗 Link en el perfil 💗

**Transcript:** sin diálogo capturable (audio de 22 chars de gibberish: probablemente música/captions sin voz). Video de 10s = clip corto tipo motion graphic.

**CTA:** Sign up | **Destino:** redsoclub.com
**Hook strategy:** pregunta retórica + reframe del número de vistas. Apunta a creadoras con micro-cuenta que se desmotivan.

---

### Ad 2: 3703164189825163 (16 feb 2026, video 0:29, ~91 días)

**Copy primario (verbatim):**
> Para disfrutar lo grande, primero aprende a disfrutar lo pequeño.🫶🏻
> Los pasos lentos, los avances silenciosos, lo que nadie ve.👀
>
> Grábate esto: tu proceso también vale y también cuenta.✨
>
> Si quieres aprender a crear y avanzar paso a paso, te esperamos en @redsoclub 💗

**Transcript verbatim del video:**
> "Para que puedas disfrutar tus grandes logros tienes que aprender a agradecer y disfrutar los pequeños. Notar las pequeñas metas cumplidas y disfrutar el camino. Porque créeme, siempre que llegues a una meta te vas a poner una nueva. Y no solo se trata de lo que tengas o no tengas esa meta que cumpliste o la que no has cumplido, es la actitud que le pongamos. Y también créeme que si le pones buena actitud se va a ser mucho más fácil, vas a lograr muchas más metas. Y aparte te lo vas a disfrutar."

**Sin link card** (probablemente brand awareness puro).
**Hook strategy:** filosofía/mindset. Lockean creadora en gratitud y proceso. Cero pitch comercial. Apunta a audiencia con burnout/comparación.

---

### Ad 3: 945598524816845 (16 feb 2026, video 2:44, ~91 días)

**Copy primario (verbatim):**
> Si este año te vas a tomar la creación de contenido en serio, este video es para ti.🙌🏻
> @sincerelymvu te comparte 5 ideas de series que pueden ayudarte a crecer en 2026 y empezar con todo.🥳
>
> Quédate hasta el final para verlas todas y elegir la que más se adapta a ti.👀
> Cuando hagas tu serie, recuerda etiquetarnos para verte, apoyarte y comentarte.📝
>
> Síguenos en @redsoclub para no perderte el video del próximo miércoles.💗

**Transcript verbatim (highlights del clip de 2:44):**
> "Si este año sí te vas a tomar tu creación de contenido en serio, este video es para ti. Te voy a dar 5 ideas de videos virales para que empieces este [año] con todo. Bienvenidos a miércoles de series en Redso Club donde todos los miércoles me voy a dar ideas de contenido porque yo sé que tú te quedas sin creatividad."

5 ideas de serie verbalizadas: (1) "El año en que me independizo" (acompañamiento longitudinal), (2) Organización/planificación semanal, (3) "Pequeños hábitos gran cambio", (4) Probar cosas nuevas/enfrentando miedos, (5) Conversación sincera semanal estilo "nombre sin filtro".

**CTA:** Sign up | **Destino:** redsoclub.com
**Hook strategy:** filtro de seriedad ("si te vas a tomar X en serio") + autoridad de María Valeria + value-first content (5 ideas tangibles). Es el video con más duración y más detalle: pieza pillar.

---

### Ad 4: 1425298645721936 (17 feb 2026, video 0:38, ~90 días, variantes múltiples)

**Copy primario (verbatim):**
> Al igual que @Gabrielarbueaty
> ¿Quién dice que debes cambiar?
> Se trata de potenciar tu seguridad interior.
> • Sé más audaz
> • Siente la confianza
> Y verás cómo todo cambia a tu alrededor.

**Headlines (variantes A/B):**
- "La versión de ti que estabas esperando."
- "No es solo cómo te ves. Es cómo te sientes."

**Transcript verbatim (testimonio de Gabriela):**
> "Esta es mi historia en Redso. Comencé creando contenido con cosas que ya tenía y un año después estoy trabajando con marcas reconocidas como Garnier, Nutricina, Loreal, Armani, entre otras. Inicié en el 2016 y ya tengo 10 [años]. Me hizo salir de mi zona de confort, me realicé maquillajes que jamás pensé que podría hacerlo y de eso se trata. De atreverse y creer. Y es que gracias a todo ese esfuerzo las marcas comenzaron a verme, a comentar mis videos y contactarme. En Redso tú encontrarás cursos de cómo trabajar con marcas y en este gran club también encontrarás muchas personas como tú que quieren dedicarse. Y te regalo este mensaje: 'Sé tú misma para que la gente que te está buscando te pueda encontrar.' Repite eso."

**CTA:** Sign Up | **Destino:** `redsoclub.com/landing-06-27-2025` (única landing dedicada)
**Hook strategy:** testimonio social proof + reframe (no cambiar, potenciar) + concreto/aspiracional (marcas tangibles). Esta ES la pieza que merece su propia landing y la tiene.

---

### Ad 5: 1256002109797023 (20 feb 2026, video 0:58, ~87 días)

**Copy primario (verbatim):**
> Te esfuerzas grabando…
> Editas perfecto…
> Y cuando lo subes se ve pixelado 😩
>
> No es tu cámara.
> Es Instagram y tus configuraciones.🔧
>
> Aquí te explicamos cómo mantener la mejor calidad posible en tus videos paso a paso ✨
>
> Guárdalo y actívalo hoy mismo.
> Si creas contenido, esto es básico.🔥💪🏼
>
> Más recursos así dentro de @redsoclub 💗

**Transcript verbatim (tutorial de 58s):**
> "Si tu video se ve borroso o pixelado, aquí te muestro exactamente cómo arreglarlo. Asegúrate de tener estos settings prendidos. Vas a ir a los settings de tu teléfono, y cuando vayas a Cámara, vas a poner la resolución en 4K por 30 frames per second. Mucha gente piensa que 4K por 60 es la mejor resolución, pero es mentira. Simplemente son los frames per second, no hace que ir a ver en mejor calidad si lo ponen en 60. Yo lo mantengo en 30. Está comprobado que 30 frames per second es la mejor opción. Después, apaga el HDR, porque Instagram no lo está tolerando muy bien y más bien hace que tu video se vea de menor calidad. Y presta bastante atención que para mí esta es la más importante. Te vas a los settings de tu Instagram, vas a bajar y le vas a dar clic a Media Quality. Cuando estés ahí, vas a tener tres opciones, vas a prender la que dice 'upload to highest quality'. Esta es la que le va a dar la mejor resolución a tu video en Instagram. Si quieren más tips de este estilo, guarden este post y síguanos aquí en la cuenta de Redso."

**CTA:** Watch more | **Destino:** redsoclub.com
**Hook strategy:** problema tangible + reframe del culpable (Instagram, no tu cámara) + solución específica enseñada en 58s. Este es el hook con mejor combinación de problema-pico + solución-tactica del lote. Replicable: una serie entera de tactical tutorials del mismo formato.

---

### Ad 6: 4332648643643520 (24 abr 2026, estático, ~23 días, variantes múltiples)

**Copy primario (normalizado, ver nota arriba):**
> Esto no es solo contenido. Es dirección, comunidad y estructura: por $24.95/mes.

**Headlines (variantes):**
- "Todo esto por $24.95/mes"
- "Únete hoy a RedsoClub"

**CTA:** Learn More | **Destino:** redsoclub.com
**Hook strategy:** anti-pitch ("no es solo X, es Y") + precio explícito en primer mensaje (filtro de presupuesto). Es la pieza que cambia el formato de feb (video largo de valor) a estático corto con precio. Sugiere que están buscando intent-cualificado.

---

### Ad 7: 1461035855719665 (24 abr 2026, estático, ~23 días, variantes múltiples)

**Copy primario (verbatim):**
> No necesitas motivación. Necesitas constancia. 👀
>
> El progreso real se construye con días normales.
>
> Eso es Redso Club: un espacio donde la constancia se vuelve inevitable. Plan, acompañamiento y comunidad para avanzar. ✅
>
> ¡Entra ahora y únete! 🙌🏼

**Headlines (variantes):**
- "¡Únete a Redso Club!"
- "No necesitas motivación. Necesitas constancia. 👀..."

**CTA:** Learn More | **Destino:** sin link card capturado en el DOM (probable que falte el destino o use redirect distinto)
**Hook strategy:** quote-style/aphorism. Reframe del trabajo creativo (constancia > motivación). Resuena con audiencia que ya intentó y falló por inconsistencia.

---

### Ad 8: 1867354043938447 (15 may 2026, estático, ~2 días, variantes múltiples): MÁS RECIENTE

**Copy primario (normalizado, ver nota arriba):**
> 200+ creadoras creciendo juntas. Comunidad activa y un camino claro: por $24.95 al mes.

**Headlines (variantes):**
- "Un club que te acompaña"
- "Entra a RedsoClub hoy"

**CTA:** Learn More | **Destino:** redsoclub.com
**Hook strategy:** prueba social específica ("200+") + precio + soft community angle. El "200+ creadoras" es inconsistente con "5,000+" del sitio y "+15,000 alumnos" del FB Page. Probable que sea cohort activo de la membresía y no total histórico, pero crea fricción de credibilidad.

---

## Insights críticos para outreach

1. **Fatiga creativa activa.** Los Ads 1-5 (5 videos UGC) llevan 87-91 días corriendo. Estándar de industria recomienda refresh creativo cada 14-21 días en cuentas escaladas. La cuenta está dejando dinero sobre la mesa o aceptando CPM/CPA crecientes. Library IDs verificables: `799161875821603`, `3703164189825163`, `945598524816845`, `1425298645721936`, `1256002109797023`.

2. **Migración formato feb → abr/may.** feb=todo video UGC con valor educativo. abr/may=todo estático con precio frontal. Sugiere que el CPA del video subió y están probando formatos más baratos para mantener volumen. Sin acceso al ad account no se puede confirmar.

3. **Inconsistencia de prueba social:** "200+ creadoras" (ad 15 may) vs "5,000+" (sitio) vs "+15,000 alumnos" (FB Page bio). Cada número por separado funciona; juntos en la journey del usuario (ad → sitio → FB) erosionan confianza. Recomendación: estandarizar a una sola métrica documentada.

4. **Una sola landing dedicada (Ad 4 → `/landing-06-27-2025`).** Los otros 7 ads botan al home. Eso es un gap obvio: cada hook merece su landing congruente con el ángulo. Para Ad 5 (pixelado), Ad 6 (precio), Ad 8 (comunidad), Ad 2 (mindset): cada uno con landing dedicada elevaría conversion rate post-click.

5. **CTAs mezclados sin lógica de funnel.** Sign Up, Watch more, Learn More. Cada CTA tiene psicología distinta y dispara evento de Meta distinto. Mezclarlos sin pixel/event mapping confunde el algoritmo sobre el evento objetivo. Recomendación: estandarizar Learn More para frio, Sign Up para warm/retarget.

6. **Ningún funnel webinar.** El funnel real es: ad → home (o landing-06-27-2025) → checkout membresía. La sección de webinar del homepage es cascarón legacy.

7. **Hook ganador a replicar: Ad 5 (pixelado).** Problema tangible y específico + reframe culpable + tutorial tactical en 58s. Merece una serie completa: cada video con un problema específico de creator (mal audio, mala iluminación, baja retención, hashtags, hora de subir, etc.). Es la fórmula más replicable del lote.

8. **Variantes A/B presentes en 4 de 8 ads (50%).** Las variantes prueban headline y CTA, no el cuerpo del copy. Eso significa que están optimizando para CTR pero no para post-click conversion (donde está la ganancia más grande).

---

## Próximos pasos (cuando entre la llamada)

- Llevar resumen de fatiga creativa (5 videos 87-91 días) como hook duro de outreach
- Citar Library ID `1256002109797023` (pixelado) como ejemplo de hook que merece serie
- Mencionar inconsistencia de prueba social (200/5K/15K) como quick win
- Ofrecer: 3-5 nuevos hooks UGC + landing dedicada por hook + pixel cleanup

---

**Raw data location:**
- Manifest: `Clients/Prospects/redsoclub/raw-data/ads/ads-manifest.json`
- Videos: `Clients/Prospects/redsoclub/raw-data/ads/videos/{library_id}.mp4`
- Transcripts: `Clients/Prospects/redsoclub/raw-data/ads/transcripts/{library_id}.txt`

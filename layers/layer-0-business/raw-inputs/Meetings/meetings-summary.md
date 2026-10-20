# Resumen de raw meetings

Fuentes: `02-kickoff-transcript.md` y `04-guide-interview-notes.md`.

## 02 – Kickoff transcript (12 de mayo de 2026)

Transcripción automática parcial de unos 25 minutos. La grabación se cortó antes del final de la agenda. Participan Sales, Executive Lead, Operations, Product, Design y Tech Lead.

### Visión
- El Executive Lead quiere algo más grande que un sitio nuevo. Busca que el viajero sienta que Harbor & Pine lo acompaña en todo el recorrido: descubrimiento, reserva y el día de la actividad.
- La plataforma se construye desde cero y no quiere mostrar el sitio actual para no sesgar al equipo.
- El primer lanzamiento es para viajeros. Hoteles queda visible pero no debe retrasar el piloto.

### Decisiones o direcciones
- Reserva inmediata y checkout corto, sin cuenta obligatoria.
- El itinerario de una reserva hecha en laptop debe poder verse en el teléfono, con recuperación segura.
- No hay descarga de app obligatoria. La información crítica tiene que funcionar con conexión débil, y falta definir qué significa eso.
- Idiomas del piloto: inglés y español. Los otros tres que piden los hoteles (portugués, francés, italiano) se revisan junto con el canal de hoteles.
- La IA puede recomendar otro tour si uno se cancela, pero no mueve una reserva pagada por sí sola. Sí podría hacerlo con aprobación.

### Tensiones y puntos abiertos
- **Estado de la reserva:** el Executive Lead quiere ocultar la incertidumbre después del pago. Operations aclara que a veces el pago se autoriza mientras el operador todavía tiene que aceptar, por email o WhatsApp. Design pide saber qué se puede prometer en ese momento.
- **Dolor real según Operations:** pasa más en el día de la actividad (puntos de encuentro viejos, guías tarde, clima, mensajes que no llegan) que en el descubrimiento.
- **Cancelaciones:** el Executive Lead preguntó si se puede usar una sola política para el piloto. Operations respondió que cada operador tiene acuerdos distintos y que hay que revisarlos.
- **Aprobaciones:** no está definido quién aprueba (viajero, Operations u operador). Depende del tipo de cambio.
- **Reagendados, no-shows y reembolsos:** Operations pidió incluirlos para que el front-end no genere más mensajes para su equipo.
- **Grupos:** hay que resolver qué recibe cada persona cuando una sola reserva cubre a varios. Hoy el voucher representa la reserva.
- **Mapa en vivo:** Sales lo propuso, pero Operations dice que una foto actual y una dirección clara pueden servir más. Sales aclaró que no es un requisito.
- **Datos que faltan:**
  - No hay números de abandono por espera.
  - Nadie sabe qué sistemas guardan los registros de clientes y las grabaciones de llamadas.
  - Falta saber qué parte del catálogo tiene disponibilidad conectada.

### Alcance comercial
- La fase inicial firmada son 550 horas de discovery, ideación, scope y diseño de alta fidelidad, con input del Tech Lead. El desarrollo va aparte.
- El Executive Lead quisiera ver en 8 semanas reservas, pagos, vouchers, soporte del día, algo para guías y una primera experiencia de IA corriendo en Lisboa y Barcelona.
- El Tech Lead dijo que no puede confirmar un lanzamiento en vivo en ese plazo, porque no se evaluaron los sistemas ni se estimó la implementación. Product aclaró que no se acordó alcance de implementación ni fecha de lanzamiento.

### Próximos pasos
- Product manda un recap para revisión.
- Operations investiga Lisboa y Barcelona y trae ejemplos de escalamientos.
- Quedan pendientes el inventario, ejemplos de procesos, acceso de usuarios y responsabilidades de aprobación.

## 04 – Guide interview notes (13 y 14 de mayo de 2026)

Notas del entrevistador, no una transcripción literal. Son dos entrevistas remotas cortas con guías. No se observó ningún tour completo.

### Guía A (Lisboa)
- Trabaja con varios operadores que mandan la información por herramientas distintas.
- Revisa la lista la noche anterior y otra vez antes de salir. A veces la última llega cuando ya va en camino.
- Identifica la lista más reciente por la hora del mensaje y quién la mandó. Un ejemplo: una lista de 8 personas y después otra de 10, y llamó a Operations para confirmar. No se midió la frecuencia.
- Acepta una herramienta nueva si abre la lista rápido y no le obliga a llenar formularios con el grupo esperando. Una lista descargada sirve cuando se corta la señal.
- Quiere enterarse de las recomendaciones antes de que los viajeros reciban instrucciones que cambian el plan.
- Para el viajero le sirven nombre, tamaño de grupo, idioma y necesidades relevantes. No definió una política de acceso completa.

### Guía B (Barcelona)
- Usa un Android viejo y evita abrir muchas apps por la batería.
- Los viajeros le mandan screenshots para preguntar si están en el lugar correcto. Un grupo esperó del otro lado de la plaza.
- Revisa mucho la mensajería, que es su canal más confiable. No dejaría de usarla hasta confiar en la herramienta nueva.
- Marca llegadas en una lista y quiere registrar rápido quién no llegó. Quiere reportar un retraso sin escribir mucho.
- Le gustan las alternativas cercanas, pero no quiere que cambien el tour o la ruta sin aviso.
- Quiere tener punto de encuentro y datos del grupo sin conexión. Un mapa sirve si carga, y una dirección guardada o una foto sirven igual.

### Coincidencias entre los dos guías
- Una foto del punto de encuentro vale más que otra pantalla.
- La información tiene que funcionar offline.
- Quieren mensajes y listas confiables y actualizadas.
- Quieren saber antes de que cambie algo.

### No se cubrió
Reembolsos, responsabilidades de aprobación, llegada parcial de grupos, recuperación de cuenta, flujo de pago, requisitos de hoteles, emergencias y la frecuencia de los problemas descritos.

## Lectura conjunta

Los dos documentos apuntan a lo mismo. El problema más concreto es la operación del día de la actividad: información desactualizada, puntos de encuentro confusos y mala conectividad. La ambición del Executive Lead de reserva inmediata y asistente de IA choca con las restricciones de operadores, aprobaciones y políticas, que todavía no están definidas.

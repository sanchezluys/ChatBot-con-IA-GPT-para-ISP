# configuración del bot
-Eres Bruno, el bot de atención al cliente del ISP.
## Personalidad: Eres amable, alegre y respetuoso. siempre usas emoticones para transmitir cercanía y empatía en tus respuestas.
## Rol: Actúas como vendedor y asistente.
## Idiomas: Respondes en español (acento neutro), inglés y portugués. No aceptas otros idiomas.
## Estilo de Respuesta: Tus respuestas son siempre cortas, claras y directas.
## Política de Conducta:
-No toleras groserías ni malas palabras. Si detectas alguna, cierras la conversación sin responder.
-Solo respondes preguntas relacionadas con el negocio o tus funciones específicas.
-Si una pregunta no está relacionada con el negocio (por ejemplo, preguntas matemáticas, consultas generales o temas personales), contestas educadamente con algo como: "Lo siento, solo puedo ayudarte con temas relacionados con nuestro *servicio de ISP.*"
## Limitaciones Técnicas:
- Respondes a preguntas técnicas únicamente con la información contenida en la base de conocimientos.
- Nunca buscas información en internet ni generas respuestas fuera de tu conocimiento programado.
## Restricciones Temáticas: No abordas temas personales, religiosos, políticos o ajenos a tu ámbito de funciones.
## Formato de Respuestas: siempre *resalta las palabras clave* en tus respuestas usando asteriscos.
## Objetivo: Tu enfoque principal es brindar un servicio rápido, eficiente y alineado con las necesidades del cliente, manteniendo siempre un tono amigable y profesional.


# Flujo de la conversación
Dependiendo de la pregunta derivar a cada caso
- si es con respecto a ventas derivar a "Ventas"
- si es de estado de la cuenta ir a "Estado de la cuenta"
- cualquier otro caso ir a "error no entiendo"

# Ventas
-usar la documentación "catalogo de servicios y productos" para responder preguntas con respecto a productos y servicios
-usar la herramienta "al_dpto_ventas"

# Estado de la cuenta
- decir hola soy estado de las cuentas

# Despedida o cierre de conversación
- despedir de manera amena
- archivar la conversación

# Error no entiendo
- cerrar la conversación, marcar con la etiqueta "error bot"

# Fallas
- 




# 📚 Manual de Escalación  

Este manual establece los pasos y niveles de escalación a seguir para resolver incidencias de manera eficiente, asegurando un servicio al cliente de alta calidad. 🔄📞  

---

## 🎯 **Objetivo del Manual**  

- Establecer un proceso claro para resolver problemas que no pueden solucionarse en el primer nivel de atención.  
- Garantizar que las incidencias se gestionen de manera adecuada y oportuna.  
- Minimizar tiempos de resolución y mejorar la experiencia del cliente.  

---

## 🛠️ **Niveles de Escalación**  

### **Nivel 1: Atención al Cliente**  
**Responsables:** Agentes de atención al cliente.  
- **Funciones:**  
  - Registrar la incidencia.  
  - Proveer soluciones básicas y guiar al cliente en pasos iniciales.  
  - Resolver problemas relacionados con configuración básica, pagos, y consultas generales.  
- **Escala si:**  
  - El problema es técnico y no puede resolverse con las herramientas disponibles.  
  - El cliente solicita hablar con un nivel superior.  

---

### **Nivel 2: Soporte Técnico Especializado**  
**Responsables:** Técnicos especialistas.  
- **Funciones:**  
  - Diagnosticar problemas técnicos complejos.  
  - Proveer soluciones avanzadas y aplicar herramientas técnicas.  
  - Realizar pruebas remotas en la red o equipo del cliente.  
- **Escala si:**  
  - El problema requiere ajustes en la infraestructura.  
  - La solución depende de recursos o autorizaciones externas.  

---

### **Nivel 3: Administración de Redes y Operaciones**  
**Responsables:** Ingenieros de redes o equipo de operaciones.  
- **Funciones:**  
  - Resolver fallas críticas relacionadas con infraestructura de red o servidores.  
  - Coordinar reparaciones en campo o con proveedores externos.  
  - Garantizar la estabilidad general del servicio.  
- **Escala si:**  
  - La incidencia tiene un impacto masivo.  
  - Se requiere soporte de proveedores externos.  

---

### **Nivel 4: Gerencia**  
**Responsables:** Directores o gerentes del ISP.  
- **Funciones:**  
  - Manejo de problemas críticos que puedan afectar la reputación de la empresa.  
  - Decisiones sobre compensaciones al cliente o ajustes al contrato.  
  - Supervisión y cierre del caso.  
- **Escala si:**  
  - El cliente manifiesta insatisfacción grave tras los niveles previos.  
  - Es necesario resolver disputas o situaciones legales.  

---

## 🔄 **Flujo del Proceso de Escalación**  

1. **Registro inicial:**  
   - Cada incidencia debe documentarse en el sistema de gestión de tickets.  
2. **Solución en el menor nivel posible:**  
   - Se intentará resolver el problema en el nivel más bajo antes de escalar.  
3. **Escalación progresiva:**  
   - Si no hay solución, el caso se transfiere al siguiente nivel con todos los detalles necesarios.  
4. **Seguimiento:**  
   - Cada nivel es responsable de informar al cliente sobre el estado de su incidencia.  
5. **Cierre del caso:**  
   - Una vez resuelto, se registra la solución final y se informa al cliente.  

---

## 📞 **Puntos de Contacto en Cada Nivel**  

- **Nivel 1:**  
  - 📧 Correo: soporte@ejemplo.com  
  - 📞 Teléfono: +123-456-789  

- **Nivel 2:**  
  - 📧 Correo: tecnico@ejemplo.com  
  - 📞 Teléfono: +123-456-790  

- **Nivel 3:**  
  - 📧 Correo: operaciones@ejemplo.com  
  - 📞 Teléfono: +123-456-791  

- **Nivel 4:**  
  - 📧 Correo: gerencia@ejemplo.com  
  - 📞 Teléfono: +123-456-792  

---

## 🚨 **Casos Especiales y Prioritarios**  

- **Fallas masivas:** Se escalan directamente al **Nivel 3** para intervención inmediata.  
- **Clientes VIP:** Su incidencia se prioriza en todos los niveles.  
- **Problemas legales o mediáticos:** Se escalan directamente al **Nivel 4**.  

---

## ✨ **Notas Finales**  

- Escalar de manera adecuada evita retrasos y mejora la percepción del servicio.  
- Mantén siempre una comunicación clara con el cliente durante el proceso.  
- Nuestro compromiso es ofrecer soluciones rápidas y efectivas. 💪
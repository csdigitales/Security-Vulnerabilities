# Fomento de la Divulgación Responsable - Implementando la norma del IEFT
Este repositorio tiene como objetivo ser un modelo base para la implementación de las vias de recepción de reportes de vulnerabilidades enviados por técnicos,  empresas, personas naturales e investigadores en ciberseguridad,  conforme al estándar RFC 9116 del IETF mediante el archivo security.txt. 


# Fundamentos del Proyecto y definición
El IETF (Internet Engineering Task Force) es una organización internacional abierta que desarrolla y publica los estándares técnicos fundamentales de Internet, como los protocolos utilizados por los sitios web (HTTP, HTTPS, DNS, TCP/IP, TLS, entre otros).
Estos estándares se presentan en documentos llamados RFCs (Request for Comments), los cuales están disponibles generalmente en archivos .txt y definen con precisión el funcionamiento de diversos aspectos de la red y los servicios web.
El objetivo de estas normas es garantizar que Internet funcione de manera interoperable, segura y abierta, permitiendo que distintos sistemas, aplicaciones y servicios web puedan comunicarse y operar correctamente entre sí.
Una de estas normas es la RFC 9116, que define el estándar para el archivo security.txt: un archivo de texto que los sitios web pueden alojar para informar a investigadores de seguridad cómo reportar vulnerabilidades de forma responsable. Este archivo debe ubicarse en una ruta estandarizada (por ejemplo: https://example.com/.well-known/security.txt) y debe contener información clara de contacto, plazos, mecanismos de cifrado y políticas de divulgación, con el fin de fomentar una gestión proactiva y transparente de incidentes de seguridad.

# Cuáles son los beneficios de la anticipación
Prevenir una acción impulsiva —aunque bien intencionada— por parte de quien detecta una vulnerabilidad es fundamental, ya que nadie mejor que la propia empresa para definir la vía más discreta y adecuada para recibir este tipo de reportes.

# Cómo se beneficia la empresa con esta buena práctica.
*Facilita la detección temprana de fallos antes de que sean explotados.
*La imagen de la empresa se ve favorablemente beneficiada local e internacionalmente.
*Es un paso compatible con marcos normativos como ISO/IEC 27001, NIST y GDPR.
*Minimiza el riesgo de incidentes costosos al facilitar reportes responsables.
*Centralización y dirección adecuada de la información.
*El archivo puede ser detectado por herramientas automatizadas de monitoreo de seguridad.
*La adopción del estándar RFC 9116, fortalece la seguridad técnica de una empresa,  también envía un mensaje claro de compromiso con la transparencia y la ética digital.



# Qué es el Bug Bounty
Es un programa de recompensas y una estrategia de ciberseguridad que permite recibir reportes de errores o vulnerabilidades a cambio de una compensación económica, conforme a la política establecida por la empresa.
Esta política establece el mecanismo para las vulnerabilidades que califican para recompensa, los casos excluidos, así como las condiciones, precios y plazos en que se otorgan dichas compensaciones.
La política se incluye dentro del archivo security.txt, y su redacción es elaborada por CS Digitales, de acuerdo a las necesidades del cliente, previa consulta y validación directa.

# Qué soluciona Cs Digitales
Cs Digitales permite a empresas y organizaciones posicionarse entre aquellas destacadas por sus buenas prácticas en ciberseguridad, a través de la evaluación, desarrollo e implementación del estándar RFC 9116.
El servicio incluye la tercerización completa del proceso: diseño, redacción, ubicación, validación, estandarización y publicación del archivo security.txt, cumpliendo con los requisitos técnicos y estratégicos definidos por la norma.

# Cómo solicitar el servicio
contacto@csdigitales.cl 

Expresa tu interés y tus datos de contacto
security@csdigitales.cl

Una vez de acuerdo, en esta dirección se reciben datos que permiten la recopilación previa de información de interés mutuo, con motivo de la habilitación de security.txt.

# Estructura según normativa del archivo security.txt
Contact: mailto:security@csdigitales.cl
Encryption: https://csdigitales.cl/encryption
Policy: https://csdigitales.cl/politica-coordinada-vulnerabilidades
Acknowledgments: https://csdigitales.cl/agradecimientos
Hiring: https://csdigitales.cl/trabaja-con-nosotros
Preferred-Languages: es, en
Canonical: https://csdigitales.cl/.well-known/security.txt
Expires: 2025-12-31T23:59:00.000

# Navegación en el repositorio
📁 .well-known/
	└── security.txt → Archivo que debe ser ubicado en el directorio Public html, carpeta .well-known/este archivo y formato normado permite 	que sea detectado por motores de búsqueda. Contiene la dirección de cada campo a cumplir, según la norma. Archivo incluido en carpeta 		Canónica.
📁 encryption/
	└── Archivo.asc.pub → contiene una clave criptográfica que se utiliza para proteger la privacidad y la autenticiddad de la información. 	Al copiar el enlace, se abrira el explorador para salvar el archivo.
📁 policy/
└── Index.html → Archivo ubicado en la carpeta politica-coordinada-vulnerabilidades. Contiene un código html que permite su publicación y visualización. Al abrirlo en el navegador contiene la política resumida y simple, fijada por la empresa para, coordinar la recepción de reporte vulnerabilidades.
📁 agradecimientos/
└── Index.html → Archivo ubicado en el directorio Public html, carpeta agradecimiento. Al desplegar la página incluye reconociemientos a personas que han realizado hallazgos o contribuciones destacadas.
📁 trabaja-con-nosotros/
└── Index.html → Archivo ubicado en el directorio Public html, carpeta trabaja-con-nosotros. Al desplegar la página incluye Información sobre oportunidades laborales, colaboración externa o programas de Bug Bounty disponibles, considerados por la empresa.
📁 paso-a-paso/
└── Instructivo.txt→ Instrucciones técnicas para implementar security.txt en un sitio web.
  Cs Digitales le hará llegar al cliente un formulario para recibir la información concerniente a los puntos del 1 al 6.
  La empresa debe suscribir una orden de servicios, que contendrá la siguiente información para la confección del archivo security.txt:
  1 Correo electrónico en el que desea recibir información de seguridad o crítica.
  2 El cliente debe otorgar la clave pública de encriptación.
  3 La política a desplegar se basa en tres puntos fundamentasles:
    Política de divulgación coordinada de Vulnerabilidades, 49 palabras. El cliente recibe una propuesta.
	  Bug Bounty, 73 palabras. El cliente informa si cuenta con servicios de alguna empresa bug bounty. Si no tiene recibe una propuesta.
    Reporte de Incidentes, 32 p. El cliente recibe una propuesta.
    Outbound CVD policy. El cliente recibe una propuesta. 
  4 Agradecimientos, este campo no es obligatorio según la norma. El cliente debe informar, si quiere incluirlo o desestimarlo por el momento.
  5 Trabaja con nosotros, el cliente nos hará saber si gusta incluir el link de la empresa.
  6 Fecha de expiración del archivo. El cliente nos informa la fecha que estime conveniente que es un campo obligatorio.

# Dónde ubicar los archivos del repositorio.
📁 public_html/
├── 📁 .well-known/
│   └── canonical/
│       └── security.txt                 ← Archivo principal requerido por RFC 9116
├── 📁 agradecimientos/
│   └── index.html                       ← Lista de contribuyentes o reconocimientos públicos
├── 📁 politica-coordinada-vulnerabilidades/
│   └── index.html                       ← Política de divulgación responsable
├── 📁 trabaja-con-nosotros/
│   └── index.html                       ← Información para campo Hiring
├── 📁 encryption/
│   └── pgp-key.asc                      ← Clave pública PGP (campo Encryption)
└── 📁 paso-a-paso/
    ├── formulario-cliente.html         ← Recolección de datos necesarios para armar el archivo
    └── orden-de-servicio.html          ← Detalles del servicio que contratan (claro y no intimidante)



  
    








# Contrato de servicios, condiciones, precios y plazos.
# Contacto y Asistencia


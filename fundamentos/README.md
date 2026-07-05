# Fundamentos de Ciberseguridad

## Subtemas
- [x] Qué es la ciberseguridad (CIA: confidencialidad, integridad, disponibilidad)
- [x] Tipos de amenazas (malware, phishing, ransomware, ingeniería social)
- [x] Vectores de ataque comunes
- [x] Conceptos de riesgo, vulnerabilidad y exploit
- [x] Marcos de referencia: NIST, ISO 27001 (básico)

---

## Notas

### Qué es la ciberseguridad

Se le conoce como ciberseguridad a la práctica de proteger sistemas, redes, dispositivos y datos conta accesos no autorizados, ataques o daños. Se sostiene sobre el modelo conocido como triada CIA:

- Confidencialidad: Que la información solo sea accesible para quienes están autorizados a verla.
- Integridad: Que los datos se matengan exactos y no sean alteados sin autoización. Esto implica poteger contra modificación o destrucción indebida de información y garantizar el no repudio y la autenticidad.
- Disponibilidad: Garantizar el acceso opotuno y confiable a la información cuando se necesita.

Este modelo forma la base de estándares y marcos como ISO/IEC 27001 y el NIST Cybersecurity Framework.

### Tipos de amenazas
Dentro de cualquier temario básico en ciberseguridad nos podemos encontrar con las siguietes amenazas:

- **Malvare:** Software malicioso (virus, gusanos, troyanos, ransomware, spyware).
- **Phishing:** Engaño mediante correos, mensajes, o sitios falsos para robar credenciales o infomación.
- **Ransomware:** Cifra los datos de la víctima y pide un rescate para liberarlos.
- **Ingeniería social:** Manipulación psicológica para que la víctima revele información o realice acciones inseguras (pretexting, baiting, tailgating, etc).
  

### Vectores de ataque
Un vector de ataque es el camino o método que usa un atacante para acceder a un sistema, los más tipicos:
- Correos electónicoos (Phishing)
- Contraseñas débiles o filtradas
- Software sin actualizar (vulnerabilidades no parchadas)
- Dispositivos USB o hardwae comprometido
- Redes Wi-Fi inseguras
- Empleados con acceso mal gestionado (insider threats)

### Riesgo, vulnerabilidad y exploit
Estos tres términos se tienden a comfundir mucho, pero tienen diferencias claras:
- **Vulnerabilidad:** Una debilidad en un sistema, software o proceso que podría ser aprovechada.
- **Exploit:** El método o código específico que aprovecha una vulnerabilidad paa causar un efecto no deseado.
- **Riesgo:** La probabilidad de que una amenaza aproveche una vulnerabilidad, combinada con el impacto que eso tendría.

### Marcos de referencia
Los marcos de diferencia (frameworks) dan una estructura rdenada para gestionar la seguridad de una organización:
- **NIST Cybersecurity Framework (CSF):** Organizando en funciones básicas: Identificar, Proteger, Detectar, Responder, y Recuperar (y ahoa también "Gobernar" en la versión 2,0). El draft de NIST CSF 2.0 define "Gobernar" como establecer y monitorear la estrategia de gestión de riesgos de ciberseguridad de la oganización, sus expectativas y su política.
- **ISO/IEC 27001:** Estándar internacioonal para sistemas de gestión de seguridad de la información (SGSI), centrado en gestión de riesgos.

### Fuentes de información
- NIST SP 800-12 Rev. 1 — An Introduction to Information Security: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.1800-28.pdf
- NIST National Cybersecurity Center of Excellence (NCCoE): https://www.nccoe.nist.gov
- CISA (Cybersecurity and Infrastructure Security Agency, EEUU): https://www.cisa.gov/topics/cyber-threats-and-advisories
- ENISA (Agencia de la UE para la Ciberseguridad) — Threat Landscape: https://www.enisa.europa.eu/publications
- MITRE ATT&CK (catálogo de tácticas y técnicas de ataque reales, usado en toda la industria): https://attack.mitre.org
- CISA Known Exploited Vulnerabilities Catalog: https://www.cisa.gov/known-exploited-vulnerabilities-catalog
- NIST Glossary (definiciones oficiales de términos de ciberseguridad): https://csrc.nist.gov/glossary
- CVE (Common Vulnerabilities and Exposures) — catálogo público de vulnerabilidades conocidas: https://www.cve.org
- NIST Cybersecurity Framework (oficial): https://www.nist.gov/cyberframework
- ISO/IEC 27001 (información oficial): https://www.iso.org/standard/27001

# Laboratorios · Fundamentos de Ciberseguridad con Tecnologías Microsoft

Registro de los laboratorios prácticos del curso **Fundamentos de Ciberseguridad con Tecnologías Microsoft** (INFOTEC), orientado a la certificación **SC-900** y a mi transición hacia **Junior Security / SOC Analyst**.

> Todo se realizó en un **entorno de laboratorio** (tenant y suscripción de prueba).

---

## Leyenda de estados

| Símbolo | Estado | Significado |
|:---:|---|---|
| 🟢 | Terminada | Realizada completa y con evidencia |
| 🔵 | En proceso | Realizada en parte o con evidencias pendientes |
| ⚪ | Planeada | Prevista para ampliar lo aprendido |

## 📊 Resumen de avance

| 🟢 Terminadas | 🔵 En proceso | ⚪ Planeadas | Total |
|:---:|:---:|:---:|:---:|
| 3 | 18 | 4 | 25 |

---

## 01 · Azure y fundamentos de nube

Laboratorios prácticos orientados a comprender la estructura de Azure y a desplegar aplicaciones web en la nube con GitHub.

| Laboratorio | Descripción | Estado |
|---|---|---|
| [01-WordPress-App-Service-Admin-Hash](./01-Azure-Fundamentals/01-WordPress-App-Service-Admin-Hash/) | Despliegue de WordPress en App Service y revisión de la directiva de regiones permitidas y administración de WordPress y phpMyAdmin, escalado del plan y cálculo de un hash SHA-256 en PowerShell | 🟢 Terminada |
| [02-Static-Web-App](https://github.com/Deni-0295/mi-primera-app-con-microsoft-azure) | Primera app: repositorio desde plantilla, `git clone`, despliegue en Azure y ciclo editar → commit → sincronizar | 🟢 Terminada |
| [03-CRUD-Kudu](./01-Azure-Fundamentals/03-CRUD-Kudu/) | Despliegue de un proyecto CRUD en App Service subiendo archivos con Kudu | 🟢 Terminada |
| [04-Custom-Domain-DNS](./01-Azure-Fundamentals/04-Custom-Domain-DNS/) | Configuración de dominio personalizado con registros DNS A y TXT, verificado con `nslookup`| 🔵 En proceso |

---

## 02 · Máquinas virtuales y Microsoft Defender

Laboratorios prácticos orientados a desarrollar habilidades de detección, investigación y respuesta ante amenazas desde la perspectiva de un analista SOC.

| Laboratorio | Descripción | Estado |
|---|---|---|
| [01-Windows-VM-RDP](./02-Defender-Labs/01-Windows-VM-RDP/) | Creación de una máquina virtual Windows 10 en Azure y conexión remota por RDP | 🔵 En proceso |
| [02-NSG-Rules](./02-Defender-Labs/02-NSG-Rules/) | Regla de NSG para bloquear el acceso RDP desde una IP específica y verificación del bloqueo | 🔵 En proceso |
| [03-Defender-Onboarding](./02-Defender-Labs/03-Defender-Onboarding/) | Incorporación de la VM a Defender for Endpoint con el script de onboarding y vinculación de identidad | 🔵 En proceso |
| [04-Attack-Simulations](./02-Defender-Labs/04-Attack-Simulations/) | Simulaciones de ataque, análisis de alertas e incidentes y relación con técnicas de MITRE ATT&CK | 🔵 En proceso |
| [05-Incident-Response](./02-Defender-Labs/05-Incident-Response/) | Live Response, aislamiento y liberación del equipo, antivirus remoto y administración de incidentes | 🔵 En proceso |
| [06-Phishing-Simulation](./02-Defender-Labs/06-Phishing-Simulation/) | Campaña simulada de robo de credenciales con Defender for Office 365 y revisión de resultados | 🔵 En proceso |
| [07-Web-Content-Filtering](./02-Defender-Labs/07-Web-Content-Filtering/) | Filtrado de contenido web e indicadores personalizados, verificados desde PowerShell | 🔵 En proceso |
| [08-Linux-WSL-Phishing](./02-Defender-Labs/08-Linux-WSL-Phishing/) | Comandos básicos y permisos en Linux (WSL) y práctica educativa de phishing para entender el ataque desde el lado atacante | 🔵 En proceso |

---

## 03 · Correo y cumplimiento con Microsoft Purview

Laboratorios prácticos orientados a la protección del correo, la prevención de fuga de datos y la conservación de evidencia para investigaciones.

| Laboratorio | Descripción | Estado |
|---|---|---|
| [01-Antiphishing-Policies](./03-Purview-Labs/01-Antiphishing-Policies/) | Revisión del Explorador de correos y creación de una directiva antiphishing con umbral de suplantación | 🔵 En proceso |
| [02-DLP-Credit-Cards](./03-Purview-Labs/02-DLP-Credit-Cards/) | Directiva de DLP para detectar tarjetas de crédito, con notificación al usuario y alerta de gravedad alta | 🔵 En proceso |
| [03-eDiscovery-Cases](./03-Purview-Labs/03-eDiscovery-Cases/) | Creación de un caso y una búsqueda de eDiscovery con orígenes de buzón | 🔵 En proceso |
| [04-Mailbox-Backup-PST](./03-Purview-Labs/04-Mailbox-Backup-PST/) | Exportación de un buzón completo en formato PST con eDiscovery *(Sesión 17)* | 🔵 En proceso |
| [05-Spoofing-Detection](./03-Purview-Labs/05-Spoofing-Detection/) | Prueba de correos suplantados y revisión de su detección y cuarentena en Defender | 🔵 En proceso |
| [06-Retention-Labels](./03-Purview-Labs/06-Retention-Labels/) | Etiqueta de retención que conserva un día y luego elimina, publicada en OneDrive | 🔵 En proceso |
| [07-Communication-Compliance](./03-Purview-Labs/07-Communication-Compliance/) | Directiva de cumplimiento de comunicaciones con revisores, ubicaciones y clasificadores | 🔵 En proceso |
| [08-Audit-Search](./03-Purview-Labs/08-Audit-Search/) | Búsqueda de auditoría por fechas, usuarios y cargas de trabajo | 🔵 En proceso |
| [09-Final-Audit-Report](./03-Purview-Labs/09-Final-Audit-Report/) | Proyecto final: informe de auditoría del tenant con puntuación de seguridad, dispositivos y usuarios en riesgo, incidentes y directivas | 🔵 En proceso |

---

## 04 · Siguientes pasos

Laboratorios prácticos que **no formaron parte del curso**; son mis ideas para ampliar lo aprendido hacia un perfil SOC.

| Laboratorio | Descripción | Estado |
|---|---|---|
| [01-KQL-Advanced-Hunting](./04-Next-Steps/01-KQL-Advanced-Hunting/) | Consultas básicas con KQL para buscar actividad sospechosa en los registros de Defender | ⚪ Planeada |
| [02-Conditional-Access-MFA](./04-Next-Steps/02-Conditional-Access-MFA/) | Creación de una política de acceso condicional con MFA en Entra ID y prueba de sus efectos | ⚪ Planeada |
| [03-Sentinel-Basics](./04-Next-Steps/03-Sentinel-Basics/) | Primeros pasos con Microsoft Sentinel como SIEM en la nube | ⚪ Planeada |
| [04-SOC-Incident-Report](./04-Next-Steps/04-SOC-Incident-Report/) | Informe de un incidente del laboratorio: línea de tiempo, técnicas MITRE y respuesta | ⚪ Planeada |

---

## Herramientas

`Microsoft Defender XDR` · `Defender for Endpoint` · `Defender for Office 365` · `Microsoft Purview` · `Microsoft Entra ID` · `Azure` · `GitHub` · `PowerShell` · `WSL / Linux` · `MITRE ATT&CK`

## Lo más importante que aprendí

- **Defensa en profundidad** y **Zero Trust**: verificar antes de confiar.
- Diferencia entre **alerta** e **incidente**, y cómo priorizar con la gravedad.
- **Seguridad** (Defender) frente a **cumplimiento** (Purview) frente a **identidad** (Entra).
- Prevenir y detectar fugas de datos con DLP, y conservar evidencia con eDiscovery y auditoría.
- Reconocer phishing y spoofing, y cómo ayudan SPF, DKIM y DMARC.

## Nota sobre las evidencias

Las capturas están **recortadas u ocultas** en datos sensibles: IDs de tenant y suscripción, correos, nombres de cuentas y direcciones IP. El tenant del curso es temporal y puede ya no estar disponible.

## Ruta de certificación

**SC-900** → **SC-200** *(planeado)*

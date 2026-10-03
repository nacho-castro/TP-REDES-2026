# Trabajos de Laboratorio - Materia Redes UTN 2026

Repositorio con los 4 trabajos prácticos de la materia **Redes de Datos** del nivel Cuarto de Ingeniería en Sistemas de la Universidad Tecnológica Nacional - Facultad Regional Buenos Aires.

---

## TL1 - Configuración de Switches LAN

**Objetivo:** Comprender y configurar dispositivos switches para el funcionamiento de **Capa 2** en redes Ethernet.

**Temas principales:**
- Conmutación de Capa 2 (switching)
- Configuración básica de switches Cisco (modelo Catalyst)
- VLANs (IEEE 802.1Q) - segmentación de redes lógicas
- Seguridad de puertos (port-security)
- Troncales (trunk) entre switches
- Arquitectura jerárquica: switches de acceso, distribución y núcleo
- Protocolo Spanning Tree (STP, IEEE 802.1D) - switch raíz, puertos raíz/designados/bloqueados
- Agregado de enlaces con LACP (EtherChannel) y balanceo de carga (src-mac / dst-mac)
- Acceso remoto por TELNET y acceso seguro con SSH v2 (desactivación de TELNET)

**Herramientas:** Cisco Packet Tracer (simulador)  
**Tiempo estimado:** 180 minutos

---

## TL2 - Redes Locales Inalámbricas (WLAN)

**Objetivo:** Configurar dispositivos WLAN como Access Points (AP) en modo Bridge (Capa 2) y Router (Capa 3) con prácticas básicas de seguridad.

**Temas principales:**
- Estándares IEEE 802.11 (WLAN)
- Configuración de Access Points (Linksys WRT300N)
- Modo Bridge (conmutación Capa 2) - LAN VENTAS
- Modo Router (conmutación Capa 3) - LAN CENTRAL ↔ LAN Seguridad
- Seguridad WLAN: WPA2-PSK con cifrado AES, SSID oculto, selección de canal
- Direccionamiento IP estático y dinámico (DHCP en el AP)
- Conceptos de Gateway y su impacto en el enrutamiento (análisis con tracert)
- Revisión de firmware como buena práctica de seguridad
- Verificación de servicios (PING, TRACERT, FTP y HTTPS hacia Server Pedidos)

**Herramientas:** Cisco Packet Tracer  
**Tiempo estimado:** 150 minutos

---

## TL3 - Configuración Básica de Routers

**Objetivo:** Implementar enrutamiento en **Capa 3** para conectar redes LAN distantes mediante una WAN.

**Temas principales:**
- Conmutación de Capa 3 (routing)
- Topología WAN: Casa Central (3 routers Local) y 3 sucursales (routers Remoto)
- Direccionamiento IP classless: Subnetting, VLSM y CIDR
- Configuración de interfaces FastEthernet y Serial (encapsulación PPP, clock rate en DCE)
- Enrutamiento dinámico con RIP v2 (passive-interface, redistribute static)
- Tablas de enrutamiento (distancia administrativa, métrica, temporizadores RIP)
- Acceso remoto con SSH v2 y pruebas de TELNET
- Debugging de RIP (`debug ip rip`)
- Access Control Lists (ACL) estándar - filtrado de paquetes IP

**Herramientas:** Cisco Packet Tracer  
**Tiempo estimado:** 120 minutos

---

## TL4 - Configuración Avanzada de Routers y VPN

**Objetivo:** Configurar routers con enrutamiento entre VLANs e implementar una **Red Privada Virtual (VPN)** con un túnel IPSec sitio a sitio entre dos sucursales (Router1 ↔ Router2) a través de un ISP.

**Temas principales:**
- Enrutamiento entre VLANs (inter-VLAN routing) - VLAN 1, 10 y 20
- Enrutamiento dinámico con EIGRP (Sistema Autónomo 1) y ruta por defecto hacia el ISP
- Redes Privadas Virtuales (VPN) sitio a sitio
- IPSec en modo túnel (transform-set AH-SHA-HMAC + ESP-3DES, crypto map)
- Internet Key Exchange (IKE / ISAKMP) - Fase 1 con AES y clave pre-compartida
- Algoritmo Diffie-Hellman (grupo 5)
- Access Control Lists (ACL) extendidas
- "Tunelización" del tráfico de la VLAN 10 y filtrado del resto de las VLANs

**Herramientas:** Cisco Packet Tracer  
**Tiempo estimado:** 120 minutos

---

## Estructura del Repositorio

```
TP-REDES-2026/
├── TL1/
│   ├── TL1-Config_Switch_LAN-2026.pdf    (enunciado)
│   ├── TL1-switch2026.pkt                (archivo simulador)
│   └── Redes TP Lab 1 - Resolución.pdf   (resolución)
├── TL2/
│   ├── TL 2-WLAN-2026.pdf                (enunciado)
│   ├── TL2-WLAN-2026.pkt                 (archivo simulador)
│   └── Redes TP Lab 2 - Resolución.pdf   (resolución)
├── TL3/
│   ├── TL3-Conf_Básica_Routers-2026.pdf  (enunciado)
│   ├── TL3-Routers-2026.pkt              (archivo simulador)
│   └── Redes TP Lab 3 - Resolución.pdf   (resolución)
├── TL4/
│   ├── TL4-Conf_Avanz_Routers_VPN-2026.pdf  (enunciado)
│   ├── TL 4 Configuración avanzada de Routers - CLI  2026.pkt   (archivo simulador)
│   └── Redes TP Lab 4 - Resolucion.pdf      (resolución)
└── README.md

```

---

## Requisitos

- **Cisco Packet Tracer** (versión indicada en laboratorio)
- Conocimientos previos en modelo OSI y redes TCP/IP
- Documentación técnica de Cisco (incluida en los PDFs)

---

## Progresión del Aprendizaje

1. **TL1** → Fundamentos de conmutación (Capa 2)
2. **TL2** → Extensión a redes inalámbricas y seguridad WLAN
3. **TL3** → Introducción a enrutamiento (Capa 3)
4. **TL4** → Enrutamiento avanzado y seguridad de redes (VPN)

---

## Evaluación

Criterios de aprobación (según cada enunciado):
- Ejecución correcta de actividades experimentales y logro de los objetivos técnicos (TL1, TL2, TL4)
- Respuestas satisfactorias a evaluaciones orales individuales (TL1, TL2, TL4)
- Evaluación de configuración en el simulador con calificación SUFICIENTE o MUY BUENO (TL1)
- Práctico en el simulador con lista de comandos y material de consulta (TL3)
- Demostración del funcionamiento mediante PING, TRACERT o navegación web (TL4)

---

**Materia:** Redes de Datos  
**Nivel:** Cuarto año - Ingeniería en Sistemas  
**Institución:** UTN - FRBA  
**Año:** 2026

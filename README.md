# Trabajos de Laboratorio - Materia Redes UTN 2026

Repositorio con los 4 trabajos prácticos de la materia **Redes de Datos** del nivel Cuarto de Ingeniería en Sistemas de la Universidad Tecnológica Nacional - Facultad Regional Buenos Aires.

---

## TL1 - Configuración de Switches LAN

**Objetivo:** Comprender y configurar dispositivos switches para el funcionamiento de **Capa 2** en redes Ethernet.

**Temas principales:**
- Conmutación de Capa 2 (switching)
- Configuración básica de switches Cisco (modelo Catalyst)
- VLANs (IEEE 802.1Q) - segmentación de redes lógicas
- Protocolo Spanning Tree (STP) - prevención de bucles
- Seguridad de puertos (port-security)
- Acceso remoto seguro (SSH y TELNET)
- Troncales (trunk) entre switches

**Herramientas:** Cisco Packet Tracer (simulador)  
**Tiempo estimado:** 180 minutos

---

## TL2 - Redes Locales Inalámbricas (WLAN)

**Objetivo:** Configurar dispositivos WLAN como Access Points (AP) en modo Bridge (Capa 2) y Router (Capa 3) con prácticas básicas de seguridad.

**Temas principales:**
- Estándares IEEE 802.11 (WLAN)
- Configuración de Access Points (WRT300N)
- Modo Bridge (conmutación Capa 2 inalámbrica)
- Modo Router (enrutamiento Capa 3 inalámbrico)
- Seguridad WLAN con WPA2/PSK
- Direccionamiento IP estático y dinámico (DHCP)
- Conceptos de Gateway y enrutamiento
- Firmware y actualización de dispositivos

**Herramientas:** Cisco Packet Tracer  
**Tiempo estimado:** 150 minutos

---

## TL3 - Configuración Básica de Routers

**Objetivo:** Implementar enrutamiento en **Capa 3** para conectar redes LAN distantes mediante una WAN.

**Temas principales:**
- Conmutación de Capa 3 (routing)
- Configuración de interfaces de routers
- Direccionamiento IP con CIDR y Subnetting
- Enrutamiento dinámico con RIP (versión 2)
- Tablas de enrutamiento
- Acceso remoto con SSH
- Debugging de protocolos de enrutamiento
- Access Control Lists (ACL) estándar - filtrado de paquetes IP

**Herramientas:** Cisco Packet Tracer  
**Tiempo estimado:** 120 minutos

---

## TL4 - Configuración Avanzada de Routers y VPN

**Objetivo:** Configurar routers avanzados con enrutamiento entre VLANs e implementar **Redes Privadas Virtuales (VPN)** con IPSec.

**Temas principales:**
- Enrutamiento entre VLANs (inter-VLAN routing)
- Protocolos de enrutamiento dinámico avanzados (EIGRP, IGRP)
- Redes Privadas Virtuales (VPN)
- IPSec en modo túnel
- Internet Key Exchange (IKE) - intercambio de claves
- Protocolos de encriptación (AES) y autenticación (SHA, HMAC)
- Algoritmo Diffie-Hellman
- Access Control Lists (ACL) extendidas
- Filtrado y "tunelización" de paquetes

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
│   ├── TL4-Configuración_Routers-2026.pkt   (archivo simulador)
│   └── Redes TP Lab 4 - Resolución.pdf      (resolución)
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

Cada trabajo incluye:
- Ejecución correcta de actividades experimentales
- Respuestas satisfactorias a evaluaciones orales individuales
- Demostración del funcionamiento mediante pruebas (PING, TRACERT, etc.)
- Configuración automática de dispositivos en el simulador

---

**Materia:** Redes de Datos  
**Nivel:** Cuarto año - Ingeniería en Sistemas  
**Institución:** UTN - FRBA  
**Año:** 2026

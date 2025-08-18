# Nmap: Utilidad, Uso y Justificación de su utilidad en Ciberseguridad

![Logo de Nmap](https://nmap.org/images/sitelogo-nmap-software-llc-168.90.png)

**Figura 1. Logo oficial de Nmap.**

## Introducción

Nmap (Network Mapper) es una herramienta de código abierto ampliamente reconocida en el ámbito de la ciberseguridad. Fue desarrollada inicialmente por Gordon Lyon (Fyodor) y es utilizada para el descubrimiento de redes y auditorías de seguridad. Su versatilidad le ha permitido convertirse en un estándar en el análisis de puertos, servicios y vulnerabilidades, siendo adoptada tanto por profesionales como por investigadores.

## Utilidad de Nmap

Nmap permite obtener información detallada de los dispositivos conectados a una red, identificando hosts activos, puertos abiertos, servicios en ejecución, sistemas operativos e incluso posibles vulnerabilidades (Lyon, 2009). Esta capacidad es fundamental en procesos como:
1. **Administración de redes:** Facilita el inventario de dispositivos y servicios.
2. **Auditorías de seguridad:** Permite detectar configuraciones inseguras y vectores de ataque.
3. **Respuesta a incidentes:** Ayuda a analizar tráfico y verificar compromisos en sistemas.
4. **Investigación académica y forense:** Es utilizado en estudios sobre protocolos y seguridad de redes.

## Uso de Nmap

El uso básico de Nmap consiste en ejecutar escaneos sobre direcciones IP o rangos, su versatilidad permite que sea usada tanto en auditorías ofensivas (pentesting) como en labores defensivas de gestión de seguridad, se detallan los diferentes usos aplicados:

1. **Escaneo de puertos (TCP/UDP):** Identifica posibles puntos de entrada para atacantes [NIST, 2007].
2. **Detección de sistema operativo (OS fingerprinting):** infiere el SO mediante respuestas a paquetes.
3. **Escaneo de servicios (Service version detection):** identifica versiones específicas de software.
4. **Scripting Engine (NSE):** utiliza scripts para detectar vulnerabilidades conocidas, realizar brute force o recolectar información avanzada (Martínez et al., 2020).
Gracias a su flexibilidad, Nmap puede integrarse con herramientas como Zenmap (interfaz gráfica), sistemas de gestión de eventos (SIEM) y entornos de pruebas de penetración como Kali Linux.
5. **Uso académico y profesional:** Es herramienta obligatoria en certificaciones como CEH, OSCP y cursos universitarios [EC-Council, 2022].

## Justificación del uso de Nmap.



## Bibliografía

Lyon, G. F. (2009). Nmap Network Scanning: The Official Nmap Project Guide to Network Discovery and Security Scanning. Insecure.Com LLC.

Conti, G., & Raymond, D. (2017). Penetration Testing: A Hands-On Introduction to Hacking. No Starch Press.

Zheng, Y., Wang, H., & Wu, C. (2019). “Application of Nmap in Network Security Detection.” Journal of Physics: Conference Series, 1239(1).

Martínez, J., Rodríguez, A., & Pérez, L. (2020). “Automated Vulnerability Detection Using Nmap Scripting Engine.” International Journal of Computer Applications, 975–8887.

EC-Council. *Certified Ethical Hacker v12 Official Curriculum*, 2022.   

Scarfone, K., & Mell, P. *Guide to Security Metrics*. NIST, 2007.  
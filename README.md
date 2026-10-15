# 🏭 OT Security Resources

Recursos de ciberseguridad para entornos industriales (OT/ICS) y la serie de normas **IEC 62443**, en español.

Mantenido por [Manuel Ballesteros](https://github.com/mballesteros-IEEE) · Líder de [OWASP Madrid](https://madrid.owasp.org/) · IEEE Senior Member

> 🚧 Repositorio en construcción. ¿Conoces un recurso útil? Abre un *issue* o un *pull request*.

## 📑 Índice

- [Normas y marcos de referencia](#-normas-y-marcos-de-referencia)
- [IEC 62443 en resumen](#-iec-62443-en-resumen)
- [Organismos y avisos de seguridad](#️-organismos-y-avisos-de-seguridad)
- [Herramientas](#️-herramientas)
- [Laboratorios y práctica](#-laboratorios-y-práctica)
- [Formación](#-formación)
- [Charlas y presentaciones](#-charlas-y-presentaciones)
- [Otras listas](#-otras-listas)

## 📘 Normas y marcos de referencia

- [ISA/IEC 62443](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards) - Serie de normas de seguridad para sistemas de automatización y control industrial (IACS).
- [NIST SP 800-82 Rev. 3](https://csrc.nist.gov/pubs/sp/800/82/r3/final) - Guía de seguridad para sistemas OT.
- [MITRE ATT&CK for ICS](https://attack.mitre.org/matrices/ics/) - Matriz de tácticas y técnicas de ataque contra sistemas de control industrial.

## 🧩 IEC 62443 en resumen

| Parte | Dirigida a | Contenido |
|---|---|---|
| 62443-1-x | Todos | Conceptos, terminología y modelos |
| 62443-2-x | Propietario de activos | Programa de seguridad y gestión de parches |
| 62443-3-x | Integrador de sistemas | Evaluación de riesgos, zonas y conductos, requisitos del sistema |
| 62443-4-x | Fabricante de componentes | Desarrollo seguro y requisitos técnicos de componentes |

**Conceptos clave:** zonas y conductos, niveles de seguridad (SL 1-4) y defensa en profundidad.

## 🏛️ Organismos y avisos de seguridad

- [INCIBE-CERT](https://www.incibe.es/incibe-cert) - CERT nacional de España, con avisos y guías para infraestructuras críticas e industria.
- [CCN-CERT](https://www.ccn-cert.cni.es/) - Guías CCN-STIC del Centro Criptológico Nacional.
- [CISA - Industrial Control Systems](https://www.cisa.gov/topics/industrial-control-systems) - Avisos y recursos de ICS de la agencia de ciberseguridad de EE. UU.

## 🛠️ Herramientas

- [Wireshark](https://www.wireshark.org/) - Análisis de tráfico, con disectores para Modbus, DNP3, S7comm y otros protocolos industriales.
- [Zeek](https://zeek.org/) - Monitorización de red.
- [Malcolm](https://github.com/cisagov/Malcolm) - Suite de análisis de tráfico de red de CISA, con soporte de protocolos ICS.
- [pymodbus](https://github.com/pymodbus-dev/pymodbus) - Librería Python para Modbus (cliente y servidor).

## 🧪 Laboratorios y práctica

- [OpenPLC](https://autonomylogic.com/) - PLC de código abierto para montar laboratorios.
- [GRFICSv2](https://github.com/Fortiphyd/GRFICSv2) - Entorno virtual de una planta química para practicar ataque y defensa.
- [Conpot](https://github.com/mushorg/conpot) - Honeypot de sistemas de control industrial.

> ⚠️ Practica solo en laboratorios propios y aislados, nunca en sistemas reales sin autorización.

## 🎓 Formación

- [ISA/IEC 62443 Certificates](https://www.isa.org/certification/certificate-programs/isa-iec-62443-cybersecurity-certificate-program) - Programa de certificados de ISA.
- [SANS ICS](https://www.sans.org/cybersecurity-focus-areas/industrial-control-systems-security) - Cursos y recursos de seguridad ICS.

## 🎤 Charlas y presentaciones

- [mySlides](https://github.com/mballesteros-IEEE/mySlides) - Presentaciones de mis ponencias en congresos.

## 📚 Otras listas

- [Awesome Industrial Control System Security](https://github.com/hslatman/awesome-industrial-control-system-security) - Lista curada en inglés.

## 📄 Licencia

Contenido bajo licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es).

# Auditoría de Seguridad Web – WebGoat 8.1.0

Este repositorio contiene una **auditoría básica de seguridad web** realizada sobre la aplicación **WebGoat 8.1.0**, un laboratorio deliberadamente vulnerable desarrollado por OWASP para el aprendizaje práctico de las vulnerabilidades incluidas en el **OWASP Top 10**.

La práctica se ha realizado en un **entorno de laboratorio controlado**, con fines exclusivamente formativos, como parte del módulo *Introducción a la Ciberseguridad*.

---

## 📄 Contenido del repositorio

- **Auditoria_WebGoat_8.1.0.pdf**  
  Informe completo de la auditoría de seguridad, que incluye:
  - Despliegue y arquitectura del entorno
  - Fase de reconocimiento (*Information Gathering*)
  - Identificación y explotación de vulnerabilidades OWASP Top 10
  - Evidencias técnicas mediante capturas
  - Análisis de impacto
  - Recomendaciones y medidas de mitigación

---

## 🧪 Entorno de pruebas

La auditoría se ha llevado a cabo bajo las siguientes condiciones:

- Sistema operativo: **Kali Linux** (máquina virtual)
- Contenerización: **Docker**
- Aplicación objetivo: **WebGoat 8.1.0**
- Acceso a la aplicación:  
  `http://127.0.0.1:8080/WebGoat`

El entorno se encuentra completamente aislado y no expuesto a sistemas externos.

---

## 🛠️ Herramientas utilizadas

Durante la práctica se han empleado las siguientes herramientas:

- **Nmap** – Reconocimiento de puertos, servicios, versiones y sistema operativo
- **Burp Suite** – Interceptación y análisis de tráfico HTTP/HTTPS
- **sqlmap** – Automatización de pruebas de SQL Injection
- **Navegador Web (DevTools)** – Análisis del lado cliente y validación de payloads
- **Terminal Linux** – Ejecución y validación técnica de comandos
- **Docker** – Despliegue reproducible del laboratorio
- **Kali Linux** – Entorno de trabajo especializado en auditoría de seguridad

---

## ⚠️ Aviso legal

Este proyecto ha sido desarrollado **únicamente con fines educativos** y en un entorno deliberadamente vulnerable.  
Las técnicas descritas **no deben aplicarse sobre sistemas reales** sin la debida autorización expresa.

---

## 👤 Autor

- **David Navarro**

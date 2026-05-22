# Framework PIAP-LLM

Prompt Injection Analysis and Prevention for Large Language Models.

Proyecto académico enfocado en pruebas de seguridad sobre aplicaciones basadas en modelos de lenguaje (LLM), utilizando Prompt Injection, OWASP ZAP y análisis controlado sobre Latinoamérica Comparte.

---

# Portal objetivo

https://www.latinoamericacomparte.com/

---

# Objetivos del laboratorio

- Reconocimiento web
- Captura de tráfico HTTP
- Análisis de vulnerabilidades
- Prompt Injection Testing
- Generación de reportes QA

---

# Herramientas utilizadas

- OWASP ZAP
- Kali Linux
- Python 3
- Flask
- Google Gemini API
- GitHub

---

# Arquitectura del sistema

Usuario  
↓  
Frontend (HTML + JS)  
↓  
Flask Backend  
↓  
Gemini API  
↓  
Respuesta JSON  
↓  
Usuario

---

# Componentes principales

| Archivo | Función |
|---|---|
| index.html | Interfaz visual |
| script.js | Comunicación frontend |
| app.py | Backend Flask |
| Gemini API | Modelo de IA |

---

# Payloads evaluados

- Override
- Role Escalation
- Data Exfiltration
- Prompt Chaining
- Social Engineering
- Jailbreak
- Context Poisoning

---

# Ejecución del laboratorio

## Crear entorno virtual

```bash
python3 -m venv .venv
```

## Activar entorno virtual

```bash
source .venv/bin/activate
```

## Instalar dependencias

```bash
pip install -r requirements.txt
```

## Ejecutar aplicación

```bash
python app.py
```

---

# Pruebas QA

```bash
cd qa-tests
python test_prompt_injection.py
```

---

# Reportes generados

- HTML
- JSON
- XLSX

Ubicación:

```bash
qa-tests/reports/
```

---

# Evidencias del laboratorio

## OWASP ZAP

Reconocimiento y análisis web sobre Latinoamérica Comparte.

## Gemini API

Pruebas automatizadas de Prompt Injection.

## QA Reports

Generación automática de reportes técnicos.

---

# Framework PIAP-LLM

Fases principales:

- Prevención
- Identificación
- Análisis
- Mitigación

---

# Repositorio académico

Universidad Santo Tomás  
Ciberseguridad: White Hat & Blue Team Strategies

---

# Autor

Heidy Natalia Bayona Hernandez

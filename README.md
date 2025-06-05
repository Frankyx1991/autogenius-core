# AutoGenius Core

**Versión optimizada de AutoGPT para usar en una máquina virtual con Ubuntu.**

Este proyecto permite instalar y ejecutar una IA local tipo AutoGPT de forma sencilla en tu entorno local.

---

## 🚀 Requisitos

- Python 3.10 o superior
- Git
- Acceso a internet en la VM

---

## 🧠 Instalación rápida

```bash
git clone https://github.com/TU_USUARIO/autogenius-core.git
cd autogenius-core
chmod +x start.sh
./start.sh
```

---

## 🛠️ Personalización

Copia el archivo `.env.example` a `.env` y añade tu clave de OpenAI:

```bash
cp .env.example .env
nano .env
```

Contenido:

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

---

## ▶️ Ejecución manual

```bash
source venv/bin/activate
python3 main.py
```

---

## 📁 Estructura del proyecto

```
autogenius-core/
├── autogpt/              # Lógica base (módulo)
├── main.py               # Archivo principal
├── requirements.txt      # Dependencias
├── start.sh              # Instalación y arranque automático
├── .env.example          # Configuración inicial
└── README.md             # Esta guía
```

---

## ✨ Créditos

Proyecto adaptado y optimizado por ChatGPT a partir de [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)


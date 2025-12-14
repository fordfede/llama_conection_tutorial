# 🦙 Tutorial: Conectar LangChain con Llama en Google Colab

Tutorial paso a paso para conectar LangChain con Llama 3.2 usando Google Colab y Hugging Face.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/fordfede/llama_conection_tutorial/blob/main/llama_config.ipynb)

## 📋 Requisitos

- Cuenta de Google (para Colab)
- Cuenta de Hugging Face (gratuita)
- Acceso aprobado a Llama 3.2 en Hugging Face
- 15-20 minutos

## 🚀 Inicio Rápido

1. **Crear cuenta en Hugging Face**: https://huggingface.co/join
2. **Solicitar acceso a Llama**: https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
3. **Crear token de acceso**: https://huggingface.co/settings/tokens
4. **Abrir el notebook en Colab** (botón arriba)
5. **Seguir las instrucciones** del notebook

## 📚 ¿Qué incluye este tutorial?

- ✅ Configuración de autenticación con Hugging Face
- ✅ Instalación de dependencias (LangChain, Transformers)
- ✅ Carga del modelo Llama 3.2 1B Instruct
- ✅ Integración con LangChain
- ✅ Ejemplo de uso básico

## ⚠️ Troubleshooting

### Error: "GatedRepoError" o "401 Unauthorized"
- Verifica que solicitaste acceso en Hugging Face
- Asegúrate de crear el token y guardarlo en Colab Secrets
- Espera unos minutos si acabas de solicitar acceso

### Error: Conflictos de dependencias
- Son warnings normales, puedes ignorarlos
- Si persisten, reinicia el runtime: `Runtime > Restart runtime`

### El modelo repite la pregunta
- Asegúrate de usar `Llama-3.2-1B-Instruct` (con "-Instruct")
- No uses el modelo base sin el sufijo Instruct

## 🔧 Tecnologías

- [LangChain](https://www.langchain.com/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
- [Meta Llama 3.2](https://huggingface.co/meta-llama)
- [Google Colab](https://colab.research.google.com/)

## 📝 Licencia

MIT License - siéntete libre de usar y modificar

## 🤝 Contribuciones

¿Encontraste un error o tienes una sugerencia? Abre un issue o pull request.

---

⭐ Si te fue útil, dale una estrella al repo!

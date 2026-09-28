<h1 align="center">Hola, soy Marc 👋</h1>

<p align="center">
  <b>Gen AI Tech Lead</b> · IA generativa <i>on-device</i> desde Mallorca 🏝️
</p>

<p align="center">
  <a href="https://marcmayol.com/"><img src="https://img.shields.io/badge/Web-marcmayol.com-1f6feb?style=flat-square&logo=astro&logoColor=white"></a>
  <a href="https://huggingface.co/natzx94"><img src="https://img.shields.io/badge/Hugging%20Face-natzx94-FFD21E?style=flat-square&logo=huggingface&logoColor=black"></a>
  <a href="https://twitter.com/srmarcmayol"><img src="https://img.shields.io/badge/X-@srmarcmayol-000000?style=flat-square&logo=x&logoColor=white"></a>
</p>

---

Entreno **LLMs y VLMs** para que corran **en el móvil** y hablen idiomas que los grandes modelos
ignoran. Me muevo por todo el recorrido: construir el dataset, hacer el *fine-tuning* (LoRA,
abliteration, destilación), cuantizar y desplegar *on-device*, y llevarlo hasta una app real.

> Creo que la IA más interesante no está en la nube: está corriendo en tu bolsillo, sin enviar
> tus datos a ningún sitio.

## 🔥 Proyectos destacados

| | Proyecto | Qué es |
|---|---|---|
| 🐉 | **[EsDrac](https://github.com/marcmayol/EsDrac)** | El **primer LLM que habla mallorquí** (*es, sa, ses*), no solo catalán estándar. Qwen2.5-7B abliterado + LoRA, des-censurado y con *tool-calling*. [Modelo en HF ↗](https://huggingface.co/natzx94/EsDrac-v1-7B) |
| 🍽️ | **[Balùa](https://github.com/marcmayol/balua)** | Cuenta las **calorías de un plato desde una foto, 100 % en el móvil**. Qwen2.5-VL-3B destilado (7B→3B) corriendo con llama.cpp. Sin nube, sin subir tus fotos. |
| 🍳 | **[On-Device AI Cookbook](https://github.com/marcmayol/on-device-ai-cookbook)** | Recetas **probadas en la práctica** para entrenar y desplegar IA en local: Blackwell, litert-torch, abliteration, cuantización. Con los errores y los *fixes* reales. |

## 🤝 Contribuciones open source

| | Repo | Contribución |
|---|---|---|
| <img src="https://github.com/microsoft.png" width="20"> | **[microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit)** | Traducción al **español** del README y el Quickstart, integrada en la web de docs. [#3673 ↗](https://github.com/microsoft/agent-governance-toolkit/pull/3673) ![Merged](https://img.shields.io/badge/PR-merged-8957e5?style=flat-square&logo=github) |

## 🛠️ En qué trabajo

- **Fine-tuning** — LoRA, QLoRA, *full fine-tune*, destilación, merges (SLERP), **abliteration**.
- **On-device** — GGUF + llama.cpp, MediaPipe / LiteRT-LM, cuantización int4/int8 para móvil.
- **Lenguas minoritarias** — llevar el mallorquí (y otras lenguas bajo-recurso) a modelos que las hablen de verdad.
- **Hardware de consumo** — todo entrenado en una RTX 5070 Ti (Blackwell, 16 GB); peleándome con lo que aún no funciona en GPUs nuevas.

`PyTorch` · `transformers` · `PEFT / TRL` · `llama.cpp` · `Kotlin / Jetpack Compose` · `Python`

## 📫 Dónde encontrarme

- 🌐 Blog y proyectos → **[marcmayol.com](https://marcmayol.com/)**
- 🤗 Modelos y datasets → **[huggingface.co/natzx94](https://huggingface.co/natzx94)**
- 🐦 X → **[@srmarcmayol](https://twitter.com/srmarcmayol)**

<p align="center"><i>Fet a Mallorca. 🐉</i></p>

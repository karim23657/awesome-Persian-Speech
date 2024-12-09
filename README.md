# Awesome-Persian-Speech [![Awesome](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/00.svg)](https://github.com/karim23657/awesome-Persian-Speech)
A collection of inspiring lists, repos, datasets, models, tools and more for Persian language speech to text (stt) and text to speech (tts) .

# List
- [Awesome-Persian-Speech](#awesome-persian-speech-)
    - [tts tools](#tts-tools)
    - [tts datasets](#tts-datasets)
    - [voice conversion](#voice-conversion)
- [Resources](#resources)
    - [Books](#books)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
    - [Websites](#websites)
- [Contributing](#contributing)

---


# tts tools

*Tools to convert text to speech.*

* [mimic3](https://github.com/MycroftAI/mimic3) - A fast and local neural text to speech system that supports Persian ([Available voices](https://github.com/MycroftAI/mimic3-voices)). [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/Kamtera/persian-tts-mimic3)
* [Persian-tts-coqui](https://github.com/karim23657/Persian-tts-coqui) - Models and demoes and training codes for Persian tts using [🐸 coqui-ai TTS](https://github.com/coqui-ai/TTS) [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/Kamtera/Persian-tts-CoquiTTS)
* [fairseq(mms tts)](https://github.com/facebookresearch/fairseq/tree/main/examples/mms) - TTS models for 1107 languages . [![Hugging Face Model](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/facebook/mms-tts-fas)
* [espeak-ng](https://github.com/espeak-ng/espeak-ng) - Open source speech synthesizer that supports more than hundred languages and accents.
* [tihu](https://github.com/tihu-nlp/tihu) - an open source Persian text-to-speech engine ( better than espeak ).
* [edge-tts](https://github.com/rany2/edge-tts) - Use Microsoft Edge's online text-to-speech service from Python WITHOUT needing Microsoft Edge or Windows or an API key.
* [SeamlessM4T](https://github.com/facebookresearch/seamless_communication) - 35 languages for speech output (Western Persian). [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/facebook/seamless_m4t)
* [pertts](https://github.com/SadeghKrmi/pertts-streamlit) - Very natural voice , can be used with [piper](https://github.com/rhasspy/piper) . [online demo](https://tts.datacula.com/) by [@SadeghKrmi](https://github.com/SadeghKrmi) , [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/k2-fsa/text-to-speech)
* [piper](https://github.com/rhasspy/piper) - A fast, local neural text to speech system , Persian model trained by [@SadeghKrmi](https://github.com/SadeghKrmi) and [@gyroing](https://github.com/gyroing)
* [Persian Piper Model gyro](https://huggingface.co/gyroing/Persian-Piper-Model-gyro) - Persian microsoft edge Farid voice , can be used with [piper](https://github.com/rhasspy/piper) , by [@gyroing](https://github.com/gyroing) , [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/gyroing/Persian_Piper_TTS_HAZM)
* [IMS-Toucan](https://github.com/DigitalPhonetics/IMS-Toucan) - a toolkit for teaching, training and using SOTA Speech Synthesis models. Supports Persian , [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/Flux9665/MassivelyMultilingualTTS)


## Platforms
| Windows <br> <img src="https://github.com/user-attachments/assets/6727ab83-b349-45c5-b962-f07f2c9e7599" width="37"> | Android <br> <img src="https://github.com/user-attachments/assets/316eb5ff-cf5b-4bf9-a212-d0eefe32daae" width="37"> | Web <br> <img src="https://github.com/user-attachments/assets/3dfe1728-f81c-4698-9d8a-e0947aeb860d" width="37"> |
| :-------------: | :--------: | :---: |
| [piper](https://github.com/rhasspy/piper)  | [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)     | [Persian-tts-coqui](https://github.com/karim23657/Persian-tts-coqui) <br> [![Hugging Face Spaces](https://cdn.statically.io/gh/karim23657/blogmaterials/main/assets/hf.svg)](https://huggingface.co/spaces/Kamtera/Persian-tts-CoquiTTS)  |
| [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)   | [MultiTTS app](https://t.me/MultiTTS_channel) |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karim23657/Persian-tts-coqui/blob/main/recepies/vits/test-vits-models.ipynb) |
| | [smart-voice](https://blindhelp.net/software/smart-voice) | |



# tts datasets

*Speech datasets for Persian language.*

* Multispeaker : [parsiGoo](https://github.com/karim23657/parsiGoo) https://huggingface.co/datasets/Kamtera/ParsiGoo
* https://www.kaggle.com/datasets/magnoliasis/persian-tts-dataset
* https://www.kaggle.com/datasets/magnoliasis/persian-tts-dataset-famale
* https://www.kaggle.com/datasets/magnoliasis/persian-tts-dataset-male
* 20 hours : https://huggingface.co/datasets/MahtaFetrat/Quran-Persian
* 86 hours : https://huggingface.co/datasets/MahtaFetrat/Mana-TTS
* https://huggingface.co/datasets/SmartGitiCorp/persian_tts
* 6 hours : [GPTInformal](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)  https://huggingface.co/datasets/MahtaFetrat/GPTInformal-Persian

# voice conversion

*Convert voices in any language to trained voices.*

[🤗 Online Demo](https://huggingface.co/spaces/litagin/rvc_okiba_TTS)

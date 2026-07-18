# Awesome Hugging Face Indonesia

Kurasi model, dataset, library, kursus, dan deployment Hugging Face untuk developer Indonesia.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/ridloabelian/awesome-huggingface-id?style=flat)](https://github.com/ridloabelian/awesome-huggingface-id/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/ridloabelian/awesome-huggingface-id)](https://github.com/ridloabelian/awesome-huggingface-id/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ridloabelian/awesome-huggingface-id/pulls)

> Fokus: resource nyata, open-source, praktis, serta relevan untuk Bahasa Indonesia. Status dan metadata terakhir diaudit pada **18 Juli 2026**.


## Fondasi Resmi

- [Transformers](https://github.com/huggingface/transformers) - Framework definisi model untuk inference dan training pada teks, vision, audio, serta multimodal.
- [Datasets](https://github.com/huggingface/datasets) - Library untuk menemukan, memuat, memproses, dan membagikan dataset machine learning.
- [Tokenizers](https://github.com/huggingface/tokenizers) - Implementasi tokenizer berperforma tinggi dengan dukungan training dan production use.
- [Hugging Face Hub](https://github.com/huggingface/huggingface_hub) - Klien Python untuk model, dataset, dan Spaces pada Hugging Face Hub.
- [Accelerate](https://github.com/huggingface/accelerate) - Abstraksi training dan inference lintas CPU, GPU, TPU, serta distributed environments.
- [Evaluate](https://github.com/huggingface/evaluate) - Library evaluasi model dan dataset dengan metrik yang dapat digunakan ulang.
- [PEFT](https://github.com/huggingface/peft) - Parameter-efficient fine-tuning untuk LoRA dan metode adaptasi model lainnya.
- [TRL](https://github.com/huggingface/trl) - Post-training model bahasa menggunakan SFT, DPO, GRPO, reward modeling, dan metode reinforcement learning.

## Belajar Hugging Face

- [Hugging Face Course](https://github.com/huggingface/course) - Materi resmi untuk mempelajari Transformers, Datasets, Tokenizers, fine-tuning, dan ekosistem Hub.
- [Agents Course](https://github.com/huggingface/agents-course) - Kursus resmi membangun AI agent menggunakan smolagents dan tooling agent modern.
- [Deep RL Course](https://github.com/huggingface/deep-rl-class) - Kursus praktis deep reinforcement learning dengan notebook dan challenge.
- [Audio Course](https://github.com/huggingface/audio-transformers-course) - Materi pemrosesan audio berbasis Transformers.
- [Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - Kursus membangun dan menggunakan diffusion models.

## Agent dan LLM

- [smolagents](https://github.com/huggingface/smolagents) - Library agent minimal yang mendukung code agents, tool calling, sandbox, dan beragam model.
- [Open R1](https://github.com/huggingface/open-r1) - Reproduksi terbuka pipeline reasoning dan post-training DeepSeek-R1.
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) - Server production untuk inference model bahasa Hugging Face.
- [Chat UI](https://github.com/huggingface/chat-ui) - Antarmuka chat open-source yang digunakan untuk HuggingChat.
- [Optimum](https://github.com/huggingface/optimum) - Toolkit optimasi model untuk hardware dan inference runtimes tertentu.

## Generative Media

- [Diffusers](https://github.com/huggingface/diffusers) - Library diffusion models untuk generasi gambar, video, dan audio.
- [PyTorch Image Models](https://github.com/huggingface/pytorch-image-models) - Koleksi besar image encoder, backbone, pretrained weights, serta script training dan inference.
- [LeRobot](https://github.com/huggingface/lerobot) - Model, dataset, dan tooling open-source untuk robot learning.

## Demo dan Antarmuka

- [Gradio](https://github.com/gradio-app/gradio) - Framework Python untuk membuat demo dan UI machine learning yang dapat diterbitkan ke Spaces.
- [Spaces Template](https://github.com/nateraw/spaces-template) - Template Cookiecutter untuk memulai proyek Hugging Face Spaces.
- [GGML Web UI](https://github.com/OpenAccess-AI-Collective/ggml-webui) - Contoh deployment model GGML ke Hugging Face Spaces dengan Docker dan Gradio.

## Bahasa Indonesia

- [IndoNLU](https://github.com/IndoNLP/indonlu) - Benchmark NLU Bahasa Indonesia beserta task, model IndoBERT, dan starter code.
- [IndoNLG](https://github.com/IndoNLP/indonlg) - Benchmark generasi bahasa Indonesia, Sunda, dan Jawa beserta IndoGPT dan IndoBART.
- [IndoLEM](https://github.com/indolem/indolem) - Benchmark NLU Bahasa Indonesia untuk morpho-syntax, semantic, dan discourse.
- [IndoBERTweet](https://github.com/indolem/IndoBERTweet) - Pretrained language model untuk Twitter Bahasa Indonesia.
- [NLP Bahasa Resources](https://github.com/louisowen6/NLP_bahasa_resources) - Kurasi dataset dan library NLP Bahasa Indonesia.
- [Awesome Indonesia NLP](https://github.com/irfnrdh/Awesome-Indonesia-NLP) - Direktori resource NLP dan Bahasa Indonesia.
- [IndoBenchmark Toolkit](https://github.com/indobenchmark/indobenchmark-toolkit) - Toolkit untuk model dan benchmark IndoBenchmark.

## Dataset Indonesia

- [Indonesian Datasets](https://github.com/Wikidepia/indonesian_datasets) - Kumpulan dataset NLP Bahasa Indonesia.
- [Indonesian NLP Resources](https://github.com/kirralabs/indonesian-NLP-resources) - Kumpulan resource data NLP Bahasa Indonesia.
- [Dataset Sentimen Bahasa Indonesia](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia) - Kumpulan dataset analisis sentimen dengan referensi paper terkait.

> Periksa lisensi setiap dataset sebelum penggunaan komersial. Lisensi repository tidak selalu identik dengan lisensi tiap dataset.

## Speech Bahasa Indonesia

- [Multilingual ASR for Indonesian Languages](https://github.com/indonesian-nlp/multilingual-asr) - Riset dan resource speech recognition untuk bahasa-bahasa Indonesia.

## Deployment dan Optimasi

- [Safetensors](https://github.com/safetensors/safetensors) - Format serialisasi tensor yang aman dan cepat dibanding pickle-based formats.
- [Candle](https://github.com/huggingface/candle) - Framework machine learning minimal berbasis Rust dengan fokus performa dan deployment.
- [Optimum Neuron](https://github.com/huggingface/optimum-neuron) - Integrasi Hugging Face untuk AWS Trainium dan Inferentia.
- [Optimum Intel](https://github.com/huggingface/optimum-intel) - Optimasi training dan inference untuk hardware Intel.
- [Optimum AMD](https://github.com/huggingface/optimum-amd) - Optimasi model Hugging Face untuk platform AMD.

## Kurasi Lanjutan

- [Awesome Hugging Face](https://github.com/huggingface/awesome-huggingface) - Daftar resmi proyek dan aplikasi yang terintegrasi dengan library Hugging Face (archived).
- [Awesome Papers](https://github.com/huggingface/awesome-papers) - Paper dan materi presentasi dari internal science day Hugging Face.
- [Awesome Hugging Face Resources](https://github.com/NielsRogge/awesome-huggingface) - Resource komunitas mengenai tooling Hugging Face.

## Kontribusi

Baca [panduan kontribusi](CONTRIBUTING.md). Setiap usulan wajib memiliki tautan aktif, deskripsi faktual, status pemeliharaan yang jelas, serta lisensi yang dapat diperiksa.

---

Terinspirasi oleh ekosistem Hugging Face dan komunitas [awesome](https://github.com/sindresorhus/awesome).

Released under [CC0](LICENSE).

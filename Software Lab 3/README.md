# MIT 6.S191 Lab 3: Fine-Tune an LLM, You Must!

![yoda](https://github.com/MITDeepLearning/introtodeeplearning/raw/2025/lab3/img/yoda_wallpaper.jpg)
In this lab, you will fine-tune a multi-billion parameter large language model (LLM). We will go through several fundamental concepts of LLMs, including tokenization, templates, and fine-tuning. This lab provides a complete pipeline for fine-tuning a language model to generate responses in a specific style, and you will explore not only language model fine-tuning, but also ways to evaluate the performance of a language model.

You will use Google's [Gemma 2B](https://huggingface.co/google/gemma-2b-it) model as the base language model to fine-tune; [Liquid AI's](https://www.liquid.ai/) [LFM-40B](https://www.liquid.ai/liquid-foundation-models) as an evaluation "judge" model; and Comet ML's [Opik](https://www.comet.com/site/products/opik/) as a framework for streamlined LLM evaluation.
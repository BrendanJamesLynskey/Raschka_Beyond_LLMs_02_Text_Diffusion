# Beyond Standard LLMs 02 &mdash; Text Diffusion Models

A companion to Sebastian Raschka's article *[Beyond Standard LLMs](https://magazine.sebastianraschka.com/p/beyond-standard-llms)*. The second of five decks unpacking the four post-transformer architecture families.

This deck takes the **text diffusion** family: LLaDA (the first credible 8B open-weights diffusion LM), Gemini Diffusion (Google's production bet), and the central trade-offs of iterative denoising vs autoregressive next-token prediction. Why parallel decoding gives you 16-64 forward passes for what an autoregressive model needs 2 000 passes for &mdash; and why streaming, conditional dependency, and tool-use all break against the same architectural choice.

Includes an **interactive diffusion-vs-autoregressive visualiser** that fills the same target sentence both ways side-by-side, so you can see the throughput win and the order-of-fill behaviour.

**Live site:** https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_02_Text_Diffusion/

## Companion deck series

| # | Deck | Architecture family |
|---|------|---------------------|
| 01 | [Linear-Attention Hybrids](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_01_Linear_Attention_Hybrids/) | MiniMax-M1, Qwen3-Next, DeepSeek V3.2, Kimi Linear &middot; gated DeltaNet &middot; KV-cache calculator |
| 02 | [Text Diffusion Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_02_Text_Diffusion/) | LLaDA, Gemini Diffusion &middot; iterative denoising &middot; diffusion-vs-AR visualiser |
| 03 | [Code World Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_03_Code_World_Models/) | CWM 32B &middot; world-modelling mid-training &middot; rollout stepper |
| 04 | [Small Recursive Transformers](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_04_Small_Recursive_Transformers/) | HRM, TRM &middot; iterative self-loops &middot; recursive trace viewer |
| 05 | [When to Reach for Non-Transformer](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_05_Decision_Tree/) | Synthesis &middot; decision-tree walker |

Part of the [Modern Architectures sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Modern_Architectures).

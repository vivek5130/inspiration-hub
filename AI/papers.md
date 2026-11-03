# Papers

Landmark AI research papers in timeline order, from the earliest ideas to today's large language models, plus the techniques that make training and running AI faster and cheaper.

[← Back to AI](README.md)

**Jump to:** [Landmark Papers Timeline](#foundations-19502011) · [Training & Inference Optimization](#training--inference-optimization)

<!--
  How to add a paper:
  - Format: - **[Paper Title](https://link)** (Year) – What it introduced and why it matters.
  - Use the exact paper title. Link to arXiv or the official publication page.
  - This file is sorted by DATE, oldest first (not alphabetically). Put the paper in the
    matching section, at its place in time.
  - Papers about making AI faster, cheaper or smaller (quantization, serving, hardware, etc.)
    go in "Training & Inference Optimization" at the bottom. Everything else goes in the timeline eras.
  - New era? Add a new "## Heading" before the optimization section, with the year range in brackets.
  - Search the repository first to avoid duplicates.
-->

## Foundations (1950–2011)

- **[Computing Machinery and Intelligence](https://academic.oup.com/mind/article/LIX/236/433/986238)** (1950) – Alan Turing asks "Can machines think?" and proposes the Turing Test.
- **[The Perceptron: A Probabilistic Model for Information Storage and Organization in the Brain](https://doi.org/10.1037/h0042519)** (1958) – Frank Rosenblatt's perceptron, the first trainable artificial neuron.
- **[Learning Representations by Back-propagating Errors](https://www.nature.com/articles/323533a0)** (1986) – Popularized backpropagation, the method still used to train neural networks.
- **[Backpropagation Applied to Handwritten Zip Code Recognition](https://doi.org/10.1162/neco.1989.1.4.541)** (1989) – Early convolutional neural network (CNN) trained to read handwritten digits.
- **[Long Short-Term Memory](https://doi.org/10.1162/neco.1997.9.8.1735)** (1997) – Introduced the LSTM, letting neural networks remember information over long sequences.
- **[Gradient-Based Learning Applied to Document Recognition](https://doi.org/10.1109/5.726791)** (1998) – LeNet-5 and the MNIST dataset; a blueprint for modern CNNs.
- **[A Neural Probabilistic Language Model](https://www.jmlr.org/papers/v3/bengio03a.html)** (2003) – First neural language model with learned word embeddings.
- **[A Fast Learning Algorithm for Deep Belief Nets](https://doi.org/10.1162/neco.2006.18.7.1527)** (2006) – Showed deep networks could be trained layer by layer, reviving interest in deep learning.

## Deep Learning Takes Off (2012–2016)

- **[ImageNet Classification with Deep Convolutional Neural Networks](https://proceedings.neurips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)** (2012) – AlexNet crushed the ImageNet benchmark using GPUs and started the deep learning boom.
- **[Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)** (2013) – Word2Vec: fast word embeddings where meaning becomes vector math.
- **[Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)** (2013) – DQN learned to play Atari games directly from pixels.
- **[Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)** (2013) – Introduced the variational autoencoder (VAE), a key generative model.
- **[Dropout: A Simple Way to Prevent Neural Networks from Overfitting](https://jmlr.org/papers/v15/srivastava14a.html)** (2014) – Randomly dropping neurons during training to make networks generalize better.
- **[Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)** (2014) – GANs: two networks compete, one generating fakes and one detecting them.
- **[Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)** (2014) – Introduced the attention mechanism for translation.
- **[Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)** (2014) – VGG showed that deeper, simpler CNNs work better.
- **[Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)** (2014) – Seq2Seq: encoder–decoder networks for translation and other sequence tasks.
- **[Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842)** (2014) – GoogLeNet / Inception, an efficient very deep image model.
- **[Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980)** (2014) – Adam, the default optimizer for training most neural networks.
- **[Batch Normalization](https://arxiv.org/abs/1502.03167)** (2015) – Normalizing layer inputs to make deep networks train faster and more stably.
- **[Deep Unsupervised Learning using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585)** (2015) – The original idea behind diffusion models.
- **[U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)** (2015) – U-Net architecture, later the backbone of image diffusion models.
- **[You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)** (2015) – YOLO made object detection fast enough for real time.
- **[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)** (2015) – ResNet's skip connections made networks with 100+ layers trainable.
- **[Mastering the Game of Go with Deep Neural Networks and Tree Search](https://www.nature.com/articles/nature16961)** (2016) – AlphaGo, the first program to beat a professional Go player.
- **[Layer Normalization](https://arxiv.org/abs/1607.06450)** (2016) – Normalization method later used in nearly every Transformer.
- **[WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499)** (2016) – Generated realistic speech one audio sample at a time.

## Transformers & Pre-training (2017–2019)

- **[Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer](https://arxiv.org/abs/1701.06538)** (2017) – Mixture of Experts (MoE): huge models that only use part of themselves per input.
- **[Attention Is All You Need](https://arxiv.org/abs/1706.03762)** (2017) – Introduced the Transformer, the architecture behind today's language models.
- **[Deep Reinforcement Learning from Human Preferences](https://arxiv.org/abs/1706.03741)** (2017) – Training AI from human comparisons; the root of RLHF.
- **[Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)** (2017) – PPO, a simple and stable reinforcement learning algorithm used in RLHF.
- **[Mastering the Game of Go without Human Knowledge](https://www.nature.com/articles/nature24270)** (2017) – AlphaGo Zero learned Go purely by playing against itself.
- **[Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/abs/1712.01815)** (2017) – AlphaZero mastered chess, shogi and Go with one algorithm.
- **[Deep Contextualized Word Representations](https://arxiv.org/abs/1802.05365)** (2018) – ELMo: word meanings that change with context.
- **[Improving Language Understanding by Generative Pre-Training](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)** (2018) – GPT-1: pre-train a Transformer on text, then fine-tune it.
- **[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)** (2018) – BERT set new records on language understanding tasks.
- **[Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)** (2019) – GPT-2 showed one large language model could do many tasks without fine-tuning.
- **[RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)** (2019) – Showed BERT gets much better with more data and careful training.
- **[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)** (2019) – T5 treated every language task as text in, text out.
- **[Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model](https://arxiv.org/abs/1911.08265)** (2019) – MuZero learned to plan without being told the rules of the game.

## Scaling & Large Language Models (2020–2022)

- **[Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)** (2020) – Showed model quality improves predictably with more data, compute and parameters.
- **[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934)** (2020) – NeRF built realistic 3D scenes from a handful of photos.
- **[Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)** (2020) – RAG: let a model look up documents before answering.
- **[Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)** (2020) – GPT-3 showed huge models can learn new tasks from a few examples in the prompt.
- **[Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)** (2020) – DDPM made diffusion models practical for high-quality image generation.
- **[An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)** (2020) – Vision Transformer (ViT) brought Transformers to images.
- **[Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/abs/2101.03961)** (2021) – Simplified Mixture of Experts to scale to a trillion parameters.
- **[Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)** (2021) – CLIP linked images and text, powering image search and generation.
- **[RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864)** (2021) – RoPE, the way most modern LLMs keep track of word order.
- **[Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)** (2021) – Codex, the model behind the first GitHub Copilot, plus the HumanEval benchmark.
- **[Highly Accurate Protein Structure Prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2)** (2021) – AlphaFold 2 largely solved the 50-year-old protein folding problem.
- **[High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)** (2021) – Latent diffusion, the basis of Stable Diffusion.
- **[Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)** (2022) – Asking models to "think step by step" greatly improves reasoning.
- **[Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)** (2022) – InstructGPT: RLHF to make models helpful, the recipe behind ChatGPT.
- **[Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556)** (2022) – Chinchilla showed models should be trained on far more data than before.
- **[PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311)** (2022) – Google's 540-billion-parameter model with strong reasoning abilities.
- **[Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682)** (2022) – Documented skills that appear suddenly as models get bigger.
- **[ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)** (2022) – Models that alternate thinking and taking actions; a foundation of AI agents.
- **[Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)** (2022) – Whisper, a robust open speech-to-text model.
- **[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)** (2022) – Training models to follow a written set of principles using AI feedback.

## Chat Models, Agents & Open Models (2023)

- **[Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)** (2023) – Models that learn when to call tools like calculators and search.
- **[LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971)** (2023) – Meta's LLaMA kicked off the wave of open-weight language models.
- **[GPT-4 Technical Report](https://arxiv.org/abs/2303.08774)** (2023) – OpenAI's multimodal GPT-4 and its performance on exams and benchmarks.
- **[Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366)** (2023) – Agents that improve by reflecting on their own mistakes.
- **[Segment Anything](https://arxiv.org/abs/2304.02643)** (2023) – SAM, a model that can cut out any object in any image.
- **[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)** (2023) – AI characters living, remembering and interacting in a small simulated town.
- **[Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)** (2023) – Exploring several reasoning paths instead of just one.
- **[Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291)** (2023) – An LLM agent that keeps learning new skills in Minecraft.
- **[Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290)** (2023) – DPO, a simpler alternative to RLHF.
- **[Let's Verify Step by Step](https://arxiv.org/abs/2305.20050)** (2023) – Rewarding each reasoning step, not just the final answer, improves math.
- **[Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288)** (2023) – Open chat models available for commercial use.
- **[SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)** (2023) – Benchmark testing whether AI can fix real software bugs.
- **[Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752)** (2023) – A fast alternative to Transformers for long sequences.
- **[Gemini: A Family of Highly Capable Multimodal Models](https://arxiv.org/abs/2312.11805)** (2023) – Google's models built to handle text, images, audio and video together.

## Open Models & Reasoning (2024–2025)

- **[Mixtral of Experts](https://arxiv.org/abs/2401.04088)** (2024) – Mistral's open Mixture of Experts model, strong for its cost.
- **[Scaling Monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/)** (2024) – Found millions of human-understandable "features" inside a production LLM.
- **[The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783)** (2024) – Meta's open models competing with leading closed models.
- **[The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292)** (2024) – An AI system that comes up with ideas, runs experiments and writes papers.
- **[DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437)** (2024) – A frontier-level open model trained at a fraction of the usual cost.
- **[DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)** (2025) – Open reasoning model trained mainly with reinforcement learning.

## Training & Inference Optimization

Papers on making AI models faster, cheaper and smaller to train and run. Each group is in timeline order.

### Hardware

- **[In-Datacenter Performance Analysis of a Tensor Processing Unit](https://arxiv.org/abs/1704.04760)** (2017) – Google's TPU, a custom chip built just for neural networks.
- **[Think Fast: A Tensor Streaming Processor (TSP) for Accelerating Deep Learning Workloads](https://doi.org/10.1109/ISCA45697.2020.00023)** (2020) – Groq's chip, later renamed the LPU (Language Processing Unit); compiler-scheduled and deterministic for very fast inference.

### Training Efficiency

- **[Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174)** (2016) – Gradient checkpointing: recompute some values instead of storing them, to save memory.
- **[Mixed Precision Training](https://arxiv.org/abs/1710.03740)** (2017) – Train in 16-bit numbers instead of 32-bit for roughly 2x speed and half the memory.
- **[GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism](https://arxiv.org/abs/1811.06965)** (2018) – Pipeline parallelism: split a model's layers across many chips.
- **[Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053)** (2019) – Tensor parallelism: split each layer across GPUs to train huge models.
- **[ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://arxiv.org/abs/1910.02054)** (2019) – Shards optimizer state, gradients and weights across GPUs (DeepSpeed).
- **[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)** (2021) – Cheap fine-tuning by training only small add-on weights.
- **[8-bit Optimizers via Block-wise Quantization](https://arxiv.org/abs/2110.02861)** (2021) – Stores optimizer state in 8 bits, cutting training memory a lot.
- **[FP8 Formats for Deep Learning](https://arxiv.org/abs/2209.05433)** (2022) – Standard 8-bit floating-point formats now used in modern GPUs.
- **[QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314)** (2023) – Fine-tuning large models on a single GPU by combining 4-bit weights with LoRA.
- **[Ring Attention with Blockwise Transformers for Near-Infinite Context](https://arxiv.org/abs/2310.01889)** (2023) – Spreads very long sequences across many devices in a ring.
- **[Microscaling Data Formats for Deep Learning](https://arxiv.org/abs/2310.10537)** (2023) – MX formats (like MXFP4): tiny number formats with shared scales for training and inference.

### Faster Attention & Architecture

- **[Fast Transformer Decoding: One Write-Head is All You Need](https://arxiv.org/abs/1911.02150)** (2019) – Multi-Query Attention (MQA): share keys and values to shrink the KV cache.
- **[FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)** (2022) – Made attention much faster by using GPU memory smartly.
- **[GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints](https://arxiv.org/abs/2305.13245)** (2023) – Grouped-Query Attention, the middle ground used by most modern LLMs.
- **[FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning](https://arxiv.org/abs/2307.08691)** (2023) – About 2x faster than FlashAttention through better GPU work splitting.
- **[DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434)** (2024) – Introduced Multi-head Latent Attention (MLA), which compresses the KV cache heavily.
- **[FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision](https://arxiv.org/abs/2407.08608)** (2024) – Uses newer GPU (Hopper) features and FP8 for even faster attention.
- **[Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention](https://arxiv.org/abs/2502.11089)** (2025) – Attention that only looks at the important parts of long inputs, built to be fast on GPUs.

### Quantization & Compression

- **[Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)** (2015) – Knowledge distillation: train a small model to mimic a large one.
- **[Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149)** (2015) – Shrank networks 35–49x by combining pruning and quantization.
- **[The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635)** (2018) – Big networks contain small subnetworks that train just as well.
- **[LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339)** (2022) – Run large models in 8 bits without losing quality by handling outliers separately.
- **[GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://arxiv.org/abs/2210.17323)** (2022) – Compress LLM weights to 3–4 bits after training.
- **[SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](https://arxiv.org/abs/2211.10438)** (2022) – Makes 8-bit weights and activations work by smoothing out outliers.
- **[SparseGPT: Massive Language Models Can Be Accurately Pruned in One-Shot](https://arxiv.org/abs/2301.00774)** (2023) – Removes about half of a large model's weights in one pass.
- **[AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://arxiv.org/abs/2306.00978)** (2023) – 4-bit quantization that protects the most important weights; widely used for local models.
- **[BitNet: Scaling 1-bit Transformers for Large Language Models](https://arxiv.org/abs/2310.11453)** (2023) – Trains language models with 1-bit weights from the start.
- **[KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization](https://arxiv.org/abs/2401.18079)** (2024) – Quantizes the KV cache to enable extremely long contexts.
- **[KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache](https://arxiv.org/abs/2402.02750)** (2024) – Shrinks the KV cache to 2 bits with no fine-tuning needed.
- **[The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits](https://arxiv.org/abs/2402.17764)** (2024) – BitNet b1.58: weights of just -1, 0 or 1 can match full-precision models.
- **[TurboQuant: Online Vector Quantization with Near-optimal Distortion Rate](https://arxiv.org/abs/2504.19874)** (2025) – Google's method to compress the KV cache to about 3 bits with little to no accuracy loss.

### Serving & Decoding

- **[Orca: A Distributed Serving System for Transformer-Based Generative Models](https://www.usenix.org/conference/osdi22/presentation/yu)** (2022) – Continuous batching: add and remove requests at every step to keep GPUs busy.
- **[Fast Inference from Transformers via Speculative Decoding](https://arxiv.org/abs/2211.17192)** (2022) – A small model drafts tokens and a large model checks them, giving 2–3x speedups.
- **[Accelerating Large Language Model Decoding with Speculative Sampling](https://arxiv.org/abs/2302.01318)** (2023) – DeepMind's version of speculative decoding, published independently.
- **[FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU](https://arxiv.org/abs/2303.06865)** (2023) – Run huge models on one GPU by offloading to CPU memory and disk.
- **[H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models](https://arxiv.org/abs/2306.14048)** (2023) – Keeps only the most important tokens in the KV cache.
- **[Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/abs/2309.06180)** (2023) – vLLM, which manages KV cache memory like an operating system, making serving much cheaper.
- **[Efficient Streaming Language Models with Attention Sinks](https://arxiv.org/abs/2309.17453)** (2023) – StreamingLLM: keep a few "sink" tokens to handle endless conversations.
- **[Splitwise: Efficient Generative LLM Inference Using Phase Splitting](https://arxiv.org/abs/2311.18677)** (2023) – Runs the prompt-reading and token-writing phases on different machines.
- **[SGLang: Efficient Execution of Structured Language Model Programs](https://arxiv.org/abs/2312.07104)** (2023) – RadixAttention reuses shared prompt prefixes for faster serving.
- **[DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving](https://arxiv.org/abs/2401.09670)** (2024) – Separates prefill and decoding to meet latency targets more cheaply.
- **[Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads](https://arxiv.org/abs/2401.10774)** (2024) – Extra prediction heads guess several tokens at once, with no separate draft model.
- **[EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty](https://arxiv.org/abs/2401.15077)** (2024) – Faster speculative decoding by drafting at the feature level.
- **[EAGLE-3: Scaling up Inference Acceleration of Large Language Models via Training-Time Test](https://arxiv.org/abs/2503.01840)** (2025) – Latest EAGLE version, with larger speedups that grow with more training data.

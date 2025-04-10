<hr>

<a href="https://github.com/NLPOptimize/awesome-tokenizers">
  <img src="https://github.com/user-attachments/assets/fda66cb0-e785-4e52-bcaf-4deed208a278" align="center" alt="awesome_tokenizers" title="https://github.com/NLPOptimize/awesome-tokenizers">
</a>

<hr>





# Awesome-tokenizer  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A repository with the 🔥 symbol is a tokenizer that is significantly faster than other tokenizers.


## 🔹 **WordPiece Tokenizer Implementations**

* 🔥 **[FlashTokenizer](https://github.com/NLPOptimize/flash-tokenizer)** (C++/Python)
  *  The world's fastest CPU tokenizer library!
- **[huggingface/tokenizers](https://github.com/huggingface/tokenizers)** *(Rust/Python)*
  - Official Hugging Face tokenizer, fast Rust implementation with Python bindings.
- 🔥 **[FastBertTokenizer](https://github.com/kekyo/FastBertTokenizer)** *(C#)*
  - Highly optimized tokenizer for speed, reduced accuracy on non-English inputs.
- **[BertTokenizers](https://github.com/microsoft/BertTokenizers)** *(C#)*
  - Microsoft's original C# tokenizer implementation (slower than FastBertTokenizer).
- 🔥 **[rust-tokenizers](https://github.com/guillaume-be/rust-tokenizers)** *(Rust/Python)*
  - Rust tokenizer library; faster than pure Python but slower than BlingFire or Flash.
- **[tokenizers-cpp](https://github.com/monologg/tokenizers-cpp)** *(C++)*
  - Wrapper around SentencePiece and Hugging Face’s tokenizers; not a standalone implementation.
- **[bertTokenizer (Java)](https://github.com/robrua/easy-bert)** *(Java)*
  - Java-based Bert tokenizer implementation.
- **[ZhuoruLin/fast-wordpiece](https://github.com/ZhuoruLin/fast-wordpiece)** *(Rust)*
  - Rust implementation using LinMaxMatching; likely comparable or slower than optimized C++ versions.
- **[huggingface_tokenizer_cpp](https://github.com/BlinkDL/huggingface_tokenizer_cpp)** *(C++)*
  - Naive pure C++ implementation; slow performance.
- **[SeanLee97/BertWordPieceTokenizer.jl](https://github.com/SeanLee97/BertWordPieceTokenizer.jl)** *(Julia)*
  - Julia implementation, not widely benchmarked.
- 🔥 **[BlingFire](https://github.com/microsoft/BlingFire)** *(C++/Python)*
  - Microsoft's high-speed tokenizer optimized for batch processing, available as Python bindings.
- **[tensorflow-text WordpieceTokenizer](https://github.com/tensorflow/text)** *(C++/Python)*
  - TensorFlow-integrated Google's tokenizer optimized for use in TensorFlow pipelines.
- **[transformers BertTokenizer](https://github.com/huggingface/transformers)** *(Python)*
  - Hugging Face's Python implementation; easy to use but slower due to pure Python nature.
- **[Deep Java Library (DJL) BertTokenizer](https://github.com/deepjavalibrary/djl)** *(Java)*
  - Amazon’s Java implementation, integrated within DJL framework.
- **[tokenizers.net](https://github.com/ScottLogic/tokenizers.net)** *(C#)*
  - .NET/C# binding of Hugging Face tokenizers optimized for .NET runtimes.
- **[Tokenizers.jl](https://github.com/JuliaText/Tokenizers.jl)** *(Julia)*
  - Julia tokenizer library inspired by Hugging Face implementations.
- **[fast-bert-tokenizer-py](https://github.com/kakaobrain/fast-bert-tokenizer-py)** *(Python/Cython)*
  - Python tokenizer accelerated with Cython.
- **[ml-commons/tokenizer](https://github.com/mlcommons/tokenizer)** *(C++)*
  - High-performance C++ tokenizer supporting WordPiece and other algorithms.

------

## 🔹 **BPE (Byte Pair Encoding) Implementations**

- **[OpenAI TikToken](https://github.com/openai/tiktoken)** *(Rust/Python)*
  - Official BPE tokenizer from OpenAI (used in GPT models), highly optimized.
- **[huggingface/tokenizers](https://github.com/huggingface/tokenizers)** *(Rust/Python)*
  - General-purpose tokenizer supporting BPE, from Hugging Face.
- **[bpe-tokenizer (Rust)](https://docs.rs/bpe-tokenizer/latest/bpe_tokenizer/)** *(Rust)*
  - Rust BPE tokenizer library, identifying frequent pairs effectively.
- **[YouTokenToMe](https://github.com/VKCOM/YouTokenToMe)** *(C++/Python)*
  - Efficient BPE tokenizer with fast training and inference, developed by VK.com.
- 🔥  /**[fastBPE](https://github.com/glample/fastBPE)** *(C++/Python)*
  - Facebook’s fast and memory-efficient BPE tokenizer, widely used in NLP research.
- 🔥 **[sentencepiece](https://github.com/google/sentencepiece)** *(C++/Python)*
  - Google's SentencePiece implementation also provides BPE as one of the algorithms.
- **[Subword-nmt](https://github.com/rsennrich/subword-nmt)** *(Python)*
  - Python implementation commonly used in MT research, simple but slower.
- 🔥 **[rs-bpe](https://github.com/gweidart/rs-bpe)** (Rust)
  - A ridiculously fast Python BPE (Byte Pair Encoder) implementation written in Rust
------

## 🔹 **SentencePiece Implementations**

- **[google/sentencepiece](https://github.com/google/sentencepiece)** *(C++/Python)*
  - Google's official, language-independent, neural-based subword tokenizer.
- **[sentencepiece-rs](https://github.com/finalfusion/sentencepiece)** *(Rust)*
  - Rust binding for Google's SentencePiece.
- **[huggingface/tokenizers](https://github.com/huggingface/tokenizers)** *(Rust/Python)*
  - Hugging Face tokenizer library supporting SentencePiece.
- **[TensorFlow Text SentencepieceTokenizer](https://github.com/tensorflow/text)** *(C++/Python)*
  - Google's TensorFlow Text includes SentencePiece tokenizer optimized for TF environments.
- **[sentencepiece.NET](https://github.com/Curiosity-ai/sentencepiece.NET)** *(C#)*
  - .NET binding for SentencePiece tokenizer.
- **[sentencepiece-jni](https://github.com/go-skynet/sentencepiece-jni)** *(Java)*
  - JNI bindings for Google's SentencePiece tokenizer for Java applications.
- **[sentencepiece-swift](https://github.com/xenova/sentencepiece-swift)** *(Swift)*
  - Swift bindings for Google's SentencePiece tokenizer.

------

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](./CONTRIBUTING.md) first.


## Question

Also, if you have any questions, please send a message directly to WeChat, Line, or Telegram below.


<details>
<summary>💬 LINE</summary>


<p align="center">
  <img src="https://github.com/user-attachments/assets/f8bf4afb-7719-4ceb-8baa-8aeb197514ca" width="512" height="512">
</p>



</details>

<details>
<summary>💬 Telegram</summary>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9516c0a3-6268-446e-a526-f0afa11c9a0e" width="512" height="512">
</p>


</details>

<details>
<summary>💬 WeChat</summary>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f8e3a896-1820-47ab-b4f4-9ec0b8741e7d" width="512" height="512">
</p>


</details>




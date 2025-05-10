# Bachelor's thesis
This repository stores the LaTeX code for my bachelor's thesis. It's called `HiPS: Steganography in chat messages using local large language models on Android`. You can download it from the releases.

## Contents
- [Bachelor's thesis](#bachelors-thesis)
- [Abstract](#abstract)
- [Acknowledgements](#acknowledgements)

## Abstract
> While you read this sentence, around one million WhatsApp messages are being sent. We share the details of our personal lives in them, from our highest hopes to our deepest fears. This is only possible because we assume them to be private.
>
> To protect user privacy, we implement an Android app called Hiding in Plain Sight (HiPS). It creates a layer of protection currently missing from popular instant messengers: Steganography. We run large language models (LLMs) locally on the smartphone to encode secret messages into unsuspicious cover texts. Our work is based on the Stegasuras project. We extend its functionality in multiple ways: By porting it to llama.cpp, we are able to swap LLMs to scale with available hardware. We create chat conversations of arbitrarily interleaved cover texts and plain texts, expose a system prompt for easy low-level access to the LLM via natural language, and enrich cover texts with emojis to make them more organic.
>
> To compare our cover texts to real chat messages, we conduct a survey amongst students of TU Darmstadt. This delivers valuable insights in how to fine-tune cover text quality for this highly relevant demographic of users.

Visit [the HiPS repository](https://github.com/tobiasvonderheidt/hips) and try it out!

## Acknowledgements
- The steganography is based on the Stegasuras project ([Paper](https://arxiv.org/abs/1909.01496), [Demo](https://steganography.live/), [Code](https://github.com/harvardnlp/NeuralSteganography)).
- This thesis was written under supervision of the [SEEMOO](https://seemoo.de/) group at [TU Darmstadt](https://www.tu-darmstadt.de/).

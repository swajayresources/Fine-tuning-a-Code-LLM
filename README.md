# Fine-tuning-a-Code-LLM
Publicly available code LLMs such as Codex, StarCoder, and Code Llama are great at generating code that adheres to general programming principles and syntax, but they may not align with an organization’s internal conventions, or be aware of proprietary libraries.

In this notebook, we’ll  show how you can fine-tune a code LLM on private code bases to enhance its contextual awareness and improve a model’s usefulness to your organization’s needs. Since the code LLMs are quite large, fine-tuning them in a traditional manner can be resource-draining. Worry not! We will show how you can optimize fine-tuning to fit on a single GPU.

Model
We’ll finetune bigcode/starcoderbase-1b, which is a 1B parameter model trained on 80+ programming languages. This is a gated model, so if you plan to run this notebook with this exact model, you’ll need to gain access to it on the model’s page. Log in to your Hugging Face account to do

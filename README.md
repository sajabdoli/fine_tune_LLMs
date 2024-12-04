# fine tune LLMs
This repo contains a notebook for fine tuning the LLM based on the [DPO (Direct Preference Optimization)](https://arxiv.org/abs/2305.18290). To reduce the trainable parameters we also incorporate  [LoRA (Low-Rank Adaptation of Large Language Models)](https://huggingface.co/docs/peft/en/package_reference/lora). The model is trained based on [Orca-Direct-Preference-Optimization](https://huggingface.co/datasets/ayoubkirouane/Orca-Direct-Preference-Optimization) which consists of the user choices for a pair of answers from the LLM for a given prompt. 

For a microsoft/phi-2 model there are: trainable params: 4,792,320 || all params: 2,784,476,160 || trainable%: 0.1721

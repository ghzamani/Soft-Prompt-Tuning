# Soft-Prompt-Tuning
Soft prompt tuning is one of the PEFT methods, introduced in [The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/abs/2104.08691). Rather than fine-tuning the entire model, this technique involves adding a soft prompt to the input, with the weights of these soft prompts learned during training.

I implemented this technique from scratch using T5 and the IMDb dataset, achieving an accuracy of 81% on the test set.

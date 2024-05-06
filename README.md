![logo](logo.jpeg)

# quantkitty

inspired by [mlabonne's autoquant](https://twitter.com/maximelabonne/status/1775095198898422072), does not contaminate cross-cell allowing you to quant multiple in one go without restarting the kernel, fixes a few quants, allows for exl-requanting once measurement is done, shows progress during the model download, auto uploads your quant and much more, all in one portable jupyter notebook that can be dropped into a runpod for easy use, no colab required

> [!NOTE]
> make sure to fill out your huggingface `USERNAME` and `HF_TOKEN` (you can create one in your [settings](https://huggingface.co/settings/tokens)) otherwise uploading your quant won't work.

> [!NOTE]
> all quants are uploaded as private, so you can double check before publishing it to your profile

supports:
- exl2 (with fast measurement requant)
- awq
- hqq
- gptq

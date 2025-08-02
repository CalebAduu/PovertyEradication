# PovertyEradication

## Fine-tuned Adapter

The fine-tuned adapter is available here: https://huggingface.co/calebadu/my_finetuned_adapter

You can download and load it using the code snippet below:
```python
# example to load adapter
from transformers import AutoAdapterModel

model = AutoAdapterModel.from_pretrained('calebadu/my_finetuned_adapter')

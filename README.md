# K-Medicon Sub2 
<img a=https://github.com/user-attachments/assets/513dbb0b-d30c-4eb5-abbd-c1e3fc7c3234>

![6e16810003ed246323b65d2ff3b4108a_1723423189_6724](https://github.com/user-attachments/assets/ada0b565-1eb5-45f3-922e-83ee5496dfce)


## Metrics
1. Install python pakcage in your environment (docker, conda, ...)
```
pip install -r requirements.txt
```
- Any Embedding Models can used for simple test when training, but BioLLM will be used for Public Test and Private Test.
- Ref: <a href=https://huggingface.co/aaditya/Llama3-OpenBioLLM-8B> Llama3-OpenBioLLM-8B </a>

2. Download Scispacy Model.
```
pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_core_sci_lg-0.5.4.tar.gz
```
- SpaCy models for biomedical text processing.</br>
- Ref: <a href=https://allenai.github.io/scispacy/>scispacy</a>

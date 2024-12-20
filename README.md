# cog-vicuna-13b-v1.5
cog packaging for vicuna model

This is an implementation of the [lmsys/vicuna-13b-v1.5](https://huggingface.co/lmsys/vicuna-13b-v1.5) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

1. Download the pre-trained weights:
```
    cog run download.py
```

2. Run predictions:
```
    cog predict -i prompt="how many counties in Texas?"
```

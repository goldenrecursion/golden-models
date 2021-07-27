# Model Packaging and Exporting Process

Run the following:

```
export MODEL_DIR
spacy package $MODEL_DIR /opt/pysetup/models --build sdist,wheel --name ceo_model --version 0.0.1
```

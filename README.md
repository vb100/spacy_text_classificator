<h2>Custom Text Classificator with Spacy and Setfit</h2>

<p>This tutorial demonstrates how to quikcly build your custom text classificator with just few new text samples by using Spacy and Spacy Setfit.
You can read more about these frameworks in the following links:
</p>
<ul>
<li><a href="https://spacy.io/">Spacy</a></li>
<li><a href="https://github.com/huggingface/setfit">Spacy SetFit</a></li>
</ul>

<p>You can install these Python packages directly in your terminal with the followin command:</p>

```bash
pip install spacy spacy-setfit
```
<p>It will take 10-20 seconds to install them.</p>

<p>Also, for this tutorial we use the standard Spacy universal English language model (small version). You can download and install it by running the following command in your terminal:</p>

```bash
python3 -m spacy download en_core_web_sm
```

<p>This model will act as a base model we will tune from with our custom train set.</p>

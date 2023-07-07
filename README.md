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

<p>Also, we use Transform released by HuggingFace, and named <b>paraphrase-MiniLM-L3-v2</b> which maps our text into tokens. You can read more about this tokenizer <a href="https://huggingface.co/sentence-transformers/paraphrase-MiniLM-L3-v2">here</a>.</p>

<hr style="border:2px solid gray">

<p><b>If you want to change you career and became advanced data analytic or data scientist, check this awesome <a href="https://turingcollege.org/DataScienceGarage">Turing College</a>!<br>
Meet industry leaders and take your role in the job market with heavy baggage of you skills!<br>
Visit: <a href="https://turingcollege.org/DataScienceGarage"https://turingcollege.org/DataScienceGarage</a>!
</b></p>

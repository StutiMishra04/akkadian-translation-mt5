# Akkadian to English Translation using mt5
<h3>Overview</h3>
<p>This project builds a neural machine translation system to translate Akkadian transliteration into English using transformer models<p>
<h3>Approach</h3>
<ul>
  <li>used mt5 (multilingual transformer) from Huggingface</li>
  <li>Fine-tuned on Akkadian-English Dataset</li>
  <li>Applied tokenization and sequence-to-sequence learning</li>
  <li>Used beam search decoding for inference</li>
</ul>

<h3>Results</h3>
<p>The validation score used was BLEU score equivalent to nearly ~ 15-16. Kaggle score was small as the dataset provided was limited and had generalization gap.</p>

<h3>Challenges</h3>
<ul>
  <li>Very small Dataset (~1500 samples)</li>
  <li>Lack of sentence-level alignment</li>
  <li>Overfitting to training data</li>
  <li>Hidden test set distribution mismatch</li>
</ul>

<h3>Technical Stack</h3>
<ul>
  <li>Python</li>
  <li>Hugging face sentence tranformers mt-5</li>
  <li>PyTorch</li>
  <li>Pandas</li>
</ul>

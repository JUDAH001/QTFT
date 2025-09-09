
# 🎈 Super Simple QTFT (Kid Edition)

A playful, tiny time-series forecaster that “guesses tomorrow from yesterday.”  
Compare 🧠 **Normal Brain** (tiny LSTM) vs 🪄 **Magic Box Brain** (a fun quantum-like layer in PyTorch).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/<YOUR_USERNAME>/<YOUR_REPO>/blob/main/notebooks/QTFT_super_simple_kid_compare.ipynb)

## Why this repo?
- End-to-end ML workflow: data → model → train → evaluate → compare
- Kid-friendly code and explanations
- Zero heavy installs (optional real quantum version via PennyLane)

## Try it in Colab
Click the badge above, then **Run all**.  
Tip: Runtime → Change runtime type → Hardware accelerator: **GPU**.

## What you’ll see
- Learning curves (train/test loss)
- Side-by-side predictions: normal vs magic brain

## Files
- `notebooks/QTFT_super_simple_kid_compare.ipynb` — main notebook with side-by-side compare
- `requirements.txt` — minimal dependencies
- `imgs/preview.png` — screenshot for README

## Install locally (optional)
```bash
python -m venv .env && source .env/bin/activate  # on Windows: .env\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## License
MIT © <YOUR_NAME>

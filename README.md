# Transformers from the Ground Up: Building TinyStories

Hands-on notebooks for the course "Transformers from the Ground Up - Building TinyStories".

You build a small GPT that writes children's stories, from first principles, all on CPU.
Each notebook here matches one lesson in the course. Read the lesson, then run and tweak
the matching notebook in your own Jupyter environment.

## Setup

1. Clone this repo:

   ```
   git clone https://github.com/avisalmon/tinystories-academy.git
   cd tinystories-academy
   ```

2. Create a virtual environment named `env`:

   ```
   python -m venv env
   ```

3. Activate it:

   ```
   Windows:    .\env\Scripts\activate
   Linux/Mac:  source env/bin/activate
   ```

4. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

5. Launch Jupyter:

   ```
   jupyter notebook
   ```

   Open the `notebooks/` folder and start with lesson 01.

## Repo layout

- `notebooks/` one Jupyter notebook per lesson
- `data/` the TinyStories dataset (committed, so everything runs offline)
- `requirements.txt` the Python dependencies

## What you build

Tensors and embeddings, attention, the transformer block, a BPE tokenizer, a full GPT,
the training loop, and text generation. By the end you train a small model of a few
million parameters and generate your own tiny stories.

## Dataset

The `data/stories/` folder holds a sample of the TinyStories dataset by Eldan and Li
(https://arxiv.org/abs/2305.07759), used here for education.

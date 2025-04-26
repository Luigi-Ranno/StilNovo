# StilNovo
Repository containing all the code related to StilNovo, a project where I try to build a language model that can reproduce ancient italian poems.
All of this was purely for didacting purposes, and should not be considered cutting edge or optimized. The goal was to learn more about NLP and how LLMs work.

# Code description
I tried two different attempts: (1) writing my own GPT transformer model, and (2) using a pretrained LLM and fine tuning to apply a style transfer and induce the LLM to produce poems. Training was performed on a macbook (2023) with limited memory, so some compromised were made.


# Data sourcing
I found the data by downloading old poems from ancient italian poets and writers (e.g. Dante Alighieri, Petrarca, etc.). Some text was downloaded from Project Gutenberg (https://www.gutenberg.org/), some from Poetry in translation (https://www.poetryintranslation.com/index.php), Letteraturaitalia (https://www.letteraturaitalia.it/) or similar websites.

# Model
The Language Model design was inspired by the Stanford CS336 course (Language Modeling from Scratch, https://stanford-cs336.github.io/spring2025/)

# Fine tuning
The code that uses a pretrained LLM and fine tunes it utilizes various libraries from Hugging Face, and open source models.

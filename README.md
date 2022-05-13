# Project 2 Generative Audio

Luke Farritor, lfarritor3@huskers.unl.edu

## Abstract

One of my side projects is a guitar-based music installation, called Soundtracks for the Present Future. The installation plays though a playlist of composed songs, stored as MIDI files. However, composing a good piece for the installation is difficult. Because it's a group of guitars with the musical range comporable to that of a piano, replicating that sound using a computer is not straightforward. The easiest way to approximate the sound of the installation is to set your instrument to "Acoustic Guitar" in your DAW, but that only gets you partially there. Each guitar has its own distinct sound, and the acoustics of the room and the mechainics of the installation effect the sound as well. Additionally, the sound of many guitars playing together is very distinct. I'd like to train a network to create an artifical recording of the guitars playing a given midi file. This might be a challenge, because I have a some (but not a huge number) of guitar recordings and their corresponding MIDI files, and I don't have physical access to the guitars to create more recordings and thus a larger dataset.

UPDATE: i got it working by the deadline but it massively overfit - it sounds too much like the original recording, in my opinion. check out the output at sample 5b prompted 2/level 2/index html to see for yourself!

## Model/Data

Briefly describe the files that are included with your repository:
- trained models
- training data (or link to training data)

## Code

Your code for generating your project:
- Python: generative_code.py
- Jupyter notebooks: generative_code.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- `.wav` files or `.mp4`
- `.midi` files
- musical scores
- ... some other form

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts

Please check arch.png (for details somewhat) if this is too long/boring for you to read etc. (though it is quite short)

Part 1 - Introduction

The core idea behind this project is to create accurate soil dynamics for the entirety of Mars to help mitigate punctures, breakages, sinkages and other malfunctions to rovers such as Curiosity and Perseverance. Naturally, these rovers are not explorers in the traditional sense of the word. It seems obvious that if NASA wanted to design an exploratory rover, it certainly could and most assuredly, this paper will not help the people who work there. But so then what is this? and why is this?


Part 2 - The Idea (Step by Step short version)

1. Write a python script for the rover. (Done)
2. Run this rover against known soil composition of the crater/areas where Curiosity "failed".
3. Iterate until validation.
4. Train a neural net on Earth's Mars-like areas using orbital imagery plus thermal imagery to predict soil composition.
5. Validate against known soil compositions of those areas.
6. Run it on the area on mars where we know the soil composition using AI4MARS and THEMIS.
7. Validate the output against known soil composition.
8. Get the entirety of Mars' soil composition.
9. Run our simulated rover on it.
10. Find unusual discoveries.

Part 3 - The Implementation (long and boring)

and.... I will update this soon. One needs only to give me a research lab. Vast.ai gpus do not suffice. 





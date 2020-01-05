# Music_keras

## Generating music with GAN

Learn Generative Adversarial Network (GAN) to generate music.

Some parts can be in Czech, because it was semestral work at Faculty of information technology at Czech technical university in Prague

# How to run this

clone this repository:
```
git clone git@github.com:Hanyman8/Music_keras.git
```
make a virtual environment and install requirements
```
python -m pip install -r requirements.txt
```

in main directory create directories `results`, `static`, `static/classical_midi_piano`


## Data
Download data `clean` = clean_midi, `aligned` = lmd_aligned a `LMD-matched metadata` lmd_matched_h5 from website
https://colinraffel.com/projects/lmd/
and extract them in the folder `static`

Data source: Colin Raffel. "Learning-Based Methods for Comparing Sequences, with Applications to Audio-to-MIDI Alignment and Matching". PhD Thesis, 2016.


## Data preparation
open jupyter notebook `data_datapreparation.ipynb` and run it
Then run ntoebook `music_gan.ipynb`

everythink should work

## Results
Results of generated midi files can be found in the file `results`
Final model cal be saved (showed at the end of the notebook)


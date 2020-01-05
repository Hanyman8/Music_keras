# mvi_sp

## Generování hudby s GANy

Naučte Generative Adversarial Network (GAN) generovat hudbu. Vyberte si, jestli budete generovat pouze noty nebo celou audio stopu.


# Jak to rozběhat

naklonujte si repozitář:
```
git clone git@gitlab.fit.cvut.cz:hanusji8/mvi_sp.git
```
vytvořte si virtuální prostředí a aktivujte ho
HOW TO: https://naucse.python.cz/2019/mipyt-zima/fast-track/install/

nainstalujte balíčky
```
python -m pip install -r requirements.txt
```

v adresáři vytvořte složky `results`, `static`, `static/classical_midi_piano`


## Data
Stáhněte si data `clean` = clean_midi, `aligned` = lmd_aligned a `LMD-matched metadata` lmd_matched_h5 ze stránky
https://colinraffel.com/projects/lmd/
a extrahujte je do složky `static`


## Předzpracování dat
otevřete jupyter notebook a spusťe notebook `data_datapreparation.ipynb`
Pak spusťte notebook `music_gan.ipynb`

a vše by snad mělo fungovat

## Výsledky
Výsledky vygenerovaných midi souborů naleznete ve složce results
Výsledný model se dá uložit (ukázáno na konci notebooku)


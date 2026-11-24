# CORSAIR-FR-16-normalisation

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)


## About
This repository contains line-aligned transcriptions of five early modern French historical texts, each paired with a version normalised to contemporary French spelling. The data were produced within the doctoral project CORSAIR (University of Geneva), funded by the Swiss National Science Foundation (SNSF grant no. 222557). Normalisation data are shared in .txt (only normalised text) and .tsv for a comparative version. The normalisation follows the rules of [FreEM](https://github.com/FreEM-corpora/FreEMnormhttps://github.com/FreEM-corpora/FreEMnorm)

## Contents

This repository contains:
| Author | Year | Title (short) |  NB of lines|
|--------|------|---------------|-------|
| Louis Régnier de La Planche  | 1576  | *Histoire de l'estat de France* | 770  |
| Simon Goulart  | 1578 | *Mémoires de l'Estat de France sous Charles Neufiesme*  | 1147 |
| Lancelot Voisin de La Popelinière  | 1572 | *La vraye et entiere histoire des troubles et choses memorables*  | ?? |
| Lancelot Voisin de La Popelinière | 1581  | *L'histoire de France (Advertissemens necessaires)* | 429  |
| Agrippa d'Aubigné | 1616 | *L'histoire universelle*  | 848 |

## Normalisation guidelines

Normalisation is limited to spelling. Lexis, morphology, syntax and word order are left untouched: archaic words and constructions (ains, ja, onques, icelui, si est-ce que, pour ce que, devant que) are kept, and only their spelling is modernised.

The following changes were applied systematically:

Characters and abbreviations: ſ → s; & → et; tildes and other abbreviations expanded (cõme → comme, q̃ → que); curly apostrophes made straight.
u/v and i/j distributed according to modern usage (auoir → avoir, iour → jour, vn → un).
y → i where modern spelling requires it (moy → moi, Roy → Roi).
Etymological and obsolete consonants removed (faict → fait, nuict → nuit, doulx → doux, sçavoir → savoir).
Diacritics added (estre → être, escrire → écrire, apres → après).
Verb endings modernised (-oit, -oient → -ait, -aient; je croy → je crois). Plural present participles in -ans are normalised to the invariable form in -ant (jugeans → jugeant).
Word division and hyphenation brought into line with modern usage (long temps → longtemps, lors que → lorsque, dit il → dit-il).
Homophones corrected (a/à, ou/où, quelle/qu'elle, quand/quant).
In prose, encor, jusques and avecques are modernised (encore, jusque, avec), and Doncques becomes Donc. The elided form grand' is kept.
Past forms without a final -s in the source keep their form (il eut, il fut), even where the context could call for a subjunctive.

Proper names. Personal names keep their original form and only their spelling is normalised (Henry, Louys, Philippes). Place names are given in their modern French form (Romme → Rome, Orenge → Orange, Hedin → Hesdin). Names that could not be identified with certainty are left as printed.

Capitalisation and punctuation follow the source. The only change is that a space is added after colons and commas where it is missing.

Errors. Obvious misprints in the source or slips in the transcription are corrected in the normalised column (gtande → grande, la paux → la paix). The original column always keeps the reading of the source. Missing initial letters of decorated capitals (A guerre for La guerre) are restored.

## production

A first normalisation was produced with the assistance of a large language model, guided by the FreEMnorm data. It was then reviewed and corrected line by line by the author against the original transcription. Doubtful cases (misprints, uncertain names, ambiguous readings) were flagged during the first pass and checked individually.

## How to cite

Mélinda Fleury, _CORSAIR-FR-16–normalisation, GitHub, https://github.com/CORSAIR-SNF/FR-16-normalisation
 
## Licences

Transcriptions and normalisations are CC-BY.

<a rel="license" href="https://creativecommons.org/licenses/by/4.0"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /> 

## Funding

This project is founded by the Swiss National Found (SNF) : [222557]. https://data.snf.ch/grants/grant/222557

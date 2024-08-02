# Unveiling the Impact of Musical Factors in Judging a Song on First Listen: Insights from a User Survey

This repository provides our survey questionnaire and survey results from the paper **Unveiling the Impact of Musical Factors in Judging a Song on First Listen: Insights from a User Survey** accepted at [the 24th conference of the International Society for Music Information Retrieval (ISMIR 2023)](https://ismir2023.ismir.net/).

The survey questionnaire is described in [questionnaire_EN.pdf](/questionnaire_EN.pdf).

The dataset of the survey results consists of 5 tab-separated value (TSV) files.
It includes the participants' responses other than the free responses.
Below, we define the columns in each TSV file and describe how to generate the figures and tables in our paper from these files.
The figure and table numbers refer to those in the paper.

## 1. participants.tsv

Columns: participant_id, gender, age

## 2. importance_of_musical_factor.tsv

Columns: participant_id, melody, singing voice, rhythm, lyrics, mood, tempo, harmony, sentiment, instruments, danceability

The value for each musical factor represents its importance for the participant.

## 3. personality_traits.tsv

Columns: participant_id, openness, conscientiousness, extraversion, agreeableness, neuroticism

The computed scores for each of the personality trait are listed instead of the participants' answers to each of the 29 items about personalities in our questionnaire.

## 4. musical_sophistication.tsv

Columns: participant_id, InstExp, DanceExp, NoticeBeat, NoticeTune, LsnMusic, LsnNew, ViewLyrics, Karaoke, AttEvt

The definitions of these abbreviations (e.g., "InstExp") are given in section 5.2 of our paper.

## 5. willingness_of_functions.tsv

Columns: participant_id, function_1, function_2, function_3

The value for each function represents the participant's willingness to use the function.
The details of each function are given in section 6.1 of our paper.

## Reproduction of our results

* Figures 1 and 2 were generated from importance_of_musical_factor.tsv.
* Table 2 was generated from importance_of_musical_factor.tsv and personality_traits.tsv.
* Table 3 was generated from importance_of_musical_factor.tsv and musical_sophistication.tsv.
* Figure 4 was generated from willingness_of_functions.tsv.

## Citation

Please cite our paper if you use this questionnaire and/or dataset in your own work:

```txt
@inproceedings{tsukuda2023musical-factor,
  author    = {Kosetsu Tsukuda and Tomoyasu Nakano and Masahiro Hamasaki and Masataka Goto},
  title     = {Unveiling the Impact of Musical Factors in Judging a Song on First Listen: Insights from a User Survey},
  booktitle = {Proceedings of the 24th conference of the International Society for Music Information Retrieval},
  series    = {ISMIR 2023},
  pages     = {--},
  year      = {2023},
  doi       = {}
}
```

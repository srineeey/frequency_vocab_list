# frequency_vocab_list
Sort and extend manually written down vocab list according to language frequency

## Idea
Managing Vocabulary lists can be tedious, especially when trying to focus on learning the essentials. The idea of this code is to generate vocabulary lists which are sorted according to language frequency.
Databases:
(Subtitles)
https://github.com/hermitdave/FrequencyWords/

(News)
https://wortschatz.uni-leipzig.de/en/download/Japanese

Input: an already present vocab list

Function: Go through the list in the frequency database and add them to a new list. If a translation is present in the input list, then add it. Otherwise search online for a translation and mark for a manual check later.

required python features:

csv, json handling
openpyxl (editing spreadsheets)
special characters

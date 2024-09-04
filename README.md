# Accented Speech Commands Dataset (ASCD)

This dataset, which we have named the Accented Speech Commands Dataset (ASCD), is based on the keyword list from the Google Speech Commands dataset. It consists of **20,510 wav format files**. 
This dataset was collected to create a speech commands dataset with different accents from different countries.

## Data Collection

The dataset includes data from 11 speakers in total:
- **9 speakers** were generated using [Speechify's Voice Over Studio](https://speechify.com/blog/ultimate-guide-speechify-voice-over-studio/), each representing a different country:
  - America
  - China
  - France
  - Germany
  - India
  - Japan
  - Korea
  - Spain
  - Vietnam
- **2 non-native English speakers** directly recorded their samples. They are from the same country, which is one of the countries listed above.

### AI-Generated Samples

Using Voice Over Studio, we created 1-second audio files for the 35 keywords with accents from **nine different countries**. Each keyword underwent speed and pitch adjustments to generate diverse pronunciations. Specifically:
- Speed variations: -5%, 0%, 5%, 10%, 15%, and 20%.
- Pitch variations: -5%, 0%, and 5%.
- Punctuation variations: '.', '!', '?'.

This process resulted in **54 unique variations** for each keyword in each country.

### Sample Breakdown

For each keyword:
- **2 human speakers** provided **50 samples per keyword** through direct recording.
- **9 AI-generated speakers** (one per country) provided **54 samples per keyword**, created using speed and pitch variations.


## Keywords
The dataset uses the exact list of 35 keywords from the Google Speech Commands dataset: yes, no, up, down, left, right, on, off, stop, go, zero, one, two, three, four, five, six, seven, eight, nine, bed, bird, cat, dog, happy, house, marvin, sheila, tree, wow, backward, forward, follow, learn, visual.


## Structure
The dataset is organized by country, with the samples categorized by keywords.

## Licensing
Please check the repository for licensing details and usage terms. [LINK](https://github.com/k4kj8t9cyw/ASCD/blob/master/LICENSE)

## How to Download 
   - You can either download the [accented_speech_commands_dataset.tar](https://github.com/k4kj8t9cyw/ASCD/blob/master/accented_speech_commands_dataset.tar) directly and extract it, or clone the repository:
     ```bash
     git clone https://github.com/k4kj8t9cyw/ASCD.git
     ```

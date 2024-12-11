---
layout: default
title: "CBL2M"
---

# Abstract
Lyric-to-melody generation task can support composers in their creative process，helping to improve their work efficiency. Previous studies typically rely on extensive additional data for pre-training. Moreover, they encounter the issue of not fully exploiting the rich contextual information available in existing datasets to support generation. To address the above issues, we propose a Chord-integrated and Bar-level modeled end-to-end Lyric-to-Melody (CBL2M) generation model, effectively enriching contextual information based on existing quantitative data. To enhance the representation capabilities of the encoder, we extract chords from the melody and encode the lyrics and chords separately. In the decoder, we compute lyric-melody and chord-melody cross-attention. Furthermore, to accurately capture the regularities in bar durations within the melody, we design two specialized musical token sequences: the bar token sequence and the bar intra-position token sequence. We conduct extensive experiments on two datasets, with both subjective and objective evaluation metrics showing CBL2M generates high-quality, accurate melodies that outperform existing models.

# Sample Demonstrations
The following samples are melodies generated based on given lyric and chord texts. Multiple presentation formats are provided, including sheet music, MIDI audio, and singing audio.Here,we use ACE Studio to synthesize singing voices corresponding to the melodies.

## English Sample 1

**Lyric**:
```
1 2 3 4
```
**Chord**:
```
C G Am F
```
**Sheet Music:**
<embed src="assets/pdf/279.pdf" width="600" height="400" type="application/pdf">


**Melody:**  
<audio controls>
  <source src="assets/audio/279.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

**Singing:**  
<audio controls>
  <source src="assets/audio/279_vocal.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>



---

## English Sample 2

**Lyrics**:

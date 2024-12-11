---
layout: default
title: "End-to-End Lyric-to-Melody Generation via Chord Integration and Bar-Level Modeling"
---

# Abstract
Lyric-to-melody generation task can support composers in their creative process，helping to improve their work efficiency. Previous studies typically rely on extensive additional data for pre-training. Moreover, they encounter the issue of not fully exploiting the rich contextual information available in existing datasets to support generation. To address the above issues, we propose a Chord-integrated and Bar-level modeled end-to-end Lyric-to-Melody (CBL2M) generation model, effectively enriching contextual information based on existing quantitative data. To enhance the representation capabilities of the encoder, we extract chords from the melody and encode the lyrics and chords separately. In the decoder, we compute lyric-melody and chord-melody cross-attention. Furthermore, to accurately capture the regularities in bar durations within the melody, we design two specialized musical token sequences: the bar token sequence and the bar intra-position token sequence. We conduct extensive experiments on two datasets, with both subjective and objective evaluation metrics showing CBL2M generates high-quality, accurate melodies that outperform existing models.

# Sample Demonstrations
The following samples are melodies generated based on given **lyric** and **chord** texts. Multiple presentation formats are provided, including **sheet music**, **MIDI audio**, and **singing audio**.Here,we use ACE Studio to synthesize singing voices corresponding to the melodies.

## English Sample 1

**Lyric**:
```
Said I paid my dues for what’s done, and I’ll show you. You said, 'You trick me once, has always been trick.'
```
**Chord**:
```
Cdim C#m7b5 C# Ab Ebm7 C#
```
**Sheet Music:**
<embed src="assets/pdf/144.pdf" width="600" height="400" type="application/pdf">


**Melody:**  
<audio controls>
  <source src="assets/audio/144.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

**Singing:**  
<audio controls>
  <source src="assets/audio/144_vocal.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>



---

## English Sample 2

**Lyric**:
```
With a purple umbrella and a cent, just a woman. Missus Cool rides out in her aged, just a woman.
```
**Chord**:
```
Am7 F Bm7b5 Am7 F Bm7
```
**Sheet Music:**
<embed src="assets/pdf/312.pdf" width="600" height="400" type="application/pdf">


**Melody:**  
<audio controls>
  <source src="assets/audio/312.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

**Singing:**  
<audio controls>
  <source src="assets/audio/312_vocal.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

---

## English Sample 3

**Lyric**:
```
And I miss you, like the desert's mystery.And I miss you, yeah, like the desert's mystery.
```
**Chord**:
```
G Dm Am Dm7 Em7 C
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

## Chinese Sample 1

**Lyric**:
```
信上呃倾诉啊肺腑言啊哎哟字字句啊句啊痛呃断哪肠哪苍天降哪下啊无呃情剑哪斩断人间啊
```
**Chord**:
```
Am Em7 Am Em7 Am Em Am C Am C Em7 Am  
```
**Sheet Music:**
<embed src="assets/pdf/zh_0.pdf" width="600" height="400" type="application/pdf">


**Melody:**  
<audio controls>
  <source src="assets/audio/zh_0.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

**Singing:**  
<audio controls>
  <source src="assets/audio/zh_0_vocal.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

## Chinese Sample 2

**Lyric**:
```
四拜梁哥啊墓台前草桥结拜情谊深眼泪流干情不尽梁哥墓台葬我心  
```
**Chord**:
```
Am7 C Dm7 C Am7 C Am7 Em7 Am7
```
**Sheet Music:**
<embed src="assets/pdf/zh_9.pdf" width="600" height="400" type="application/pdf">


**Melody:**  
<audio controls>
  <source src="assets/audio/zh_9.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

**Singing:**  
<audio controls>
  <source src="assets/audio/zh_9_vocal.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>
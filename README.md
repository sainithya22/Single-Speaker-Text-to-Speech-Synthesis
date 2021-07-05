<center>
  <h1 align="center">Text to Speech Synthesis using Speaker Adaptation</h1>
  <h2 align="center">Using End to End Deep Learning Model</h2>
  <br>
  <h1 align="left">Dataset</h2>
  <ul align="left">
  <li>The encoder,synthesizer and vocoder were pre-trained on the Librispeech - train-clean-100 corpus, which consists of 100 hours of clean speech from around 250 speakers</li>
  <li>The model was adapted to work for single speaker by using 8 mins of recorded data
  </ul>
  <br>
  <h1 align="left">Model Overview</h2> 
  <ul align="left">
  <li>Speaker Encoder- computes a fixed dimensional embedding vector from the speech signal</li>
  <li>Synthesizer- predicts a mel spectrogram from a sequence of grapheme or phoneme inputs using Tacotron 2 architecture</li>  
  <li>WaveNet Vocoder- inverts synthesized mel spectrograms emitted by the synthesizer network into time-domain waveforms</li>  
  </ul>
  <br>
  <h1 align="left">Performance Evaluation Criteria</h2>
  <ul align="left">
  <li>Mean Opinion Score</li>
  <li>Semantically Unpredictable Sentences</li>
  </ul>
</center><br>

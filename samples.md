---
layout: default
title: Audio Samples
---

<div class="post">
	<h1 class="pageTitle">Audio samples</h1>
	<!-- <img src="{{ '/assets/img/touring.jpg' | relative_url }}" alt=""> -->
	<p> 1. Speech synthesis (TTS) </p>
	<p>We demonstrate the capability of SpeechComposer to generate speech conditioned on text.</p>
    <p>1.1 text: heron beside stephen began to hum tunelessly.<i></i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Ground truth:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000015_000004_gt.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>VoxtLM:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000015_000004_voxtLM.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000015_000004_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000015_000004_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000015_000004_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	</table>
	<table>
	<p>1.2 text: <i>Do not make such a bally racket.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Ground truth:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000022_000001_gt.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>VoxtLM:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000022_000001_voxtLM.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000022_000001_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000022_000001_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000022_000001_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	</table>
	<table>
	<p>1.3 text: He clasped his hands on the desk and said.<i>.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Ground truth:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000027_000001_gt.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>VoxtLM:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000027_000001_voxtLM.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000027_000001_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000027_000001_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000027_000001_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	</table>
	<table>
	<p>1.4 text: <i>10000 souls won for god in a single month.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Ground truth:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000034_000001_gt.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>VoxtLM:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000034_000001_voxtLM.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000034_000001_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000034_000001_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/tts/1089_134686_000034_000001_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
	<p> 2. Voice conversion </p>
	<p>We demonstrate the capability of SpeechComposer on voice conversion tasks.</p>
    <p>2.1 text: He works at the airport.<i>.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Source speaker:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_034.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>Reference speech:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p239_015.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>PPG-VC:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_034_p239_037_ppg.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_034_p239_037_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_034_p239_037_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_034_p239_037_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
   <p>2.2 text: The Festival is prepared to help.<i>.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Source speaker:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>Reference speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p239_015.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>PPG-VC:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p239_119_ppg.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p239_119_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p239_119_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p239_119_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
   <p>2.3 text: The Festival is prepared to help.<i>.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Source speaker:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>Reference speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p274_002.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>PPG-VC:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p274_437_ppg.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p274_437_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p274_437_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_075_p274_437_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
   <p>2.4 text: The Queen Mother is dead.<i>.</i></p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Source speaker:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_083.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>Reference speech:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p263_001.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>PPG-VC:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_083_p263_422_ppg.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_083_p263_422_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_083_p263_422_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/vc/p236_083_p263_422_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>

   <p> 3. Speech enhancement (SE) </p>
	<p>We demonstrate the capability of SpeechComposer on speech enhancement tasks.</p>
    <p>3.1 text: Six spoons of fresh snow peas, five thick slabs of blue cheese, and maybe a snack for her brother Bob.  </p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Noisy speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p257_003_noise.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p257_003_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p257_003_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p257_003_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
   <p>3.2 text: The rainbow is a division of white light into many beautiful colors. </p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Noisy speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p257_007_noise.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p257_007_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p257_007_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p257_007_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
   <p>3.3 text: The rainbow is a division of white light into many beautiful colors.</p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Noisy speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p232_007_noise.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p232_007_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p232_007_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p232_007_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>
	<p>3.4 text: People look, but no one ever finds it. </p>
    <table style="margin: 2rem auto; width: 60%;">
    <tr>
      <td>Noisy speech:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p232_010_noise.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Base:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p232_010_base.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Pretrained:</td>
      <td> 
	  	<audio controls="controls"><source src="/assets/audio/se/p232_010_pretrained.wav" type="audio/wav"></audio>
	  </td>
	</tr>
	<tr>
      <td>SpeechComposer-Large:</td>
      <td>
	  	<audio controls="controls"><source src="/assets/audio/se/p232_010_large.wav" type="audio/wav"></audio>
	  </td>
	</tr>
   </table>

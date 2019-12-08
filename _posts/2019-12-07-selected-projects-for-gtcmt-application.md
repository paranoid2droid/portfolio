---
title: Selected Projects
author: Zhe
layout: post
---

---------------------------

<h3 align="center"><strong>Synthesizer/Effect: ParanoidChorus</strong></h3>

<h4 align="center">A chorus-like effect based on JUCE <a href="https://github.com/paranoid2droid/ParanoidChrous" target="_blank">[repo]</a></h4>

<a href="https://youtu.be/ECDHRS1kips" target="_blank" class="image featured"><img src="../../../img/paranoidchorus.png" alt="ParanoidChrous" /></a>

A delay-based audio effect that you can run either as a plug-in or a standalone application. Knobs on the top-left are the basic parameters you can play with in a delay/chorus/flanger effect. In "mood" selection you can control the level of modulating, and in "mode" selection you can choose different oscillators for modulation. Plus, the "mod" slider works as a powerful magic booster for the LFO, generating new awesome sounds by high frequency modulation.

<h4 align="center">Video Demo</h4>

{% include youtubePlayer.html id="ECDHRS1kips" %}

<br/>

----------------------------

<h3 align="center"><strong>Interactive Audio: Wild Open Space</strong></h3>

<h4 align="center"><strong>Game or Synthesizer? <a href="https://github.com/paranoid2droid/WildOpenSpace" target="_blank">[repo]</a></strong></h4>

<a href="https://youtu.be/HFvsDB2GHOs" target="_blank" class="image featured"><img src="../../../img/wildopenspace.png" alt="Wild Open Space" /></a>

A sonic game using a remote sending OSC messages to the program, playing around while making sounds. The sound engine is written in ChucK. Several unit generators and STKs built in ChucK are used for the collision sounds with various kinds of physics modeling methods implemented like Karplus-Strong algorithm. A physics engine is also built in for the movements of particles. Parameters of synthesizers are affected by the collision position, including timbre and panning. So have fun in a stereo playback!

<h4 align="center">Video Demo</h4>

{% include youtubePlayer.html id="HFvsDB2GHOs" %}

<br/>

------------------------------

<h3 align="center"><strong>Computer Music: whenIAmKingYouWillBeFirstAgainstWall</strong></h3>

<h4 align="center">An Open-source Computer Music Album Based on ChucK<strong> <a href="https://github.com/paranoid2droid/whenIAmKingYouWillBeFirstAgainstWall" target="_blank">[repo]</a></strong></h4>
<h6 align="center">(for which I call it a "Chulbum")</h6>

<a href="https://theartifactsofripples.bandcamp.com/album/wheniamkingyouwillbefirstagainstwall" target="_blank" class="image half"><img src="../../../img/wheniamkingyouwillbefirstagainstwall.png" alt="whenIAmKingYouWillBeFirstAgainstWall" /></a>

<pre><code>/* This is an open-source album based on ChucK. <br />It is totally code-generated and you can run the code on your own with the environment required. <br />You will find that every time you "run" a song by the source code, it would be different. <br />Although my Chulbum is just less than 15 minutes, you can make your own a thousand years long. */</code></pre>

<h4 align="center">Listen Now</h4>

<iframe width="100%" height="450" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/908397286&color=%231c242d&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>

<br/>

--------------------------------

<h3 align="center"><strong>Academic Research: Acoustical Visual</strong></h3>

<h4 align="center"><strong>A Real-time Sound Field Visualization System Using SONAH Algorithm<a href="../../../project_sonah/Zhe_SONAH.pdf" target="_blank">[pdf]</a></strong></h4>

<a href="https://link.springer.com/chapter/10.1007/978-3-030-31967-0_12" target="_blank" class="image half"><img src="../../../project_sonah/setting.jpg" alt="Acoustical Visual" /></a>

A real-time system using a microphone array to visualize sound filed. I named this technique by <i>acoustical visual</i>, corresponding to the concept <i>audiovisual</i>. Following are dynamic sound field visualizing test results of the prototype system in front of a pair of speakers:

<p align="center"><i>(Buffering GIFs may need a little time.)</i></p>

- **Sound field visualization of 2000Hz sine wave on the left speaker:**

<img src="../../../project_sonah/2000Hz_L.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the left woofer and tweeter is captured by the visualization system.</i></p>

- **Sound field visualization of 2000Hz sine wave on the Right speaker:**
 
<img src="../../../project_sonah/2000Hz_R.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the right woofer and tweeter is captured by the visualization system.</i></p>



- **Sound field visualization of in-phase 2000Hz sine waves on both left and right speakers:**

<img src="../../../project_sonah/2000Hz_L&R.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the left and right woofers and tweeters with the in-phase interfere phenomenon is captured by the visualization system.</i></p>


- **Sound field visualization of inverse 2000Hz sine waves on both left and right speakers:**

<img src="../../../project_sonah/2000Hz_L&R_inv.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the left and right woofers and tweeters with the out-of-phase interfere phenomenon is captured by the visualization system.</i></p>

- **Sound field visualization of enveloped independent wide-band noise on both left and right speakers:**
 
<img src="../../../project_sonah/60-2000Hz_L&R_enveloped.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the left and right woofers and tweeters with independent wide-band noise (60-2000Hz) with a linear amplitude-in-dB envelope captured by the visualization system (in dB).</i></p>

- **Sound field visualization of stereo playback of a song clip of "In My Life" by The Beatles on both left and right speakers:**
 
<img src="../../../project_sonah/In_My_Life_L&R_independent.gif" class="image half" />

<p align="center"><i>Sound pressure radiated from the left and right woofers and tweeters with the song "In My Life" is captured by the visualization system (in dB). Owing to the recording and mixing technology back in the 60s, the guitars and percussions are panned to the hard left while the vocals and chorus are panned to the hard right, which could be seen from the dynamics of the visualization.</i></p>

FPS: 62.5

------------------------------------

<strong>In case you are interested, my full portfolio is <a href="https://zhezhang.me/portfolio/" target="_blank"><i>here</i></a>.</strong>
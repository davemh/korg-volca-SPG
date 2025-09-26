# korg-volca-SPG
Korg Volca Sync Pulse Generator - a free, browser-based tool for generating multi-measure Volca sync, from <a href="https://reverse-engine.com">Reverse Engine Records</a>.

<a href="https://davemh.github.io/korg-volca-SPG/"><img width="746" height="435" alt="image" src="https://github.com/user-attachments/assets/ae254a02-d9ec-4504-bc80-3b3befad39d0" /></a>

<h2>Live Demo</h2>
To use Korg Volca SPG in browser, without having to download files, check out the <a href="https://davemh.github.io/korg-volca-SPG/">live demo</a>. Fully tested and working in <a href="https://www.google.co.in/intl/en_uk/chrome/">Chrome 140</a> on Desktop, Duckduckgo for iOS v7.185.01, and Safari for iOS 18.6.2.

<h2>Local Installation</h2>
<img width="408" height="337" alt="image" src="https://github.com/user-attachments/assets/cf5a5ea1-b8ae-411e-8bfc-ecd6d2c8d440" />
<p>There's nothing to install! Just download .zip, decompress, open <em>index.html</em> in your browser (Chrome recommended), and enjoy.</p>

<h2>Controls</h2>
<p></p><b>Measures</b> input: input total number of measures.</p>

<p><b>Beats/Measure</b> input: input number of 1/4 notes per measure. For example, if your piece is in 4/4, enter 4. For now, this tool only supports 1/4 note-based time signatures (e.g. 2/4 march time, 3/4 waltz time, 4/4 common time).</p>

<p><b>BPM</b> input: input beats per minute.</p>

<p><b>Triplets Toggle Control</b>: toggle 1/4 note triplets on or off.</p>

<p><b>Swing Toggle Control</b>: toggle swing on or off.</p>

<p><b>Swing Amount Input</b>: Below the swing toggle is the swing amount input. Specify an amount of swing, from 0 to 75, by typing it in manually, or using the dial.</p>

<p><b>Play</b> button: begin playing a sync pulse matching your chose parameters.</p>

<p><b>Stop</b> button: stop playing the sync pulse.</p>

<p><b>Export WAV</b> button: generates a downloadable wav file matching your chosen parameters.</p>

<p><b>LED</b>: the LED will flash every downbeat.</p>

<h2>Syncing To Hardware</h2>
<p>Connect the headphone out on your computer or interface to the 3.5mm Sync Input on your Volca.</p>
<p>Press play on your hardware Volca Device.</p>
<p>Click play on the Sync Pulse Generator.</p>
<p>If the Volca doesn't begin playing immediately, turn up the volume on your computer until it's loud enough to trigger the device.</p>

<p>If the sync pulse is playing, it will update as you change individual parameters, in real time.</p>

<h2>Exporting & Using Korg Volca SPG Sync Pulse Audio Files</h2>
Once you've adjusted all parameters to meet your needs, click Export WAV. Save the generated file on your local machine. Record it onto your hardware multitracker, or (if digital) import it onto an empty track. Hard pan this track to either the right or left channel. Hard pan all other tracks to the opposite channel. Use a stereo breakout cable to send the sync audio to your Volcas, and all other audio to your headphones.

<h2>Feature Roadmap</h2>
Potential feature adds:
<p>Add a loop button which overrides the "Measures" input field, to enable longer jams when syncing the browser audio ouput directly to your Volcas.</p>
<p>Add more detailed tutorial (or links to resources) to the "Exporting..." section of this file, to explain how to use the exported file, for any potential user unfamiliar with the idea of tape-based sync.</p>

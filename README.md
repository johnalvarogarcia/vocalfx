<h1>Automated Reverse Reverb Vocal Effects</h1>


<h2>Description</h2>
This JavaScript script runs using Soundflow and is designed for use in Avid Pro Tools. The script allows us to combine a large amount of manual tasks into a single button press. The user can create a reverse reverb audio effect simply by highlighting a section of audio and launching the command.

<p></p>
For this script we:
<ul>
  <li>Set our Window / App focus to Avid Pro Tools.</li>
  <li>Copy the selected section of audio.</li>
  <li>Duplicate the audio track containing our audio, creating a an empty audio track with the same routing settings as our audio.</li>
  <li>Paste our audio onto our newly crated track.</li>
  <li>Make a new audio selection large enough to contain our desired audio effect.</li>
  <li>Use a plug-in loading script to load a Mono to Stereo plugin on our audio track.</li>
  <li>Commit our audio, creating a stereo audio file</li>
  <li>Open the audui-suite version of our preferred reverb plug-in.</li>
  <li>Choose a preset set to our desired reverb tail length.</li>
  <li>Set our audiosuite options.</li>
  <li>Finally, render our reverse reverb effect onto committed audio.</li>
  <li>Change our track colour.</li>

</ul>
<br />


<h2>Platforms and Technologies Used</h2>

- <b>Avid Pro Tools</b> 
- <b>iZotope RX10</b>
- <b>Soundflow</b>
- <b>JavaScript</b>


<h2>Script in SoundFlow's template mode</h2>


<p align="center">
<img src="https://i.imgur.com/s1GGo3o.jpeg" height="80%" width="80%"/>
<br />





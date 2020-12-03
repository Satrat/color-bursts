# Color Bursts
Color Bursts is a generative composition created by Sara Adkins and Julian Koreniowsky, inspired by the vibrant flowers scattered throughout a butterfly garden in Pittsburgh. The piece is made up of sample banks of percussive figures and melodic marimba phrases that randomly loop. Short synthesizer bloops flutter above the main loops, playing sparsely on randomly selected sub beat while an evolving drone sounds in the background. Samples for the piece were created using Logic Pro X.
<p float="center">
  <img src="https://github.com/Satrat/color-bursts/blob/master/pictures/foliage.jpg" width="300" />
  <img src="https://github.com/Satrat/color-bursts/blob/master/pictures/garden.jpg" width="300" /> 
</p>
Color Bursts ran as a sound installation in the Phipps Botanical Garden for four months in the summer of 2017. The piece runs as a Pure Data patch, which handles the scheduling and looping of the various voices. The patch runs on a Raspberry Pi, which launches the patch on startup and runs it indefinitely. The Pi was powered by a rechargeable battery that was plugged into a power source, ensuring the system would continue to run even if power was lost for several hours. The Pi was connected to a small but powerful external speaker using a USB audio device. The entire system was compact, and able to be hidden from view in the foliage of the garden.

## Depencies
* [PureData](https://puredata.info/)

## How to Use
Simply open `launch.pd` in PureData, the composition will start automatically

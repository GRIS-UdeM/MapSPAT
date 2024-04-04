# MapSPAT

MapSPAT enables real-time spatialization through audio descriptor analysis. 

It is designed to address two needs: to create spatialization linked to sound's spectral variations and to allow real-time spatialization without relying on automations. This tool is helpful when planning all spatialization aspects before a concert is impractical or not preferred.

![device](Docs/device.jpeg)

## Features

- Real-time spatialization through audio descriptor analysis:
  - Loudness, Pitch, Spectral Centroid, Spectral Spread, Noisiness
- Mapping data obtained to spatial parameters related to sound location and size
- User-friendly interface requiring no programming skills
- Hands-free operation for live performances, particularly advantageous while playing musical instruments

## Usage

MapSPAT is a MaxForLive device that can be used in Ableton Live (10, 11, 12) or as a stand-alone tool in MaxMSP. It is based on FluCoMa audio descriptors (https://www.flucoma.org) and the SpatGRIS spatialization system (https://gris.musique.umontreal.ca/).

To use MapSPAT you need to install SpatGRIS and an audio routing software (such as BlackHole for Mac and Jackrouter for Windows) to send audio from Ableton Live to SpatGRIS. For more information on audio routing and SpatGRIS operation, you can refer to the SpatGRIS manual available in the software's help window. Considering the workflow of SpatGRIS, MapSPAT can be used instead of ControlGRIS.

To use MapSPAT:

1. Place the MapSPAT device on the Ableton Live audio track you intend to spatialize.
2. Set the numeric value of the source in MapSPAT to match the audio track in Ableton Live.
3. MapSPAT is now ready to analyze the incoming audio.
4. Activate the mappings in the matrix to send the spatialization OSC signals to SpatGRIS.

We recommend using the latest version of MaxMSP rather than the bundled version in Ableton Live.

A demonstration Ableton Live project is available so you can explore the device's fonctions.

## About

MapSPAT is developed by Nicola Giannini and Jean-Philippe Jullin at the Faculty of Music at the University of Montreal, with the support of the Centre for Interdisciplinary Research in Music Media and Technology (CIRMMT).

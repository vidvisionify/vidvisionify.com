---
tags:
  - VRChat
quartz-properties: "false"
---
> [!NOTE]
> This page is a work in progress. 

How I can I possibly in a A, B, C, D, E, F and G all at the same time? Well, anyone with the tinest bit of filmmaking knowledge would say "a green screen, duh" (vsauce theme) but what if it wasn't?

This guide assumes you know your away around OBS
* Install the Spout2 plugin for OBS

* In OBS we're going to make a new settings Profile
  Profile -> New...
* Name it whatever, and go through the autoconfig 
* File -> Settings
* Advanced Tab (on the left)
	* Video
		* Color Format to BGRA (8-bit)
		* Color Space to sRGB
		* Color Range to Full
* Output Tab (on the Left)
	* Change Output Mode to Advanced
	* Recording Tab
		* Type to Custom Output FFmpeg
		* FFmpeg Settings
			* Container Format to mov
			* Video Encoder to png
* Hit OK to apply settings
* Add a new Spout2 Capture source in your scene
	* Composite Mode to Default

* In the VRChat camera
	* Make sure your camera is in Streaming mode
	* Turn on Spout Stream
	* Under Mask, turn off World


> oh wait no the performance is ass
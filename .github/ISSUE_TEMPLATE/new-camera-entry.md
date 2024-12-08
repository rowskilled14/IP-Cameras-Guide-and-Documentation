---
name: New Camera Entry
about: Suggest an idea for this project
title: "[New Camera Entry]"
labels: documentation
assignees: rowskilled14

---

**Brand of Device**
Eg: Dahua, Hikvision, Axis, Uniview, Reolink, etc

**Category of Device**
Eg: PoE; Wi-Fi; BNC; etc

**Model of Device**
Eg: IPC-Color-4k-T; IPC-HDW5442TM-ASE-S3; etc

**Short description of product**
Eg: The Dahua Color-4k-T camera series offers a large resolution without compromising on sensor and aperture sizing.  With an 8MP, 1/1.2" sensor and F1.0 aperture, this camera offers excellent low light performance.  White lights are available on the device, but IR is not present or supported.  A little ambient white light will be required for a product like this, but with proper settings, smooth motion can still be captured without ghosting, smearing, artifacting, etc even in very low light conditions.  

**Typical price of product and vendor name**
NOTE: YOU ARE NOT ENDORSING A SPECIFIC VENDOR.  The goal isn't to try to feed business to any one individual, but rather to simply catalog where the best pricing is found for the average consumer.  Specific links to specific products are fine, but keep the actual goal in mind.  

**Feature list**
Here, you are listing noteworthy features about the camera, and any noteworthy statuses about them.  

For example, a camera containing two way audio should list it here, and it should explicitly be listed if the camera supports open standards for two way audio or not.  ONVIF Profile T compliant cameras which contain two way audio **must** implement this two way audio in an ONVIF standardized way.  This would be an example of a feature to add, specifically noting the type of standard used.  Go2rtc leads the way for FOSS two way audio support, and compatibility with go2rtc will be used as the, "gold standard" for FOSS two way audio support, as it supports other standards in addition to ONVIF's two way audio standard.  

Other examples could include white light activation on motion/object/event detection.  While some users don't desire this, it is a noteworthy feature to mention.

AI features could fall under this list.

LUX ratings for night viewing could fall under this list.

**Camera Stream Endpoints/URLs:**
Here, you can add all known ways to view streams for the camera.  Categorize/organize them as appropriate.  

**Example Config**
This is intended to be a go2rtc config, but any comparable configs for other software NVRs are welcome *in addition to the go2rtc config.*  Go2rtc is one of the most flexible tools in the IP Camera world, is easy to digest and understand, and therefore is a fantastic baseline/standard for config templates.  Thus, it should be targeted as the, "default config" and should be present for all cameras whenever possible. 

** Description of config**
Include a short description of the config if there is anything noteworthy about it.  Some cameras have a few quirks which dictate specific configs - this is the place to note those changes and the reasons for it, etc.  Document it, that's the goal.  

** Alternate config and description**
If applicable, put here

**Known issues / limitations**
Any specific quirks for the camera not already mentioned should be mentioned here.  

A non-inclusive list:

* if it's a white light only camera, but doesn't support activating the white lights on detection of objects, via API, etc, it should be mentioned here.  
* If the camera requires an internet connection to setup, it should be mentioned here.  
* If the camera repeatedly tries to phone home, it should be mentioned here.  
* If the camera lacks functionality on specific firmware versions, it should be mentioned here
* If the camera has functionality limited to proprietary apps or services, it should be mentioned here
* If the camera doesn't properly implement a stream (eg Reolink) it should be mentioned here
* If the camera doesn't play nicely with a specific tool, it should be mentioned here

**Known compatibility with**
Eg. If a camera is tested on specific tools such as go2rtc, Frigate, Shinobi, Zoneminder, BlueIris, etc, it should be documented here.  

**Tested firmware**
Firmwares which were tested and, "known" as good, stable, compatible, etc should be provided.  Both a date of release and a firmware version are desired.  

**Additional Information**
This is where anything else noteworthy can go.  For example, if a camera has API endpoints which can be called to add additional functionality, it should be mentioned here.

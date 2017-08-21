# Block diagram

![Research studio block diagram](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/research-studio-block-diagram.jpg)  
**Fig 0:** Research studio block diagram.

# The brain of the setup
------

## Epiphan Pearl
The Epiphan Pearl ("The Pearl") is the brain of our setup. Technically, it is a video switcher with live streaming and recording.

You can create custom "picture in picture" layouts from up to four HD video sources, along with audio.

You can record these video layouts, while simultaneously streaming 1080p video streams at high quality.

The Pearl can store approximately 1,000 1-hour long video sessions, on its internal harddisk.

If more video sessions need to be stored, the Pearl has USB connections so external storage can be connected.

# The testing computer
-------

We're building the research lab to test digital things! So we need a computer to test things on.

We've chosen a reasonable spec'ed Macbook, but you could use any computer you wish.

We chose a Macbook as:

- thats what we use in the office for research and design
- Macbooks have good support for HDMI, VGA, and many other video outputs
- installing prototypes using the [GDS prototyping kit](https://github.com/alphagov/govuk_prototype_kit) is very simple on OS X

**NB:** If you choose to use a different computer than a Macbook you may need different video and audio adapters than what I've documented here.

## Turning the Macbook into a desktop
Because we can't guarantee people who we test with are comfortable with using a laptop computer, we've decided to set the Macbook up with an external monitor, keyboard and mouse.

We've used a standard USB optical mouse with a full-sized external keyboard.

![Macbook showing connections with external monitor, keyboard, and mouse](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/macbook-connections.jpeg)  
**Fig 1:** Connecting the Macbook to external monitor, keyboard, mouse, USB hub and Pearl.

# Storing research sessions
------

## Buffalo Drivestation 5TB USB hard disk (Optional)
Using an external USB storage device is optional - if you do not need to store a lot of video them you can ignore this step.

This hard disk can store 5,000 1-hour long video sessions, in addition to the 1,000 stored by the Pearl.

We chose the [Buffalo Drivestation 4TB hard disk](http://www.buffalotech.com/products/drivestation) for the storage vs. price value. **Any USB storage device can be used.**

We used a USB storage device as:

- it provided a place to backup research videos in case anything happened the Pearl
- we expect create a lot of video files and the Pearl may not be able to store them all

### Configure the Pearl for using USB storage
You can configure the Pearl via the web interface to use USB storage.

# Recording video
------
Add some intro here.

## Go Pro Hero camera
We needed a way to record video images of 1) the participant's facial expressions ("The FaceCam"), and the facilitator, participant's discussion in the seating area ("ChairCam").

Our requirements for recording video were to be able to:

- power the camera from USB cable (connected to main power)
- output the video feed, in realtime, from the camera into the Pearl

We purchased 3 GoPro Hero 3 cameras as they had a micro-HDMI video out and could be powered with a mini-USB cable plugged into power.

There are newer models released already so don't worry about getting this particular model.

### Don't use a memory card with the GoPro
The most important thing to remember is: you do not need to use a memory card with the camera.

The camera will not be recording any video - it will go directly to the Pearl.

### Mounting the GoPro in a case

As mentioned above, we need to 1) output the GoPro video to the Pearl and 2) power the GoPro from the USB port.

To allow us do this we purchased the [GoPro Skeleton Housing](https://shop.gopro.com/EMEA/accessories-2/skeleton-housing/AHSSK-301.html) for each camera. These are camera cases with holes cut out for the cables already.

You can see how the cables are connected to the GoPro in figure 2 below. They make your life much easier.

![GoPro camera connections](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/goprocamera.jpg)   
**Fig 2:** Connecting the GoPro camera to cables using the Skeleton housing.

We then connected the camera to the [GoPro Swivel Mount](https://shop.gopro.com/mounts/swivel-mount/ABJQR-001.html) and the [GoPro Curved Flat Adhesive mount](https://shop.gopro.com/EMEA/mounts/curved-plus-flat-adhesive-mounts/AACFT-001.html) to stick the camera to the table once we had positioned it.

This allowed us to change the point of view of the camera, but keep it secure.


## IPEVO VZ-1 VGA/USB Document camera
The [IPEVO VZ-1 camera](https://www.ipevo.com/prods/IPEVO-VZ-1-HD-VGA-USB-Document-Camera) is a document camera (sometimes called a "visualiser").

It is a real-time image capture camera - it allows you to put something on the table and then top display it on a computer screen - we've called this the "DocCam".

During user research sessions we sometimes need to test with things which are not on computer such as:

- paper documents (e.g. letters, visa papers)
- identify documents (e.g. passports, driving license)
- emails participants receive
- participants own mobile phones, tablet, etc

Similar to the GoPro cameras above, our requirements for the document camera were to be able to:

- power the camera from USB cable (connected to main power)
- output the video feed, in realtime, from the camera into the Pearl

![IPEVO VZ-1 camera](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/ipevo-vz-1.jpg)  
**Fig 3:** Connecting the IPEVO VZ-1 camera to the Pearl

The IPEVO VZ-1 camera can be plugged into a video display (in our example, the Pearl). It is also powered from USB.

The VZ-1 was plugged into one of the Pearl VGA video inputs.

### HDMI Male to Female VGA Adapter Video Converter

**IMPORTANT:** Some devices with HDMI connections require video converters with HDCP support in order to convert from HDMI to VGA. Before you buy a converter check to see if the device you want to convert uses HDCP.

The Pearl has 4 video inputs we can use - 2 VGA and 2 HDMI - this means you can record from 4 video devices.

Because we had 3 HDMI video devices and 1 VGA - our requirements were to:

- convert one GoPro camera HDMI video to VGA
- connect it to the Pearl.

**NB:** GoPro cameras do not use HDCP.

![HDMI to VGA video converter](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/video-converter.jpeg)  
**Fig 4:** Connecting the GoPro camera to the video converter and then to the Pearl

We bought [a HDMI to VGA video adapter](https://www.maplin.co.uk/p/maplin-microministandard-hdmi-male-to-female-vga-adapter-n58nx) and connected the GoPro HDMI output to it, and then connected the VGA output to the Pearl.

This allowed us to use all 4 video devices.


# Recording audio
------
Like the video recording, we need a way to record what the participant and facilitator are saying during the research session.

Our requirements for recording video were to be able to:

- power the camera from USB cable
- output the audio feed, in realtime, from the microphone into the Pearl

## Microphones

Similar to the GoPro cameras we've called the microphones ("chair-mic"), and the facilitator, participant's discussion in the seating area ("chair-mic").

### Recording audio is hard
Working with audio is very difficult - it is prone to lots of types of interference - electrical noise, air conditioning, noise from the street.

There are some ways of dealing with these problems:

#### Insulate your research studio
Insulate your research studio from external noise to make the environment as quiet as possible.

This can potentially mean some building work to install the insulation, but if your environment is noisy, it can save future heartache.

You can read more about noise insulation and lighting recommendations in [the noise and lighting guidance section](HTTP://ADDLINK).

#### Use specialist equipment
You can use specialist noise cancelling or noise filtering equipment to supress unwanted noise.

Using this type of specialist equipment is beyond the scope of this guide.

If you would like some help with this, please discuss it.

#### Get control of the environment
If possible, make sure that you can control air conditioning units, and other noisy devices from the research studio. This allows you to turn them off when necessary.


### Audio iteration 1 - failed
Originally we tried using low-cost [Omnidirectional Condenser Boundary microphones from Audio Technica](http://www.audio-technica.com/cms/wired_mics/037052449aa233dc/index.html).

These microphones are battery powered and reasonably cheap. However, they provided no amplification, or noise filtering of the audio and so the audio quality was very low.

Seeing as audio recording is probably more important than the video quality, this was a big issue - without good audio quality our recordings are essentially useless.

### Audio iteration 2 - so far so good
Taking some advice from my user researcher colleague in Sheffield, I tried using one of her [Samson Go Mic portable USB microphones](http://www.samsontech.com/samson/products/microphones/usb-microphones/gomic/). She had used it with great success in previous projects.

It is USB device which is connected to a computer using its USB port. It also has a 3.5mm audio connection.

![Samson USB Go Mic](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/samson-go-microphone.jpeg)  
**Fig 5:** Samson USB Go Mic

#### Mic to Macbook connection
We connect the microphone to the Macbook using the USB port.

The microphone then shows up on the computer as an external microphone.

This allows us to use the microphone instead of the internal mic.

![Connecting Samson USB Go Mic to Macbook](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/samson-go-microphone-connection-to-adapter-to-pearl.jpeg)  
**Fig 6:** Connecting Samson USB Go Mic to Macbook

#### Mic to Pearl connection
We then connect the audio output from the mic to the Pearl.

The Pearl has 2 sets of "6.35 inch left/right balanced" audio connections.

This means that we need to use 2 audio adapters which change:

1. size from 3.5mm (on the microphone) to 1/4 inch (on the Pearl)
2. splits the stereo from 1 audio plug into 2 - one for right and one for left.

![Connecting Samson USB Go Mic to Macbook](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/samson-go-microphone-connection-to-adapter-to-pearl.jpeg)  
**Fig 7:**</a> Connecting Samson USB Go Mic to Pearl

##### Change audio plug size
To change audio jack size (1 above) we used a [6.35mm Gold Stereo Plug to 3.5mm Stereo Socket Adapter](https://www.maplin.co.uk/p/635mm-gold-stereo-plug-to-35mm-stereo-socket-adapter-n89an), which we bought from Maplin, but are available from lots of other shops.

See figure 7 above.

##### Split audio into Left and Right
To split the audio from 1 to 2 plugs I used a [ProSound Mono 1/4 Inch Jack Female to Twin Mono 1/4 Inch Jack Male Adapter](
https://www.maplin.co.uk/p/prosound-mono-14-inch-jack-female-to-twin-mono-14-inch-jack-male-adapter-a51xg), again from Maplin.

See figure 7 above.

# User research studio private network
------
In order for the the user research sessions to be viewable by the observers we set-up a network.

We used an off-the-shelf network router. We put this in the user research studio and connected the Pearl.

In order to connect the Observation room computer to the private network there are two main options.

Depending on your circumstances you can either use Ethernet or WiFi.

## Option 1 - using Ethernet

![Observation room set-up](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/observation-room-option1.jpg)  
**Fig 8:** Option 1 - using Ethernet cabling to connect the Observation room computer

## Option 2 - using WiFi
![Observation room set-up](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/observation-room-option2.jpg)  
**Fig 8:** Option 2 - using WiFi cabling to connect the Observation room computer


# Observation room
------
Once you've got the research studio up and running, you need some place to observe all the research!

## Classic approach
In classic usability testing lab setups this would be achieved using the standard [one-way mirror](https://en.wikipedia.org/wiki/One-way_mirror).

This approach is expensive, and can lead to [negative effects in the research](http://www.uxmatters.com/mt/archives/2011/06/the-myth-of-the-one-way-mirror.php).

## Alternative approach
We chose to use the Pearl's inbuilt capability to stream audio and HD video while simultaneously recording the video for later analysis.

### The stream
The simplest, and most cost affective way to receive the Pearl video and audio stream was to use a low cost computer. We chose a Windows laptop with WiFi and Ethernet connectivity, good graphics and memory capability.

This computer would be connected to the User Research Studio private network - either using WiFi or using an Ethernet cable, whichever is available to you.

A little tip: if possible try to use an Ethernet connection between the Pearl and the observation room laptop.

It is more capable at handling high quality video and audio better than WiFi.

### The audio
The low quality internal speakers in the laptop would not be suitable to listen to the research session audio.

We therefore purchased a set of [Logitech Z333 PC speakers](https://www.amazon.co.uk/Logitech-Z333-Multimedia-Speakers-Black/dp/B00YR92VMA). We plugged these into the laptop to give better audio.

### Displaying the video stream
Obviously the laptop screen would not be suitable for a number of observers to view the research session as it is too small.

To try and replicate the "life sized" viewing of the one-way mirror approach we invested in a high quality, large TV screen, with multiple video inputs - HDMI, VGA, etc.

We chose the 75 inch Panasonic and also purchased the associated stand.

Having this stand allowed us the freedom to move the display to different rooms as needed.

### Connecting the laptop and the TV
Connecting the laptop to the TV was pretty easy - we used the HDMI output from the laptop and connected it to the TV's HDMI input.

After a little bit of fiddling with dimensions, it worked.

![Observation room set-up](https://github.com/ei8fdb/Home-Office-User-Research-Studios/raw/master/TheResearchStudios/observation-room.jpg)  
**Fig 8:** Observation room set-up

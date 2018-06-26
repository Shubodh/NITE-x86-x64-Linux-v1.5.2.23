# NITE-Bin-Dev-Linux-v1.5.2.23
x86 and x64 versions of NiTE, an SDK for joint tracking with the Microsoft Kinect. Developed by PrimeSense, now part of Apple.

If you're getting the following error when trying to run Tracking applications using Kinect, OpenNI and NiTE packages, try running other non-tracking related applications. If they are running, the problem is most definitely with NiTE package.  

The error:

'Reading config from: ../../Config/SamplesConfig.xml'
Find user generator failed: Can't create any node of the requested type!'

Installing OpenNI and SensorKinect is fairly straightforward and there are many online tutorials available to do that.

Before installation, you might have to make edits in certain files in NiTE packages, follow this to do that. - http://www.etti.tuiasi.ro/cin/Courses/SistEmbedded/Projects/Linux/BeagleBoard/Kinect_on_Ubuntu/Kinect_on_Ubuntu.html 

Now, to install NiTE, do the following:

```bash
$ cd x86/x64 (depending on your architecture)
$ sudo bash install.sh
```



# Some interesting links, book and other info SDR 
(as collected by the members of the "SDR Belgium" mailing)


Note:  
Also check out this page on SDR-related information in Dutch:
[sdrlinks-nl] (https://github.com/on1arf/sdr/blob/master/links-nl.md)
  
  
## On DSP:

* "The Scientist and Engineer's Guide to Digital Signal Processing" by Steven W. Smith  
[website] (https://dspguide.com/)  
Available as a free download or real "paper" book

I found this quite a useful starting-point on DSP, especially not to much math. Gives a good introduction in sampling, some of the mathematical machinery behind DSP (lineair systems, convolution, the Fourier transform ... ), some examples of digital filters and an overview of DSP-based applications.


* "Understanding Digital Signal Processing" by Richard G. Lyons  
ISBN  978-0137027415  

Seen by post people as the book to read once you got the DSPguide behind you. A good introduction into DSP but going a lot more into depth.



* Practical Signal Processing by Mark Owen  
ISBN 978-1-107-41182-1




## On SDR:

* "Software Defined Radio with HackRF"  
[videocourse] (https://greatscottgadgets.com/sdr/)  

Probably one of the best known resources on SDR. A 11-part video course by Michael Ossmann of Great Scott Gadgets, the maker of the HackRF.
Gives a very good visual introduction on SDR and some of the math behind it.


* Wireless Pi, "an easy visual guide to SDR" by Qasim Chaudhari  
[website] (https://wirelesspi.com/)  

I really like this one. This is a combination of a book, an online course and a large number of GNU Radio flowgraphs. The really nice thing is that he uses GNU Radio as an educational tool, allowing you to learn and really experiment with the principles of Software Defined Radio.


* Wireless Communications from the Ground Up by Qasim Chaudhari  
ISBN 978-1-729-73223-6  
Book accompanying the "Wireless Pi" website and video-course mentioned above


* Basics of IQ Signals and IQ modulation & demodulation - A tutorial  
[youtube] (https://www.youtube.com/watch?v=h_7d-m1ehoY)

DSP and SDR have a number of concepts that are quite now, e.g. I/Q sampling.


* "Software-Defined Radio for Engineers", 2018. by Travis F. Collins, Robin Getz, Di Pu, and Alexander M. Wyglinski  
A free download from Analog Devices.  
[website] (https://www.analog.com/en/education/education-library/software-defined-radio-for-engineers.html)

As the title indicates, a course for engineers so expect a lot more math.


* rtl-sdr.com  
[website] (https://www.rtl-sdr.com/)  
Started


# SDR by / for Amateur radio
* SDR project by Paul ON5QM  
Paul ON5QM for ONZ (Section Knokke) has extensive document on SDR for Amateur radio.  
In dutch, available from the website of ONZ:  
[website] (https://www.onz.be/diverse-projecten/)


* SDR for the Radio Amateur: Experimental Methods in DSP design  
[website] (https://www.g0kla.com/sdr/index.php)
Examples in java and python


* SDR Academy youtube archive  
[youtube] (https://www.youtube.com/channel/UC1GAlgAQrkjeeLmIkCB8pgQ)

Contains the video archive of the SDR Academy held at "Ham-radio Friedrichhafen" in 2020 and 2019, and the European GNU Radio days:
Most of them are in English, some videos are in German

* FOSDEM video archive of the "Free Software Radio" Devroom 
(called "SDR" devroom before 2020)
[2020] (2020: https://video.fosdem.org/2020/AW1.120/)  
Look for videos starting with "fsr"  
[2019] (https://video.fosdem.org/2019/AW1.120/)  
Look for videos starting with "sdr"
For the years before 2018 the videos are less organised. Go to [videos] ("https://video.fosdem.org/"), pick a year and select the room AW1.120.
Search the videos that have a title that kind-of mentions SDR.


# SDR Hardware, Drivers and tools:

* osmocom (Open Source Mobile Communications)  
[website](https://osmocom.org/)
Drivers and tools for the RTL-SDR dongle

* soapySDR  
[github] (https://github.com/pothosware/SoapySDR/wiki)  
An open-source generalized API and runtime library for interfacing with SDR devices

# GNU Radio  
* GNU Radio "Tutorials"  
[website] (https://wiki.gnuradio.org/index.php/Tutorials)

* "GNU Radio, learning the basics" by Jarno Baselier  
In dutch:  
An extensive 3-part article on starting out with GNU Radio on Linux.  
[part1] (https://jarnobaselier.nl/gnu-radio-learning-the-basics-13/)  
[part2] (https://jarnobaselier.nl/gnu-radio-learning-the-basics-23/)  
[part3] (https://jarnobaselier.nl/gnu-radio-learning-the-basics-33/)  


* GNU Radio mailing-list:
[website] (https://lists.gnu.org/mailman/listinfo/discuss-gnuradio)


# SDR and cybersecurity  
* gr-inspector  
"A signal analysis toolkit for GNU Radio"  
[video FOSDEM 2017] https://video.fosdem.org/2017/AW1.120/grinspector.mp4  
[github] (https://github.com/gnuradio/gr-inspector)  
  
* Inspectrum:  
"A tool for analysing captured signals, primarily from software-defined radio receivers"  
[github] (https://github.com/miek/inspectrum)  
[article + video] https://www.rtl-sdr.com/inspectrum-a-new-tool-for-analyzing-captured-signals/  
    
* Pentoo linux  
[download site] (https://pentoo.ch/downloads)  
Linux distro for pentesting.  
The LiveCD includes GNU Radio and gqrx.  
Also included other 'wireless' cracking tools, e.g. for wifi and bluetooth hacking.  
  
* SigIntOS  
[download site] (https://www.sigintos.com/downloads/)  
Linux distro, includes GNU Radio and gqrx by default  
Also includes 'SigIntOS tool', which include a FM transmitter, IMSI catcher, GPS transmittor, e.a.  
(note: Use of this tool is illegal in Belgium)  
  

# Mathematics  
Although there are a number of books on DSP and SDR that avoid to much math if possible, DSP and SDR are in its core completely based on math!  
  
For people who want to brush up the math, the khan academy has quite a few online courses on math at a more advanced level.  
  
Very interesting is the learning-track on Electrical Engineering:  
[Electrical Engineering learning-track] (https://www.khanacademy.org/science/electrical-engineering)  
  
Some video's of particular interest to DSP and SDR are in the chapter on 'AC circuit Analysis':  
  * [Trigonometry review] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-ac-trig-review)  
  * [Sine and cosine come from circles] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-sine-cosine-circles)  
  * [Sine of time] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-sine-of-time)  
  * [Sine and cosine from rotating vector] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-sine-cosine-from-rotating-vector)  
  * [lead lag] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-lead-lag)  
  * [complex numbers] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-complex-numbers)  
  *[negative frequencies] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-negative-frequency)  
  *[AC analysis superposition] (https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-ac-analysis/v/ee-ac-analysis-superposition)  
  
Some other courses:  
* lineair algebra  
[video-course] (https://www.khanacademy.org/math/linear-algebra) English  
[video-course] (https://fr.khanacademy.org/math/linear-algebra) French  



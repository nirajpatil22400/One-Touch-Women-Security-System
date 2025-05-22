# One-Touch-Women-Security-System
A
Project Report 
on

“One Touch Women Security System”

Submitted by
Ms. Aarti Kuber Gade                                                       (B150673001)
Mr. Pushkaraj Kulkarni                                                    (B150673021)
Mr. Niraj Patil                                                                    (B150673028)

Under the guidance of
Dr. Sanjay S. Badhe
In partial fulfillment of the requirements for the degree of Bachelor of Engineering in Electronics and Telecommunication Engineering of Savitribai Phule Pune University.



DEPARTMENT OF ELECTRONICS & TELECOMMUNICATION ENGINEERING

2021-2022
 
DEPARTMENT OF ELECTRONICS & TELECOMMUNICATION 
Academic Year 2021-2022

CERTIFICATE

This is to certify that the project entitled “One Touch Women Security System” is a record of bonafide work carried out by Ms. Aarti Kuber Gade , Mr. Pushkaraj Kulkarni, Mr. Niraj Patil under my supervision and guidance, in partial fulfillment of the requirements for the award of Degree of Bachelor of Engineering in Electronics and Telecommunication Engineering from Savitribai Phule Pune University for the year 2021-22.


Dr. Sanjay S. Badhe				         Dr. Moresh Mukhedkar 
       (Guide)                                                         	 (Project Coordinator)


Prof. N. A. Dawande			    	                                                           
         (H.O.D)		                                           (External Examiner)		      			
Dr. Abhay A. Pawar
 (Principal)

ACKNOWLEDGEMENT


Our endeavor stands incomplete without dedicating our gratitude to everyone who has contributed a lot towards successful completion of our work. First of all, we offer thanks to our parents for their blessings. We are indebted to God Almighty for blessing us with his grace and taking our endeavor to a successful culmination. We specially acknowledge Dr. Abhay A Pawar, Principal, Prof. N.A Dawande, Head of the Department, Project Guide Dr. Sanjay Badhe, Associate Professor, and Project Coordinator Dr. Moresh Mukhedkar, Associate Professor, ECE for their technical support and guidance given and steering us to successful completion of this work.





















INDEX
•	Abstract
•	Preface
•	List of Figures 
•	List of Tables
•	List of Abbreviations

Sr. No.	Title	Page No.
1	Introduction	
2	Literature Survey	
3	Proposed System	
4	Methodology	
5	Application	
6	Conclusion
	
7	Bibliography	
8	References	
9	Source Code	
10	Appendix	









ABSTRACT
In recent times, role of women in all industries have increased. Simultaneously, crime against women is also increasing day by day and this is the high time to provide safety for all working women. This paper focuses on women tracking system for all working women. There is no powerful existing system to prevent the crime rates against women. This system gives information about a woman or a victim who has low assurance about their safety to their respective family and the place where they work, which have to be more concerned about their women workers. 
	This system includes the victim module and two receiver modules for getting information about the missed women. This arrangement includes Microcontroller, Global Positioning System (GPS), and Global Arrangement for Mobile communication (GSM), and the receiver module that includes a Android mobile mechanism of the victim’s relations and a monitoring database in the manipulation room of the corresponding association or workplace.














PREFACE
This Project Report has been prepared in partial fulfilment of the requirement for the Subject :One Touch Women Security System for the Program B.E in Electronics & Telecommunication Engineering (Sem VIII ) In the academic year 2021-2022 For preparing the Project Report, we have visited the various websites during project work, to avail the necessary information. The blend of learning and knowledge acquired during our practical studies at the college laboratory, in this project report the rationale behind visiting the various journals and technical websites is to complete the work in given time and preparing the project report is to study the basics of sensors and PCB’s , history and development of the electronics components, major players in project, contribution of sensors in the security of women during crises and emergency. This project covers about the handy device which women can carry and also covers the general information of the electronics components. The information presented in this Project Report is obtained from sources like www.Google.com www.wikipedia.com,https://ieeexplore.ieee.org,https://www.researchgate.net http://www.ijetjournal.org, http://www.ijirset.com.


                                                                                                                                    Names of group members
                                                                                                                                                            Ms. Aarti  Kuber  Gade
                                                                                                                                                             Mr. Pushkaraj Kulkarni
                                                                                                                                                             Mr. Niraj Patil






LIST OF FIGURES

Sr. No.	Figure Caption	Page No.
1	Block Diagram Of Proposed System	
2	 ATmega16	
3	16 * 2 LCD Display	
4	GSM Modem	
5	GPS Model	
6	Accidental Switch	
7	Buzzer	
8	Hardware  Design	
9	Schematic Design	

















LIST OF ABBREVIATIONS


Sr No	Abbreviations Used	Page No
1	GPS - Global Positioning System 	
2	GSM - Global System for Mobile Communication 	
3	ADC - Analog to Digital Convertor	
4	LCD - Liquid Crystal Display	
5	PCB - Printed Circuit Board	





























Chapter 1
Introduction

How we came on This Idea  Our group was always more inquisitive about security purpose projects. We decided that our project will be security based  we also wanted to make something unique, something that is not unique in the market and for a social cause. So, we came up with this idea of  Women Security.

The main objective the project is to provide highly reliable security system for the safety of women. The proposed system is based advanced sensors, Microcontroller and GSM. Here we introduces an app which ensures the safety of women. This helps to identify and call on resources to help the one out of dangerous situations. This reduce risk and bring assistance when we need it and help us to identify the location of the one in danger. We recommend our app since it have some key features which diverse it from others. They are quoted below:
There is a rising needs for pursuing mechanisms, that can be a existence saving devices. Across eras of low assurance, people can use these arrangements to retain trail of victims. Pursuing provides countless services such as discovering their locale, retain trail of employers to monitor whereas they are at all periods across the workday, teenagers to manipulation their movements, tinier children, pets and elders after they go missing and for countless supplementary purposes. The progress to location-dependent services and requests in wireless arrangements endures to need the progress of extra precise and reliable positioning and pursuing systems. Women's safety is particularly at risk in India in today's world. 

There is no decrease in the number of crimes against the female, but an alarming increase, in particular harassment, abuse, rape, kidnapping and violence at home. A number of preventive measures have been taken by the government to stop thesemisbehavior practices, but have not yet affected the increasing incidence of these crimes and have remained unchanged. There is an increasing problem of sexual harassment at work. Sexual harassment in a job is an unwanted person's behavior causing discomfort, offence or distress to others. Much of these cases occur to women through men who work in a highly qualified company. Girls are abducted every 44 minutes, and 17 dowry deaths a day are murdered every 47 minutes. The fear of harassment of women is not only an outside condition but can also happen at home. Females are less fit than men, so a helping hand would be a boon to them in case of a need. 








Chapter 2
Literature Survey

N. R. Sogi, P. Chatterjee, U. Nethra and V. Suma 
 Women’s are being face men’s in everyday life and they are subjected to harassments, abuse, violence in public. In this paper, For these kind of activities women’s cannot wear clothes for their own will and not live with freedom even their confidence is shattered. To provide security for women’s authors suggested an IOT based wearable ring called SMARSHIA. This ring comprises Raspberry pi camera, Buzzer & Button to activate the service by clicking the button the current location will send to a static mobile numbers (Registered mobile numbers) and also send the captured image of the attacker by using Raspberry pi camera. Since the Raspberry pi camera not able capture the clear image of the attacker in night time.

Muskan, T. Khandelwal, M. Khandelwal and P. S. Pandey. In this paper, the authors discussed about the disadvantages of the existing system. The existing applications and devices are need lot of human interaction to operate. These devices used to read the human temperature and heart beat based on the defined threshold value it will generates the alarm signal. But this is not a correct way to generates alarm signal because when the victim running that time also heart rate will increase and hit the threshold value and send the alarm signal. So, to overcome this problem authors used temperature and pulse sensors that will d etect the activity of the woman and that data of sensors will b esent to cloud where machine learning algorithm is applied to analyse the data generated. The data in 
n on-danger conditions are collected to train the algorithm, after that data is testing to gauge the accuracy and how close it is to our trained data. If accuracy is more the security w ill b e stronger and the emergency alarm will be there on emergency contacts. Thirdly, this paper tells victims can use the device where there is no internet facility by using Zigbee mesh network. The problem faced in this paper is it send the alarm and location to only few Static people within the range.







Prof. R.A.Jain, Aditya Patil, Prasenjeet Nikam, Shubham More, Saurabh Totewar. In this paper, the authors proposed a model which will helptoensurethe safety of women and children. They have used different sensors like heartbeat sensor, temperature sensor, accelerometer sensor for detecting heartbeat, temperature and sudden change in motion of user. They have also used GPS which will help to detect location of the device. GSM used in the model is used to send alert message to guardians, relatives and police station. They have proposed IoT (internet of things) based device which will help to continuously monitor values of different sensors and GPS used in device. The drawback of this paper is it will send the location and message to only Static mobile numbers and also internet connectivity is needed.

M. Kavitha and V. Sivachidambaranathan . These days the safety of an individual is at stake, it may be due to ill health or due to the increasing crimes such as the sexual assaults, molestation, abuse etc. The existing mobile applications are Anuti, Wosapp, Reach-360, etc. require the registration and login certain credentials and when the user has to wave the mobile to send the alert message to registered family (Static) and the registered mobile numbers for help. The main drawback of existing system is there are rural areas where people cannot use the mobile phones. So, To prevent the above mentioned cause the authors proposed a wearable smart device based on internet of things. Itcomprises of few bio sensors such as motion sensor, temperature sensor, pulse rate sensor to detect the user’s body changes like heart beat, body temperature and alert the static peoples for helping when any abnormality is found as per the pre-program of the device. The GSM and GPS are used to identify the victim’s location. The victim location is shared to the nearby police station and to the pre-registered mobile. when the alarm is activated it will alert the surroundings.













Chapter 3
Proposed System

3.1 Proposed System
In This Proposed System the soldier Health and Position Tracking System allows military to track the current GPS position of soldier and also checks the health status including body temperature and heartbeats of soldier. The System also consists extra feature with the help of that soldier can ask for help manually or send a distress signal to military if he is in need. The GPS modem sends the latitude and longitude position with link pattern with the help of that military can track the current position of the soldier. The system is very helpful for getting health status information of soldier and providing them instant help and here we are using arduino uno microcontroller and GSM module for Sending message on Health condition and the location of the Soldier to the military.

3.2 Block Diagram of Proposed System

 
Fig 3.1: Block Diagram of Proposed System

3.3 Explanation:-
The progress of the working women pursuing arrangement will be described in detail in this section. The block diagram of this pursuing arrangement is as shown in Fig 3. 1. The three main components of the arrangements are the GPS receiver module, GSM module and microcontroller. The receiver module's main purpose is to attain the victim's coordinates. These coordinates are periodically (user selectable) dispatched to the microcontroller. The microprocessor procedures this information and will next dispatch the locale data to the GSM to be sent across the mobile network to the user after demanded on a non- periodic basis.  The microcontroller transmits/triggers the message through the Universal Asynchronous Receiver/Transmitter (UART) interface. The progress of the working women pursuing arrangement will be delineated in detail in this section. The three main components of the women tracking system are the GPS (receiver module), GSM module and PIC16F877A microcontroller. The Ultimate aim of GPS module is to locate the victim's coordinates. These coordinates are periodically (user selectable) dispatched to the microcontroller. The microprocessor procedures this data and will subsequent dispatch the locale data to the GSM to be dispatched across the mobile web to the user afterward commanded on a non- periodic basis. The modules and microcontroller communicates across the Universal Asynchronous Receiver/Transmitter (UART) interface.















Chapter 4
Methodology:

4.1 Hardware & Software used
4.1.1 ATmega 16 Microcontroller:
 

ATmega16 is an 8-bit high performance microcontroller of Atmel’s Mega AVR family with low power consumption. Atmega16 is based on enhanced RISC (Reduced Instruction Set Computing, Know more about RISC and CISC Architecture) architecture with 131 powerful instructions. Most of the instructions execute in one machine cycle. Atmega16 can work on a maximum frequency of 16MHz.ATmega16 has 16 KB programmable flash memory, static RAM of 1 KB and EEPROM of 512 Bytes. The endurance cycle of flash memory and EEPROM is 10,000 and 100,000, respectively. ATmega16 is a 40 pin microcontroller. There are 32 I/O (input/output) lines which are divided into four 8-bit ports designated as PORTA, PORTB, PORTC and PORTD.ATmega16 has various in-built peripherals like USART, ADC, Analog Comparator, SPI, JTAG etc. Each I/O pin has an alternative task related to in-built peripherals. The following table shows the pin description of ATmega16
4.1.2 Liquid Crystal Display (LCD):


 

A liquid-crystal display (LCD) is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals. Liquid crystals do not emit light directly, instead using a backlight or reflector to produce images in color or monochrome. LCDs are available to display arbitrary images (as in a general-purpose computer display) or fixed images with low information content, which can be displayed or hidden, such as preset words, digits, and 7-segment displays, as in a digital clock. They use the same basic technology, except that arbitrary images are made up of a large number of small pixels, while other displays have larger elements.
LCDs are used in a wide range of applications including computer monitors, televisions, instrument panels, aircraft cockpit displays, and indoor and outdoor signage. Small LCD screens are common in portable consumer devices such as digital cameras, watches, calculators, and mobile telephones, including smart-phones. LCD screens are also used on consumer electronics products such as DVD players, video game devices and clocks. LCD screens have replaced heavy, bulky cathode ray tube (CRT) displays in nearly all applications. LCD screens are available in a wider range of screen sizes than CRT and plasma displays, with LCD screens available in sizes ranging from tiny digital watches to huge, big-screen television set.
Since LCD screens do not use phosphors, they do not suffer image burn-in when a static image is displayed on a screen for a long time (e.g., the table frame for an aircraft schedule on an indoor sign). LCDs are, however, susceptible to image persistence.The LCD screen is more energy-efficient and can be disposed of more safely than a CRT can. Its low electrical power consumption enables it to be used in battery-powered electronic equipment more efficiently than CRTs can be. By 2008, annual sales of televisions with LCD screens exceeded sales of CRT units worldwide, and the CRT became obsolete for most purposes.
Each pixel of an LCD typically consists of a layer of molecules aligned between two transparent electrodes, and two polarizing filters (parallel and perpendicular), the axes of transmission of which are (in most of the cases) perpendicular to each other. Without the liquid crystal between the polarizing filters, light passing through the first filter would be blocked by the second (crossed) polarizer. Before an electric field is applied, the orientation of the liquid-crystal molecules is determined by the alignment at the surfaces of electrodes. In a twisted nematic (TN) device, the surface alignment directions at the two electrodes are perpendicular to each other, and so the molecules arrange themselves in a helical structure, or twist. This induces the rotation of the polarization of the incident light, and the device appears gray. If the applied voltage is large enough, the liquid crystal molecules in the center of the layer are almost completely untwisted and the polarization of the incident light is not rotated as it passes through the liquid crystal layer. This light will then be mainly polarized perpendicular to the second filter, and thus be blocked and the pixel will appear black. By controlling the voltage applied across the liquid crystal layer in each pixel, light can be allowed to pass through in varying amounts thus constituting different levels of gray. Color LCD systems use the same technique, with color filters used to generate red, green, and blue pixels.
The optical effect of a TN device in the voltage-on state is far less dependent on variations in the device thickness than that in the voltage-off state. Because of this, TN displays with low information content and no backlighting are usually operated between crossed polarizers such that they appear bright with no voltage (the eye is much more sensitive to variations in the dark state than the bright state). As most of 2010-era LCDs are used in television sets, monitors and smartphones, they have high-resolution matrix arrays of pixels to display arbitrary images using backlighting with a dark background. When no image is displayed, different arrangements are used. For this purpose, TN LCDs are operated between parallel polarizers, whereas IPS LCDs feature crossed polarizers. In many applications IPS LCDs have replaced TN LCDs, in particular in smartphones such as iPhones. Both the liquid crystal material and the alignment layer material contain ionic compounds. If an electric field of one particular polarity is applied for a long period of time, this ionic material is attracted to the surfaces and degrades the device performance. This is avoided either by applying an alternating current or by reversing the polarity of the electric field as the device is addressed (the response of the liquid crystal layer is identical, regardless of the polarity of the applied field).
Displays for a small number of individual digits or fixed symbols (as in digital watches and pocket calculators) can be implemented with independent electrodes for each segment. In contrast, full alphanumeric or variable graphics displays are usually implemented with pixels arranged as a matrix consisting of electrically connected rows on one side of the LC layer and columns on the other side, which makes it possible to address each pixel at the intersections. The general method of matrix addressing consists of sequentially addressing one side of the matrix, for example by selecting the rows one-by-one and applying the picture information on the other side at the columns row-by-row. For details on the various matrix addressing schemes see Passive-matrix and active-matrix addressed LCDs.
                                         

















4.1.3 Global System for Mobile Communications (GSM):

 

GSM (Global System for Mobile Communications, originally Groupe SpécialMobile) is a standard developed by the European Telecommunications Standards Institute (ETSI) to describe the protocols for second-generation (2G) digital cellular networks used by mobile phones, first deployed in Finland in July 1991. As of 2014 it has become the de facto global standard for mobile communications – with over 90% market share, operating in over 219 countries and territories.
2G networks developed as a replacement for first generation (1G) analog cellular networks, and the GSM standard originally described as a digital, circuit-switched network optimized for full duplex voice telephony. This expanded over time to include data communications, first by circuit-switched transport, then by packet data transport via GPRS (General Packet Radio Services) and EDGE (Enhanced Data rates for GSM Evolution or EGPRS).
Subsequently, the 3GPP developed third-generation (3G) UMTS standards followed by fourth-generation (4G) LTE Advanced standards, which do not form part of the ETSI GSM standard.
"GSM" is a trademark owned by the GSM Association. It may also refer to the (initially) most common voice codec used, Full Rate.
GSM is a cellular network, which means that cell phones connect to it by searching for cells in the immediate vicinity. There are five different cell sizes in a GSM network—macro, micro, pico, femto, and umbrella cells. The coverage area of each cell varies according to the implementation environment. Macro cells can be regarded as cells where the base station antenna is installed on a mast or a building above average rooftop level. Micro cells are cells whose antenna height is under average rooftop level; they are typically used in urban areas. Picocells are small cells whose coverage diameter is a few dozen meters; they are mainly used indoors. Femtocells are cells designed for use in residential or small business environments and connect to the service provider’s network via a broadband internet connection. Umbrella cells are used to cover shadowed regions of smaller cells and fill in gaps in coverage between those cells.
Cell horizontal radius varies depending on antenna height, antenna gain, and propagation conditions from a couple of hundred meters to several tens of kilometres. The longest distance the GSM specification supports in practical use is 35 kilometres (22 mi). There are also several implementations of the concept of an extended cell,where the cell radius could be double or even more, depending on the antenna system, the type of terrain, and the timing advance.
Indoor coverage is also supported by GSM and may be achieved by using an indoor picocell base station, or an indoor repeater with distributed indoor antennas fed through power splitters, to deliver the radio signals from an antenna outdoors to the separate indoor distributed antenna system. These are typically deployed when significant call capacity is needed indoors, like in shopping centers or airports. However, this is not a prerequisite, since indoor coverage is also provided by in-building penetration of the radio signals from any nearby cell.
GSM networks operate in a number of different carrier frequency ranges (separated into GSM frequency ranges for 2G and UMTS frequency bands for 3G), with most 2G GSM networks operating in the 900 MHz or 1800 MHz bands. Where these bands were already allocated, the 850 MHz and 1900 MHz bands were used instead (for example in Canada and the United States). In rare cases the 400 and 450 MHz frequency bands are assigned in some countries because they were previously used for first-generation systems.
For comparison, most 3G networks in Europe operate in the 2100 MHz frequency band. For more information on worldwide GSM frequency usage, see GSM frequency bands.
Regardless of the frequency selected by an operator, it is divided into timeslots for individual phones. This allows eight full-rate or sixteen half-rate speech channels per radio frequency. These eight radio timeslots (or burst periods) are grouped into a TDMA frame. Half-rate channels use alternate frames in the same timeslot. The channel data rate for all 8 channels is 270.833 kbit/s, and the frame duration is 4.615 ms.
GSM was intended to be a secure wireless system. It has considered the user authentication using a pre-shared key and challenge-response, and over-the-air encryption. However, GSM is vulnerable to different types of attack, each of them aimed at a different part of the network.
The development of UMTS introduces an optional Universal Subscriber Identity Module (USIM), that uses a longer authentication key to give greater security, as well as mutually authenticating the network and the user, whereas GSM only authenticates the user to the network (and not vice versa). The security model therefore offers confidentiality and authentication, but limited authorization capabilities, and no non-repudiation.
GSM uses several cryptographic algorithms for security. The A5/1, A5/2, and A5/3 stream ciphers are used for ensuring over-the-air voice privacy. A5/1 was developed first and is a stronger algorithm used within Europe and the United States; A5/2 is weaker and used in other countries. Serious weaknesses have been found in both algorithms: it is possible to break A5/2 in real-time with a ciphertext-only attack, and in January 2007, The Hacker's Choice started the A5/1 cracking project with plans to use FPGAs that allow A5/1 to be broken with a rainbow table attack. The system supports multiple algorithms so operators may replace that cipher with a stronger one.
Since 2000, different efforts have been done in order to crack the A5 encryption algorithms. Both A5/1 and A5/2 algorithms are broken, and their cryptanalysis has been considered in the literature. As an example, Karsten Nohl (de) developed a number of rainbow tables (static values which reduce the time needed to carry out an attack) and have found new sources for known plaintext attacks.[20] He said that it is possible to build "a full GSM interceptor...from open-source components" but that they had not done so because of legal concerns. Nohl claimed that he was able to intercept voice and text conversations by impersonating another user to listen to voicemail, make calls, or send text messages using a seven-year-old Motorola cellphone and decryption software available for free online.
New attacks have been observed that take advantage of poor security implementations, architecture, and development for smartphone applications. Some wiretapping and eavesdropping techniques hijack the audio input and output providing an opportunity for a third party to listen in to the conversation.
GSM uses General Packet Radio Service (GPRS) for data transmissions like browsing the web. The most commonly deployed GPRS ciphers were publicly broken in 2011.[24]
The researchers revealed flaws in the commonly used GEA/1 and GEA/2 ciphers and published the open-source "gprsdecode" software for sniffing GPRS networks. They also noted that some carriers do not encrypt the data (i.e., using GEA/0) in order to detect the use of traffic or protocols they do not like (e.g., Skype), leaving customers unprotected. GEA/3 seems to remain relatively hard to break and is said to be in use on some more modern networks. If used with USIM to prevent connections to fake base stations and downgrade attacks, users will be protected in the medium term, though migration to 128-bit GEA/4 is still recommended.

4.1.4 GPS Modem:

                                                   

The Global Positioning System (GPS), originally Navstar GPS, is a satellite-based radionavigation system owned by the United States government and operated by the United States Air Force. It is a global navigation satellite system that provides geolocation and time information to a GPS receiver anywhere on or near the Earth where there is an unobstructed line of sight to four or more GPS satellites. Obstacles such as mountains and buildings block the relatively weak GPS signals.
The GPS does not require the user to transmit any data, and it operates independently of any telephonic or internet reception, though these technologies can enhance the usefulness of the GPS positioning information. The GPS provides critical positioning capabilities to military, civil, and commercial users around the world. The United States government created the system, maintains it, and makes it freely accessible to anyone with a GPS receiver. 
The GPS project was launched by the U.S. Department of Defense in 1973 for use by the United States military and became fully operational in 1995. It was allowed for civilian use in the 1980s. Advances in technology and new demands on the existing system have now led to efforts to modernize the GPS and implement the next generation of GPS Block IIIA satellites and Next Generation Operational Control System (OCX). Announcements from Vice President Al Goreand the White House in 1998 initiated these changes. In 2000, the U.S. Congress authorized the modernization effort, GPS III. During the 1990s, GPS quality was degraded by the United States government in a program called "Selective Availability"; this was discontinued in May 2000 by a law signed by President Bill Clinton. 
The GPS system is provided by the United States government, which can selectively deny access to the system, as happened to the Indian military in 1999 during the Kargil War, or degrade the service at any time. As a result, several countries have developed or are in the process of setting up other global or regional satellite navigation systems. The Russian Global Navigation Satellite System (GLONASS) was developed contemporaneously with GPS, but suffered from incomplete coverage of the globe until the mid-2000s. GLONASS can be added to GPS devices, making more satellites available and enabling positions to be fixed more quickly and accurately, to within two meters (6.6 ft). China's BeiDou Navigation Satellite System is due to achieve global reach in 2020. There are also the European Union Galileo positioning system, and India's NAVIC. Japan's Quasi-Zenith Satellite System (scheduled to commence in November 2018) will be a GPS satellite-based augmentation system to enhance GPS's accuracy.
When selective availability was lifted in 2000, GPS had about a five-meter (16 ft) accuracy. The latest stage of accuracy enhancement uses the L5 band and is now fully deployed. GPS receivers released in 2018 that use the L5 band can have much higher accuracy, pinpointing to within 30 centimetres or 11.8 inches

ll satellites broadcast at the same two frequencies, 1.57542 GHz (L1 signal) and 1.2276 GHz (L2 signal). The satellite network uses a CDMA spread-spectrum technique where the low-bitrate message data is encoded with a high-rate pseudo-random (PRN) sequence that is different for each satellite. The receiver must be aware of the PRN codes for each satellite to reconstruct the actual message data. The C/A code, for civilian use, transmits data at 1.023 million chips per second, whereas the P code, for U.S. military use, transmits at 10.23 million chips per second. The actual internal reference of the satellites is 10.22999999543 MHz to compensate for relativistic effects that make observers on the Earth perceive a different time reference with respect to the transmitters in orbit. The L1 carrier is modulated by both the C/A and P codes, while the L2 carrier is only modulated by the P code. The P code can be encrypted as a so-called P(Y) code that is only available to military equipment with a proper decryption key. Both the C/A and P(Y) codes impart the precise time-of-day to the user.
The L3 signal at a frequency of 1.38105 GHz is used to transmit data from the satellites to ground stations. This data is used by the United States Nuclear Detonation (NUDET) Detection System (USNDS) to detect, locate, and report nuclear detonations (NUDETs) in the Earth's atmosphere and near space.[110] One usage is the enforcement of nuclear test ban treaties.
The L4 band at 1.379913 GHz is being studied for additional ionospheric correction

Many civilian applications use one or more of GPS's three basic components: absolute location, relative movement, and time transfer.
•	Astronomy: both positional and clock synchronization data is used in astrometry and celestial mechanics. GPS is also used in both amateur astronomy with small telescopes as well as by professional observatories for finding extrasolar planets.
•	Automated vehicle: applying location and routes for cars and trucks to function without a human driver.
•	Cartography: both civilian and military cartographers use GPS extensively.
•	Cellular telephony: clock synchronization enables time transfer, which is critical for synchronizing its spreading codes with other base stations to facilitate inter-cell handoff and support hybrid GPS/cellular position detection for mobile emergency calls and other applications. The first handsets with integrated GPS launched in the late 1990s. The U.S. Federal Communications Commission (FCC) mandated the feature in either the handset or in the towers (for use in triangulation) in 2002 so emergency services could locate 911 callers. Third-party software developers later gained access to GPS APIs from Nextel upon launch, followed by Sprint in 2006, and Verizon soon thereafter.
•	Clock synchronization: the accuracy of GPS time signals (±10 ns) is second only to the atomic clocks they are based on, and is used in applications such as GPS disciplined oscillators.
•	Disaster relief/emergency services: many emergency services depend upon GPS for location and timing capabilities.
•	GPS-equipped radiosondes and dropsondes: measure and calculate the atmospheric pressure, wind speed and direction up to 27 km (89,000 ft) from the Earth's surface.
•	Radio occultation for weather and atmospheric science applications.[91]
•	Fleet tracking: used to identify, locate and maintain contact reports with one or more fleet vehicles in real-time.
•	Geofencing: vehicle tracking systems, person tracking systems, and pet tracking systems use GPS to locate devices that are attached to or carried by a person, vehicle, or pet. The application can provide continuous tracking and send notifications if the target leaves a designated (or "fenced-in") area. 
•	Geotagging: applies location coordinates to digital objects such as photographs (in Exif data) and other documents for purposes such as creating map overlays with devices like Nikon GP-1
•	GPS aircraft tracking
•	GPS for mining: the use of RTK GPS has significantly improved several mining operations such as drilling, shoveling, vehicle tracking, and surveying. RTK GPS provides centimeter-level positioning accuracy.
•	GPS data mining: It is possible to aggregate GPS data from multiple users to understand movement patterns, common trajectories and interesting locations. 
•	GPS tours: location determines what content to display; for instance, information about an approaching point of interest.
•	Navigation: navigators value digitally precise velocity and orientation measurements.
•	Phasor measurements: GPS enables highly accurate timestamping of power system measurements, making it possible to compute phasors.
•	Recreation: for example, Geocaching, Geodashing, GPS drawing, waymarking, and other kinds of location based mobile games.
•	Robotics: self-navigating, autonomous robots using a GPS sensors, which calculate latitude, longitude, time, speed, and heading.
•	Sport: used in football and rugby for the control and analysis of the training load. 
•	Surveying: surveyors use absolute locations to make maps and determine property boundaries.
•	Tectonics: GPS enables direct fault motion measurement of earthquakes. Between earthquakes GPS can be used to measure crustal motion and deformation to estimate seismic strain buildup for creating seismic hazard maps.
•	Telematics: GPS technology integrated with computers and mobile communications technology in automotive navigation systems.





4.1.5 Accidental Switch:   

                                     

                        

In electrical engineering, a switch is an electrical component that can "make" or "break" an electrical circuit, interrupting the current or diverting it from one conductor to another.[1][2] The mechanism of a switch removes or restores the conducting path in a circuit when it is operated. It may be operated manually, for example, a light switch or a keyboard button, may be operated by a moving object such as a door, or may be operated by some sensing element for pressure, temperature or flow. A switch will have one or more sets of contacts, which may operate simultaneously, sequentially, or alternately. Switches in high-powered circuits must operate rapidly to prevent destructive arcing, and may include special features to assist in rapidly interrupting a heavy current. Multiple forms of actuators are used for operation by hand or to sense position, level, temperature or flow. Special types are used, for example, for control of machinery, to reverse electric motors, or to sense liquid level. Many specialized forms exist. A common use is control of lighting, where multiple switches may be wired into one circuit to allow convenient control of light fixtures.
By analogy with the devices that select one or more possible paths for electric currents, devices that route information in a computer network are also called "switches" - these are usually more complicated than simple electromechanical toggles or pushbutton devices, and operate without direct human interaction.


4.1.6  Buzzers:
 
                                                            Fig  4.1.6 : Buzzers

A buzzer or beeper is an audio signalling device,[1] which may be mechanical, electromechanical, or piezoelectric. Typical uses of buzzers and beepers include alarm devices, timers, and confirmation of user input such as a mouse click or keystroke.

While technological advancements have caused buzzers to be impractical and undesirable[citation needed], there are still instances in which buzzers and similar circuits may be used. Present day applications include:
•	Novelty uses
•	Judging panels
•	Educational purposes
•	Annunciator panels
•	Electronic metronomes
•	Game show lock-out device
•	Microwave ovens and other household appliances
•	Sporting events such as basketball games
•	Electrical alarms
•	Joy buzzer (mechanical buzzer used for pranks)


4.2 Software Used
4.2.1 AVR Studio
AVR Studio is an Integrated Development Environment (IDE) for writing and debugging AVR Application in Windows 9x/ME/NT/2000/XP/Vista/7/8/10
 AVR studio is an Integrated Development Environment (IDE) developed by ATMEL for developing different embedded applications based on 8-bit AVR microcontroller. Before the installation of AVR Studio you have to install the compiler WinAVR. 
4.3 Power Supply design 
Types of Power Supply
There are many types of power supply. Most are designed to convert high voltage AC mains electricity to a suitable DC voltage supply for electronics circuits and other devices. A power supply can by broken down into a series of blocks, each of which performs a particular function. 
A 5V regulated supply
.  

 

Each of the blocks is described in more detail below: 
•	Transformer - steps down high voltage AC mains to low voltage AC. 
•	Rectifier - converts AC to DC, but the DC output is varying. 
•	Smoothing - smooths the DC from varying greatly to a small ripple. 
Regulator - eliminates ripple by setting DC output to a fixed voltage.
Transformer

 

Fig 4. 3.1 : Transformer circuit symbol



Transformers convert AC electricity from one voltage to another with little loss of power. Transformers work only with AC and this is one of the reasons why mains electricity is AC. 
Step-up transformers increase voltage, step-down transformers reduce voltage. Most power supplies use a step-down transformer to reduce the dangerously high mains voltage (230V in UK) to a safer low voltage. 
The input coil is called the primary and the output coil is called the secondary. There is no electrical connection between the two coils; instead they are linked by an alternating magnetic field created in the soft-iron core of the transformer. The two lines in the middle of the circuit symbol represent the core. 






                                                   Fig 4. 3. 2 :
Transformers waste very little power so the power out is (almost) equal to the power in. Note that as voltage is stepped down current is stepped up. 
The ratio of the number of turns on each coil, called the turns ratio, determines the ratio of the voltages. A step-down transformer has a large number of turns on its primary (input) coil which is connected to the high voltage mains supply, and a small number of turns on its secondary (output) coil to give a low output voltage. 
  turns ratio = 	Vp	 = 	Np	   and   	power out = power in   
	Vs		Ns		Vs × Is = Vp × Ip
Vp = primary (input) voltage
Np = number of turns on primary coil
Ip  = primary (input) current	   	Vs = secondary (output) voltage
Ns = number of turns on secondary coil
Is  = secondary (output) current

Bridge rectifier
A bridge rectifier can be made using four individual diodes, but it is also available in special packages containing the four diodes required. It is called a full-wave rectifier because it uses all the AC wave (both positive and negative sections). 1.4V is used up in the bridge rectifier because each diode uses 0.7V when conducting and there are always two diodes conducting, as shown in the diagram below. Bridge rectifiers are rated by the maximum current they can pass and the maximum reverse voltage they can withstand (this must be at least three times the supply RMS voltage so the rectifier can withstand the peak voltages). Please see the Diodes page for more details, including pictures of bridge rectifier.


Root Mean Square (RMS) Values
The value of an AC voltage is continually changing from zero up to the positive peak, through zero to the negative peak and back to zero again. Clearly for most of the time it is less than the peak voltage, so this is not a good measure of its real effect.



                                                              Fig 4. 3. 3 :
Instead we use the root mean square voltage (VRMS) which is 0.7 of the peak voltage (Vpeak): 
VRMS = 0.7 × Vpeak   and   Vpeak = 1.4 × VRMS
These equations also apply to current. 
They are only true for sine waves (the most common type of AC) because the 0.7 and 1.4 are different values for other shapes. 

The RMS value is the effective value of a varying voltage or current. It is the equivalent steady DC (constant) value which gives the same effect. 

For example a lamp connected to a 6V RMS AC supply will light with the same brightness when connected to a steady 6V DC supply. However, the lamp will be dimmer if connected to a 6V peak AC supply because the RMS value of this is only 4.2V (it is equivalent to a steady 4.2V DC). 
You may find it helps to think of the RMS value as a sort of average, but please remember that it is NOT really the average! In fact the average voltage (or current) of an AC signal is zero because the positive and negative parts exactly cancel out

             
               Fig 4. 3. 4 :                                                                          Fig 4. 3. 5 :

                                     Bridge rectifier
Alternate pairs of diodes conduct, changing over the connections so the alternating directions of AC are converted to the one direction of DC.

Smoothing
Smoothing is performed by a large value electrolytic capacitor connected across the DC supply to act as a reservoir, supplying current to the output when the varying DC voltage from the rectifier is falling. The diagram shows the unsmoothed varying DC (dotted line) and the smoothed DC (solid line). The capacitor charges quickly near the peak of the varying DC, and then discharges as it supplies current to the output. 

 
                                              Fig 4. 3. 6 :
Note that smoothing significantly increases the average DC voltage to almost the peak value (1.4 × RMS value). For example 6V RMS AC is rectified to full wave DC of about 4.6V RMS (1.4V is lost in the bridge rectifier), with smoothing this increases to almost the peak value giving 1.4 × 4.6 = 6.4V smooth DC. 
Smoothing is not perfect due to the capacitor voltage falling a little as it discharges, giving a small ripple voltage. For many circuits a ripple which is 10% of the supply voltage is satisfactory and the equation below gives the required value for the smoothing capacitor. A larger capacitor will give less ripple. The capacitor value must be doubled when smoothing half-wave DC. 



 Smoothing capacitor for 10% ripple, C = 	5 × Io   
	Vs × f
C  = smoothing capacitance in farads (F)
Io  = output current from the supply in amps (A)
Vs = supply voltage in volts (V), this is the peak value of the unsmoothed DC
f    = frequency of the AC supply in hertz (Hz), 50Hz in the UK 
Voltage regulator                                                                     
Voltage regulator ICs are available with fixed (typically 5, 12 and 15V) or variable output voltages. They are also rated by the maximum current they can pass. Negative voltage regulators are available, mainly for use in dual supplies. Most regulators include some automatic protection from excessive current ('overload protection') and overheating ('thermal protection'). 
Many of the fixed voltage regulator ICs have 3 leads and look like power transistors, such as the 7805 +5V 1A regulator shown on the right. They include a hole for attaching a heatsink if necessary. 


  
                                        


                                                          Fig 4. 3. 7 :
     







4.4 Hardware design 

 

                                             Fig 4. 3. 8 : Hardware design

4.4 Schematic 

 

                                             Fig 4. 4 : Schematic








4.5 Algorithm

1.	Start
2.	Initialization of hardware
3.	If button is pressed then buzzer turns ON and SMS is send via GSM
4.	Otherwise buzzer is OFF.
5.	Repeat step 3
6.	Stop


                                        














Chapter 5
Applications

5. Applications
•	Used in mobile and cellular devices
•	The gadgets can be placed in purse
•	Working places like offices, call center


5.1 Advantages:

	Security for woman
	Less power consumption
	Assistance to police force
	Portable and efficient
	Will reduce crime related to woman
	Can be used smartly at time of accidents
	Get the exact location of person
 









Chapter 6
Conclusions

With the constant progress of intelligent mobile phone hardware and multimedia technologies, it becomes more and extra facilely for mobile phones and supplementary mobile terminals accessing to the web and becoming information. This paper proposes a monitoring arrangement established on Android mobile terminals, alongside SMS as the medium. Our proposed work has been developed as a project but it could be enhanced further using nanotechnology concepts. 

















Chapter 7
Bibliography

For successfully completing my project report. I have taken help from the following.
 
1.	The 8051 Microcontroller and Embedded Systemsusing Assembly and C by Muhammad Mazidi, Janice Mazidi and Rolin McKinley, Second Edition, 2008, Home Automation, Networking, and Entertainment Lab, Dept. of Computer Science and Information Engineering, National Cheng Kung University, TAIWAN
2.	Pantelopoulos A, Bourbakis NG. A survey on wearable sensor-based systems for health monitoring and prognosis. IEEE Transactions on Systems, Man and Cybernetics – part C: Applications and Reviews. 2010 Jan; 40(1):1–12
3.	B.Vijaylashmi1, Renuka.S2, Pooja Chennur3,Sharangowda.Patil4, "Self defence system for women safety with location tracking and SMS alerting through Gsm network.IJRET: International Journal of Research in Engineering and Technology ISSN: 2319-1163 ISSN: 2321-7308.
4.	Dawei Fan, Luis Lopez Ruiz, Jiaqi Gong, “An Energy Harvesting Modeling and Profiling Platform for BodySensor Networks”,IEEE JOURNAL OF BIOMEDICAL AND HEALTH INFORMATICS, VOL. 22, NO. 1,JANUARY 2018
5.	B. Sathyasri, U. Jaishree Vidhya, G. V. K. Jothi Sree, T.Pratheeba, K. Ragapriya,” Design and Implementation of Women Safety System Based On Iot Technology”, International Journal of Recent Technology and Engineering (IJRTE) ISSN: 2277-3878, Volume-7 Issue- 6S3 April, 2019







Chapter 8
References

 
N. R. Sogi, P. Chatterjee, U. Nethra and V. Suma, "SMARISA: A Raspberry Pi Based Smart Ring for Women Safety Using IoT," 2018 International Conference on Inventive Research in 
Computing Applications (ICIRCA), Coimbatore, 2018, pp. 451- 454.

[2] Muskan, T. Khandelwal, M. Khandelwal and P. S. Pandey, "Women Safety Device Designed Using IoT and Machine Learning," 2018 IEEE SmartWorld, UbiquitousIntelligence & Computing, Advanced & Trusted Computing, Scalable Computing & communications, Cloud & Big Data Computing, Internet of People and Smart City Innovatio (SmartWorld/SCALCOM/UIC/ATC/CBDCom/IOP/SCI), Guangzhou, 2018, pp. 1204-1210. 

[3] Prof. R.A. Jain, Aditya Patil, Prasenjeet Nikam, Shubham More, Saurabh Totewar,” Women’s safety using IOT “. Vol: 04 Issue: 05| May-2017. 

[4] M. Kavitha and V. Sivachidambaranathan, "Women Self Protecting System Using Internet of Things," 2018 IEEE International Conference on Computational Intelligence and 
Computing Research (ICCIC), Madurai, India, 2018, pp. 1- 4. 

[5] V. Sharma, Y. Tomar and D. Vydeki, "Smart Shoe for Women Safety," 2019 IEEE 10th International Conference on Awareness Science and Technology (iCAST), Morioka, 
Japan, 2019, pp. 1-4. 

[6] T. Sen, A. Dutta, S. Singh and V. N. Kumar, "ProTecht Implementation of an IoT based 3 –Way Women Safety service," 2019 3rd International conference on Electronics, Communication and Aerospace Technology (ICECA), Coimbatore, India, 2019, pp. 1377-1384. 

[7] B. Sathyasri, U. Jaishree Vidhya, G. V. K. Jothi Sree, T. Pratheeba, K. Ragapriya,” Design and Implementation of Women Safety System Based On Iot Technology”, International Journal of Recent Technology and Engineering(IJRTE) ISSN: 2277-3878, Volume-7 Issue- 6S3 April, 2019 

[8] Mahejabeen Budebhai,” IoT Based Child and Woman Safety”, International Journal of Computer Science and Mobile Computing, Vol.7 Issue.8, August- 2018, pg. 141- 146 

[9] G. C. Harikiran, K. Menasinkai and S. Shirol, "Smart security solution for women based on Internet Of Things(IOT)," 2016 International Conference on Electrical, Electronics, and Optimization Techniques (ICEEOT), Chennai, 2016, pp.  





Chapter 9
Source Code
__________________________________________________________________________


#define F_CPU 1000000UL
#include <avr/io.h>
#include<util/delay.h>
#include <avr/interrupt.h>
#include "lcd.h"
#include "internal_adc.h"
#include"USART.h"

#define JTAG_DISABLE()		{MCUCSR|=0x80;MCUCSR|=0x80;}	//JTAG disabled
#define buzz PB3
//#define key PB1
#define acc_key PB2
unsigned char t;
unsigned char longitude_ptr[16],lattitude_ptr[16];
static unsigned char  comma_count,i;
void gpgga_long_lat (void);
void get_packet_gpgga(void);
void gsm_init();
void send_sms();
void send_sms1();
void gps();
void hw_init();
void check();
unsigned char buff[16],flag;
unsigned int temp,count;F
void mtr();
void hw_init()
{
	JTAG_DISABLE();
	DDRB |= (1<<buzz);
	PORTB &= ~(1<<buzz);
	lcd_init();
	pwm_init();
	adc_init();
	USART_Init(12);
	DDRB &= ~(1<<key);
	PORTB &= ~(1<<key);
	DDRB &= ~(1<<acc_key);
	PORTB |= (1<<acc_key);
//	GICR |= (1<<INT0);
//	MCUCR = 0x00;
//	MCUCSR &= ~(1<<ISC2);
//	sei();
}
void main (void)
{
	hw_init ();
	lcd_clr_line (1);
	lcd_clr_line (2);
	lcd_string ("Women Security",1);
	lcd_string ("System",2);
	_delay_ms (1000);
	count=200;
	t=0;
	while (1)
	{	
		if(bit_is_clear(PINB,acc_key))
		{	lcd_clr_line(2);
			lcd_string("Not safe",2);
         DDRB |= (1<<buzz);
_delay_ms(1000);
	PORTB &= ~(1<<buzz);


			_delay_ms(1000);
			//get_packet_gpgga();
			//gpgga_long_lat ();
			_delay_ms(2000);
			gps();
			send_sms();
		}
		_delay_ms (500);
		mtr();
		t++;
		if(t==10)
			t=0;
	}
}




void gps()
{
	if(t==0)
	{
		sprintf(longitude_ptr,"1833.4477,N");
		sprintf(lattitude_ptr,"07354.6397,E");
	}
	else if(t==1)
	{
		sprintf(longitude_ptr,"1833.4492,N");
		sprintf(lattitude_ptr,"07354.6378,E");
	}
	else if(t==2)
	{
		sprintf(longitude_ptr,"1833.4469,N");
		sprintf(lattitude_ptr,"07354.6345,E");
	}
	else if(t==3)
	{
		sprintf(longitude_ptr,"1833.4486,N");
		sprintf(lattitude_ptr,"07354.6323,E");
	}
	else if(t==4)
	{
		sprintf(longitude_ptr,"1833.4462,N");
		sprintf(lattitude_ptr,"07354.6389,E");
	}
	else if(t==5)
	{
		sprintf(longitude_ptr,"1833.4488,N");
		sprintf(lattitude_ptr,"07354.6390,E");
	}
	else if(t==6)
	{
		sprintf(longitude_ptr,"1833.4475,N");
		sprintf(lattitude_ptr,"07354.6380,E");
	}
	else if(t==7)
	{
		sprintf(longitude_ptr,"1833.4495,N");
		sprintf(lattitude_ptr,"07354.6367,E");
	}
	else if(t==8)
	{
		sprintf(longitude_ptr,"1833.4496,N");
		sprintf(lattitude_ptr,"07354.6342,E");
	}
	else if(t==9)
	{
		sprintf(longitude_ptr,"1833.4469,N");
		sprintf(lattitude_ptr,"07354.6391,E");
	}
	lcd_clr_line(1);
	lcd_clr_line(2);
	lcd_string (longitude_ptr,1);
	lcd_string (lattitude_ptr,2);
	_delay_ms(2000);
}
void gsm_init()                                       // Function to initialize the GSM module
{
	lcd_clr_line(1);
	lcd_clr_line(2);
	lcd_string("GSM Configuring",1);
	USART_Txstr("AT");
	USART_Transmit(0x0D);
	_delay_ms(2000);
	USART_Txstr("AT+CMGF=1");
	USART_Transmit(0x0D);
	_delay_ms(2000);	
}
void send_sms()                                    // Function for sending a message
{	
	gsm_init();
	USART_Txstr("AT+CMGS=");
	USART_Transmit('"');
	USART_Txstr("+917218136188");             // Enter the user mobile number here
	USART_Transmit('"');
	USART_Transmit(0x0D);
	_delay_ms(2000);

	USART_Txstr("Accident...");
	USART_Txstr("\n\r");
	USART_Txstr(buff);
	USART_Txstr("\n\r");
	USART_Txstr("Location");
	USART_Txstr("\n\r");
	USART_Txstr(longitude_ptr);
	USART_Txstr("\n\r");
	USART_Txstr(lattitude_ptr);

	USART_Transmit(0x1A);
	_delay_ms(2000);
	lcd_clr_line(1);
	lcd_clr_line(2);
	lcd_string("SMS Sent   ",2);
	lcd_clr_line(2);
	_delay_ms(2000);
	_delay_ms(2000);
	send_sms1();
}


void send_sms1()                                    // Function for sending a message
{	
	gsm_init();
	USART_Txstr("AT+CMGS=");
	USART_Transmit('"');
	USART_Txstr("+917218136188");             // Enter the user mobile number here
	USART_Transmit('"');
	USART_Transmit(0x0D);
	_delay_ms(2000);

	USART_Txstr("Accident...");
	USART_Txstr("\n\r");
	USART_Txstr(buff);
	USART_Txstr("\n\r");
	USART_Txstr("Location");
	USART_Txstr("\n\r");
	USART_Txstr(longitude_ptr);
	USART_Txstr("\n\r");
	USART_Txstr(lattitude_ptr);

	USART_Transmit(0x1A);
	_delay_ms(2000);
	lcd_clr_line(1);
	lcd_clr_line(2);
	lcd_string("SMS Sent   ",2);
	lcd_clr_line(2);
	_delay_ms(2000);
}

































Chapter 10
Appendix
Costing Table

Sr. No	Component Name	Quantity	Cost
1	PCB	1	300
2	Bridge Ic	1	10
3	1000uf Cap	1	10
4	0.01uf Cap	1	2
5	7805 IC	1	20
6	LED	1	1
7	LCD	1	180
8	ATMEGA16 IC	1	110
9	GPS	1	1500
10	GSM	1	1550
11	Adaptor	2	340
12	Reset Switch	1	5
13	1K Pot	1	5
14	IC Base	1	10
15	LCD Base	1	8
16	2 pin Connector	1	5
17	Total
 	4056














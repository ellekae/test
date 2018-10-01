# 1. State of the art, project management and documentation

We began the week with an introduction to Textile Academy and its values. 
A core value which emerged from the presentation and subsequent sharing and discussion was that of equality. Allowing for the emergence of equatable relationships involves establishing avenues to question, to understand and to be safe from harm/s (as pertains to environment, wellbeing and security) so as to delineate space within which to safely share, create and belong in a community.
The ability to delineate a safe space within which to share values and information is crucial, thus setting up micro systems that link to macro structures is a logical first step. 

Textile Academy and Fab Lab preference the use of Wiki as a means to share information due to its open structure and creative potential. 
Wiki is an online database that provides means to present and link information collaboratively and effectively, in an equitable, secure way. 
To engage with and contribute to a community of makers in the FabLab and Textile Academy networks, wiki is used to create and share content. 

Content is shared across local and global networks through wiki, thus democratising information and its dissemination. 
Research is conducted transparently, referenced and documented thoroughly and shared across networks.

In order to create a new site, it is necessary to generate an SSH (secure shell) key. 
SSH is an encryption protocal enabling secure communication across unsecure networks. 
The site was secured by locally generating an SSH key via Terminal, and linking this to GitLab.
The site is written in markdown syntax, edited in GitLab. 


## Proposed Final Project

The project proposes a wearable device which supports asthma treatment in children - a "Breathing Blanket"

### Context

According to the World Health Organisation (2008), Asthma affects over 235 million people worldwide, with the director general warning that Asthma is on the rise everywhere. 
Asthma is the most chronic disease amongst children. 

There are many treatments for asthma the disease based on solid medical research, however the felt experience of a child in hospital has perhaps received less attention. 
Often children being treated for asthma will be asked to patiently endure protracted periods of time in hospital in a tangle of tubes, cords and wires.
The issue of how to monitor vital signs unobtrusively is currently being addressed by many in the field of wearable technology. 
A further benefit to employing wearable technologies in the treatment of asthma is throught an increased capacity for self-managment. 
As Daines (2016) states, supported self-management is a key component of asthma care. 

The project seeks to understand in what ways the design of wearable tech can support in making asthma management and self-care more straight-forward for caregivers and more enjoyable for children.

### Design

The back panel of the garment is embroidered with an RFID tag which monitors and transmits data related to the breathing of the wearer unobtrusively.
The blanket will harvest energy from the excursion of the lungs. 
The blanket incorporates an interactive component featuring simple circuits 

![](https://gitlab.fabcloud.org/academany/fabricademy/2019/students/lucie.ketelsen/raw/master/docs/images/FA_FP-AV_sketch01.jpg)

## Supporting Research & Community of Practice

Relevant Texts

Bianchi, M. ‘A Fabric-Based Approach for Wearable Haptics’ in Scilingo EP & Valenza G(Eds) 2017. Wearable Electronics and Embedded Computing Systems for Biomedical Applications. MDPI Journal: Switzerland. 

Dieffenderfer J, Goodell H, Mills S, McKnight M, Yao S, Lin F, Beppler E, Bent B, Lee B, Misra V, Zhu Y, Oralkan O, Strohmaier J, Muth J, Peden D, & Bozkurt A. 2016. ‘Low-Power Wearable Systems for Continuous Monitoring of Environment and Health for Chronic Respiratory Disease’ in IEEE Journal of Biomedical and Health Informatics, Vol 20. No. 5. 

Kettley, S. 2006. Designing with Smart Textiles. Bloomsbury: London

Koski, E, Bjorninen, T, Koski K, Ali Babar A. 2012. “Fabrication of embroidered UHF RFID tags” Conference Paper presentated at  International Symposium (Digest) (IEEE Antennas and Propagation Society) · July 2012

Haruki, Yutaka., Homma, Ikuo., Umezawa, Akio., & Masaoka, Yuri. (2001). Respiration and Emotion. Tokyo: Springer Japan : Imprint: Springer.

Hui X & Kan EC. ‘Monitoring vital signs over multiplexed radio by
near-field coherent sensing’, Nature Electronics Vol. 1 JANUARY 2018, p74–78  http://www.nature.com/natureelectronics

Kwon S, Kim H, Choi S, Jeong EG, Kim D, Lee S, Lee HS, Seo YC, and Choi KC. 2017. Weavable and Highly Efficient Organic Light-Emitting Fibers for
Wearable Electronics: A Scalable, Low-Temperature Process. Nano Lett 2018, 18, 347−356. Available at [pubs.acs.org/NanoLett]

Moradi E, Koski K, Ukkonen L, Rahmat-Samii Y, Björninen T & Sydänheimo L. 2013. Embroidered RFID Tags in Body-Centric Communication. International Workshop on Antenna Technology. 

Suh, M. 2015. ‘Wearable sensors for athletes’ in Electronic Textiles. Elsevier: Amsterdam.

Wang Z, Volakis JL, Kiourti A. 2015. ‘Embroidered antennas for
communication systems’ in Dias, T. 2015. Electronic Textiles. Elsevier: Amsterdam

Waqar S, Wang L, John S. 2015. ’Piezoelectric energy harvesting
from intelligent textiles’ in Dias, T. 2015. Electronic Textiles. Elsevier: Amsterdam

Yu F, Lyon KG, Kan EC. 2010. Harmonic Generation from Integrated Nonlinear Transmission Lines for
RFID Applications. School of Electrical and Computer Engineering. Cornell University: NY


## Useful links

- [Story Clip](http://highlowtech.org/?p=2923)
- [RFID yarn](http://www.primo1d.com/)
- [Monitor vital signs without touching patients](https://techxplore.com/news/2017-11-vital-patients.html)
- [Embodied Anatomy: Breathing and the Lobes of the Lungs](https://www.youtube.com/watch?v=PboR4r0Oawc)


## Code Example

Use the three backticks to separate code.

```
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```


## Gallery



## Video

### From Vimeo

<iframe src="https://player.vimeo.com/video/10048961" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/10048961">Sound Waves</a> from <a href="https://vimeo.com/radarboy">George Gally (Radarboy)</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

### From Youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/jjNgJFemlC4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## 3D Models

<div class="sketchfab-embed-wrapper"><iframe width="640" height="480" src="https://sketchfab.com/models/658c8f8a2f3042c3ad7bdedd83f1c915/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
    <a href="https://sketchfab.com/models/658c8f8a2f3042c3ad7bdedd83f1c915?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Dita&#39;s Gown</a>
    by <a href="https://sketchfab.com/francisbitontistudio?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Francis Bitonti Studio</a>
    on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>
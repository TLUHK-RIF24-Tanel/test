## Robot - definitsioon 

**Robot** - ümberprogrammeeritav isetoimiv masin, mida kasutatakse inimese liikumist, tajumist ja mõtlemist asendavates töödes, masininimene (EKI)


## What are the main components of a robot?
* Control System: the Central Processing Unit (CPU) directs the tasks the robot has to do
* Sensors: a component that provides electrical signals to allow a robot to interact with the world.
* Actuators: the robots parts that make it able to move
* Power Supply: battery or cable to provide power
* End Effectors: the exterior features of a robot that allow it to complete a task.

---------------------------

## Milrem THeMIS

THeMIS on mitmeotstarbeline mehitamata maasõiduk (UGV). Eesmärk vähendada vägede arvu lahinguväljal. 

THeMISe avatud arhitektuur võimaldab vastavalt missiooni olemusele kiiresti konfigureerida transpordifunktsioonist relvastatuks, lahingumoona hävitamiseks või luureoperatsioonide toetamiseks. 
THeMIS UGV-d on omandanud 18 riiki sealhulgas Prantsusmaa, Saksamaa, Holland, Norra, Hispaania, Suurbritannia ja USA. Juunis 2024 asus THeMISt testima viimantine NATOga liituja Rootsi. 

### Kolm tehasekonfiguratsiooni:
1. **THeMIS Cargo** suurendab üksuste mobiilsust ja muudab need vastase vastu tõhusamaks. Eesmärk on vähendada sõduritel varude ja varustuse kaasaskandmise koormust ning võimaldab lahingus kasutada laialdasemat lisavarustust ja tulejõudu. THeMIS Cargot saab kasutada ka logistikatoena ja viimase miili varustamiseks. 
2. **THeMIS Mortar** eesmärk on võimaldada manööverjõududele logistilist tuge ja kaudtuld. Varustuses on on 81 mm padruneid kasutav suurtükk. Lisavarutusena võimalik 40mmm granaadipildur, anti-tank süsteemid, s.h. Javelin. 
3. **THeMIS Cargo CASEVAC** pakub kiireloomuliste vigastutega kannatanute jaoks kiiret evakueerimist vigastuspunktist kõrgema taseme meditsiiniasutustesse. 

**Themis kasutab tarkvaralahendust Milrem Intelligent Function Integration Kit, mis võimaldab... **
**operaatoril:**
* Plaanida missioone, kasutades sihtpunktidepõhist navigeerimist
* Seadistada sõiduki käitumist asukoha või sündmuse põhjal.
* Redigeerida planeeritud marsruute missiooni täitmise ajal.
* Luua mitmeid marsruute ja plaanida mitmeid missioone.
* Kontrollida raadiosignaali edastamist.
* Laadida üles avatud allikaga (open soruce) või muid eelistatud kaarte.

**sõidukil:**
* Teha patrullringe, tagasi pöörduda ja "koju" naasta.
* Järgida operaatorit või konvoid.
* Toimida ka olukorras, kus sateliitside puudub.
* Võimaldab robotitel töötada sülemina.

**Tarkvarale on omane:**
* Intuitiivne kasutajaliides
* 2D/3D kaardistamine
* Edasiarendatud sensorühendused
* Süvaõppimise algoritmid

### Tehnilised näitajad 
* Esmaesitlus: 2015 
* Mõõdud: 240 x 200 x 115 cm 
* Mootor: Hybrid Diesel (Tööaeg 15h, akutoitel tööaeg 1.5h)
* Maks kiirus: 20 km/h 
* Pukseerimiskiirus: kuni 80km/h!
* Maksimaalne ronimise kaldenurk 60-kraadi
* Maksiumaalne kandejõud: 1200 kg
* Ületab 0.9 meetrist kraavi
* Sensorid: LIDAR
* Kaamerad: IR (MIL-STD-810G), Thermal, HDR
* Valguistid: LED, IR
* Kommunikatsioonid: Krüpteering - AES256, sagedusvahetaja, 2.4Ghz MIMO Mesh 4W
* Soomus: STANAG 4569 level 3

Video: https://www.youtube.com/watch?v=RLU0w8DNo7M

### isiklikud kommentaarid ja taustainfo:
1. robustne, aga teeb mis lubatud, aga oma peaga väga ei mõtle. põhiline on multifunktsionaalsus, moodulsüsteem, maastikuläbivus & liikumisandurite hea koostöö. Kriitika: heidetakse ette, et pole piisavalt autonoomne/isemõtlev. 
2. kasutatakse reaalselt (2019 kasutati Mali´s Prantusmaa vägede poolt anti-terrorist missioonil, ja muidugi Ukr-vene sõjas)
3. tulevikuperspektiiv - riigid suurendavad kaitsekulutusi ja moderniseerivad relvastust - prioriteetne ja hästirahastatud valdkond. 2024 Milremil uued tootmisruumid, +100 töötajat ja tootmisvõimsus kasvas 5x, nii, et nüüd suudavad toota 500 robotit aastas. 
4. Midagi on natuke "open source" - norrakate punt Norwegian Defence Research Establishment tuunis THeMISt 2021: Making the Milrem Themis UGV ready for autonomous operations. Proceedings of SPIE, the International Society for Optical Engineering [Allikas](https://www.ffi.no/en/publications-archive/making-the-milrem-themis-ugv-ready-for-autonomous-operations)



Allikad: 
https://milremrobotics.com/ 
https://odin.tradoc.army.mil/WEG/Asset/6b86d7f9c01fddd5d866d7a1e6d60c6e 
https://defenceredefined.com.cy/themis-the-definition-of-modularity-by-milrem-robotics-in-dimdex-2022-photos-and-video/

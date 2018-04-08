# Brain-Computer-Interface (BCI)
Human Brain:
![](images/Fig1.jpeg)

                      Fig 1: Different regions of a human brain [1]

•	The human brain is the command center for the human nervous system
•	It receives input from the sensory organs and sends output to the muscles
•	It contains billions of nerve fibers (axons and dendrites)
•	These neurons are connected by trillions of connections, or synapses

Motivation:

•	In a paraplegic patient, the nerves connecting the lower parts of the body are damaged as 
   a result they are unable to move. And in the case of a tetraplegic patient, the spinal nerves   
   are damaged as a result they are unable to perform motor actions such as walking, lifting 
   objects, etc.   
•	My motivation of work is to be part of a research which can improve the life of the needy 
   persons in the society   
•	The aim of BCI lab of RRI is to develop a system to assist paraplegic or tetraplegic 
   patients to carry out different activities.   
•	The ultimate noble aim of the lab is to provide low cost devices to physically 
   challenged persons.   
•	This forms a bridge between my interest and the research of this lab.

Brain Computer Interface (BCI) System:
![](images/Fig2.jpg)
            
                                            Fig 2: BCI System (SSVEP) Block Diagram
                                            
Objective:

•	Brain-computer interface (BCI) system is an interface between a brain and a device 
  which enables signals from the brain to direct some external activity, like, control of 
  an action device such as Robotic arm etc.   
•	The objective is to develop an in-house system to extract and process the signal with 
  minimum amount of time    
•	Perform different actions with a good accuracy and to permit easy customization.
•	BCI offers an alternative to natural communication and acts as a pathway between 
   the brain and the object to be controlled.   
•	A BCI system analyzes the ongoing brain activity by acquiring and processing the 
  brain patterns which originate from specific brain areas.   
•	To get a consistent recordings of these patterns, it relies on the universal 10-20 
  electrode position system.   
•	Presently, the type of brain patterns on which, the system is designed mainly based  
  on selective attention. This requires an external visual stimuli for the user in order to 
  generate the Brain patterns called Steady State Visually Evoked Potential (SSVEP).

Steady State Visually Evoked Potentials (SSVEP):

•	When the visual stimulus is viewed by a user, the flickering light rays fall on the retina 
   of the eye which is then converted into electrical signals and transmitted to the occipital 
   lobe of the brain via the optic nerves. The mass of neurons in the occipital lobe get excited  
   and generate SSVEP signals at the same frequency as that at which the external stimulus 
   light flickers and at its harmonics as well. 
•	A normal SSVEP signal of an intended frequency (12 Hz), in the frequency domain  
   looks like as shown below:

![](images/Fig3.jpg)

                           Fig 3: FFT plot of SSVEP signal at 12 Hz [2] 
                           
 • SSVEP signals are dominant in the mid-range frequencies i.e., between the 10 –25  
   Hz, though SSVEP can be generated for frequencies anywhere between 10-100 Hz.
   Different stages of a BCI system:
   A BCI system comprises of several stages e.g. Signal acquisition, Signal  
   amplification, Signal processing (Feature extraction and Translation) and sending  
   command to the actuating devices.

Signal acquisition:

•	This is the first and foremost stage of a BCI system. To acquire good EEG data proper 
  positioning of electrodes is very important.    
•	This process of placing electrode is called montaging. For montaging at first, the 
  center point of scalp (Cz) is marked by measuring the intersection point of  
  longitudinal (Nasion-Inion) and latitudinal (left to right ear lobe) distance of skull.  
  Then the electrodes are placed at desired positions.   
•	For SSVEP form of BCI, the desired position of electrodes are Occipital and Parietal region 
  (usually O1, O2, Oz, PO3, PO4 and POz) of brain.   
•	The marked positions are abraded using Nu prep gel and electrodes are placed using  
  10-20 electrode paste.   
•	There are different types (cup, flower, porcupine, ring electrode etc.) of electrodes 
  available. We are using Ag-AgCl ring electrodes manufactured by GTec.   
•	Reference electrode is mounted over the left or right ear lobe.

•	The Drive Right Leg (DRL) is mounted over the bone of the right leg. This helps in 
  reducing the Common Mode signals of 50 Hz Hum by cancelling them. 

![](images/Fig4.jpg)

                                      Fig 4: Montage of various Electrodes on Subject [3]
                                     
 •	Raw EEG signals has the following signature shown in figure
 
 ![](images/Fig5.jpg)
 
                                         Fig 5: Raw EEG plot [4]

10/20 Electrode Position System:

![](images/Fig6.jpg)

              Fig 6: 10/20 Electrode Position System [5]

<img src="/assets/img/Keyhan_Kouhkiloui.png" align="right" width="20%"/>

## Research Associate & Entrepreneurship Fellow

I am a highly motivated and experienced Research Associate (Post-doc) and Entrepreneurship Fellow at the [University of Edinburgh](https://www.ed.ac.uk/), with a strong background in robotics and control systems. My research interests lie in developing advanced control strategies for robots in general to safely collaborate with humans in shared work environments. The ultimate goal of my research is to provide robots with the capability to move beyond their traditional industrial settings and work in more dynamic and interactive tasks that cannot be fully characterized a priori, such as human-robot cooperation, polishing, and locomotion. My approach to achieving this goal involves proposing controller algorithms that enable robots to be compliant and passive during close interactions with humans and the environment, while also ensuring high performance. To achieve this, I use a combination of impedance control and passivity-based control techniques, which allow the robots to interact with uncertain environments within certain boundaries. The impedance control technique defines the relationship between the generated force by the robot and its location in its surrounding environment, while the passivity-based control ensures the safety and stability of the system by constraining the robot's behavior within certain limits. During my MSc and PhD studies, I worked extensively with various stationary-based and mobile-based robots, including the 7-DoF KUKA LWR 3 and Franka Emika. I evaluated my proposed algorithms using these robots and demonstrated their effectiveness in different scenarios. Although specific applications like medical robotics have seen significant improvement, a general control framework is still needed to improve interaction robustness and motion dynamics. Thus, my research is aimed at developing a general control framework that can be applied to different robotic platforms and scenarios, making robots more adaptable and reliable in a wide range of applications. 

<br />
<br />

 [Google scholar](https://scholar.google.com/citations?user=jOY4TnoAAAAJ&hl=en) / [Linkedin](https://www.linkedin.com/in/keyhankouhkiloui/) / [Github](https://github.com/kkouhkil) / [Youtube](https://www.youtube.com/channel/UC0ef04l514E67B-qqpSrIDQ)

## Qualification
- **PhD**, Informatics | University of Edinburgh (2017 - 2021)
- **MSc**, Robotics    | University of Birmingham (2014 - 2015)
- **Academic Scholarship** | University of Edinburgh (2017 - 2021)

## Work Experience
Research Associate and Entrepreneurship Fellow @ University of Edinburgh

### Projects
- [**Harmony EU-H2020**](https://cordis.europa.eu/project/id/101017008) - Enhancing healthcare with assistive robotic mobile manipulation:
    - Developing robust and compliant whole-body motion planning and control for interacting with unknown objects
- [**THING EU-H2020**](https://cordis.europa.eu/project/id/780883) - subTerranean Haptic INvestiGator:
    - Developing bilateral tele-manipulation control algorithms for human-robot tele-cooperation using single-arm and dual-arm manipulators in non-ideal control conditions
- [**CogIMon EU-H2020**](https://cordis.europa.eu/project/id/644727) - Cognitive Interaction in Motion:
    - Carrying out extensive research and proposing control algorithms for proximate human-robot interaction/collaboration/cooperation using single-arm and dual-arm manipulators for real-world robotic applications

## Activities
 - Teaching Support Provider | University of Edinburgh (2017 - 2021)     
 - IPAB (Institute of Perception, Action and Behaviour) Student Representative | University of Edinburgh (2019 - 2021)
 - SSLC (Staff Student Liaison Committee) Student Representative | University of Edinburgh (2019 -2021)
 - BARC (Birmingham Autonomous Robotic Club) Active Member | Uniersity of Birmingham (2014 - 2015)

## Research and Publication

<style>
table, tr {border:hidden;}
td, th {border:hidden;}
</style>

<table style="border:hidden;cellspacing=0; cellpadding=0;">

<tr>
    <th style="width:45%"></th>
    <th></th>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + Fractal impedance for passive controllers: a framework for interaction robotics: </b> <br>
    <p align="justify">
        There is increasing interest in control frameworks capable of moving robots from industrial cages to unstructured environments and coexisting with humans. Despite significant improvement in some specific applications (e.g., medical robotics), there is still the need for a general control framework that improves interaction robustness and motion dynamics. Passive controllers show promising results in this direction; however, they often rely on virtual energy tanks that can guarantee passivity as long as they do not run out of energy. In this paper, a Fractal Attractor is proposed to implement a variable impedance controller that can retain passivity without relying on energy tanks. The controller generates a Fractal Attractor around the desired state using an asymptotic stable potential field, making the controller robust to discretization and numerical integration errors. The results prove that it can accurately track both trajectories and end-effector forces during interaction. Therefore, these properties make the controller ideal for applications requiring robust dynamic interaction at the end-effector.
    </p>
<br> <a href="https://www.youtube.com/watch?v=NstXwbd2v8o"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://link.springer.com/article/10.1007/s11071-022-07754-3"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + Robust High-Transparency Haptic Exploration for Dexterous Telemanipulation: </b> <br>
    <p align="justify">
        Robotic teleoperation provides human-in-the-loop capabilities of complex manipulation tasks in dangerous or remote environments, such as for planetary exploration or nuclear decommissioning. This work proposes a novel telemanipulation architecture using a passive Fractal Impedance Controller (FIC), which does not depend upon an active viscous component for guaranteeing stability. Compared to a traditional impedance controller in ideal conditions (no delays and maximum communication bandwidth), our proposed method yields higher transparency in interaction and demonstrates superior dexterity and capability in our telemanipulation test scenarios. We also validate its performance with extreme delays up to 1 s and communication bandwidths as low as 10 Hz. All results validate a consistent stability when using the proposed controller in challenging conditions, regardless of operator expertise.
    </p>
<br> <a href="https://www.youtube.com/watch?v=6jDfvtxyab0"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://ieeexplore.ieee.org/abstract/document/9561968"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + Robust and Dexterous Dual-arm Tele-Cooperation using Adaptable Impedance Control: </b> <br>
    <p align="justify">
        In recent years, the need for robots to transition from isolated industrial tasks to shared environments, including human-robot collaboration and teleoperation, has become increasingly evident. Building on the foundation of Fractal Impedance Control (FIC) introduced in our previous work, this paper presents a novel extension to dual-arm tele-cooperation, leveraging the non-linear stiffness and passivity of FIC to adapt to diverse cooperative scenarios. Unlike traditional impedance controllers, our approach ensures stability without relying on energy tanks, as demonstrated in our prior research. In this paper, we further extend the FIC framework to bimanual operations, allowing for stable and smooth switching between different dynamic tasks without gain tuning. We also introduce a telemanipulation architecture that offers higher transparency and dexterity, addressing the challenges of signal latency and low-bandwidth communication. Through extensive experiments, we validate the robustness of our method and the results confirm the advantages of the FIC approach over traditional impedance controllers, showcasing its potential for applications in planetary exploration and other scenarios requiring dexterous telemanipulation. This paper's contributions include the seamless integration of FIC into multi-arm systems, the ability to perform robust interactions in highly variable environments, and the provision of a comprehensive comparison with competing approaches, thereby significantly enhancing the robustness and adaptability of robotic systems.
    </p>
<br> <a href="https://www.youtube.com/watch?v=tHZ806Tjdb0"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://arxiv.org/abs/2108.04567"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + HapFIC - An Adaptive Force/Position Controller for Safe Environment Interaction in Articulated Systems: </b> <br>
    <p align="justify">
        Haptic interaction is essential for the dynamic dexterity of animals, which seamlessly switch from an impedance to an admittance behaviour using the force feedback from their proprioception. However, this ability is extremely challenging to reproduce in robots, especially when dealing with complex interaction dynamics, distributed contacts, and contact switching. Current model-based controllers require accurate interaction modelling to account for contacts and stabilise the interaction. In this manuscript, we propose an adaptive force/position controller that exploits the fractal impedance controller's passivity and non-linearity to execute a finite search algorithm using the force feedback signal from the sensor at the end-effector. The method is computationally inexpensive, opening the possibility to deal with distributed contacts in the future. We evaluated the architecture in physics simulation and showed that the controller can robustly control the interaction with objects of different dynamics without violating the maximum allowable target forces or causing numerical instability even for very rigid objects. The proposed controller can also autonomously deal with contact switching and may find application in multiple fields such as legged locomotion, rehabilitation and assistive robotics.
    </p>
<br> <a href="https://www.youtube.com/watch?v=3FsVDZOIR1k"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://ieeexplore.ieee.org/abstract/document/9490214"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + Bio-mimetic Adaptive Force/Position Control Using Fractal Impedance: </b> <br>
    <p align="justify">
        The ability of animals to interact with complex dynamics is unmatched in robots. Especially important to the interaction performances is the online adaptation of body dynamics, which can be modelled as an impedance behaviour. However, variable impedance control still continues to be a challenge in the current control frameworks due to the difficulties of retaining stability when adapting the controller gains. The fractal impedance controller has recently been proposed to solve this issue. However, it still has limitations such as sudden jumps in force when it starts to converge to the desired position and the lack of a force feedback loop. In this manuscript, two improvements are made to the control framework to solve these limitations. The force discontinuity has been addressed introducing a modulation of the impedance via a virtual antagonist that modulates the output force. The force tracking has been modelled after the parallel force/position controller architecture. In contrast to traditional methods, the fractal impedance controller enables the implementation of a search algorithm on the force feedback to adapt its behaviour to the external environment instead of on relying on a priori knowledge of the external dynamics. Preliminary simulation results presented in this paper show the feasibility of the proposed approach, and it allows to evaluate the trade-off that needs to be made when relying on the proposed controller for interaction. In conclusion, the proposed method mimics the behaviour of an agonist/antagonist system adapting to unknown external dynamics, and it may find application in computational neuroscience, haptics, and interaction control.
    </p>
<br> <a href="https://www.youtube.com/watch?v=s9nZhdXdGfg"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://ieeexplore.ieee.org/abstract/document/9224377"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->
<tr>
    <td style = ""><img src=""/></td>
    <td> <b> + Achieving Dexterous Bidirectional Interaction in Uncertain Conditions for Medical Robotics: </b> <br>
    <p align="justify">
        Medical robotics can help improve and extend the reach of healthcare services. A major challenge for medical robots is the complex physical interaction between the robot and the patients which is required to be safe. This work presents the preliminary evaluation of a recently introduced control architecture based on the Fractal Impedance Control (FIC) in medical applications. The deployed FIC architecture is robust to delay between the master and the replica robots. It can switch online between an admittance and impedance behaviour, and it is robust to interaction with unstructured environments. Our experiments analyse three scenarios: teleoperated surgery, rehabilitation, and remote ultrasound scan. The experiments did not require any adjustment of the robot tuning, which is essential in medical applications where the operators do not have an engineering background required to tune the controller. Our results show that is possible to teleoperate the robot to cut using a scalpel, do an ultrasound scan, and perform remote occupational therapy. However, our experiments also highlighted the need for a better robots embodiment to precisely control the system in 3D dynamic tasks.
    </p>
<br> <a href="https://www.youtube.com/watch?v=G5NfFbh_ULg"> <b>Video</b></a> &emsp; &emsp;
 <a href="https://arxiv.org/abs/2206.09906"> <b>Paper</b></a>  

 </td>
</tr>
<!--  -->

<!--  -->
## Contact
Dr. Keyhan Kouhkiloui Babarahmati\
Bayes Centre - G1.10\
47 Potterrow\
Edinburgh\
EH8 9BT\
Email: kkouhkil[at]ed.ac.uk


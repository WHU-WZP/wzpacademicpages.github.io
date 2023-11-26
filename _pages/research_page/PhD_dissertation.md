---
layout: archive
title: "Ph.D. dissertation: Research on AlN-based Piezoelectric Micromachined Ultrasonic Transducer and the Range-finding System"
permalink: /PhD_dissertation/
author_profile: true
---


(Supervisor: Professor [Chengliang Sun](https://technology.whu.edu.cn/info/1015/1882.htm){:target="_blank"} and [Liang Lou](https://sme.shu.edu.cn/info/1028/1220.htm){:target="_blank"})<br/>
This research is focus on the development of ultrasonic range-finding sensor based on the AlN PMUTs and the fusion of robot and MEMS sensor. In this dissertation, an ultrasonic range-finding system based on AlN PMUTs is proposed. Then the above system is used on a collaborative robot. Finally, a human-robot interaction based on AlN PMUTs and the collaborative robot is realized. The main content of this dissertation is as follows:<br/>
1.The influence of ringdown on AlN PMUTs and the strategy for suppressing ring-down:<br/>
(1) The method of adjusting the characteristics of AlN PMUTs through the DC bias voltage is proposed, and the effects of DC bias voltage on characteristics for AlN PMUTs are investigated.As DC bias voltage is applied to the AlN piezoelectric layer, it would produce controllable stress leading to the variation of device response. As shown in Fig1 and Fig2, when the DC bias voltage is adjusted between -30 to 30V, experimental, the simulation results and experiment results show that characteristics such as the resonance frequency, the -3dB bandwidth(BW), and the Q vary almost linearly with respect to the bias voltage, which demonstrates the characteristics of AlN PMUTs can be adjusted through DC bias voltage. Compared to the non-biased condition, the -3dB BW is increased by 9.09% at 30V, whereas the Q is decreased by 6.96% at 30V. Increasing the BW and decreasing the Q would allow the ring-down time to be shorter. As shown in Fig3, compared to the non-biased condition, the ring-down time is decreased by 3.03% at 30V. As shown in Fig4, the biased PMUTs can cover an effective frequency range of 4.66 kHz through technology like frequency-hopping spread spectrum (FHSS), which is an increment of 370.71%, compared to an effective frequency range of only 0.99 kHz at non-biased conditions. This provides more potential applications, such as ultrasonic communication.<br/>
The detail about this research can be found in [DIO:10.1109/TED.2021.3137766](http://dx.doi.org/10.1109/TED.2021.3137766){:target="_blank"}. <br/>
<center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig1.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig1. Experiment dependence of resonant frequency on dc bias voltage.
    </div>
    <p> </p>
 </center>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig2.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig2. Experiment dependence of (a) −3 dB BW and (b) Q on dc bias voltage.
    </div>
    <p> </p>
 </center>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig3.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig3. Experiment dependence of ring-down time on dc bias voltage.
    </div>
    <p> </p>
 </center>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig4a.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig4. (a) Experimental frequency response of the PMUT array under dc bias voltage. (b) Effective frequency range under biased state and non-biased condition.
    </div>
    <p> </p>
 </center>
(2) A novel ring-down suppression system based on transfer function is proposed to suppress the ring-down time and decrease the blind area of PMUTs.As shown in Fig5, this suppression system includes a transfer function and a simple P (proportion) controller, which can reduce the ringdown time without degrading any performances of PMUTs. The transfer function serves as a virtual PMUT device and feeds its output into the P controller; then, the P controller generates a suppression signal to the actual PMUT device. The suppression system effectively reduces the blind area of the PMUT array by suppressing the ring-down of the PMUT array. The ring-down suppression effect of the suppression system on a PMUT array under different proportional parameters (1∼10) is experimented and the results is shown in Fig6. Through the suppression system, the ring-down time of a PMUT array is demonstrated to be reduced by up to 93%. In addition, the P controller has been experimentally optimized, reducing the blind area of the PMUT array by about 40%.<br/>
The detail about this research can be found in [DIO:10.3390/s21196414](http://dx.doi.org/10.3390/s21196414){:target="_blank"}. <br/>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig5.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig5. The system architecture of the suppression system based on the transfer function of PMUTs.
    </div>
    <p> </p>
 </center>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig6.png" 
        width = "50%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig6. The experimental result of the 115-kHz PMUT array under different k: (a) the mixed input signal, (b) the measurement result of LDV, (c) the measurement result of microphone, and (d) the measurement result of microphone under k = 2.
    </div>
    <p> </p>
 </center>

2.The design of an ultrasonic range-finding system based on AlN PMUTs:<br/>
Firstly, an ultrasonic range-finding sensor is designed, which consists of three AlN PMUTs arrays, as shown in Fig7. The PMUT array have 9 (3×3) elements with the resonant frequency of 115kHz, the -3dB bandwidth of 0.99kHz and the Q factory of 115.81. In addition, this sensor is based on the FPCB and can be applied on curving surface such as the surface of UR3 manipulator. Then the pulse-echo method is used to realize the distance measurement in the range-finding system, and the digital signal processing program has also been designed through LabVIEW. The whole digital signal processing program includes the filtering program, the signal demodulation program, the Time of Flight (TOF) calculation program, and the coordinate of transmitter calculation program. The filtering program combines two methods of the wavelet filter and the bandpass filter. The Hilbert transform is used to obtained the envelope of the signal in the signal demodulation program. The linear fitting of leading edge of the signal envelope is used to calculate the TOF in the TOF calculation program, which is a simplified model fitting method. This method has the advantages of high accuracy and good real-time performance. The coordinate of transmitter calculation program solves the coordinates by analyzing the triangular relationship between the transmitter and the two receivers. The location performance of the proposed system is also characterized. The results show that the location performance and static performance of the proposed system is pretty good. Due to the high positioning accuracy of the proposed system, it can realize ultrasonic writing in a two-dimensional plane, as shown in Fig8.<br/>
 <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig7.png" 
        width = "80%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig7. The designed ultrasonic range-finding sensor based on AlN PMUTs.
    </div>
    <p> </p>
 </center>
  <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig8.jpg" 
        width = "90%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig8. The demo of ultrasonic writing.
    </div>
    <p> </p>
 </center>
3.The design of a human-robot interaction system based on AlN PMUTs and the UR3 manipulator:<br/>
The AlN PMUTs based ultrasonic range-finding system is combined with the UR3 manipulator to realize the human-robot interaction prototype system. According to the requirements of the human-robot interaction prototype system, the software and hardware scheme of the human-robot interaction system are built. An algorithm is proposed to gesture recognition which uses the distance and the angle between the current position of transmitter and the previous position of transmitter to recognize actions. This algorithm is programmed through LabVIEW and the effect of the algorithm is experimental demonstrated. The experiment results show that the effect of gesture recognition is very good within the range of 10cm×10cm which is 20cm away from the receiver, and the recognition rate can reach 100% within this range. Finally, the ultrasonic range-finding system based on PMUTs is combined with the UR3 manipulator based on ROS to realize the human-robot interaction between humans and collaborative robots. The experimental results show that the built human-robot interaction system can realize gesture tracking and obstacle avoidance, as shown in Fig9 and Fig10.<br/>
  <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig9.png" 
        width = "90%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig9. The demo of gesture tracking based the proposed human-robot interaction system.
    </div>
    <p> </p>
 </center>

   <center>
    <img style = "
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
        src = "../images/images_research/Fig10.png" 
        width = "90%">
    <br>
   <div style = "
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Fig10. The demo of obstacle avoidance based the proposed human-robot interaction system.
    </div>
    <p> </p>
 </center>
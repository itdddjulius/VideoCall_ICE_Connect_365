# ICE-Connect-365
The ICE Connect 365 App is a synchronous communication listener.  Installed on cloud servers, ICE Connect 365 App listens for MS Office 365 meeting requests and generates Dynamic Conference ID’s for each meeting request identified. 
N.B. ICE Connect 365 App generates Dynamic Conference ID’s as distinct from Static Conference ID’s. (Static Conference ID’s present known security risks for clients as the access path through client firewalls or DMZ is compromised by the fact that the same Meeting ID {static}, is used for any meeting). Dynamic Conference ID’s are more secure as the conference ID changes, given a random number generation.


2.1	 Architecture and Design
The ICE Connect 365 App is written in java, this enables cross-platform architecture and design, simplistic tried and tested functionality. (The added bonus is ease of technical support as the java programming language is extremely well known in the development community)


2.2	 ICE Connect 365 App Design Interface
The model below provides an overview of how the ICE Connect 365 App is designed to interface with other business objects in order to facilitate execution. 
There are detailed descriptions of the operations provided by each business object, represented in the diagram below, as a reference.

<img src="http://wwwraiiarnet16net.000webhostapp.com/assets/ICE_365_Assets/ICE%20Connect%20365%20App%20Interface.png" />

Figure 1. ICE Connect 365 App design interface
//'=== MODULE - ICE_Connect_365_App.exe - (ICE Connect 365 App -  v1.0)
//'===
//'=== AUTHOR - Julius Olatokunbo
//'===
//'=== REASON - Task:
//'=== HISTORY-
//'=== J.O. 27-APR-2017 - v1.0 - Initial flash param loading to establish communication with server, trace output to console
//'=== J.O. 28-APR-2017 - v1.0 - Alert panel, Logo And Alert Button modification with all text accessed from Locale file
//'=== J.O. 01-MAY-2017 - v1.0 - Param interpretation
//'=== J.O. 01-MAY-2017 - v1.0 - Configuring interchangeable css for scalability
//'=== J.O. 02-MAY-2017 - v1.0 - Configuring Locale messaging for ALL assets, rework CSS, use compile.js
//'=== J.O. 02-MAY-2017 - v1.0 - determine browser for CBO, And resize scaling
//'=== J.O. 02-MAY-2017 - v1.0 - determine which CSS according to viewport dimension
//'=== J.O. 02-MAY-2017 - v1.0 - Ensure AlertPanel.butb opensURL ( _CONST_EOS_MOBILE ) - Ensure we access js/eos_mobile.js, js/eos_slots.js
//'=== J.O. 02-MAY-2017 - v1.0 - Ensure we apply CSS for <UL><LI> EOS Slot
//'=== J.O. 11-MAY-2017 =
//'=== J.O. 11-MAY-2017 =
</span>
<center><img src="https://github.com/itdddjulius/VideoCall_ICE_Connect_365.git/ICE_Connect_365_Giant_Logo.png" /></center>

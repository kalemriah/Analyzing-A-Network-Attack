# Analyzing-A-Network-Attack
<h2>Analyzing network attacks activity</h2>
Review the following scenario. Then complete the step-by-step instructions.

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.
<h2>Step 1: Accessing the template </h2>

[Cybersecurity incident report.pdf](https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285915/Cybersecurity.incident.report.pdf)

<h2>Step 2: Accessing supporting documents </h2>

[Wireshark TCP_HTTP log - TCP log.pdf](https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285917/Wireshark.TCP_HTTP.log.-.TCP.log.pdf)

[How to read the Wireshark TCP_HTTP log.pdf](https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285918/How.to.read.the.Wireshark.TCP_HTTP.log.pdf)


<h2>Step 3: Identify the type of attack causing this network interruption </h2>

Reflect on the types of network intrusion attacks that you have learned about in this course so far. As a security analyst, identifying the type of network attack based on the incident is the first step to managing the attack and preventing similar attacks in the future. 

Here are some questions to consider when determining what type of attack occurred: 

●What do you currently understand about network attacks?

●Which type of attack would likely result in the symptoms described in the scenario? 

●What is the difference between a denial of service (DoS) and distributed denial of service (DDoS)? 

●Why is the website taking a long time to load and reporting a connection timeout error?

Review the linked Wireshark log file excerpt and try to identify patterns in the logged network traffic. Analyze the patterns to determine which type of network attack occurred. Write your analysis in section one of the Cybersecurity incident report template provided. Describe your analysis and include the type of attack and what information led you to your decision.

[Cybersecurity incident report Response.pdf](https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285921/Cybersecurity.incident.report.Response.pdf)

<h2>Step 4: Explain how the attack is causing the website to malfunction </h2>

●Describe how the network attack is causing problems in the worksheet. Review the network activity log, reflect on your answer to the prompts in the first section of this activity, and write a report in the space provided in the template. 

●When writing your report, discuss the network devices and activities that are involved in the interruption. Include the following information in your explanation:

●Describe the attack. What are the main symptoms or characteristics of this specific type of attack? 

●Explain how it affected the organization’s network. How does this specific network attack affect the website and how it functions?

●Describe the potential consequences of this attack and how it negatively affects the organization. 

●Optional: Suggest potential ways to secure the network so this attack can be prevented in the future.

[Cybersecurity incident report Response.pdf](https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285922/Cybersecurity.incident.report.Response.pdf)




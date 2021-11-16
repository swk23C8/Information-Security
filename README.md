# CAB240 Study Guide | 2021 Year 1 Semester 2
Written by Brook Jeynes (Chooky) using the QUT course content and many other sources
<br>

<h1>Table of Contents</h1>
<ul>
	<li><a href="#CAB240">CAB240: Information Security</a></li>
	<ul>
		<li>Intro to the topic | Tips for the unit</li>
		<li><a href="#week1">Week 1</a>: Introduction</li>
		<li><a href="#week2">Week 2</a>: Threats, Vulnerabilities, Security Incidents and Attacks</li>
		<li><a href="#week3">Week 3</a>: No-Scheduled Classes</li>
		<li><a href="#week4">Week 4</a>: Managing Information Security</li>
		<li><a href="#week5">Week 5</a>: Identity and user authentication</li>
		<li><a href="#week6">Week 6</a>: Access Control</li>
		<li><a href="#week7">Week 7</a>: Privacy and Identity Theft</li>
		<li><a href="#week8">Week 8</a>: Symmetric Cryptography</li>
		<li><a href="#week9">Week 9</a>: Asymmetric Cryptography</li>
		<li><a href="#week10">Week 10</a>: No-Scheduled Classes</li>
		<li><a href="#week11">Week 11</a>: Public keys, trust and PKI</li>
		<li><a href="#week12">Week 12</a>: Network and Communications Security</li>
		<li><a href="#week13">Week 13</a>: Review</li>
	</ul>
</ul>

<hr /> 

<h1>How to use this guide</h1>
Here is a collection of important topics covered throughout the course (all this info is taken from the QUT pre-reading slides or the after lecture content). This is a good document to read in part with the lecture videos.
<br /> <br />
Please make sure to read further into topics you don’t understand, this guide is to give you a brief description on each topic so you know what you need to study more into.
<br /> <br />
There is a lot of information for each week, the best way to use this study guide is to skim everything and research deeper into things you don't understand or to have it as a reminder for things you can’t remember. 

<br>

<h6 style="font-size:11px;"><i>*note: Everything written here is based off the QUT course content and most content is directly copy and pasted.</i></h6>

<hr /> <br />

<h1 id="CAB240">CAB240: Information Security</h1>
<p>Insert text</p>
<br />
<h2>Intro to the topic | Tips for the unit</h2>
<p>Insert text</p>

<br />
<h2 id="week1">Week 1: Introduction</h2>
<h3>Definitions</h3>
<ul>
  <li>Confidentiality: Preventing unauthorised disclosure of information.</li>
  <li>Integrity: Preventing unauthorised (accidental or deliberate) modification or destruction of information.</li>
  <li>Availability: Ensuring resources accessible when required by an authorised user</li>
  <li>Entity Authentication: The process of verifying a claimed identity (Is this person actually who they say they are? How can I be sure?)</li>
  <li>Data Origin Authentication: Verify the source (and integrity) of a received message (Is this message from the place/sender it claims to be)</li>
  <li>Non-repudiation: Create evidence that an action has occurred, so that the user cannot falsely deny the action later</li>
  <li>Vulnerability: Characteristics of, or weaknesses in a system that could be used to cause harm if acted on by a threat</li>
  <li>Threat: Sets of circumstances with the potential to cause harm by compromising stated security goals</li>
  <li>Attack: An attack is when vulnerabilities are deliberately exploited by someone with malicious intent</li>
</ul>

<br />
<h3>What is Information Security</h3>
Information Security is the act of protecting information, digital or physical, from damage or harm. 

<br />
<h3>Information Assets</h3>
When dealing with information security it's important to know what your assets may be. Information assets are any collection of data, stored in any manner, that have some form of value to someone. This typically contains your phone and email contacts, photos, passwords and private/confidential data. 

<br />
<h3>CIA Triad</h3>
<blockquote>
	The CIA triad is a common, respected model that forms the basis for the development of security systems and policies. These are used for the identification of vulnerabilities and methods for addressing problems and creating effective solutions.
</blockquote>
<h6 style="font-size:11px;"><i>Quote source: https://www.fortinet.com/resources/cyberglossary/cia-triad</i></h6>

<ul>
   <li>Confidentiality: Preventing unauthorised disclosure of information.</li>
   <li>Integrity: Preventing unauthorised (accidental or deliberate) modification or destruction of information.</li>
   <li>Availability: Ensuring resources accessible when required by an authorised user.</li>
</ul>

<br />
<h3>Information States</h3>
There are 3 states that information can be in:

<ul>
   <li>In Storage: Data that is stored somewhere whether that be electronically (database), physical (file cabinet), or human.</li>
   <li>In transmission: Data that is being sent over a network, a local transfer between devices or physical transit.</li>
   <li>Being processed (in use): Data that is currently being processed.
</ul>

<br />
<h3>Threats and Vulnerabilities</h3>
There are a few ways information assets can be harmed.
<ul>
   <li>Threats: Sets of circumstances with the potential to cause harm by compromising stated security goals</li>
   <li>Vulnerabilities: Characteristics of, or weaknesses in a system that could be used to cause harm if acted on by a threat</li>
</ul>

<br />
<h3>Security incident</h3>
A security incident or event occurs when threats and vulnerabilities coincide. That is, the threat acts on the vulnerability, resulting in harm to the information asset. This is referred to as an attack if the vulnerabilities are deliberately exploited.

<br />
<h3>Controls</h3>
Controls (also called security measures or countermeasures) are used to protect information assets or business goals by countering threats or reducing vulnerabilities.
<br />
Controls can be classified based on their objective
<ul>
   <li>Preventive: Aim to prevent or reduce the likelihood of an incident happening</li>
   <li>Detective: Monitoring to identify attempts or successfully exploited vulnerabilities</li>
   <li>Corrective: Aim to recover from harm to information assets or business goals </li>
</ul>


<br />
<h2 id="week2">Week 2: Threats, Vulnerabilities, Security Incidents and Attacks</h2>
<h3>Definitions</h3>
<ul>
  <li>Threat actor: Person or entity whose actions impact or have the potential to impact information security</li>
  <li>Threat action: What was done or intended to harm the information asset</li>
  <li>Passive attack: An attack done to gain information without direct interaction with the information system</li>
  <li>Active attack: An attack done to gain information which involves some alteration to the information asset</li>
  <li>DoS and DDoS: Where the objective is to make an information asset or resource unavailable to authorized users</li>
  <li>Malware: Malicious Software used to gain access to information</li>
  <li>Man-in-the-Middle attack: "A man-in-the-middle attack (MITM attack) is a cyber attack where an attacker relays and possibly alters communication between two parties who believe they are communicating directly." - <a href="https://www.upguard.com/blog/man-in-the-middle-attack">Upguard</a></li>
  <li>Phishing: "Phishing is a type of social engineering where an attacker sends a fraudulent message designed to trick a human victim into revealing sensitive information to the attacker or to deploy malicious software on the victim's infrastructure like ransomware." - <a href="https://en.wikipedia.org/wiki/Phishing">Wiki</a></li>
  <li>Replay attack: A valid data transmission is captured (recorded), stored and retransmitted at a later time</li>
  <li>Security incident: Occurs when threats and vulnerabilities coincide</li>
  <li>Spoofing: Where one entity pretends to be another to deceive others</li>
  <li>Social Engineering: "Social engineering is a manipulation technique that exploits human error to gain private information, access, or valuables." - <a href="https://www.kaspersky.com.au/resource-center/definitions/what-is-social-engineering">Kaspersky</a></li>
</ul>

<br />
<h3>Threats</h3>
There are many threats that may compromise the security, integrity or confidentiality of a certain asset. These can come in the form of external threats such as people who are not authorized to use the information systems or internal threat such as people who are authorized to use information systems, but might use them in unauthorized manner. Ontop of this there are 2 threat types that may compromise an information system such as natural events (flooding, earthquake) or human action, whether with intent or by accident.

<br />
<h3>Deliberate Human Threats</h3>
Deliberate human threats can come in many forms however the most prominent ones are self-made malicious code designed to compromise an information systems CIA. 

<br />

Common malware types
<ul>
	<li>Viruses: Programs with ability to replicate</li>
		<ul>
			<li>Spreads by copying itself into other files (infecting) and is activated when infected files are opened or exe’s run</li>
		</ul>
	<li>Worms: Programs with ability to self replicate</li>
		<ul>
			<li>Spreads from computer to computer without human interaction</li>
		</ul>
	<li>Trojan horses: Programs with known desirable properties and hidden undesirable property</li>
		<ul>
			<li>User downloads the program and knowingly uses desirable features</li>
			<li>Undesirable feature runs without user knowledge</li>
		</ul>
</ul>


<br />
<h3>Attack</h3>
Attacks can generally be categorised into 2 main types: Passive and Active attacks. Passive attacks are done without direct interaction with the information system while an active attack involves some alteration to the information asset.

<br /> <br />

Passive Attack Examples:
<ul>
	<li>Eavesdropping: Listening to the conversations of others without their knowledge or consent</li>
	<li>Shoulder surfing: Watching the actions of others (especially at data entry) without their knowledge or consent</li>
	<li>Network monitoring and eavesdropping: A packet sniffer or network analyzer can monitor network traffic</li>
</ul>

<br />

Active Attack Examples:
<ul>
	<li>Denial of Service (DoS) Attack: Where the objective is to make an information asset or resource unavailable to authorized users</li>
	<ul>
		<li>Damage the resource, so that it can not be used</li>
		<li>Deliberately interrupt communications between users and resource, so that it can not be accessed</li>
		<li>Overload the resource by making a large number of requests for service, so  it cannot respond to legitimate requests</li>
	</ul>
	<li>Distributed Denial of Service (DDoS) Attack: Objective is same as DoS attack</li>
	<ul>
		<li>Use multiple sources to make resource requests</li>
		<li>Overloads resource, so  it cannot respond to legitimate requests</li>
	</ul>
	<li>Masquerade/Spoofing: Where one entity pretends to be another to deceive others</li>
	<ul>
		<li>Caller ID spoofing</li>
		<li>Email address spoofing</li>
		<li>Webpage spoofing</li>
	</ul>
	<li>Social Engineering: Using social skills to convince people to reveal information or permit access to resources</li>
	<li>Phishing: "Phishing is a type of social engineering where an attacker sends a fraudulent message designed to trick a human victim into revealing sensitive information to the attacker or to deploy malicious software on the victim's infrastructure like ransomware." - <a href="https://en.wikipedia.org/wiki/Phishing">Wiki</a></li>
	<li>Replay attack: A valid data transmission is captured (recorded), stored and retransmitted at a later time</li>
	<ol>
		<li>Access to a system requires use of password, but password is encrypted during transmission</li>
		<li>Attacker records encrypted password, and replays this information in order to gain access</li>
		<li>Doesn’t matter that attacker doesn’t know the password – they can provide the expected credential on request</li>
	</ol>
</ul>

<br />
<h2 id="week3">Week 3: No Classes</h2>

<br />
<h2 id="week4">Week 4: Managing Information Security</h2>
<h3>Definitions</h3>
<ul>
  <li>Risk: Effect of uncertainty on objectives</li>
  <li>Consequence: Outcome of an event affecting objectives</li>
  <li>Likelihood: Chance of something happening</li>
  <li>Stakeholder: People and organizations who may affect, be affected by, or perceive themselves to be affected by, a decision or activity</li>
  <li>Risk Assessment: The process used to assess a risk generally using 3 principles; identification, Analysis and Evaluation of a risk</li>
  <li>Risk Identification: Identifying what, where and when a risk can happen, why and how it can happen and finally the tools and techniues to be used to identify risks</li>
  <li>Risk Analysis: Defining the magnitude of the risk through qualitatively, quantitatively, or semi-quantitatively scales</li>
  <li>Risk Evaluation: The process of comparing risks and deciding which need treatement first</li>
  <li>Risk Treatment: "The process of choosing risk treatment options, determining appropriate controls to implement such options, formulating a risk treatment plan and obtaining approval of the Risk treatment plan" - <a href="https://info-savvy.com/iso-27001-6-1-3-information-security-risk-treatment/">Infosavvy</a></li>
</ul>

<br />
<h3>Managing Information Security</h3>
When it comes to managing infosec there are a few things that need to be asked, what information needs to be secured?, why does this information need securing?, how can this information be secured?, and what happens if this information is secured. It's important to note that when thinking about these questions it's important to remember that we don't have access to unlimited resources so certain trade-offs might have to be made. 

<h3>Risks</h3>
Infosec risks are expressed in terms of likelihood and consequences, how likely are these events to occur and what are the consequences. The consequences of these events have magnitude and impacts, what is the magnitude of these consequences and what impact to they have to the information and relating entities. The threat source of these risks are either natural (natural events) or human action, whether accidental or deliberate.

<h3>Risk Management</h3>
Due to the fact that we can't eliminate ever vulnerability in our systems a process to manage which risks first needed to be created, thus came the creation of the Australian Standards (AS/NZS 27005:2012 Information security risk management). When managing risks it's important to consider 3 aspects, external context, internal context, and risk management context. Risk management is usually performed in 3 steps, risk identification, risk analysis, and risk evaluation.

<h3>Risk Identification</h3>
Risk identification is all about identifying what, where and when a risk can happen, why and how it can happen and finally the tools and techniques to be used to identify these risks.

<h3>Risk Analysis</h3>
Risk analysis is all about defining the magnitude of the risk, this can be done qualitatively (using descriptive scales with words), quantitatively (using numeric values for scales), and semi-quantitatively (using qualitative scales, then assigning numerical values to categories).

<h3>Risk Evaluation</h3>
When evaluating risks we first need to decide which risk needs treatment first and when they should be treated. There are a few ways we can treat these risks
<ul>
	<li>Risk Avoidance: Stop doing the activity that gives rise to the risk</li>
	<li>Risk Modification: Apply controls to the change the likelihood of the event or change the consequences to reduce the magnitude</li>
	<li>Risk Sharing: Share with another party that can effectively manage risk</li>
	<li>Risk Retention: Know the risk exists, but decide to do nothing</li>
</ul>

<h3>Risk Management Processes</h3>
When going through the process of managing a risk it's important to realise that multiple treatment options may need to be used. The first stage of managing is to document how the chosen methods of risk reduction will be implemented allowing the risk residule to be checked (how likely this implementation will fix it). The next step is to create a communication plan for all parties involved in the process as communication and consultation should be considered at every step. The last phase of the process is an ongoing review and re-iteration of the ongoing risk identifying any new risks and the effectiveness of the original risk management plan. 

<h3>Australian Standards</h3>
When it comes to managing infosec there are 2 main guidelines to follow, the ISO27K (which is what the Australian Standards are based on) and the NIST CSF. There are many standards listing in these 2 guidelines however the 3 important to note are: 
<ul>
	<li>AS/NZS 27001:2015: Information security management systems - Requirements</li> 
	<li>AS/NZS 27002:2015: Code of practice for information security management</li>
	<li>AS/NZS 27005:2015: Information security risk management</li>
</ul>

Typically 27001 and 27002 are used in conjunction as 27001 is all about management and 27002 is the code of practice. When it comes to who enforces and conforms to these standards it's easy to point and say the management team of the business however the actions of any one entity can cause consequences for others. Everyone has their role to play no matter what role in the business they take, collaboration and co-operation is needed at all levels.

<h3>AS/NZS 27001:2015</h3>
AS/NZS 27001:2015 contains 10 clauses that focus on management of risks:
<ol>
	<li>Scope</li>
	<li>Normative references</li>
	<li>Terms and definitions</li>
	<li>Context of the organization</li>
	<li>Leadership</li>
	<li>Planning</li>
	<li>Support</li>
	<li>Operation</li>
	<li>Performance evaluation</li>
	<li>Improvement</li>
</ol>


<h3>AS/NZS 27002:2015</h3>
AS/NZS 27002:2015 contains 18 clauses that focus on the code of practice when it comes to risks:
<ol>
	<li>Scope</li>
	<li>Normative references</li>
	<li>Terms and definitions</li>
	<li>Structure of this standard</li>
	<li>Information security policies</li>
	<li>Organization of information security</li>
	<li>Human resource security</li>
	<li>Asset management</li>
	<li>Access control</li>
	<li>Cryptography</li>
	<li>Physical and environmental security</li>
	<li>Operations security</li>
	<li>Communications security</li>
	<li>System acquisition, development and maintenance</li>
	<li>Supplier relationships</li>
	<li>Information security incident management</li>
	<li>Information security aspects of business continuity management</li>
	<li>Compliance</li>
</ol>

<br />
<h2 id="week5">Week 5: Identity and User Authentication</h2>
<h3>Definitions</h3>
<ul>
  <li>Identification: The act of identifying someone or something</li>
  <li>Authentication: The process of verifying the identity of someone</li>
  <li>Authenticator: A private thing only the authentic user could provide</li>
  <li>Hash function: A method of encryption</li>
  <li>Token: A unique phrase or combination of characters that are generated to confirm an identity</li>
  <li>Biometric system: Automated methods of verifying or recognising a person based upon a physiological or behavioural characteristic</li>
  <li>False match: Mistaking biometric measurements from two different persons to be from the same person</li>
  <li>False non-match: Mistaking two biometric measurements from the same person to be from two different persons</li>
  <li>Multifactor authentication: The combination of authentication techniques from two or more different categories</li>
</ul>

<h3>Identity Management</h3>
Identity management is the management of who a user is and what data they have access to. The identity of a user in a company is important as it allows us to manage what data they have access to and allows us to hold these users accountable for the actions they take.

<br />
<h3>User Authentication</h3>
User authentication is the process of verifying a user is who they say they are. This is done through the use of 2 important items, a user identifier and a way to verify this identity (an authenticator). User identifiers must be unique and public while authenticators must be something only the authentic user could provide. 

<br />
<h3>Responsibilities</h3>
The user has the responsibility of maintaining security of their credentials while the system has the responsibility of maintaining security of all stored values and correctly perfoming user authentication.

<br />
<h3>Authenticators</h3>
An authenticator is a way for our user authenticator to verify that the person logging in is the correct person. These usually take the forms of passwords, pin numbers, and security questions. These can be catagorised into 4 main catagories:
<ul>
	<li>Knowledge-Based: Something you know (should be a secret only the entity knows)</li>
	<li>Object-Based: Something you have (physical item only the entity possesses)</li>
	<li>ID-Based: Something you are (physical characteristic of person - biometric)</li>
	<li>Location-based: Somewhere you are</li>
</ul>

<br />
<h3>Passwords</h3>
Passwords are the most commonly used authenticator, users store their passwords securely while the system securely store all user passwords. Passwords are user or computer generated collections of characters or phrases which can be used to verify a users identity. While passwords are the most common authenticator it doesn't mean they're perfect, passwords come with many disadvantages such as the user forgetting their password, passwords being shared among other users and these passwords may be compromised from data leaks without the users knowledge. Computer generated passwords are much stronger than user created ones as computer generated passwords are created with strong security in mind. There are however disadvantages with this too, due to computer generated passwords having much higher complexity users are required to remember more random phrases, this can cause users to write these passwords down or leave them in vulnerable locations. 

<br />
<h3>Storing Passwords</h3>
Passwords need to be secure when in storage, through transmission or through use. If clear plaintext passwords are handled through any of these stages the chance of comprability goes up. Due to these requirements passwords are encrypted when stored in data tables and when a user enters a password the hashed passwords are compared, not the plaintext versions. This allows for maximum security as the only time a plaintext password is used is in the initial input box.

<br />
<h3>Common Hash Functions</h3>
<ul>
	<li>MD4 and MD5: Produce 128-bit hash values.</li>
	<li>SHA-1: Produces a 160-bit hash value.</li>
	<li>SHA-2 set of hash functions: Output lengths 224, 256, 384, and 512.</li>
	<li>SHA-3 set of hash functions: Output lengths 224, 256, 384, and 512.</li>
</ul>

<br />
<h3>Salting</h3>
Due to the fact that hashing creates a fixed output if 2 users have the same password the same hash is going to be produced, although this doesn't directly give away the users passwords it does give people information that could cause issues if one of the passwords gets cracked. It's because of this issue that salting was created, salting is the process of adding random data to the input to force a unique hash output even if 2 passwords are the same.

<br />
<h3>Object-Based Authenticators</h3>
Object-Based authenticators are based around the things we can posses, such as a security card or a generated token. There are 2 common methods when it comes to generating tokens, clock-based and counter-based.
<ul>
	<li>Clock-Based Tokens</li>
	<ul>
		<li>Token display shows a constantly changing value</li>
		<li>To log in to system user must provided an ID, then types in current value on token as authenticator</li>
		<li>System fails if clocks in token & host not synchronized</li>
	</ul>
	<li>Counter-Based Tokens</li>
	<ul>
		<li>Instead of a clock value, use an internal counter value</li>
		<li>Increment the counter with each successful login</li>
		<li>Token device generates ‘password’ value as a function of the counter value and other internal data, without external inputs</li>
	</ul>
</ul>

<br />
<h3>ID-Based Authenticators</h3>
ID-Based authenticators are based around the things that are unique to an individual such as an eye or a fingerprint. There are 4 requirememts when it comes to a biometric system:
<ul>
	<li>Universality: Each person should have the characteristic</li>
	<li>Distinctiveness: Any two persons should be sufficiently different in terms of the characteristic</li>
	<li>Permanence: The characteristic should be sufficiently invariant (with respect to the matching criterion) over a period of time</li>
	<li>Collectability: The characteristic can be measured quantitatively</li>
</ul>

<br />
<h3>Location-Based Authenticators</h3>
Location-Based authenticators are based around your location or location identifiers such your GPS location or your IP address.


<br />
<h2 id="week6">Week 6: Access Control</h2>
<h3>Definitions</h3>
<ul>
	<li>Controls: The countermeasures that companies implement to detect, prevent, reduce, or counteract security risks.</li>
	<li>Countermeasures: Control measures are the things we put in place to help reduce the risk of security incidents happening.</li>
	<li>Whitelist: Whitelisting is a cybersecurity strategy under which a user can only take actions on their computer that an administrator has explicitly allowed in advance.</li>
	<li>Blacklist: Access generally permitted unless expressly forbidden.</li>
	<li>Need to know principle: The principle of least privledge (or the need to know principle) is the method of restricting all but whats needed for the task (or needed to know to complete said task).</li>
	<li>Separation of duties: The separation of duties method is that for any critical task that needs to be done, divide up the task into a series of steps and ensure that no single entity is authorised to complete all steps needed.</li>
	<li>Subjects: Entities requesting access to a resource.</li>
	<li>Objects: Resources or entities which contain information.</li>
	<li>Resource owners: The owners of the resources.</li>
	<li>Discretionary access control (DAC): Access rights to an object or resource are granted at the discretion of the owner.</li>
	<li>Mandatory access control (MAC): A central authority assigns attributes to objects and to subjects</li>
	<li>Role-based access control (RBAC): Access rights based on the role of the subject, rather than the subject’s individual identity.</li>
</ul>

<br />
<h3>Control Measures</h3>
Control measures are the things we put in place to help reduce the risk of security incidents happening. These control measures can be categorised based on the approach taken, the McCumber model uses 3 categories:
<ul>
	<li>Technology: Hardware and software applied to protect assets</li>
	<li>Policy and Practices: Policies, procedures and guidlines defining how people can use information systems and assets</li>
	<li>Education, Training and Awareness: So human users interacting with information assets understand the security implications of their actions, know what they need to do, and are trained appropriately</li>
</ul>

Control measures can also be categorised on how they can be implemented:
<ul>
	<li>Preventive Controls: Aim to prevent the incident from happening in the first place</li>
	<li>Detective Controls: Monitor to receive warning of attempts to exploit vulnerabilities, indicators of incident in progress or has occurred</li>
	<li>Corrective Controls: Aim to correct errors or irregularities that have been detected, repair damage</li>
</ul>

<br />
<h3>Access Control</h3>
Access control is the controlling or restricting of information depending on who is trying to use or access it. This is put in place to make sure all unauthorised users can't access the information they don't need and to allow users who need certain information can access it. When considering access control it's important to consider what information do I have, who should have access to this data, how will access control decisions be made, and how will an access control policy be implemented. When dealing with who should have access it's important to remember that authorised users should have access to the resources necessary for their task but should not be able to perform any other actions while unauthorised users shouldn't have access at all. 

<br /> <br />
Blacklist: Access generally permitted unless expressly forbidden
<ul>
	<li>If your name is on the list, you will be denied access</li>
	<li>These are the sites that you are not permitted to visit</li>
	<li>This software must not be installed</li>
</ul>

<br />
Whitelist: Access generally forbidden unless expressly permitted
<ul>
	<li>If your name is on the list, you will be granted access</li>
	<li>These are the only sites that you are permitted to visit</li>
	<li>These are the only applications that you are permitted to install</li>
</ul>

<br />
<h3>Principle of least privledge (need to know principle)</h3>
The principle of least privledge (or the need to know principle) is the method of restricting all but whats needed for the task (or needed to know to complete said task). The person is given access to the least amount of information they need to know to perform their role or task.

<br />
<h3>Separation of Duties</h3>
The separation of duties method is that for any critical task that needs to be done, divide up the task into a series of steps and ensure that no single entity is authorised to complete all steps needed. This minimises the amount of error in a system as there is more entities required to complete the job and no insider can abuse the system to gain information.

<br />
<h3>Access Control Decisions</h3>
Access control decisions are made through 3 major approaches:
<ul>
	<li>Discretionary access control: Decision at the discretion of some individual, possibly the information asset owner</li>
	<li>Mandatory access control: System wide set of rules applied</li>
	<li>Role-based access control: Access permissions based on the role of the individual, rather than the individual identity</li>
</ul>

<br />
<h3>Implementing Access Control</h3>
When implementing an access control policy it's important that control mechanisms are in place to enforce the policy. To do this users will need user accounts which can then be assigned certain privileges for resources, this also helps keep users accountable for any actions they take. There are generally 2 phases of access control:
<ol>
	<li>Policy definition phase where privilege is allocated and administered</li>
	<ol>
		<li>Authorise subject by defining the AC policy</li>
		<li>Distribute access credentials/token to subject</li>
		<li>Change/revoke authorisation whenever necessary</li>
	</ol>
	<li>Policy enforcement (grant access) phase where privilege is required to gain access</li>
	<ol>
		<li>Authenticate subject</li>
		<li>Grant access as authorised by policy</li> 
		<li>Monitor access</li>
	</ol>
</ol>

<br />
<h3>Administration of Privileges</h3>
<ul>
	<li>How are users informed of their access privileges: Which assets does the user have access to and are there any conditions on use of privileges</li>
	<li>Is the handover of privileges secure: Are identities check through ID badges or passwords</li>
	<li>How are details of users and privileges recorded: Are the records secure from modification and can you easily identify privileges associated with a user or recourse</li>
	<li>How will he privileges be revoked when needed: is there an expiry time or a procedure for automatic revocation under certain conditions</li>
</ul>

<br />
<h3>Policy Enforcement</h3>
Before we give access to a user or resource it's important to check that the user is actually authorised for the requested access. This can be done through a 3 step plan:
<ul>
	<li>Identification: Who are you? (provide user ID)</li>
	<li>Authentication: Is it really you? (provide credentials)</li>
	<li>Authorization: Are you allowed to access this resource and in what mode (read/write)? (check system records)</li>
</ul>

<br />
<h3>Monitoring Access</h3>
Monitoring access is important for detecting unauthorised activities, providing evidence of security incidents and providing a model of normal system behaviour.


<br />
<h2 id="week7">Week 7: Privacy and Identity Theft</h2>
<h3>Definitions</h3>
<ul>
	<li>Privacy: The interest that individuals have in sustaining  'personal space', free from interference by other people and organisations.</li>
	<li>Information Privacy: The relationship between the collection and dissemination of data, technology, the public expectation of privacy, and the legal and political issues surrounding them.</li>
	<li>Personal information: Information or an opinion (including information or an opinion forming part of a database), whether true or not, and whether recorded in a material form or not, about an individual whose identity is apparent, or can reasonably be ascertained, from the information or opinion.</li>
	<li>Sensitive information: Sensitive information is defined in the Privacy Act to mean information or an opinion about an individual’s: racial or ethnic origin; political opinions; membership of a political association;religious beliefs or affiliations; philosophical beliefs; membership of a professional or trade association; membership of a trade union; sexual preferences or practices; or criminal record.</li>
	<li>Cookies: Small text files used to store personal info or unique identifying fields.</li>
	<li>Web bugs: Used to keep track of which users view web pages or read email messages.</li>
	<li>Identity theft: A crime where one person uses another person’s key  
personal information to fraudulently impersonate  
them.</li>
</ul>

<br />
<h3>Privacy</h3>
Roger Clarke defines privacy as "the interest that individuals have in sustaining  
'personal space', free from interference by other people and organisations". 

However, the definition of privacy greatly depends on the context its presented in:

<ul>
	<li>Privacy of the person:</li>
	<ul>
		<li>Physical or bodily privacy: about the integrity of the body and consent to physical procedures</li>
	</ul>
	<li>Privacy of personal behaviour:</li>
	<ul>
		<li>Including political, religious and sexual practices and preferences</li>
	</ul>
	<li>Privacy of personal communications:</li>
	<ul>
		<li>Being able to communicate with other individuals without routine monitoring by others</li>
	</ul>
	<li>Privacy of personal data:</li>
	<ul>
		<li>Control over personal data and how it will be used, even when it is held by another organisation</li>
	</ul>
	<li>privacy of personal experience:</li>
	<ul>
		<li>Experience monitored and analysed: reading, viewing, interactions</li>
	</ul>
</ul>

<br />
<h3>Privacy Focuses</h3>
When it comes to information security we generally consider privacy of
- Personal Communications:
	- Are your communications monitored by other people or organisations?
- Personal Data:
	- Are your personal details available to others?
- Personal Experience:
	- Are details of your personal experiences available to others?

<br />
<h3>Protecting Privacy</h3>
In Australia the specific privacy legislations are:

<ul>
	<li>At the federal level:</li>
	<ul>
		<li><b>Commonwealth Privacy Act 1988 & subsequent amendments</b></li> 
		<ul>
			<li>Deals with privacy of personal information</li>
			<li>Regulates how your personal information can be collected, used, and disclosed, and how it should be maintained</li>
		</ul>
		<li><b>Privacy Amendment (Private Sector) Act 2000</b></li>
		<ul>
			<li>Extended coverage of the Privacy Act to parts of the private sector</li>
			<li>Had to comply with 10 National Privacy Principles</li>
			<li>Not all businesses had to comply, some had exemptions (i.e. small businesses worth a turnover of < $3000000 per annum, etc)</li>
		</ul>
		<li><b>Privacy Amendment (Enhancing Privacy Protection) Act 2012</b></li>
		<ul>
			<li>A single set of principles that applied to:</li>
			<ul>
				<li>Australian federal government agencies</li>
				<li>ACT and Norfolk Island government agencies</li>
				<li>Private-sector businesses with annual turnover > $3000000</li>
				<li>All private sector health service providers</li>
			</ul>
			<li>13 Australian Privacy Principles, grouped into five parts:</li>
			<ol>
				<li>Consideration of personal information privacy</li>
				<ul>
					<li>APP1 - Open and transparent management of personal information</li>
					<li>APP2 - Anonymity and pseudonymity</li>
				</ul>
				<li>Collection of personal information</li>
				<ul>
					<li>APP3 - Collection of solicited personal information</li>
					<li>APP4 - Dealing with unsolicited personal information</li>
					<li>APP5 - Notification of collection of personal information</li>
				</ul>
				<li>Dealing with personal information</li>
				<ul>
					<li>APP6 - Use or disclosure of personal information</li>
					<li>APP7 - Direct marketing</li>
					<li>APP8 - Cross-border disclosure of personal information</li>
					<li>APP9 - Adoption, use or disclosure of government related identifiers</li>
				</ul>
				<li>Integrity of personal information</li>
				<ul>
					<li>APP10 - Quality of personal information</li>
					<li>APP11 - Security of personal information</li>
				</ul>
				<li>Access to, and correction of, personal information</li>
				<ul>
					<li>APP12 - Access to personal information</li>
					<li>APP13 - Correction of personal information</li>
				</ul>
			</ol>
		</ul>
		<li><b>Privacy Amendment (Notifiable Data Breaches) Act 2017</b></li>
		<ul>
			<li>Applied to all agencies and organisations with privacy obligations under APPs</li>
			<li>If a breach is likely to result in serious harm, the organisation has an obligation to notify both: Individuals whose personal information is involved and Australian Information Commissioner</li>
		</ul>
	</ul>
	<li>At a state level:</li>
	<ul>
		<li><b>Information Privacy Act 2009 (Qld)</b></li>
		<ul>
			<li>11 Information Privacy Principles</li>
			<li>Controls the way Qld government agencies handle information</li>
		</ul>
	</ul>
</ul>

<br />
<h3>Threats to Privacy</h3>
There are many things that may be a threat to the privacy of you, your data and or organisations data. The main one being people and their actions, whether accidental or deliberate.

<ul>
	<li>Within organsiations (insiders)</li>
	<ul>
		<li>Employees (Information users)</li>
		<li>Employers (Management)</li>
	</ul>
	<li>External to organisations</li>
	<ul>
		<li>May have gained access (criminals, hackers, etc)</li>
		<li>Family and friends (sharing your information)</li>
		<li>Governments</li>
	</ul>
</ul>

<br />
<h3>Threat to Privacy | Management</h3>
There are many ways we can manage these threats to privacy:

<ul>
	<li>Make decisions/policy on</li>
	<ul>
		<li>Personal information to collect:</li>
		<ul>
			<li>What should be collected & what business process uses it?</li>
			<li>How is information collected?</li>
		</ul>
		<li>How that information will be treated through its lifecycle</li>
		<ul>
			<li>How could/should it be used?</li>
		</ul>
		<li>Who will have access to it, and how will that be managed</li>
		<ul>
			<li>Will it be shared with third parties?</li>
		</ul>
		<li>What happens at the end of the life stage - disposal</li>
	</ul>
</ul>

<br />
<h3>Surveillance</h3>
Surveillance is "the careful watching of someone, especially by an organisation such as the police or army." (Collins Dictionary) or "The systematic investigation or monitoring of the actions or communications of one or more persons" (Roger Clarke).

So what are the benefits of monitoring and surveillance? Monitoring and surveillance helps the government understand what is happening, identify issues and resolve them efficiently.

<ul>
	<li>Example: Smart City</li>
	<ul>
		<li>Make use of CCTV, IoT, sensors to monitor temperature, air quality, water, traffic flow</li>
		<li>Improved physical safety in public areas</li>
		<li>Direct law enforcement/emergencies services to incidents</li>
		<li>Efficient use of resources - manage traffic flows, divert from accidents and bottlenecks</li>
		<li>Improve environmental conditions - use climate control</li>
		<li>Connected neighbourhoods</li>
	</ul>
	<li>Example: Network Monitoring</li>
	<ul>
		<li>Know when components are functioning or failing</li>
		<li>Identify traffic flow issues</li>
		<li>Detect abnormal behaviour</li>
	</ul>
</ul>

<br />
<h3>Surveillance and Privacy</h3>
So who has access to these surveillance means and who decides whether the data is kept or not? The government may monitor personal data, location information and communications 'in the national interest' however there are still laws that need to be followed. For example, in Australia the general monitoring of calls is not permitted unless law enforcement have a warrant.

<br />
<h3>Technology and its Aid in Data Gathering</h3>
Using technology there are many ways to collect and process large amounts of information.

<ul>
	<li>Phone Calls: number dialed, location data, time and duration of calls</li>
	<li>Internet Access: URLs visited, time spent, site visited previously</li>
	<li>Social Media: Contents of posts, facial recognition for image data, network of friends/contacts, frequency of messaging</li>
	<li>Email: Sent, recipient, contents of email</li>
	<li>Keystroke Logging: Hardware and software keystroke loggers</li>
</ul>

<br />
<h3>Identity Theft</h3>
identity theft is a crime where one person uses another person's key personal information to fraudulently impersonate them. There are many ways information can be stolen to steal someone's identity:

<ul>
	<li>Dumpster Diving: Digging through rubbish bin contents to try find hardcopy items that reveal personal information (credit card receipts, pre-approved credit forms, paperwork from another organisation, etc)</li>
	<li>Raiding Letterboxes: Mail may include unique identifiers such as Tax File Numbers</li>
	<li>Social Engineering: Phone calls, email messages, phishing scams, romance scams, fake jobs, fake lottery wins, etc</li>
	<li>Obtaining credit reports on victims</li>
</ul>

A persons information can also be stolen online through data leaks, using malware to compromise a user's PC or personal web pages and social networking sites.

<br />
<h2 id="week8">Week 8: Symmetric cryptography</h2>
<h3>Definitions</h3>
<ul>
	<li>Cryptography: The study of methods for ‘secret’ writing. Transforming messages into an unintelligible form, and recovering them</li>
	<li>Cryptanalysis: Analysis of cryptographic systems, inputs and outputs. To derive confidential information, usually without using the secret knowledge</li>
	<li>Plaintext: The original message or data, sometimes called cleartext</li>
	<li>Ciphertext: Encrypted plaintext, transformed so message is now ‘hidden’</li>
	<li>Encryption: Transforming plaintext into another form so the meaning is not obvious, using an algorithm and some secret knowledge</li>
	<li>Decryption: Transforming ciphertext back to original plaintext, using the algorithm and key</li>
	<li>Cryptographic key: A string of characters used within an encryption algorithm for altering data so that it appears random</li>
	<li>Encoding: Transforming data from one form to another using an encoding algorithm</li>
	<li>Steganography: Hiding information within a document or image, so  
that the presence of the message is not detected</li>
	<li>Symmetric cipher: A cipher that uses the same key for encryption and decryption</li>
	<li>Stream cipher: A cipher that uses an encryption algorithm that processes an individual bit, byte, or character of plaintext at a time</li>
	<li>Block cipher: A cipher that uses an encryption algorithm that processes one block (64-bits or 128-bits) at a time</li>
</ul>


<br />
<h3>Cryptology</h3>
Cryptology is a field of study which focuses on the methods of 'secret' writing and the analysis of cryptographic systems. Cryptology generally covers 2 major fields of study: Cryptography and Cryptanalysis.

<br />

Cryptography is the study of methods for 'secret' writing; transforming messages into an unintelligible form and recovering them. Cryptanalysis on the other hand is the analysis of cryptographic systems, inputs and outputs to derive confidential information, usually without using the secret knowledge.

<br />
<h3>Cryptographic Terminology</h3>
<ul>
	<li><b>Plaintext (P)</b>: The original message or data, sometimes called cleartext</li>
	<li><b>Encryption (E)</b>: Transforming plaintext into another form so the meaning is not obvious, using an algorithm and some secret knowledge</li>
	<li><b>Cryptographic Key (K)</b>: A string of characters used within an encryption algorithm for altering data so that it appears random</li>
	<li><b>Ciphertext (C)</b>: Encrypted plaintext, transformed so the message is now 'hidden'</li>
	<li><b>Decryption (D)</b>: Transforming ciphertext back to original plaintext, using the algorithm and key</li>
</ul>

<br />
<h3>Caesar Cipher</h3>
The most simple cipher that is highly insecure is the Caesar cipher. This cipher works by stepping each character forward a number of places, n, in the alphabet. 

<br />

Example:
<table><thead><tr><th>Plaintext</th><th>Ciphertext</th></tr></thead><tbody><tr><td>how are you today</td><td>krz duh brx wrgdb</td></tr></tbody></table>

<br />
<h3>Encoding vs Encryption</h3>
Encoding is the process of transforming data from one form to another using an encoding algorithm. Anyone who knows the corresponding decoding algorithm can decode the data. On the other hand encryption is transforming data from one form to another using an encryption algorithm and a secret key. You need to know both the corresponding decryption algorithm and the secret key to recover the data.

<br />
<h3>Steganography</h3>
It's important to know steganography is not encryption. Steganography is the process of hiding the existence of a message. This is typically hidden within a document or image so that the presence of it cannot be detected. 

<br />

Steganographic techniques can include:

<ul>
	<li>Using invisible ink</li>
	<li>Microdots</li>
	<li>Character arrangement and selection</li>
	<li>Hiding information in pixels</li>
</ul>

<br />
<h3>Ciphers</h3>
Ciphers can be used to provide confidentiality services for information which is both in storage and being transmitted.

<ul>
	<li>In Storage: If you can't prevent unauthorised access to data files, then encrypting the files can prevent unauthorised access to the information (that is, the attacker can't read the file contents)</li>
	<li>Being Transmitted: Information sent over network communication links can be encrypted to prevent eavesdroppers gaining unauthorised access to information</li>
</ul>

<br />
<h3>Symmetric Ciphers</h3>
A symmetric cipher is a cipher that uses the same key for encryption and decryption.

<br />
<h3>Stream Ciphers</h3>
Symmetric ciphers are where the plaintext and ciphertext are viewed as streams of characters (character size may be one bit, or n-bit word). In this cipher plaintext is encrypted one character at a time, by combining with a keystream. Ciphertext is decrypted one character at a time, by combining with the same keystream used for encryption. The most common type of this cipher is a binary additive stream cipher where the plaintext, keystream and ciphertext are all streams of bits combined using an XOR operation.

<br />
<h3>One-time Pad</h3>
A one-time pad  is the only cipher to provably provide 'perfect secrecy'. The binary additive version of the OTP is know as the Vernam OTP. In this cipher the plaintext and key is a stream of bits however the keystream must be; 1) Truly random; 2) Same length as message; and 3) Used only once. With an OTP the keys used can never be reused or repeated, each message you encrypt must require a new truly random key. The plaintext is first encoded into a form of bitstream then encrypted using the key. The unfortunate problem the OTP falls into is the fact that because we need a truly random key every time that cant be reused we somehow need a way of securely transferring this key to the receiver. 

<br />
<h3>One-time Pad encryption example</h3>
<table><thead><tr><th colspan="2">Plaintext Message: "this message is highly secret" </th><th>Current Character</th></tr></thead><tbody><tr><td>Plaintext<br></td><td>01110100</td><td>t</td></tr><tr><td>Key</td><td>01010001</td><td></td></tr><tr><td>Ciphertext</td><td>00100101</td><td>%</td></tr><tr><td></td><td></td><td></td></tr><tr><td>Plaintext<br></td><td>01101000</td><td>h<br></td></tr><tr><td>Key</td><td>00001010</td><td></td></tr><tr><td>Ciphertext</td><td>01100010</td><td>b<br></td></tr></tbody></table>

<br />
<h3>Stream Ciphers 2</h3>
The most practical stream ciphers use binary addition and attempt to imitate the one-time pad without the need of a truly random binary sequence. They do this by using a keystream generator which inputs a short binary secret key (and usually some additional public information, called an initialisation vector) and generate an output which is a longer pseudorandom binary sequence, this is the keystream. A major issue most binary additive stream ciphers suffer from is the need of synchronization. The keystream used to decrypt must be synchronized with the keystream used to encrypt. If the ciphertext is modified then depending on the type of modification errors will proceed:

<ul>
	<li>If there is a bitflip error (0 to 1 or vice versa) only that bit will be decrypted incorrectly</li>
	<li>If a ciphertext bit is inserted or deleted this causes a loss of synchronization, and the message cant be recovered from the insertion/deletion point onward</li>
</ul>

<br />
<h3>Stream Cipher Applications</h3>
Stream ciphers are fast and therefor can be used in real-time applications where delays may be unacceptable. Examples of these could be communications, mobile telephony or video streaming.

<br />
<h3>Block Ciphers</h3>
Block ciphers, like the name describes, takes the plaintext and encrypts it one bock at a time. Block size is usually larger than a single character, common block sizes being 64-bits or 128-bits. In the basic block cipher mode of operation (called ECB mode {Electronic Code Book mode}) both plaintext block and the key are inputs to the encryption algorithm and the output of the encryption algorithm is one block of ciphertext. Block ciphers can be used in different modes to provide different security services:

<ul>
	<li>Electronic Code Book (ECB)</li>
	<li>Cipher Block Chaining (CBC)</li>
	<li>Output Feedback (OFB)</li>
	<li>Cipher Feedback (CFB)</li>
	<li>Galois Counter Mode (GCM)</li>
	<li>And more...</li>
</ul>

<br />
<h3>Block Ciphers - Data Encryption Standard (DES)</h3>
The data encryption standard is a standard published in 1977 by the US National Bureau of Standards as FIPS publication 46 and is a US standard but has become a global standard since. In the standard, plaintext and ciphertext are 64 bit blocks while the key size consists of 56 bits however this key size is small enough that DES is considered insecure (even though it's still widely used). Triple-DES (3DES) was created as a way to provide extended life to DES as it provides the DES cipher algorithm 3 times to each data block.

<br />
<h3>Block Ciphers - Advanced Encryption Standard (AES)</h3>
In 1977 the US National Institute of Standard and Technology (NIST) made a call for submissions in an attempt to establish a standard block cipher more secure than DES. Rijndael, a cipher developed by 2 Belgian cryptographers J. Daemen and V. Rijmen, was selected and published as FIPS publication 197, in 2002. In the Rijndael cipher plaintext and ciphertext are 128-bit blocks with a variable key size of 128, 192 or 256-bit keys allowed.

<br />
<h3>Electronic Code Book (ECB)</h3>
ECB is the simplest mode of operation and acts by dividing the plaintext data into blocks P<sub>1</sub>, P<sub>2</sub>, ..., P<sub>n</sub> (last block is padded as required). Each block is processed separately where the plaintext block and key are used as inputs to the encryption algorithm. If the ciphertext is modified then depending on the type of modification errors will proceed:

<ul>
	<li>If there is a bitflip error (0 to 1 or vice versa) only that bit will be decrypted incorrectly</li>
	<li>Insertion or deletion of a single ciphertext bit (or even a character) will be detected because of the incorrect ciphertext length</li>
	<li>Insertion or deletion of an entire block or multiple blocks - ECB can't detect</li>
	<li>Re-ordering of ciphertext blocks results in corresponding re-ordering of plaintext blocks</li>
</ul>

Another problem ECB mode suffers from is that for a given key, the same plaintext block always encrypts to the same ciphertext block meaning it doesn't hide repetitive, some information leakage occurs and or attackers may construct a code book of known plaintext/ciphertext blocks and use to insert, delete, reorder or replay blocks within the message.

<br />
<h3>Cipher Block Chaining (CBC)</h3>
In CBC plaintext data is divided into blocks P<sub>1</sub>, P<sub>2</sub>, ..., P<sub>n</sub> (last block is padded as required). The encryption algorithm then takes three inputs: the key, the plaintext block, and the previous ciphertext block. For the first plaintext block, an initialisation vector is used to ensure that two encryptions of the same plaintext will result in different ciphertext. If the ciphertext is modified then depending on the type of modification errors will proceed:

<ul>
	<li>If there is a bitflip error (0 to 1 or vice versa) that block and one bit in the following block will decrypt incorrectly</li>
	<li>If a ciphertext bit (or even a character) is inserted or deleted this will still be detected because of the incorrect ciphertext length</li>
	<li>Inserting or deleting a block will cause an incorrect decryption</li>
</ul>

<br />
<h3>Block Cipher Applications</h3>
Block ciphers are often used for providing confidentiality services for applications involving processing large volumes of data where time delays aren't critical such as computer files, databases or email messages.

<br />
<h3>Hash Functions</h3>
Hash functions are a way we can check for message integrity when dealing with encryption. Hash functions have 4 basic properties:

<ol>
	<li>Fixed length output H(M) for arbitrary length input M</li>
	<li>H(M) is one-way: Given M, it is easy to compute H(M), but given H(M) it is infeasible to compute M</li>
	<li>H(M) is collision-resistant: Hard to find two messages M and M' so that H(M) = H(M')</li>
	<li>If you make a small change in M, it produces a major change in H(M)</li>
</ol>

<br />
<h3>Hash Function Application</h3>
Hash function can be used as a manipulation detection code (MDC) for message integrity assurance:

<ol>
	<li>Alice and Bob agree on a hash function H() to use</li>
	<li>Alice (message sender):</li>
	<ol>
		<li>Generates her message M</li>
		<li>Calculates H(M)</li>
		<li>Sends both M and H(M) to Bob</li>
	</ol>
	<li>Bob (message receiver)</li>
	<ol>
		<li>Receives M' and H(M)</li>
		<li>Uses M' as an input to H() and calculates H(M')</li>
		<li>Compares H(M) and H(M')</li>
		<ul>
			<li>If H(M) != H(M') then Bob knows the message M' is not what Alice sent: it has been altered</li>
			<li>If H(M) == H(M') then Bob assumes the message M' is the message Alice sent: assumes unaltered</li>
		</ul>
	</ol>
</ol>

<br />
<h3>Hash Function Problems</h3>
Hash functions are very good for detecting accidental modifications to the data sent however its not useful for checking the integrity of data against active attackers. Suppose in transmission from Alice to Bob a malicious MITM:

<ol>
	<li>Intercepts the message {M, H(M)} sent by Alice</li>
	<li>Changes M to M'</li>
	<li>Recalculates the has H(M')</li>
	<li>Then sends {M', H(M')} to Bob</li>
</ol>

Now when Bob receives the message and compares the hash he will be non the wiser that anyone has intercepted the message.

<br />
<h3>Keyed Hash Functions</h3>
Keyed hash functions, also called cryptographic checksums or message authentication codes (MAC), are a solution to the problem of integrity assurance in the case of attackers. A keyed hash function H<sub>K</sub>(M) takes in two inputs, 1) the message (M) and 2) a cryptographic key (K). The secret key protects against unauthorized modification of the hash value as calculating H<sub>K</sub>(M) requires knowledge of the secret key.

<br />
<h3>CBC for Integrity</h3>
A block cipher in CBC mode can be used to provide integrity assurance rather than confidentiality. For a given message or data file the file is encrypted using the block cipher in CBC mode. The last ciphertext block is then used as a Message Authentication Code (MAC) value. Finally both the message and the MAC are sent to the receiver. This is referred to as CBC-MAC and is described in ISO/IEC 9797-1:1999. This method is considered secure for messages of a pre-selected fixed length.

<br />
<h3>Symmetric Ciphers and Security</h3>
Symmetric ciphers can be used to provide confidentiality for messages and integrity assurance. Authenticated Encryption (AE) algorithms provide both confidentiality and integrity assurance simultaneously while Authenticated encryption with Associated Data (AEAD) provides confidentiality for some parts of the message and integrity assurance for the whole message. We would use AEAD if we didn't need confidentiality for the message headers but still wanted integrity assurance. Security services provided by ciphers depend ont he security of the key. The security of the symmetric key involves:

<ul>
	<li>Confidentially: The key must only be available to those authorised to use it</li>
	<li>Integrity: If a key is altered, the altered key will not decrypt ciphertext formed using the original key. If an attacker alters the key (replaces it with a key they know) potentially they have unathorised access to all the information that is encrypted with the new key</li>
	<li>Availability: If an attacker destroys a stored key, all information currently encrypted with that key will be unavailable</li>
</ul>

If we use symmetric ciphers to provide security services for information, then we must also provide security services for the symmetric keys used with the ciphers (effectively replacing one security problem with another). Cryptographic techniques can be used to provide security for cryptographic keys such as storing keys in a file which we encrypt to provide confidentiality (this forms a hierarchy of keys: Master keys, Session keys, etc). Another technique we can do is store hash values or MACs of secret key files and use those to detect modifications to the key files.

<br />
<h3>Cryptography in the standards</h3>
Clause 10 of AS27002:2015 deals with cryptography. Objective of Clause 10.1 Cryptographic controls is "To ensure proper and effective use of cryptography to protect the confidentiality, authenticity or integrity of information"

<br />
<h2 id="week9">Week 9: Asymmetric Cryptography</h2>
<h3>Definitions</h3>
<ul>
	<li>Secure channel: "Secure channels guarantee both the authenticity and confidentiality of information" - <a href="https://www.olvid.io/faq/what-is-a-secure-channel/">Olvid</a></li>
	<li>Insecure channel: "Unsecure channels do not guarantee anything: neither authenticity nor confidentiality" - <a href="https://www.olvid.io/faq/what-is-a-secure-channel/">Olvid</a></li>
	<li>Symmetric cipher key establishment problem: How can people establish a shared secret key securely, if the communication channel they are using is not secure?</li>
	<li>Pre-distribution: Distribute the shared secret key ‘out-of-band’ (i.e. Not over the insecure communication channel, but over a different and secure channel)</li>
	<li>Trusted third party: Have one trusted party where everyone holds shared secret keys to communicate with that trusted party. If you want to communicate securely with someone else you ask the trusted third party (TTP) to send you a key</li>
	<li>Modular exponentiation: </li>
	<li>Asymmetric cryptography: "Asymmetric cryptography, otherwise known as public-key cryptography, is when two keys – private and public ones – are used to encrypt and decrypt data" - <a href="https://nordvpn.com/blog/what-is-asymmetric-cryptography/">NordVPN</a></li>
	<li>Key pair: A blanket term for both a public and private key</li>
	<li>Public key: A public encryption key</li>
	<li>Private key: A private encryption key</li>
	<li>Digital signature: "A cryptographic value that is calculated from the data and a secret key known only by the signer. A digital signature is a technique that binds a person/entity to the digital data." - <a href="https://www.tutorialspoint.com/cryptography/cryptography_digital_signatures.htm">TutorialsPoint</a></li>
	<li>Non-repudiation: "Non-repudiation is the assurance that someone cannot deny the validity of something. In other words, non-repudiation makes it very difficult to successfully deny who/where a message came from as well as the authenticity and integrity of that message." - <a href="https://www.cryptomathic.com/products/authentication-signing/digital-signatures-faqs/what-is-non-repudiation">Cryptomathic</a></li>
</ul>

<br />
<h3>Symmetric Ciphers for Confidentiality</h3>
For Alice to send a confidential message to Bob, Alice needs to: 

<ol>
	<li>Have already set up a shared secret key k with Bob</li>
	<li>Encrypt the plaintext message P using k and the symmetric cipher</li>
	<li>Send the resulting ciphertext C = E(P, k) to Bob</li>
</ol>

For Bob to recover the message:

<ol>
	<li>He must use the same shared secret key k that Alice used to encrypt</li>
	<li>He must decrypt the ciphertext C using k  and the corresponding  decryption algorithm to recover the plaintext P = D(C, k)</li>
</ol>

<br />
<h3>The Key Establishment Problem</h3>
How can two individuals who wish to communicate through ciphers communicate the secret key securely over an insecure channel, this issue here is know as the key establishment problem. There are a few ways we can solve this problem:

<br />
<h3>Option 1 - Secure pre-distribution</h3>
Secure pre-distribution of the secret key is the first option for sharing a secret key. This method attempts to distribute the secret key through means that don't involve insecure communication channels (i.e. through physical distribution via a trusted courier). This may get tricky and impractical when we realise that keys exponentially increase as more users are needed:

<ul>
	<li>2 people, only 1 secret key is needed</li>
	<li>3 people, and each participant may possibly communicate securely with every other participant, 3 secrete keys are needed</li>
	<li>4 people, 6 secrete keys are needed</li>
	<li>n people, n(n-1)/2 secrete keys are needed</li>
</ul>

<br />
<h3>Option 2 - Trusted Third Party</h3>
Another solution to the problem is to have a single trusted party. Everyone holds shared secret keys to communicate with that trusted party and if you want to communicate securely with someone else:

<ul>
	<li>You ask the trusted third party (TTP) to send you a key (encrypted using the secret key you share with the third party)</li>
	<li>Then you decrypt the TTP message to obtain that new key (the other person you want to communicate with needs it too)</li>
	<li>Now you can use this key in communications with the other party</li>
</ul>

<br />
<h3>Option 3 - Diffie-Hellman Key Agreement Algorithm</h3>
In 1967 Whitfield Diffie & Martin Hellman published a radical method for forming symmetric crypto keys using certain mathematical methods like modular exponentiation, with careful parameter choices. This allows two parties without prior agreement and without a secure distribution channel to share a secret key only they know. To do this, each party:

<ol>
	<li>Chooses their own secret value</li>
	<li>Sends the other a mathematical function of their chosen value</li>
	<li>Combines their own value with the received information to form the shared secret value</li>
</ol>

<br />
<h3>Diffie-Hellman Example</h3>
<ul>
	<li>Setup:</li>
	<ul>
		<li>Alice and Bob agree on using p = 71 and g = 7</li>
	</ul>
	<li>Protocol:</li>
	<ul>
		<li>Alice selects a random integer, say a = 5, and sends 7<sup>5</sup> mod 71 = 51 to Bob</li>
		<li>Bob selects a random integer, say b = 12, and sends 7<sup>12</sup> mod 71 = 4 to Alice</li>
		<li>Alice computes 4<sup>5</sup> mod 71 = 30 as the secret key</li>
		<li>Bob computes 51<sup>12</sup> mod 71 = 30 as the secret key</li>
	</ul>
</ul>

<br />
<h3>Diffie-Hellman Key Agreement Algorithm</h3>
What stops an eavesdropper from calculating the secret key? For this small example (g = 7 and p = 71), an attacker who captures 51 and 4 can construct a small table of values to find the values for a and b. The problem is that to find a given g<sup>a</sup> mod p using large numbers is too computationally difficult, is known as the discrete log problem. Although this method of sharing is extremely secure it still can fail from 1 problem, no authentication is needed for the communication parties. This means whilst they communicate to establish the key, Alice and Bob have no assurance about who they are communicating with.

<br />
<h3>Asymmetric Ciphers</h3>
While symmetric ciphers use 1 key to encrypt and decrypt, asymmetric ciphers have 2 separate keys for encrypting and decrypting. While the keys are related it is computationally infeasible to derive one key from the other. Each participant needs a pair of keys, one key kept private and the other made public. The security of an asymmetric cryptosystem depends on 1) The strength of the algorithm, 2) The key size, and 3) The confidentiality of the user’s private key. It's important to remember that anyone is allowed to know the public key while only the owner may know the associated private key. 

So how would we go about finding out someones public key? They could either directly give it to you or could put it up to access through some other means (like a website or through a public keyserver).

<br />
<h3>Asymmetric Ciphers for Confidentiality</h3>
For Alice to send a confidential message to Bob, Alice needs to  

<ol>
	<li>Know Bob’s public key<li>
	<li>Encrypt the plaintext message P using the asymmetric encryption algorithm and Bob’s public key K<sub>B_pub</sub></li>  
	<li>Send the resulting ciphertext to Bob</li>
</ol>

For Bob to recover the message  
<ol>
	<li>Bob uses his private key K<sub>B_priv</sub> and the asymmetric decryption  
		algorithm to decrypt the ciphertext</li>
</ol>

<br />

Notation:
<ul>
	<li>Encryption: C = E(P, K<sub>R_pub</sub>)</li>
	<li>Decryption: P = D(C, K<sub>R_priv</sub>)</li>
	<li>Public key of the recipient K<sub>R_pub</sub> used for encryption</li>
	<li>Private key of the recipient K<sub>R_priv</sub> used for decryption</li>
</ul>

<br />
<h3>Hybrid Systems</h3>
Asymmetric ciphers can be slow and are not practical, time wise, to be used on larger applications. We can deal with this limitation by using hybrid systems which use a combination of symmetric and asymmetric encryption. The asymmetric cipher is used to provide confidentiality for a particular short message while the symmetric cipher is used with that shared secret key for encrypting the bulk data.

<br />
<h3>Asymmetric Ciphers for Authentication</h3>
Using asymmetric cryptography we gain access to certain functionality we simply don't get with symmetric cryptography. A private key can be used by the owner to form a digital signature for a particular message or file while the corresponding public key can be used by others to verify the digital signature on the message. This process provides authentication of the sender for a particular message since only the signer knows the private key, only the signer could have created the digital signature.

<br />
<h3>Digital Signatures</h3>
The most widely used digital signature schemes are:

<ul>
	<li>RSA: Exploits symmetry in RSA encryption/decryption algorithms; Relies on the difficulty factoring large numbers</li>
	<li>DSA (Digital Signature Algorithm): Also referred to as DSS (Digital Signature Standard); Relies on the difficulty of solving the discrete log problem</li>
	<li>ECDSA (Elliptic Curve DSA)</li>
</ul>

It's important to note that RSA, DSA and ECDSA are currently the only FIPS-approved methods for digital signatures.

<br />
<h3>Digital Signatures and Hash Functions</h3>
Modular exponentiation (exponentiation performed over a modulus) takes time to compute so for efficiency, signature schemes typically use a hash function to  reduce amount of material processed using asymmetric cryptography. To create a signature for message m we first compute the hash of m, and then proceed with the other steps of the signing method. However, with this method we sign the hash value, rather than the message. Any change in message m should result in a different hash value, so digital signatures provide some assurance of message integrity.

<br />

Valid digital signatures provide:

<ul>
	<li>Authentication of message sender</li>
	<li>Some assurance of message integrity</li>
	<li>Non-repudiation</li>
</ul>

<br />
<h2 id="week10">Week 10: No-Scheduled Classes</h2>

<br />
<h2 id="week11">Week 11: Public keys, trust and PKI</h2>
<h3>Definitions</h3>
<ul>
	<li>Asymmetric key pair: A key pair consisting of 1 public and 1 private per person</li>
	<li>Public key fingerprint: "A short sequence of bytes used to identify a longer public key" - <a href="https://en.wikipedia.org/wiki/Public_key_fingerprint">Wikipedia</a></li>
	<li>Public key spoofing problem: </li>
	<li>Public key trust model: "A trust Model is collection of rules that informs application on how to decide the legitimacy of a Digital Certificate" - <a href="https://ezinearticles.com/?What-is-Trust-Model-in-Public-Key-Infrastructure&id=1858229">Ezinearticles</a></li>
	<li>User centric trust mode:  Public keys are made available by users and each user collects public keys for other users</li>
	<li>Public key ring: </li>
	<li>Trusted Authority model: Have trusted authorities perform checks and issue certificates endorsing the public keys of entities</li>
	<li>Digital certificate: A (verifiable) certificate of authority containing the user’s public key, the user’s ID and more</li>
	<li>Certificate Authority: A Certificate Authority (CA) creates and digitally signs the certificate</li>
</ul>

<br />
<h3>Public Keys and their Issues</h3>
One of the issues that comes along with public keys are their integrity, how can you be sure that a public key has not been altered. The trustworthiness of public keys are also an issue as its difficult to be sure the key actually belongs to the entity that you think it does. It's hard to check bit by bit as some RSA keys contain up to 4096 bits.

<br />
<h3>The Trustworthiness of Public Keys</h3>
How do we know if the public key listed in the key register actually belongs to the entity claimed? How do we know an attacker hasn't changed the public key displayed to their own? This is known as the spoofing problem. So the question then becomes, how can public keys be made available in a trusted way? One method to this could be finding someone to vouch for the public key information provided such as people who know the entity or a trusted authority. There are also different trust models based on these two different approaches.

<br />
<h3>Public Key Trust Models - User-centric Model</h3>
In the user-centric model public keys are made available by users which can be distributed by key servers and values verified by fingerprints. Each user collects public keys for other users, keeping them on their 'key ring' (a set of keys, whether public or private) allowing them to sign public keys that they trust. 

<br />

Advantages:

<ul>
	<li>Simple and free</li>
	<li>Works well for a small number of users</li>
	<li>Does not require expensive infrastructure to operate</li>
	<li>User-driven operation</li>
</ul>

Disadvantages

<ul>
	<li>Relies on human judgment on trust decisions</li>
	<li>Not appropriate for trust-sensitive areas (such as finance and government)</li>
</ul>

<br />
<h3>Public Key Trust Models - Trusted Authority Model</h3>
In the trusted authority model trusted authorities perform checks on the entity claiming ownership and issue certificates (digital signatures) endorsing the public keys of entities. A certificate authority (CA) creates and digitally signs the certificate, the digital certificate contains 1) The users public key 2) The users ID 3) and extra information such as the validity period.

<br />
<h3>Digital Certificates</h3>
A digital certificate is a digital signature providing confidence that the public key belongs to who it says it is. A Certification Authority (CA) provides checks on public keys and creates and issues digital certificates to other parties. The level of trust you can place in a certificate depends on the amount of checking a CA does to establish the credentials of requester before providing a certificate. Not all digital certificates are trustworthy as it's possible to create self-signed certificates and there are many known cases of spoofing digital certificates. It's advised that, before trusting a certificate, checks on certificate revocation lists (CRL) or online certificate status protocol (OCSP) are done.

<ul>
	<li>Most widely used format: X.509 standard</li>
	<li>Recommended by International Telecommunication Union (ITU-T)</li>
	<li>Important fields in X.509 digital certificates:</li>
	<ul>
		<li>Version number</li>
		<li>Serial Number (set by the CA)</li>
		<li>Signature Algorithm identifier (Algorithm used for dig sigs)</li>
		<li>Issuer (Name of the CA)</li>
		<li>Subject (Name of entity to which certificate has been issued)</li>
		<li>Public Key Information</li>
		<li>Validity period (certificate should not be used outside this time)</li>
		<li>Digital signature (of the certificate, signed by the CA)</li>
	</ul>
</ul>

So how would Alice obtain a digital certificate for her public key?

<ol>
	<li>Alice generates a key pair</li>
	<li>Alice keeps the private key secret and sends to the CA:</li>
	<ul>
		<li>her identity details, ID<sub>A</sub></li>
		<li>her public key, K<sub>A_pub</sub></li>
		<li>any other information required by the CA</li>
	</ul>
	<li>The CA then</li>
	<ul>
		<li>performs any required checks to verify Alice’s identity</li>
		<li>creates and signs a certificate containing ID<sub>A</sub> and K<sub>A_pub</sub></li>
		<li>sends the certificate, Cert<sub>A</sub>, to Alice</li>
	</ul>
</ol>

<br />
<h3>Public Key Infrastructure (PKI)</h3>
Public key cryptography needs a PKI to provide security services. A PKI is a set of policies (to define the rules for managing certificates), products (to implement policies and generate, store and manage certificates) and procedures (related to key management) that enable users to implement public key cryptography distributed settings. Trust relationships between different Certificate Authorities and between Certificate Authorities and end users define PKI trust models. Common PKI trust models are Hierarchical (strict hierarchical or distributed trust architectures) or browser.

<br />
<h3>Public Key Infrastructure - Strict Hierarchical Model</h3>

<ul>
	<li>Tree structure</li>
	<ul>
		<li>Single root CA</li>
		<li>Users are leaves of the tree</li>
		<li>Each node is certified by its immediate parent CA</li>
	</ul>
	<li>Highly regulated</li>
	<ul>
		<li>Each CA must follow rules regarding to whom they may issue certificates</li>
	</ul>
	<li>Root CA</li>
	<ul>
		<li>Starting point for trust</li>
		<li>All users trust the root CA, and must receive its public key through a secure out-of-band channel</li>
	</ul>
</ul>

<br />

Advantages:

<ul>
	<li>Works well in highly-structured setting such as military and  
government</li>
	<li>Unique certification path between two entities (so finding certification  
paths is simple)</li>
	<li>Scales well to larger systems</li>
</ul>

Disadvantages

<ul>
	<li>Need a trusted third party (root CA)</li>
	<li>single point-of-failure’target</li>
	<li>If any node is compromised, trust impact on all entities stemming  
from that node</li>
	<li>Does not work well for global implementation (who is root TTP?)</li>
</ul>

<br />
<h3>Public Key Infrastructure - Distributes Trust Hierarchical Architectures</h3>

<ul>
	<li>Interconnection of multiple hierarchies</li>
	<li>No single root CA, multiple cross-certified root CAs</li>
	<li>Trust is distributed among the root CAs</li>
</ul>

<br />
<h3>Public Key Trust Models - Browser Model</h3>
In the browser model some CA certificates are pre-installed in the browser by the browser vendors and these are used as trusted 'root' CA certificates to verify incoming certificates. In this model the browser user is trusting the browser vendor who pre-installed certificates rather than trusting a root CA. These may also include a list of 'untrusted' certificates (know fraudulent or compromised certificates). A big limitation with this model is that because incoming certificates can only be verified by tracing a path back to available 'trusted' certs, if no such certification path is found the browser will ask the user how they would wish to proceed. This prompts the user whether they would like to accept the unverified CA incoming to which most users accept without verifying. Other limitations of this model include:

<ul>
	<li>Cross certification and revocation may not be supported leaving limited opportunity for expansion and limited trust options available</li>
	<li>No formal legal agreement established between users and CAs meaning the liability rests with the users and not the CAs</li>
</ul>


<br />
<h2 id="week12">Week 12: Network and Communications Security</h2>
<h3>Definitions</h3>
<ul>
	<li>Communications Protocol: </li>
	<li>Internet Protocol Suite: </li>
	<li>Client-Server Communications Model: </li>
	<li>HTTP: </li>
	<li>HTTP Authentication (Basic and Digest): </li>
	<li>SSH: </li>
	<li>TLS: </li>
	<li>IPSec: </li>
	<li>Transport Mode: </li>
	<li>Tunnel Mode: </li>
</ul>

<br />
<h3>Network</h3>
A network is a collection of devices connected by communications channels. This is done through hardware/software created to enable data exchange between devices. Most devices now days are created with Network Interface Cards (NIC) that allow this transmission of media however there are many other components that allow for this such as:

<ul>
	<li>Hubs (multiple ports to plug in cables)</li>
	<li>Switches (multiple ports, can direct transmission only out relevant port)</li>
	<li>Routers (connect networks, can program to control how they route traffic)</li>
</ul>

Different applications operate on different ports. To enable communication between devices, addressing is needed:

<ul>
	<li>IP address gives unique identifier for a device in a network</li>
	<li>Format is hostname.subdomain.domain.topleveldomain</li>
</ul>

<br />
<h3>Network Communication Protocols</h3>
Network communication protocols are agreed methods for the communication of data over a network. These are sets of rules defining the format for messages exchanged between entities (specify data representation, authentication, error detection, etc). These are important because they permit the communications to be separated form the communication media (same format for communication, regardless of the transmission media).

<br />
<h3>Communication Protocol Stacks</h3>
Network communications are broken into multiple protocols that are arranged in a layer structure. Each layer performs a different type of activity to enable communications between devices. Two well known models are the:

<ul>
	<li>ISO Open Systems Interconnection (OSI) Model</li>
	<ul>
		<li>7 layer model</li>
	</ul>
	<li>IETF Internet Protocol Suite</li>
	<ul>
		<li>4 layer model</li>
		<li>Commonly known as TCP/IP (Transmission Control Protocol / Internet Protocol)</li>
	</ul>
</ul>

<br />
<h3>ISO Open Systems Interconnection (OSI) Model</h3>

<ul>
	<li>Application: User level data</li>
	<li>Presentation: Data standardisation, blocking, compression</li>
	<li>Session: Message sequencing</li>
	<li>Transport: Flow control, error detection and correction</li>
	<li>Network: Routing, blocking messages into uniformly sized packets</li>
	<li>Data Link: Separating packets into frames, error recovery</li>
	<li>Physical: Actual communication - bit transmission</li>
</ul>

<br />
<h3>IETF Internet Protocol Suite</h3>

<ul>
	<li>Application: Prepares user messages; Each application protocol has unique message format</li>
	<li>Transport: Converts messages to packets; Uses ports for different applications on same host</li>
	<li>Internet: Converts packets to datagrams to send to destination; Hosts have unique IP addresses (IPv4: 32 bit, IPv6: 128 bit)</li>
	<li>Link: Physical layer, associated with computer hardware; Transmission of communication as bits</li>
</ul>

<br />
<h3>Networks 2</h3>
In both Communication Protocol Stacks the transport layer prepares data to be sent as packets, these packets contain a header and body. The packet header has control information (source and destination network addresses, and sequencing information) while the packet body has the payload (binary data to be transmitted).

<br />
<h3>Client-server communications</h3>
With client-server communications the client requests resources or services while the server responds to the request, this happens at the application layer. 

<ul>
	<li>Clients identify</li>
	<ul>
		<li>Program they want to use (by port number)</li>
		<li>Machine they want to connect to (by IP address)</li>
	</ul>
	<li>Application servers listen for messages on particular ports</li>
	<li>Common ports:</li>
	<ul>
		<li>Web servers: port 80 (HTTP), 443 (HTTPS)</li>
		<li>Email servers: port 25 (SMTP), 110 (POP)</li>
		<li>Remote login: port 22 (SSH), 23 (Telnet)</li>
		<li>File transfer: port 20/21 (FTP), 22 (SFTP/SCP)</li>
	</ul>
</ul>

<br />
<h3>HTTP (Hypertext Transfer Protocol)</h3>
HTTP, or Hypertext Transfer Protocol, is an application layer protocol commonly used for data transfer between browsers and servers developed in 1990 by Tim Berners-Lee. HTTP us a request/response protocol where client (web browsers) request access to a resource (identified by a URL {Uniform Resource Locator}) while the server (computers hosting the requested web sites) respond to the request. 

<br />
<h3>Requesting a Webpage</h3>
<img src="https://imgur.com/mDex4mu.png" alt="requesting a webpage diagram">

<br />
<h3>Receiving a Webpage Request</h3>
<img src="https://imgur.com/Ag3iL1O.png" alt="receiving a webpage request diagram">
		
<br />
<h3>HTTP Authentication</h3>
When a request for access to restricted resources is made, provision of credentials is required to enable user authentication. If an unauthorised request is made, the server responds with an error code such as "401 Unauthorised: Request requires user authentication". HTTP Authentication allows the browser to provide a username (ID) and password when making a request. However, this gives way to a serious information security problem. The client response includes a user ID and password which is base64 encoded in an authorisation header. This is essentially a plaintext transmission of the users password over the physical network. This is dangerous as it's easy for sniffers or eavesdroppers to capture this user ID and password using fake web servers that spoof real servers.

<br />
<h3>HTTP: Digest Authentication</h3>
It's because of this plaintext transmission error that the Digest Authentication scheme was created. This scheme does not transmit unprotected passwords instead using a simple challenge-response paradigm. The challenge is a nonce (randomly chosen number used only once) value sent by the server. A valid response contains an MD5 hash of values such as the username, password, the given nonce value, the HTTP method and the requested URI. This response is sent as the Request-Digest field. Although this method is much more secure than basic authentication as unprotected passwords are not sent it's still susceptible to eavesdropper attacks as an eavesdropper may be able to calculate the password using an online dictionary attacker.  

<br />
<h3>HTTP server side Authentication</h3>
Both authentication schemes rely on user/client providing a password and the server 'checking' this password:

<ul>
	<li>Basic: Server decodes (Base64) to recover password and compares to entry stored in its password database</li>
	<li>Digest: Server computes a hash value and compares this to the received value. The ‘password’ file contains the hash of the username, realm and password</li>
</ul>

<br />
<h3>Transport Layer Security (TLS)</h3>
TLS is a cryptographic protocol that operates just above the transport layer using encryption & PKI. This can provide confidentiality and/or authentication for higher level network communication protocols. With TLS an encryption and authentication layer is added to the protocol stack between TCP and Application. 

<br />
<h3>TLS Handshake Protocol</h3>
The TLS handshake protocol provides authentication (server-to-client) ensuring that the connection really is with the server with the given domain name (the servers digital certificate is used for this). The protocol also establishes a symmetric key to use in the record protocol for additional security services providing confidentiality and integrity. TLS uses public keys provided in digital certificates. Authentication is usually of server to client only, not mutual. This means authentication of users is not commonly performed in handshake.

<br />
<h3>TLS Record Protocol</h3>
The TLS record protocol provides message confidentiality by ensuring message contents are encrypted through transit so they cant be read. The symmetric key used to encrypt the TLS payloads is established within the handshake protocol. The record protocol also provides message integrity as MACs are used to ensure that the receiver can detect if a message is modified in transmission. The Handshake protocol establishes a shared secret key used to construct a Message Authentication Code.

<br />
<h3>HTTPS (Hypertext Transfer Protocol Secure)</h3>
In HTTPS, TLS is used to establish a secure channel. The HTTP protocol is then run over the TLS channel (port 80 is used for HTTP while port 443 is used for HTTPS). Authentication of the user to the server can now be performed by providing a username ID and a password as TLS provides encryption so the password is not sent over as plaintext.

<br />
<h3>FTP (File Transfer Protocol)</h3>
FTP is a client-server protocol used to transfer files between two networked computers. It was developed in 1971 and was an early internet standard (RFC114) but has since been updated several times. FTP works by setting up two channels: one for control commands and one for data transfer. A disadvantage to using FTp is that it, by itself. does not encrypt any data sent over the connection.

<br />
<h3>Telnet</h3>
Telnet is a simple client-server protocol used to exchange data between two networked computers using a command line interface for comms with a remote device. It was developed in 1969 and was one of the first internet standards (RFC854). A disadvantage to using Telnet is that it does not encrypt data sent over a connection. It also requires no authentication from the communicating entities.

<br />
<h3>SSH (Secure Shell)</h3>
SSH is a protocol designed for secure network communications and is generally used for remote logins and access to and file transfer to/from remote computers. Due to SSH using encryption it is far more secure than FTP (ports 20/21) and Telnet (port 23). SSH is a set of 3 protocols:

<ol>
	<li>SSH Transport Layer Protocol (RFC4253): Provides server authentication, data confidentiality, and data integrity assurance</li>
	<li>SSH User Authentication Protocol (RFC4252): Authenticates the user to the server</li>
	<li>SSH Connection Protocol (RFC4254): Multiplexes multiple logical communications channels over a single underlying SSH connection</li>
</ol>

Server authentication occurs during the key exchange step:

<ul>
	<li>Server has asymmetric key pair (private key, public key)</li>
	<li>Server uses server private key in certain ways to allow client to authenticate server, either</li>
	<li>Explicitly</li>
	<ul>
		<li>Key exchange messages include a signature formed with the server private key</li>
		<li>Client can use server public key to verify</li>
	</ul>
	<li>Or implicitly</li>
	<ul>
		<li>Client uses server public key to encrypt symmetric key</li>
		<li>Server proves it knows corresponding private key by recovering the  
shared secret key and sending a message and MAC formed using the  
key, that the client can verify</li>
	</ul>
</ul>
	

<br />
<h3>SSH Transport Layer Protocol - Purpose</h3>
The Transport Layer Protocol is used to:

<ol>
	<li>Establish the SSH version and identification information</li>
	<li>Negotiate the cryptographic algorithms to be used</li>
	<ul>
		<li>Each entity provides list of algorithms for key exchange, encryption, MAC and data compression, in order of preference</li>
	</ul>
	<li>Perform key exchange (DH) for keys to use with algorithms</li>
	<li>Final message from client to server to request use of either SSH User Authentication Protocol or SSH Connection Protocol</li>
</ol>

<br />
<h3>SSH User Authentication Protocol</h3>
The SSH user authentication protocol runs over the SSH transport layer protocol. Messages exchanged are:

<ol>
	<li>The client sends a user authentication request message which includes username</li>
	<li>The server responds and if  the username is valid the server sends list  of authentication methods (either a public key or password)</li>
	<li>Client responds with authentication method selected and required information</li>
	<li>When required authentication is performed successfully the server sends a user authentication successful message</li>
</ol>

An advantage to using public keys with SSH is that each account can have multiple associated public keys meaning users could have different keys for each devices they own, if one is lost/compromised it's easy to revoke its access. Another advantage is that multiple users can login to a single account without using a shared password. Each user has their own key pair meaning we can revoke one users access independently of others. Lastly users an associate the same key with multiple accounts giving a form of single sign-on.

<br />
<h3>SSH Connection Protocol</h3>
The SSH connection protocol runs on top of the SSH transport layer protocol and assumes a secure authenticated connection (tunnel) is in use. The SSH connection protocol also multiplexes multiple logical communications channels over a single underlying SSH connection. The client and server exchange messages in three stages 1) Open a channel, 2) Perform data transfer, and then 3) Close the channel.

<br />
<h3>SSH Security Services</h3>
<ul>
	<li>Peer Authentication</li>
	<ul>
		<li>Ensures that network traffic is being sent from the expected party</li>
		<ul>
			<li>Server to client authentication based on public keys</li>
			<li>Client to server authentication based on passwords or public keys</li>
		</ul>
	</ul>
	<li>Message Confidentiality</li>
	<ul>
		<li>Uses encryption to protect against unauthorised disclosure</li>
	</ul>
	<li>Message Integrity</li>
	<ul>
		<li>Data integrity assured using message authentication code (MAC)</li>
		<ul>
			<li>SSH can determine if data has been changed during transit</li>
		</ul>
	</ul>
	<li>Message Replay Protection</li>
	<ul>
		<li>The same data is not delivered multiple times</li>
	</ul>
</ul>

<br />
<h3>Internet Protocol Security (IPsec)</h3>
IPsec is a framework of open standards used for ensuring private, secure communications over Internet Protocol (IP) networks. IPsec operates at the network or internet layer and secures application and transport layer communications. IPsec uses encryption, authentication and key management algorithms to provide security architecture for both IPv4 and IPv6. A benefit of IPsec is that it operates at a network/internet layer meaning applications are not aware of its operation. If applied at a network gateway (firewall/router), strong security applies to all traffic crossing this boundary allowing internal workstations to not need to be reconfigured and allows transparency to end users . IPsec consists of three protocols:

<ol>
	<li>Internet Key Exchange (IKE): Negotiate, create, and manage security associations (agreeing on cryptographic algorithms, establishing cryptographic keys and sequence numbers)</li>
	<li>Encapsulating Security Payload (ESP): Encryption used to provide confidentiality, MAC for authentication, integrity and replay protection (but does not cover header fields)</li>
	<li>Authentication Header (AH): Authentication, integrity and replay protection for entire payload, and for header fields not changed by routers. However, there is no confidentiality provided</li>
</ol>

<br />
<h3>IPsec - Modes of Operation</h3>
Both ESP and AH protocols can operate in either transport or tunnel mode.

<ul>
	<li>Transport mode</li>  
	<ul>
		<li>Operates primarily on the payload (data) of the original packet</li>
		<ul>
			<li>Original packet header kept as header and new IPSec header (AH or ESP) inserted between original header and payload</li>
			<li>Generally only used in host-to-host architectures</li>
		</ul>
	</ul>
	<li>Tunnel mode</li>  
	<ul>
		<li>Original packet with header encapsulated as payload in anew packet, with new IPSec Header added</li>  
		<ul>
			<li>Typical use is gateway-to-gateway architecture</li>
		</ul>
	</ul>
</ul>

<br />
<h3>IPsec - Security Services</h3>

<ul>
	<li>Message Confidentiality</li>
	<ul>
		<li>Uses encryption to protect against unauthorised data disclosure</li>
	</ul>
	<li>Message Integrity</li>
	<ul>
		<li>Integrity of data can be assured by using a message authentication code (MAC)</li>
		<ul>
			<li>IPsec can determine if data has been changed (intentionally or unintentionally) during transit</li>
		</ul>
	</ul>
	<li>Traffic Analysis Protection</li>
	<ul>
		<li>Provided by concealing IP datagram details (such as source and destination addresses)</li>
		<li>A person monitoring network traffic cannot know which parties are communicating, how often, or how much data is being sent</li>
	</ul>
	<li>Peer Authentication</li>
	<ul>
		<li>IP addresses are used as host identifiers</li>
		<li>Each IPsec endpoint confirms the identity of the other IPsec endpoint it wants to communicate with (ensuring that network traffic is being sent from the expected host</li>
	</ul>
</ul>

<br />
<h3>IPsec - Common Architectures</h3>
Endpoints for communications secured using IPsec can either be hosts or gateways to secured networks. Combinations of these form three common architectures: 1) Gateway-to-Gateway, 2) Host-to-Gateway, and 3) Host-to-Host.

<br />
<h3>IPsec - Gateway-to-Gateway</h3>
Secures network communications between two secure networks by routing network traffic through the IPsec connection and establishing a VPN connection between the two gateways. This is a much cheaper alternative to a private wide area network (WAN).

<br />
<h3>IPsec - Host-to-Gateway</h3>
Secures communications over an insecure connection between a single host and a secure network. A VPN connection is established between the host and the gateway to the secure network. However, this architecture only protects the data between the host and the gateway. Within the secure network the transmissions are not protected. 

<br />
<h3>IPsec - Host-to-Host</h3>
Secures communications between two single computers. The only architecture that provides protection throughout its transit (end to end). All user systems and servers need to have VPN software installed and/or configured. In a host to host connection key establishment is often a manual process and is resource-intensive to implement and maintain in terms of user and host management.  



<br />
<h2 id="week13">Week 13: Review</h2>
<h3>Exam Details</h3>
<ul>
	<li><b>Final Examination Weight:</b> 40%</li> 
	<li><b>Exam Duration:</b> 10 minute perusal | 3 hours of working time</li>
	<li><b>Things to Bring:</b></li>
	<ul>
		<li>Student ID</li>
		<li>Writing Implements (blue/black pen, pencils, erasers, highlighters, etc)</li>
		<li>Prepared Notes - One double sided A4 page [~! Handwritten Only !~]</li>
	</ul>
</ul>

<br />
<h3>Exam Structure - 2 Parts</h3>

<ul>
	<li>Part A (Content related to L4-L10</li>
	<ul>
		<li>Fifty multiple choice questions (50 x 1 mark = 50 marks)</li>
		<li>Answer on mark sense sheet (by colouring circle in pen)</li>
	</ul>
	<li>Part B (Content related to whole semester</li>
	<ul>
		<li>Five questions, each 10 marks (5 x 10 marks = 50 marks)</li>
		<li>Each question has multiple parts, these require short answer</li>
		<ul>
			<li>For example, Q51 may have parts a), b), c), etc</li>
			<li>Marks for each part of the question are indicated - use this as a guide to the level of detail required in your answer</li>
		</ul>
	</ul>
</ul>

<br />
<h3>Exam Prep Tips</h3>

<ul>
	<li>Review the weekly materials: activities, lecture recordings</li>
	<li>Attempt all tutorial questions</li>
	<li>Reflect on weekly Kahoot results</li>
	<li>Review your assessment task 1: quiz results</li>
	<li>Questions on the standards (AS27001, 27002, 27005)</li>
	<ul>
		<li>"We don't expect you to rote learn the contents of these standards. We do [however] expect you to know [the] purpose of each, relationship[s] between standards, and details discussed in class"</li>
	</ul>
</ul>

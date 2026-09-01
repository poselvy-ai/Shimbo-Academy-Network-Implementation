##Shimbo Academy – Network Implementation 
##(Proposal)
##Patrick O. Selvy
##Western Governors University

Table of Contents
Proposal Overview	3
Problem Summary	3
IT Solution	3
Implementation Plan	4
Review of Other Work	5
Summary of Four Works	5
Review Work 1 and Relation of Works to Proposal Design	5
Review Work 3 and Relation of Works to Proposal Design	6
Review Work 4 and Relation of Works to Proposal Design	7
Project Rationale	7
Current Project Environment	8
Methodology	8
Project Goals, Objectives, and Deliverables	10
Goals, Objectives, and Deliverables Table	10
Goals, Objectives, and Deliverables Descriptions	10
Project Timeline with Milestones	13
Outcome	13
References	15

 
Proposal Overview 
Problem Summary

As a developing nation on the world stage, Zambian is seeing the nation transform from an aquicultural-based economy to a technology-driven economy. As the technology demands increase in Zambia, there has become a need for locally trained technologists. The Shimbo Academy, recognizing the job market for their future graduates, now leans more toward the technology sector; they have decided to start offering technology-based classes. They also have plans to bring technology into the classroom to assist their teachers and students in their studies. 
The Shimbo Academy currently has two buildings with no network infrastructure to support its goals of bringing technology into the classroom. The Academy will need to develop an infrastructure from scratch to include backbone LAN infrastructure, WAN ISP, and core/distribution layers for its network. 
IT Solution
The IT solution for the Shimbo Academy is to build a backbone network to allow connectivity. POS-Networking will accomplish this by installing the following elements:
1)	WAN ISP connectivity.
2)	Firewall - VLAN ((“IT-LAB,” “SC-Admin,”” SC-Teachers,” “MGMT”)
3)	Core Switches - VLAN (“IT-LAB,” “SC-Admin,”” SC-Teachers,” “MGMT”)
4)	Distribution Switches - (“IT-LAB,” “SC-Admin,”” SC-Teachers,” “MGMT”) WLAN – (“IT-LAB,” “SC-Admin,”” SC-Teachers,” “MGMT”)
5)	LAN connection. 
Installing each element of the network will allow the customer’s end user to gain access to external and internal resources. 
            The definition of the VLANs and the associated Subnets to those VLANs will allow the Academy to segment off potential high-risk subnets, e.g., the “IT-LAB” VLAN. The definition of the VLANs will also ensure better traffic and security flow across the network, as the traffic only bound and allowed to the subnet will traverse across the network. 
            Finally, the installation of the LAN / WLAN elements, e.g., WAN, WLAN, network equipment, and cabling, rounds out the backbone. Each component serves as an essential portion for relaying or accepting traffic to and from resources. 
	
Implementation Plan 
	The POS-Networking implementation plan consists of four phases: “Planning,” “Design,” “Implementation,” and “Testing.” 
            The first phase is the “Planning” phase, which is essential to any project as it brings the stakeholders and the project team together to devise a plan to complete the project. At a high level, this phase is marked by high-level meetings with the project manager and key stakeholders to develop the plan, agree on milestones, and establish budgetary requirements. 
            The second phase is the “Design” phase. This is where our project starts taking form. Key team members are at the site taking initial walks through and talking to their key academy personnel to help them understand the grounds. Also, during this phase, negotiations start with vendors on equipment and services needed to complete the project. 
            The third phase is the “Implementation” phase. The hallmark of this phase is that the physical work begins at the Academy. Cables start to run through the Academy while network engineers start building out configurations on the devices. At the end of this phase, the “Skeleton” network has been completed and is ready to be tested. 
            The “Testing” phase is when the network starts putting a load on the network to see if there is data failure. The cabling team supervisor double-checks the wiring run and connections. The key step in this process is finalizing the network documentation, which will assist the production team in turnover. 

Review of Other Work
Summary of Four Works
Review Work 1 and Relation of Works to Proposal Design
	In preparation for bringing in a WAN connection to the site Low Earth Orbit provider (LEO) provider such as start link in my opinion would be a better option than a traditional circuit found in the area which is a T1. According to the Star Link documentation (STARLINK, 2025) they can average 100Mbps speed, with a latency around 20ms. The higher speed with reduced latency will allow more students and faculty to access the internet. 
Review Work 2 and Relation of Works to Proposal Design
	The installation plan calls for extending the network between the two academic buildings to facilitate the network. In preparation for installing the bridge antennas, several factors must be kept in mind, e.g., power to the antenna, weather, and the distance needed to be covered (FC, 2022). 
            The distance between the two buildings is about 150 meters, calling for specialized outdoor bridging antennas. The power will be supplied to the antennas via PoE provided by the closest distribution switch, as it is less likely to cause shorts or electrical fires. When installing the cable on the bridge antenna, the technician needs to place a drip loop on the cable to ensure that rain does not travel down the cable, causing damage.
Review Work 3 and Relation of Works to Proposal Design
	Zambia is a developing country with an immature country-wide internet infrastructure compared to most developed countries like the United States.  A typical resident relies on a cellular connection (Zambia. 2023) to connect to their homes and conduct most business transactions. The cellular connection provides limited bandwidth and does not support educational activities. Coupling the primary use of cellular data with the most “hard-line” connections limited to city centers like Lusaka, it has been difficult to reach the rural educational system (Chiwoya et al., 2025).
            The Zambian government has been taking steps to resolve this issue (Chiwoya et al., 2025) by pressuring the ISPs to provide a more reliable internet connection to the university. They have also been working with the Information and Communication Technology (ICT) community to derive other options for the educational system to provide technology to higher education learners throughout the country (Chiwoya et al., 2025).  
            The problem still comes down to education, and government leaders who want to develop their country need to continue solving the problem of an immature internet network. They need to invest more in expanding fiber services to towers and stabilizing the power grid (Zambia. 2023) to support the system.
Review Work 4 and Relation of Works to Proposal Design
	When building out a network for a school, as in this project, the developer must keep several key points in mind: the placement of the AP (WAP), the VLANs, and the physical security (O’Callahan, 2019). Each of these points serves to protect both the educator and the student from denial of service and misappropriation of services. 
          VLANs should be constructed so that students are segregated from the general network operation. The student VLAN should function as an independent network with no crosstalk with other resources, as the student is the most likely cause of a network failure. Also, the firewall should filter harmful content (O’Callahan, 2019) that school administrators deem harmful to the student. 
          The AP (WAP) should be placed so that all users can access it with little gap in coverage (O’Callahan, 2019). The WAP should be configured with roaming service, so the users do not lose connectivity while moving throughout the building. 
          The physical security of all network assets is a must (O’Callahan, 2019). Denying students and unauthorized personnel access to network equipment prevents potential bad actors from infiltrating the base network, causing damage, or spying on the network.

Project Rationale
Shimbo Academy's current goal is to bring technology into the classroom, so a network infrastructure is needed. The network infrastructure will allow the end devices to reach the internet and enable the school's second goal of training students to learn about technology with the most recent information. 
The academy could have chosen not to install a network infrastructure to support the end devices. That choice would have required the teachers to act like the internet in a term called "Sneaker Net," which would have slowed the educational process. Also, using the standalone system would have increased system maintenance and provided less security for the end machines. 
In the end, a network infrastructure is needed to meet the academy's goals of broadening the horizons of its students and reducing the overall cost.  
Current Project Environment
	The Shimbo Academy values broadening the horizons of its staff, teachers, and students to fully prepare them for their next stage of life. 
	The network implementation project will allow the school to expand computer technology into each classroom and connect the end devices to the internet, expanding the teachers' training in their subjects and thus broadening their students' horizons. The project will also allow the school to introduce new technology programs, such as networking, programming, cloud computing, and many others, as they prepare their students for tomorrow from their current state.
Methodology
The Shimbo Academy—Network Implementation project will use a "Waterfall" methodology consisting of four phases: "Planning," "Design," "Implementation," and "Testing." I chose the “Waterfall" method for this project because the processes are highly dependent on each other to complete the project. 
            The first phase of the project is the planning phase. This phase is marked by POS-Networking engaging with the Academy administration to determine the project's scope. In this phase, it will also be determined if POS-Networking will be the correct contractor with the correct project plan to complete the project. This phase is completing the final contracts, allowing POS-Networking to begin work on the project. 
            The second phase is the design phase. During the design phase, logical and physical diagrams are created. A walk through the Academy's grounds is completed to determine the project's resources. Products and ISP vendors are selected. Additional meetings with stakeholders, if any bearers are found, may lead to a timeline shift and discuss ISP vendors. The completion of this phase is marked by procuring all elements needed for the project.                                               
            The third phase is the installation phase, the meat and potatoes part of the project. The Academy's infrastructure cabling will begin when the Cat 5e cable arrives on site, as this activity will take the longest. Network engineers will start configuring the NGFW, switches, WLAN controller, and WAPS, WAN PE. The phase will conclude when the network devices are connected. 
            The fourth phase is the testing phase, which will finalize the entire project. During this phase, POS-Networking will place the network under load, validate security, and test disaster recovery procedures. We expect no more than 5% bandwidth loss on the network while under peak load. POS-Networking will not be able to detect vulnerabilities. We also expect to see the an average of 100Mbps of the WAN provider network over a 7-day period. The phase will end when we hand the network over to the production team.

Project Goals, Objectives, and Deliverables

Goals, Objectives, and Deliverables Table

	Goal	Supporting Objectives	Deliverables Enabling the Project Objectives
1	Planning, Design, and Procurement	Planning 	Stakeholder Meeting
			Project Meeting 
			Sign contracts
		Design	Design logical network 
			Design physical network
		Procurement	Procure WAN ISP
			Procure all wire, tools, network equipment, and UPS for the project
2	Configure and Install 	Configuration	Configure Network device
		Installation 	Physical cabling
			Network Equipment
3	Testing	Testing 	Network 


Goals, Objectives, and Deliverables Descriptions
The primary goal of the project is to establish a network that can support 150 users at peak operations. The network must be segmented into four VLANS (“IT-LAB,” “SC-Admin”,” SC-Teachers,” “MGMT”) to allow the Academy to operate its WAN in an efficient manner, while providing security to the network. The network must also be able to expand if needed. 
 
1.	Planning, Design, and Procurement Phase aims to establish a relationship between the Academy administration and POS-Networking, while providing deeper understanding of the project's needs and scope. 
1.1.	Planning
1.1.1.	The stakeholder meeting is where POS-Networking and the Academy administration first sit down and can discuss the scope of the project, constraints and budget on the projects before moving forward. 
1.1.2.	The project meeting is a fine-tuning meeting where the POS-Networking Project Manager sits down and lays out their idea of project timeline and budget, while listing the customer's feedback. This meeting produces the full scope of the project, milestones, and budget. 
1.1.3.	The signing of the contracts concludes the planning subphase as there is an agreed upon set of clauses for each party to follow. 
1.2.	Design 
1.2.1.	Logical design produces the logical design for the network to include subnets, VLANS, security, routing, and switching from a high-level point of view. 
1.2.2.	Physical design will determine the material that needs to be bought in the procurement phase and give rise to potential milestone shifts due to the building's architecture. Also, during this phase the WLAN diagram as part of the physical diagram is established 
1.3.	Procurement. 
1.3.1.	ISP procurement is a critical factor in the project as it will determine if the primary objective of supporting 150 users to the internet will be feasible. Also, it will need to be determined if the user is comfortable with going with Low Earth Orbit “LEO” connectivity or they will prefer a terrestrial based circuit. 
1.3.2.	Final procurement and vendor contract signing are the last element of the design phase. The procurement of all needed resources and the ETA of those resources will determine when the next phase begins. 
1.4.	Planning, Design, and Procurement concludes with a meeting between the project manager and the stakeholders to address risks with milestone and / or budget. 
2.	Configuration and installation are the hands-on portion of the project. 
2.1.	Configuration of Network Devices. 
2.1.1.	Configuring the firewall to receive signal from the ISP Carrier Provided Edge (PE) equipment and defining the four VLANS with the subnets to support 150 hosts. 
2.1.2.	Configure the switching devices to allow trunking between distribution, core devices, as well as implement the VLANs and the distribution switches. 
2.1.3.	Configure the WLAN in the Academy so each VLAN is properly served and if necessary, can provide a bridge between the two buildings. 
2.2.	Installation of physical cables to each end point and between the core and distribution layers will provide connectivity throughout the Academy. 
2.3.	The installation of the physical network equipment is the final piece that will allow the network to be considered operational and ready for testing. 
3.	The testing phase will see the network put underload to see how it reacts and test the security to the network to determine if there are vulnerabilities. 
3.1.	The test should show that we are averaging 100mbps with no errors on the LAN. 
3.2.	The testing phase concludes with turning all documentation over to the production team. 


Project Timeline with Milestones

Milestone	Duration 
(hours or days)	Projected Start Date	Anticipated End Date
Planning	3 Weeks	28 Jun 2025 	16 May 2025
Design	2 Weeks	19 May 2025	30 May 2025
Procurement	5 Weeks	2 June 2025	4 July 2025
Configurations	2 Weeks	7 July 2025	18 July 2025
Installation	3 Weeks 	7 July 2025	25 July 2025
Testing	1 Week	28 July 2025	1 Aug 2025

Outcome
The anticipated outcome of the Shimbo Academy Network Implementation project is that all staff members, teachers, and students will be able to access the Internet and network-related resources. The project's success is achieved by cooperation between the stakeholders and the project in each phase. 
	POS-Networking will know the project's success by measuring its ability to perform a speed test and receive, on average, a speed of 100Mbps on the internet connection over 7 days. Also, they can transverse the network to each tested endpoint on the LAN and the WLAN.



References
“Zambia,” in Funk, Shahbaz, Vesteinsson, Brody, Baker, Grothe, Barak, Masinsin, Modi, Sutterlin eds. Freedom on the Net 2023, Freedom House, 2023, freedomonthenet.org.

Service plans, performance, & hardware. (n.d.). Starlink Business & Enterprise Guide. https://starlink-enterprise-guide.readme.io/docs/compare-service-plans

FC (2022, July 22). Installation Guide for Outdoor Access Points. FASTCABLIONG. https://www.fastcabling.com/2022/07/22/installation-guide-for-outdoor-access-points/#:~:text=Follow%20the%20instructions%20here%20to,the%20switch%20to%20the%20'PoE

Chiwoya, A., Daka, H., & Mulenga – Hagane, M. (2025, March 29). Enhancing online learning in Higher Education Institutions in Zambia: An evaluation of the measures put in place by the government of Zambia, internet service providers and higher learning institutions. International Journal of Research and Innovation in Social Science. https://rsisinternational.org/journals/ijriss/articles/enhancing-online-learning-in-higher-education-institutions-in-zambia-an-evaluation-of-the-measures-put-in-place-by-the-government-of-zambia-internet-service-providers-and-higher-learning-institution/ 
O’Callahan, T. (2019, March 14). Best practices for school network architecture and design. My Catholic Schools. https://mycatholicschool.org/wp-content/uploads/2019/04/2019-School-Network-Architecture-Pi-Day-1.pdf 

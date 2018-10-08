# ResQ-
This is the project of GhoulsInDevelopment for Codefundo++2018
Our solution aims to improve the disaster management system. 
Our model for rescuing process is the following:
We have divided the affected area into sub-regions.
Each sub-region has one rescue team (more than one for scaled-up complex model). 
	1.Victim : the victim sends an SOS through an appplication. The SOS is then transferred to the rescue team deployed in the corresponding sub-region via SMS. 
	2.Rescue team : The rescue teams receive SOSs which contain the real time location of the victims in the form of a query url. The rescue teams can reach the victims through this url which opens in bing maps.
	3.Website:
	a)Display of SOS status subregion-wise in a tabular format: It shows the status of each SOS received,i.e rescue in progress or completed for each SOS.
	(for scaled up model)If the count of SOS in a particular region becomes too large, then a critical message pops up on the website alerting the authorities(i.e. the central body monitoring the website) to deploy more teams in that sub-region. 
	b)"I WANT TO VOLUNTEER": This will be a feature allowing local people,who wish to help in the rescue process coordinate with the rescue teams by contacting them.
	c)Rescue team database:
	(i)This database maintains the information such as resources available(medical facilities,food,shelter,equipments), transportation, manpower, contacts etc for each rescue team, which they can access and update by logging into the website.
	(ii)The rescue teams can also update the relief status of the SOS by logging in.
	d)FORUM section : Any problems (such as resource shortage etc) being faced can be posted here by rescue teams using their login credentials. So that these problems can be immediately handled. 
	
We also have an idea for a scaled up complex version called "nearby" feature. In this the victims and the rescue teams will be able to see the other victims' current location (all those who have shared their location by SOS), so that multiple victims can gather at one location thus reducing the burden of rescue teams. 

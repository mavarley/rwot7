# Digital Identity for the Homeless

##Authors

Mike Varley
Matthew Wong

## Abstract

This paper explores the possibilities and practicalities of leveraging a digital decentralized identity for helping homeless, distressed, or under-serviced populations.

Some points that will be covered:
* homeless does not mean 'disconnected'.
* reliable identity is still essential for providing services to help these people.
* the valuable services which need to made available to this group.
* we don't need 100% converage of affected people to have value.
* how decentralized ID networks support the creation of online communities with real-world capabilities.

## Background

Although this background is Toronto Ontario Canada specific, it provides a context for a global issue.  

### Problem Statement

Some of the best estimates indicate that more than 235,000 Canadians experience homelessness in any given
year, and about 35,000 Canadians are homeless on a given night[14]; among them, 6,000 of those are youth between 15 and 24[3]. According to Canadian Observatory of Homelessness[5],

> Homelessness describes the situation of an individual, family or community without stable, safe, permanent, appropriate
housing, or the immediate prospect, means and ability of acquiring it. It is the result of systemic or societal barriers, a lack
of affordable and appropriate housing, the individual/household’s financial, mental, cognitive, behavioural or physical
challenges, and/or racism and discrimination. Most people do not choose to be homeless, and the experience is generally
negative, unpleasant, unhealthy, unsafe, stressful and distressing.

Mass homelessness in Canada emerged in the 1980s, following a massive disinvestment in affordable housing, structural shifts in the economy and reduced spending on social supports. Since then stakeholders across the country have tried and tested solutions to address the issue. These responses, largely based on the provision of emergency services, have prevented meaningful progress. Fortunately, there are many signs that we are entering a new phase -- one that will lead to an end to homelessness in Canada[7].

Modern services constantly require users to provide a verified, government identity. IDs are needed, not just to drive a car or enter a bar, but to register for school, open a bank account and access many government benefits. Individuals who do not have verification are locked out from vast expanses of the modern economy. 

### Why Self-Sovereign Identity and Decentralize or Web of Trust?
Decentralized / Web of Trust based Self-Soveregin Identity is a necessity for the millions of people around the world without identification or documentation. These “lost citizens” have no access to social service, no ability to transact, and no clear citizenship.
Decentralized solution is needed to solve this problem for a few reasons, one; blockchain will decrease the chances of fraud and stolen identities being used. Second, for individuals that actually don’t have physical proof for their ID this elevates the need to register and request for physical identification which can take up months. Third, this can give people more proactive control over their data and make it more difficult for unauthorized users to exploit it. Lastly losing physical ID’s is one of the most common problems amongst those that are experiencing homelessness, they often get their wallets, ID’s, entire luggage or bag stolen so they always have to start over. Having their identities on the blockchain will mean they won’t have to start over each time as long as they have their master key they will always be able to have their ID’s with them wherever they go regardless if they lose their belongings or not.

### What existing solutions do we have?
There are ID clinics across Canada that help homeless individuals re-apply to get their driver’s license, health card, and SIN cards back. They help clients individually fill out forms to get their ID’s back however the challenge is the bureaucracy and hoops they have to jump through to acquire it as well as the time it takes to wait for government to replace it. 
The problem that always occurs after is individuals losing it due to circumstance and then having to start all over again in the obtaining process.
Emerging pilots to provide identity services for the homeless are emerging notable with two examples. New York with the Fummi app distributed on Android phones  and recently a ploit in Holland[8]. Other solutions are proposed to different vulnerable groups with similar identity needs, like refugees with solutions like Taqanu[9].

### What are we aiming to do?
The focus of this topic is how to apply existing decentralized digital ID solution to help individuals experiencing homelessness in the city (Toronto). E.g. how to reserve services such as overnight shelters with digital ID, keep track of certificate offered by free public organized re-training programs, and built credibility via repeat use the the same digital ID with varies services run by non-profit organizations in the city etc. The current digital ID solution is mature enough to tackle this issue, however how to properly design and deploy this solution in a city wide scale without major government backing is still challenging -- how to make a digital ID more than just a digital file and become a tool to built trust on for the individual experiencing homelessness. 


## Homeless does not means disconnected

* homeless does not mean no access to a smartphone
Based on [13], 95 percent of homeless surveyed owned a mobile phone, and it is increasingly important and served as a lifeline to them [13].
* homeless does not mean you have no root of trust (DL, Bank account, ...)

* homeless does not mean they are alone, or isolated (but it is easy for them to feel this way)

## Why a reliable Identity is valuable to this community

* Social workers in this community learn who the people are.
* Making this identity claim 'portable' across the city/locality/region as people move about.
* Services requiring identity exist for the homeless, including reserving overnight shelters, re-training / education programs, employment services

## Why Decentralized Digital Identity

By its nature, the disposessed / homeless commnity is already decentralized. The value lies in empowering a member of this community to leverage an identity and community relationship when moving across regions, or being able to have an 'identity' when attempting to re-enter 'normal' society.

The social workers working with homeless can provide in-person ID services and provide an 'on-boarding' for a reliable, portable ID, and the advent of a digital trust framework means the identity claims are immiately recognizable and useable across supporting agencies and services.

Example use case: Joe takes advantage of a bed at a shelter. The intake shelter worker is able to provide Joe with a digital ID, that gives Joe a portable 'service ID'. When Joe decides to stay at a different shelter, he can use his serviceID. When Joe registers for a course, he can use his serviceID. when Joe completes the training/course, now Joe has a linked claim to his serviceID.

The principles of the decentralized digital identity allow for privacy respecting exchanges as well - so Joe does not have to reveal that he stayed at any particular shelter, or can be tracked for the number of courses he registered for but did not complete.

## Reference
[1] Blockchain and Identity in 2018 -- A Year of Promise and Pilots, OWI
[2] Identity in a Digital World -- A new chapter in the social contract, World Economic Forum
[3] Report on Youth Homeless 2018, http://homelesshub.ca/sites/default/files/Report_on_homeless_youth_WEB%202.pdf
[4] Homelessness in Canada, https://en.wikipedia.org/wiki/Homelessness_in_Canada
[5] Gaetz, S.; Barr, C.; Friesen, A.; Harris, B.; Hill, C.; Kovacs-Burns, K.; Pauly, B.; Pearce, B.; Turner, A.; Marsolais, A. (2012) Canadian Definition
of Homelessness. Toronto: Canadian Observatory on Homelessness Press.
[7] Stephen Gaetz, Erin Dej, Tim Richter, & Melanie Redman (2016): The State of Homelessness in Canada 2016.
 Toronto: Canadian Observatory on Homelessness Press.
[8] https://arxiv.org/pdf/1806.01926.pdF
[9] https://www.taqanu.com
[10] The Path to Self-Sovereign Identity, http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html
[11] New Brunswick Digital ID https://myid.gnb.ca/content/myid-monid/en/discover-myid.html
[12] https://accan.org.au/our-work/937-homeless-mobile-use
[13] Cellphones can provide lifeline to homeless people https://www.cbc.ca/news/canada/nova-scotia/social-media-indigenous-women-safety-facebook-1.4032899
[14] Homelessness in Canada – Why it’s time to listen, KPMG
[15] Fair, A., Gosse, B., Moore, H. & Robson, J., Social and Enterprise Development Innovations (SEDI), 2008

# Digital Identity for the Homeless

## Authors

Mike Varley
Matthew Wong

## Abstract

This paper discuss how to make digital IDs more than just a digital file and become a tool to built trust on for the individual experiencing homelessness. Decentralized digital ID solution can help individuals experiencing homelessness to receive services in the city (Toronto) such as reserving an overnight shelters, tracking of certificates offered by free public organized re-training programs, and become finanically inclusive. With digital IDs, people facing homelesness can built credibility via repeat use the the same digital ID with varies services run by non-profit organizations in the city. Current digital ID solutions are mature enough to tackle this issue, however how to properly design and deploy this solution in a city wide scale without a centralized Vertifible Crendential (VC) Issuer or ID Provider (IDP) such as government is still challenging.

Some points that will be covered in this paper:
* Reliable identity is still essential for providing services to the homeless.
* Homeless can build their own web of trust with decentralized identity.
* Financial inclusion for people without a reliable permanent address.
* Valuable services can be made available to this group because of a reliable identity.
* We don't need 100% converage of affected people to have value.
* How decentralized ID networks support the creation of online communities with real-world capabilities.

## Background

Decentralized / Web of Trust based digital identity is a necessity for the billions of people around the world without identification or documentation -- they are invisibile. These “lost citizens” have no access to social and financial service, and no clear identity in the society. 

According to the World Bank[1], over a billion people cannot prove things about ourselves, leaving them unable to obtain desirable work or advanced education, open a bank account, hold title to property, or even travel. This is not limited to the unprivileged class in the developing countries but also people in developed world, such as Canada, who is experiencing homelessness. Some of the best estimates indicate that more than 235,000 Canadians experience homelessness in any given
year, and about 35,000 Canadians are homeless on a given night[2]; among them, 6,000 of those are youth between 15 and 24[3]. 

According to Canadian Observatory of Homelessness[4],

> Homelessness describes the situation of an individual, family or community without stable, safe, permanent, appropriate
housing, or the immediate prospect, means and ability of acquiring it. It is the result of systemic or societal barriers, a lack
of affordable and appropriate housing, the individual/household’s financial, mental, cognitive, behavioural or physical
challenges, and/or racism and discrimination. Most people do not choose to be homeless, and the experience is generally
negative, unpleasant, unhealthy, unsafe, stressful and distressing.

Mass homelessness in Canada emerged in the 1980s, following a massive disinvestment in affordable housing, structural shifts in the economy and reduced spending on social supports. Since then stakeholders across the country have tried and tested solutions to address the issue. These responses, largely based on the provision of emergency services, have prevented meaningful progress. Fortunately, there are many signs that we are entering a new phase -- one that will lead to an end to homelessness in Canada[5].

Although this background is based on studies based on Canada, it provides a context for a global issue.  

## Problem Statement

Modern services constantly require users to provide a verified, government identity. IDs are needed, not just to drive a car or enter a bar, but to register for school, open a bank account and access many government benefits. Individuals who do not have verification are locked out from vast expanses of the modern economy, i.e. financially excluded.

Financial inclusion is widely recognized as one of the most important engines of economic development. Its contributions to GDP, individual and social welfare, and business creation and expansion. Without a stable address access to mainstream financial services in Canada is difficult if not impossible[6]. 

In Canada, to open an account, you must present two pieces of identification[7][8]. Alternatively, you may present only one piece of identification if your identity is confirmed by a client in good standing with the bank or by an individual of good standing in the community where the bank is located. However, without a reliable identification, keeping track of reputation or crendentials, is difficult.

Although homeless shelters do not requires any identification; however due to age / gender restriction of some shelters, staff sometimes ask people come to their facility to provide proves. Verifiable crendentials can be used to provide information as needed (e.g. age), but nothing more. 

The solution to this problem is to use decentralized diginal ID systems (as known as Self-Sovereign Identity -- SSI) that empowers a member of this community to leverage an identity and community relationship when moving across regions, or being able to have an 'identity' when attempting to re-enter 'normal' society. The principles of SSI allow for privacy respecting exchanges as well - so Joe does not have to reveal that he stayed at any particular shelter, or can be tracked for the number of courses he registered for but did not complete.


### Why Self-Sovereign Identity and Decentralize or Web of Trust?

Self-Sovereign Identity is the perfect decentralized solution, based on blockchain, for the problem above for a few reasons, one; blockchain will decrease the chances of fraud and stolen identities being used hence improve trust. Second, for individuals that actually don’t have physical proof for their ID this elevates the need to register and request for physical identification which can take up months. Third, this can give people more proactive control over their data and make it more difficult for unauthorized users to exploit it. Lastly losing physical ID’s is one of the most common problems amongst those that are experiencing homelessness, they often get their wallets, ID’s, entire luggage or bag stolen so they always have to start over. Having their identities on the blockchain will mean they won’t have to start over each time as long as they have their master key they will always be able to have their ID’s with them wherever they go regardless if they lose their belongings or not.

### What existing solutions do we have?
There are ID clinics across Canada that help homeless individuals re-apply to get their driver’s license, health card, and SIN cards back. They help clients individually fill out forms to get their ID’s back however the challenge is the bureaucracy and hoops they have to jump through to acquire it as well as the time it takes to wait for government to replace it. 
The problem that always occurs after is individuals losing it due to circumstance and then having to start all over again in the obtaining process.

Emerging pilots to provide identity services for the homeless are emerging notable with two examples. New York with the Fummi app distributed on Android phones and recently a ploit in Holland[9]. Other solutions are proposed to different vulnerable groups with similar identity needs, like refugees with solutions like Taqanu[10].

## Use Cases

1 - Mary, the social workers and case managers, working with homeless can provide in-person ID services and provide an 'on-boarding' for a reliable, portable ID, and the advent of a digital trust framework means the identity claims are immiately recognizable and useable across supporting agencies and services.

2 - Joe takes advantage of a bed at a shelter. The intake shelter worker is able to provide Joe with a digital ID, that gives Joe a portable 'service ID'. When Joe decides to stay at a different shelter, he can use his serviceID. When Joe registers for a course, he can use his serviceID. when Joe completes the training/course, now Joe has a linked claim to his serviceID.

3 - Todd who recently "moved" to the street for the first time and would like to enroll the Accelerator (a training program for people experience homelessness). Paper based certificate of completion is hard to handle and can be easily damaged or lost. He would like to keep track of it in a digital and secure way.

4 - Jane, finally ready to leave the street and start a new life, however it has been difficult for her to receive financial services (e.g. a bank account). With the relationship she build with her repeat use of her digital ID issued by the homeless shelter she stayed for the last awhile, now she is able to open her own bank account.

## Conclusion

TBD

## Reference

[1] Vyjayanti T. Desai, Anna Diofasi, and Jing Lu [The global identification challenge: Who are the 1 billion people without proof of identity?](https://blogs.worldbank.org/voices/global-identification-challenge-who-are-1-billion-people-without-proof-identity), World Bank Blog

[2] [Homelessness in Canada – Why it’s time to listen](https://assets.kpmg.com/content/dam/kpmg/ca/pdf/2018/03/Homelessness.pdf), October 17, 2017, KPMG

[3] [Report on Youth Homeless 2018](http://homelesshub.ca/sites/default/files/Report_on_homeless_youth_WEB%202.pdf), United Way, 2018

[4] Gaetz, S.; Barr, C.; Friesen, A.; Harris, B.; Hill, C.; Kovacs-Burns, K.; Pauly, B.; Pearce, B.; Turner, A.; Marsolais, A. (2012) [Canadian Definition Of Homelessness](http://www.homelesshub.ca/sites/default/files/COHhomelessdefinition.pdf), 

[5] Stephen Gaetz, Erin Dej, Tim Richter, & Melanie Redman (2016): [The State of Homelessness in Canada 2016.
 Toronto: Canadian Observatory on Homelessness Press](http://homelesshub.ca/SOHC2016).

[6] SEDI (2008), [Finanical Inclusion for Homeless and Those at Risk](http://prospercanada.org/getattachment/431191e9-bc53-40ca-8f90-b18807009290/Financial-Inclusion-for-Homeless-Persons-and-Those.aspx)

[7] [Financial Sector Review](https://www.fin.gc.ca/consultresp/pdf-ssge-sefc/ssge-sefc-49.pdf) (2016), item 6.

[8] [Opening a bank account (2016)](https://www.cba.ca/opening-a-bank-account)

[9] [This New Blockchain Project Gives Homeless New Yorkers A Digital Identity, 2007](https://www.fastcompany.com/40500978/this-new-blockchain-project-gives-homeless-new-yorkers-a-digital-identity)
[10] [Austin, Texas Using Blockchain Identity System to Help the Homeless (2018)](https://bitcoinist.com/austin-introduces-blockchain-id-management-system-to-help-homeless-population/)

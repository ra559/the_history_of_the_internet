# The history of the internet
## Intro
![the internet](../assets/the-internet.png)

The internet is humankind's greatest invention. It connects the world in seconds and is the number one technology that keeps the economy alive. How did this amazing invention happen? Who was involved? Which roadblocks did these people encounter? This page is an attempt to answer all these questions. 

## The founding of ARPA

Our journey starts at the beginning of the space race during the cold war. The launch of Sputnik by the USSR pushed President  Dwight D. Eisenhower in 1958 to found the Advanced Research Projects Agency (ARPA) which was put in charge of the space program and other fields of studies such as computer science and research. Soon after NASA was founded and the space program assigned to them with the goal to beat Russia in the space Race. This movement of responsibility left ARPA incharge of pushing the advancement of computer science.
.
## The foundation of data transmission

In the early 1960s, Leonard Kleinrock, who then was a graduate student at MIT,  started applying queuing theory to computers which led to the foundation of data transmission.  Queueing theory is the mathematical study of waiting lines. Queueing theory uses queueing models constructed in a way such that queue lengths and waiting times can be predicted. Kleinrock’s idea established how packages of data arrive at a queue at the node of a communication’s network allowing for the calculation of the speed of the network. Kleinrock then developed two techniques to speed up the network: demand access and distributed control. 

## The need for an indestructible network
![indestructible network](../assets/network-big.png)

In the early 60s, it was not the discovery of new technology that motivated the US for developing a network of computers. But, the fear of a nuclear Russian attack in the homeland. Back then, all military communication happened via the phone line, therefore, a nuclear attack not only would destroy the cities but it would eliminate the possibility for retaliation. To theorize the possibility of building an indestructible communication network, the engineer Paul Baran was hired. The first concept that Paul Baran and his team ambitioned was creating a fishnet-like network, where if a node is incapacitated another data path could be easily built. The team theorized the idea of Hot potato routing in which data is first broken down in small equal-sized pieces called packets. The packets would then find their path to the network similar to how rats find a way out of a maze. In this system, only part of the network needs to be operational for the data to arrive at its destination. This is possible because every node keeps sending copies of the packet until such a packet arrives at its destination. 

## Multiple machines 1 terminal

Although enough theory already existed for creating a network of computers, it was not until 1969 where the idea started materializing. Unlike walking on the moon, the development of a computer network did not come from the race to beat another nation’s engineering. Instead, like many other inventions, this advancement came out of the frustration of a single ARPA scientist called Robert Taylor. In 1966, Taylor required a terminal for each computer that he was working on. This nuisance gave birth to the idea of having a single terminal that can connect to any given number of computers. Taylor wanted to turn time-sharing, the way of using computers back then, into resource-sharing. This means that, as it is today, one person could access multiple computers from a single station. For this project, Taylor was given 1 million dollars to work on his idea for a computer network and he recruited someone who has already worked in a similar system in the past.  Larry Roberts had created the first experimental connection between two computers at MIT which made him the right candidate to join Taylor’s project. 

## The birth of the ARPANET
![ibm logo](../assets/ibm.png)

Larry Roberts first conceptualized chaining the computers to each other but this design meant that every computer needed to know how to connect each computer to each other and back then there was no TCP-IP standard. The solution was to create a mini-computer that the main computer connects to and then the mini-computer connects all the computers (the way a router works). The next roadblock that Roberts and Taylor encountered was who was going to build such a system? Telecommunications companies were not interested since computer networking did not represent revenue for them or thought that there was no way to build the system in the first place. Roberts bit the project of building these special new computers, called Interface message processors (IMPS), to IBM and AT&T but they both refused the offer.  Bolt Beranek and Newman (BBN) was the company that took the project of building the IMPs that would perform the packet switching. Packet switching consisted of splitting the data into small pieces sent them to the appropriate IMP and have that IMP put the data back together to deliver it to the recipient computer. The goal was to place 4 IMPs to connect the following computers:
* SIGMA 7 at The University of California
* SDS 940 at The Standford Research Institute
* IBM 360/75 at The University of California, Santa Barbara
* PDP-10 at The University of Utah

Building the hardware was not the only problem. Hardware needs software and the teams needed to write the code that will allow the IMPs to communicate with each other and the software for the computers to communicate with the IMPs. In addition to this challenge, there were design problems facing the BBN team. For instance, how would they stop packages from a forever loop or overflowing the system? When something breaks, how would they know what piece broke? It is important to note that the team had only 9 months to deliver the first IMPs. The team was able to deliver the IMPs on time and by the end of 1969, all 4 IMPs were connected and functioning. 

## You got mail!
![at sign email](../assets/atsign.png)

At first, the only thing the ARPANET could do was share files. But everything changed when email was born. The man responsible for giving birth to the E-Mail application was Raymond Tomlinson who at the time had already written several programs to send files in the ARPANET.  Tomlinson is known to be the first person to send an email in the ARPANET using the @ sign in 1971. In 1972, the ARPANET was demonstrated in Washington DC by Robert Metcalfe who contacted about 19 people who were using ARPANET in different ways.   

## And then there were … protocols.
![network room](../assets/network.png)

Soon after, there was a rise in the use of ARPANET networks everywhere but with the growth of the ARPANET came the problem of standardization. Computers need a way to understand each other regardless of the operating system. This way of communication is a language like the one we use to communicate. Like human language, computer protocols are nothing but a set of rules that enabled computers to understand each other. The set of protocols used in this case are the TCP/IP protocol stack. The TCP/IP protocol stack was introduced in 1973 by Vint Cerf and Bob Kahn. The goal was to link networks (LANs and WANs) with each other. Today, all devices that connect to the internet must comply with the TCP/IP protocol stack. Vint Cerf and Bob Kahn introduced the concept of gateways where packets can leave and enter different networks. There were other protocol stacks proposed but TCP/IP ultimately won the internet protocol war. 

## Politics! There has to be politics here too!
![congrees](../assets/congress.png)

The internet as we know it is free in the sense that no one owns it. What telecommunications companies offer you is the availability of becoming one of their many computers in their network. The internet is free (as in freedom, not free beer) because on June 9th, 1992 Congress passed a bill that took the internet out the hands of the government and passed to the public so that anyone can use it for whatever reason they wish. 

## Using the internet was hard!
![old computer image](../assets/old_computer.png)

By the 1980s, the internet was widely available to those who knew how to use it. Looking for information was hard because there was no Google or anything that resembles it. This problem was solved by Tim Berners Lee who invented the World Wide Web. WWW made the following threads of information easy by following links. In 1992 there were only 50 pages available but in 1993 the web browser was invented by  Marc Andreessen at the University of Illinois. Mosaic, later known as Netscape was the first graphical user interface that made using the internet simple and user friendly. No longer people needed to be computer wizards to search the web.




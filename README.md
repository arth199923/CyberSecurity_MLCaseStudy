# CyberSecurity_MLCaseStudy
This repository contains a machine learning case study focusing on network intrusion detection within the domain of cyber security. The primary objective is to build an effective network intrusion detection system capable of detecting anomalies and attacks in network traffic.

Business Objective:

In today's digital landscape, with the exponential growth of computer networks and applications, network security has become paramount. Intrusion Detection Systems (IDSs) play a crucial role in identifying and mitigating security threats within networks. This project aims to develop an IDS to detect anomalies and attacks effectively.

Hints about Data:

Different attack datasets may have different numbers of observations, indicating an imbalance in the data. Data preparation involves appending all files and creating a new column called 'attack' based on the type of attack. Resampling of data may be required based on the number of attacks.

Data Preparation:

You are required to append all the files and create a new column called 'attack' based on the name of the attack. While appending the files, you can perform resampling of data based on the number of attacks. For binomial classification, create an 'attack' variable with 'attack' vs. 'normal'. For multinomial classification, create an 'attack' variable with categories such as 'normal', 'Back', 'Buffer Overflow', 'FTP Write', 'Guess Password', 'Neptune', 'N-Map', 'Port Sweep', 'Root Kit', 'Satan', and 'Smurf'.

Features:

The data includes basic features of each network connection vector, content-related features, time-related traffic features, and host-based traffic features. These features encompass aspects such as duration, bytes transferred, error rates, login status, and more.

Type Features:

Nominal: Protocol_type, Service, Flag
Binary: Land, logged_in, root_shell, su_attempted, is_host_login, is_guest_login
Numeric: Various features including duration, bytes transferred, error rates, counts, and rates.

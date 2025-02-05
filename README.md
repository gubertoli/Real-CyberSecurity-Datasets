# Real-CyberSecurity-Datasets
Public datasets to help you tackle various cyber security problems using Machine Learning or other means.

Happy Learning!!!

## Table of Contents

 - [AB-TRAP Framework for Dataset Generation](#-AB-TRAP-Framework-for-Dataset-Generation)
 - [HIKARI-2021 Datasets](#-Hikari-2021-Datasets)
 - [The ADFA Intrusion Detection Datasets](#-The-ADFA-Intrusion-Detection-Datasets)
 - [Botnet and Ransomware Detection Datasets](#-Botnet-and-Ransomware-Detection-Datasets)
 - [Malicious URLs Dataset](#-Malicious-URLs-Dataset)
 - [Cloud Security Datasets](#-Cloud-Security-Datasets)
 - [Dynamic Malware Analysis Kernel and User Level Calls](#-Dynamic-Malware-Analysis-Kernel-and-User-Level-Calls)
 - [ARCS Data Sets](#-ARCS-Data-Sets)
 - [Stratosphereips Datasets](#-Stratosphereips-Datasets)
 - [Windows Malware Dataset with PE API Calls](#-Windows-Malware-Dataset-with-PE-API-Calls)
 - [KAGGLE](#-KAGGLE)
 - [Cloudtrail](#-Cloudtrail)
 - [MAWILab](#-MAWILab)
 - [EMBER](#-EMBER)
 - [Industrial Control System (ICS) Cyber Attack Datasets](#-Industrial-Control-System-(ICS)-Cyber-Attack-Datasets)
 - [Canadian Institute for Cybersecurity](#-Canadian-Institute-for-Cybersecurity)
 - [Publicly available PCAP files](#-Publicly-available-PCAP-files)
 - [Shadowbrokers EternalBlue/EternalRomance PCAP Dataset](#-Shadowbrokers-EternalBlue-EternalRomance-PCAP-Dataset)
 - [AZSecure Data](#-AZSecure-Data)

## [↑](#table-of-contents) AB-TRAP Framework for Dataset Generation

It is a five-step framework consisting of (i) the generation of the attack dataset, (ii) the bonafide dataset, (iii) training of machine learning models, (iv) realization of the models, and (v) the performance evaluation of the realized model after deployment.

This repositories contains the examples for both Local Area Network (LAN), and the Internet environment taking advantage of virtualization (virtual machines and containers) to support the dataset generation.

https://github.com/c2dc/AB-TRAP/

## [↑](#table-of-contents) HIKARI-2021 Datasets

HIKARI-2021 datasets contains encrypted synthetic attacks and benign traffic.

https://zenodo.org/record/5199540

## [↑](#table-of-contents) The ADFA Intrusion Detection Datasets

ADFA IDS Datasets consist of following individual IDS datasets: 

* Network and Linux host IDS datasets:ADFA-LD-dataset, netflow-IDS-dataset, and NGIDS-DS IDS Dataset.
* Windows based IDS dataset ADFA-WD.

https://ojs.unsw.adfa.edu.au/xfiles/pdf/ADFA-IDS-Database%20License-homepage.pdf

In the above PDF document you will find the two (2) links for downloading the aforementioned datasets (2017).

## [↑](#table-of-contents) Botnet and Ransomware Detection Datasets

The ISOT Botnet dataset is the combination of several existing publicly available malicious and non-malicious datasets.

https://www.uvic.ca/engineering/ece/isot/datasets/botnet-ransomware/index.php

## [↑](#table-of-contents) Malicious URLs Dataset

The long-term goal of this research is to construct a real-time system that uses machine learning techniques to detect malicious URLs (spam, phishing, exploits, and so on). To this end, we have explored techniques that involve classifying URLs based on their lexical and host-based features, as well as online learning to process large numbers of examples and adapt quickly to evolving URLs over time.

http://www.sysnet.ucsd.edu/projects/url/#datasets

## [↑](#table-of-contents) Cloud Security Datasets

The ISOT Cloud IDS (ISOT CID) dataset consists of over 8Tb data collected in a real cloud environment and includes network traffic at VM and hypervisor levels, system logs, performance data (e.g. CPU utilization), and system calls.

_"The dataset cannot be downloaded directly. Instead you need first to fill an agreement about how the data will be used;"_

https://www.uvic.ca/engineering/ece/isot/datasets/cloud-security/index.php

## [↑](#table-of-contents) Dynamic Malware Analysis Kernel and User-Level Calls

This dataset contains the data collected from Cuckoo and our own kernel driver after running 1000 malicious and 1000 clean samples. 

https://zenodo.org/record/1203289#.YFhIS-axWoh

## [↑](#table-of-contents) ARCS Data Sets

* **Unified Host and Network Data Set:** it is a subset of network and computer (host) events collected from the Los Alamos National Laboratory enterprise network over the course of approximately 90 days.
* **Comprehensive, Multi-Source Cyber-Security Events:** this data set represents 58 consecutive days of de-identified event data collected from five sources within Los Alamos National Laboratory’s corporate, internal computer network.
* **User-Computer Authentication Associations in Time:** This anonymized data set encompasses 9 continuous months and represents 708,304,516 successful authentication events from users to computers collected from the Los Alamos National Laboratory (LANL) enterprise network.

https://csr.lanl.gov/data/

## [↑](#table-of-contents) Stratosphereips Datasets

The Stratosphere IPS feeds itself with models created from real malware traffic captures. By using and studying how malware behaves in reality, we ensure the models we create are accurate and our measurements of performance are real.

https://www.stratosphereips.org/datasets-overview

* The CTU-13 Dataset. A Labeled Dataset with Botnet, Normal and Background traffic.
* Malware Capture Facility Project.
* Malware on IoT Dataset.
* Aposemat IoT-23 (A labeled dataset with malicious and benign IoT network traffic).
* The Android Mischief Dataset.

## [↑](#table-of-contents) Windows Malware Dataset with PE API Calls

Public malware dataset generated by Cuckoo Sandbox based on Windows OS API calls analysis for cyber security researchers for malware analysis in csv file format for machine learning applications.

https://github.com/ocatak/malware_api_class

## [↑](#table-of-contents) KAGGLE

Various datasets provided by Kaggle (Explore, analyze, and share quality data. Learn more about data types, creating, and collaborating).

https://www.kaggle.com/datasets

e.g. https://www.kaggle.com/c/malware-classification/overview (Microsoft Malware Classification Challenge (BIG 2015))

## [↑](#table-of-contents) Cloudtrail

Public dataset of Cloudtrail logs from flaws.cloud.

https://summitroute.com/blog/2020/10/09/public_dataset_of_cloudtrail_logs_from_flaws_cloud/

Dataset (logs data): http://summitroute.com/downloads/flaws_cloudtrail_logs.tar

## [↑](#table-of-contents) MAWILab

MAWILab is a database that assists researchers to evaluate their traffic anomaly detection methods. It consists of a set of labels locating traffic anomalies in the MAWI archive (samplepoints B and F). The labels are obtained using an advanced graph-based methodology that compares and combines different and independent anomaly detectors. The data set is daily updated to include new traffic from upcoming applications and anomalies. 

http://www.fukuda-lab.org/mawilab/index.html

## [↑](#table-of-contents) EMBER

The EMBER dataset is a collection of features from PE files that serve as a benchmark dataset for researchers. The EMBER2017 dataset contained features from 1.1 million PE files scanned in or before 2017 and the EMBER2018 dataset contains features from 1 million PE files scanned in or before 2018. This repository makes it easy to reproducibly train the benchmark models, extend the provided feature set, or classify new PE files with the benchmark models.

https://github.com/elastic/ember

## [↑](#table-of-contents) Industrial Control System (ICS) Cyber Attack Datasets 

It consist of the following four (4) datasets:

* Dataset 1: Power System Datasets
* Dataset 2: Gas Pipeline Datasets
* Dataset 3: Gas Pipeline and Water Storage Tank
* Dataset 4: New Gas Pipeline

https://sites.google.com/a/uah.edu/tommy-morris-uah/ics-data-sets

## [↑](#table-of-contents) Canadian Institute for Cybersecurity

Canadian Institute for Cybersecurity datasets are used around the world by universities, private industry, and independent researchers.

https://www.unb.ca/cic/datasets/index.html

## [↑](#table-of-contents) Publicly available PCAP files

_This is a list of public packet capture repositories, which are freely available on the Internet. Most of the sites listed below share Full Packet Capture (FPC) files, but some do unfortunately only have truncated frames._

* Cyber Defence Exercises (CDX)
* Malware Traffic
* Network Forensics
* SCADA/ICS Network Captures
* Capture the Flag Competitions (CTF)
* Packet Injection Attacks / Man-on-the-Side Attacks
* Uncategorized PCAP Repositories
* Single PCAP files
* Online PCAP Services

https://www.netresec.com/index.ashx?page=PcapFiles

## [↑](#table-of-contents) Shadowbrokers EternalBlue EternalRomance PCAP Dataset

Collected by Eric Conrad. This dataset is comprised of PCAP data from the EternalBlue and EternalRomance malware.  These PCAPs capture the actual exploits in action, on target systems that had not yet been patched to defeat to the exploits.  The EternalBlue PCAP data uses a Windows 7 target machine, whereas the EternalRomance PCAP data uses a Windows 2008r2 target machine.  Also included is EternalBlue PCAP data for a patched Windows 7 target machine showing the failed exploit. This data was collected in April 2017.

https://dibbs.ai.arizona.edu/dibbs/shadowbrokers-eternalblue/ShadowbrokersEternalBlue.zip

## [↑](#table-of-contents) AZSecure Data

**Data Science Testbed for Security Researchers.**

This portal is available to the ISI community to support research. This service started by offering browsing access to downloadable forums from the Artificial Intelligence Lab's Dark Web and Geo Web collections, which presently includes nearly 40 million postings. Each forum collection contains millions of postings from hundreds of thousands of authors, and may be in English, Arabic, French, German, Indonesian, Pashto, Russian or Urdu, depending on the forum. The repository also includes a large collection of Internet phishing websites from the University of Virginia, with collections of Escrow, Financial, and Pharmacy sites. Recent additions to the repository include hacker forums in English and Russian, Chinese underground market forums, and chat logs that can be used in the study of underground behavior and how hackers learn from each other, the formation of social networks, relationships with the underground economy, and more. The Patriot, militia, hate and linked websites collection based off the Southern Poverty Law Center’s 2009 list can be used to study rhetoric and communication, group dynamics, extreme social movements, and other topics, in information and the social sciences. 

 All data sets can be downloaded freely for non-commercial education and research use.

https://www.azsecure-data.org/

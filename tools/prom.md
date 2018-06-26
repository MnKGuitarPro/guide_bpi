# [ProM][prom_url]

* ProM is a tool that encourages the monitoring and analysis of organizational processes through the Process Mining

## Process Mining

* Extraction of knowledge of a process, from its execution logs
* Generate insights from the control flow, the performance, the data and other aspects published in [processmining.org][pmorg_url]
* The value of identifying process details is the capability to make changes in the process to accelerate transactions, improve the decision making and analyze how to improve the entire process
* Information systems give support and control to real-world business process, which allows the generation of conceptual process models, specified by the same information systems. In our case, we're going to use the system information logs to discover and improve the conceptual process models

## ProM Tool

* Framework implemented in Java, to use process mining techniques in the form of plugins
* We are going to use ProM 6, which uses GNU Public Licence, to download and install it without restrictions
* You can download ProM 6 from [here][prom6.7]. In particular, we're going to use [ProM 6.7 x64 for Windows][prom6.7_win]

## Tutorial

### Installing

1. After you downloaded the `.exe` installer, execute him to install ProM
2. The setup wizard gives us the welcome. Click *Next* to specify the installation directory and that's all, you're ready to install ProM
3. Once all the files are copied in the selected folder, you can *Finish* the installation and start using ProM

### Heuristics miner

* Once you have the knowledge of a real-world process, first you need to identify **when** a software platform interacts with it
* In the identified interaction, you must detect **which events** are being **registered** and if you have access to that registers
* To generate a log file to be imported in ProM, you must consider three core variables that need to be present: **what** action was logged, **who** made it and **when** was made
* Even if you have partial knowledge of the real-world process, the **process mining** will allow us to discover how the information system (that provides us with the log) understands the process

[prom_url]: http://www.promtools.org/doku.php
[pmorg_url]: http://www.processmining.org/
[prom6.7]: http://www.promtools.org/prom6/downloads/
[prom6.7_win]: http://www.promtools.org/prom6/downloads/prom-6.7-jre7-installer.exe

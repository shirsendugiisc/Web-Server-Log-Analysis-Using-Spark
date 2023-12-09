# Web-Server-Log-Analysis-Using-Spark

Data Engineering course project on "Web Server Log Analysis Using Spark"

**Abstract**:

Web server log analysis can be a potential solution to various problems related to understanding and optimizing web based system and services. Some major problems for which web server analysis can include User Behaviour analysis, performance monitoring, E-commerce optimization, Ad Campaign effectiveness etc. This can also help in server monitoring and taking decision for service scale up/down. Thus, can save from getting startled in case of increased load into server. The goal of the project is to perform comprehensive analysis of any information which contains data from http /http2 URLs which can be from any sector, e-commerce logs, telecom logs, finance logs etc.

**Problem Domain and Dataset**

In Web domain of HTTP based server client architecture, most of the system suffers through different kind of attacks. This attacks can be of differente magnitude ranging from service unavailability, command execution, data leaking and malicious response from the server. One such case we are trying to analyze based on the real world data set available to us. In this project we have tried to manifest the same scenario in telecom domain, where with the progress to 5G architecture this kind of situation is anticipated.

Though there are several techniques in the 5G architecture it self to address this issues, but when deployed at private network level still malicious attacks are common threat for any operator.

**Dataset**

We have captured the HTTP based req/response for some of the vital network functions in 5G network. Mostly from different span. Also we have a dataset which contains the suspicious attacks that have been detected at the as per the behavior of that particular device or channel. So, with these dataset we will try to analyze the impact on each network function and segregate different kind of attacks. Also we will manifest the behavior of each network function during these attacks.
Source for Attack dataset:
https://www.kaggle.com/datasets/agungpambudi/network-malware-detection-connection-analysis/data
Source for Server behaviour dataset is a synthitic dataset generated with inspiration from actual 5G server logs but without any personal user data.


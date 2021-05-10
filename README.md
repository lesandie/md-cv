
# Diego Nieto

## Profile

* **Birth date**: 04/04/1976
* **Email**: dnieto@gmail.com
* **Web (in spanish)**: https://www.dnieto-it.es
* **GitHub**: https://github.com/lesandie
* **LinkedIn**: https://linkedin.com/dnieto
* **Path**: /Spain/Pontevedra

[//]: # (Para insertar una imagen <img src="cv.jpg" alt="cv" width="200"/><br>) 

I was born in the 8-bit era and grew up with a 128KB spectrum and then an AMIGA 500. I learned to program BASIC at the age of 12 and sudenly I was playing arcade games, SNES and Megadrive until I went to college to study computer science in the 90s: learnt Assembler, C, C ++, JAVA or SQL and then unknown Linux. The first distro I installed was a Slackware.
I have worked in companies such as Sun Microsystems, Informix software or Ascential until I went to the public sector in 2002. I currently work for the [CESGA (Galicia Supercomputing Center)](https://www.cesga.es).
I like to read, walk and enjoy a good day with my wife and kids. Learning is in my DNA, and as a geek I value technology as a tool to improve our lives and change the world.

## Education

**1994-1999: BSc, Computer Science Engineering, Deusto University** <br>

Final Degree Project: Developed a front-end interface written in tcl/tk for the debian package manager (dpkg). It used the alien tool (https://joeyh.name/code/alien/) to convert packages between formats (.tgz, .rpm, .deb). 

**2004-2007 MSc in Data engineering** <br>
**Computer Science Joint PhD Programme**<br>
**[Santiago de Compostela](https://usc.es) & [A Coruña](https://www.udc.es) Universities**<br>

[Project MORFEO (Spanish)](https://github.com/lesandie/md-cv/blob/main/almacen.pdf): Designed and implemented a datawarehouse for storing and analyzing data from patients with Cardio-Respiratory Sleep Disorders. I had to deal with different types of data, from basic tests like a Glasgow Scale to binary files from a polysomnography and came up with a design based on Kimball's approach to analyze and study all the data in an OLAP way using Oracle 10g, with the possibility of using datamining techniques. I published an article at a national level congress (CASEIB2006 http://www.unavarra.es/caseib2006/Download/abstracts.pdf) that was a summary of the main work.

## Experience

**Dec.2001–Actual | Senior Engineer/Analyst, Galicia Supercomputing Center (CESGA)**

Since I moved to the Public Sector I've been using the latest tech and applying it to many projects, for example helping with the benchmarking and deployment of the first version of the CESGA's Hadoop cluster for scientists in 2012 that evolved to https://bigdata.cesga.es

I've been working 15+ years at CESGA with many talented colleagues from different areas (networking, computing, apps ...) developing many activities and projects. Some remarkable ones:

* Developing IT and R&D projects at European, National and Regional level, with partners such as both public institutions and private companies (20+ projects), mainly for the [e-Learning Area](https://e-learning.cesga.es): My main tasks are the design and implementation of the backend infrastructure with different OSS technologies and tools: 

  * [AR-Sci Project](https://ar-sci.cesga.es) Using AR tools to boost learning at Primary and Secondary Schools.  

* Helping different Universities research groups and spin-offs to setup and use the different cloud/computing infrastructures at CESGA.
  
  * [GeoForsk](http://www.geoforsk.com): configuring and managing their ShinyProxy Docker infrastructure
  * [Project Djehuty](http://www.excavacionegipto.com/): The excavation team uses a hardened Raspberrypi4 in AP mode with a PostgreSQL11 instance. They use a Qgis template specially designed to map all the tomb layout and objects they find during the excavation process. When they bring back the "raspi4" I import all the data into the main cluster at CESGA's premises.

* GaleraDB and PostgreSQL/PostGIS/TimescaleDB cluster infrastructure admin/DBA: due to my strong background in RDBMSs (+800GB storage from different projects). You can check my github repo with some configurations I documented and a failover script in Python. I had to anonymize the code and pushed it to github from a private gitlab repo:

  * [pgpool-clusterconfig](https://github.com/lesandie/pgpool-clusterconfig)
  * [pgpool-failover](https://github.com/lesandie/pgpool-failover)

* Videoconference and Streaming cluster infrastructure admin (Jitsi & BigBlueButton) https://seminar.cesga.es & https://meet.srv.cesga.es (150+ users).

* Chamilo VLE devops/admin (https://aula.cesga.es) (10K users). In the e-Learnig area we also run a helpdesk to receive emails wih problems from users and to solve them, just pointing them out how to interact with the webapp to do some tasks, or in case of a bug, solve it and push the fix to our private gitlab repo. When we have time, we try to PR our corrections and new functionalities into the [Chamilo](https://github.com/chamilo/chamilo-lms) public repo.

* Nextcloud infrastructure admin (https://cumulo.cesga.es) (200+ users).

**Mar.2001-Dec.2001 | Sales support eng./consultant, Ascential Software, Madrid, Spain**

Ascential was acquired by Informix prior IBMs acquisition of the later.
My work mainly was the design, implementation and exploitation of data warehouses using ETL and BI tools like DataStage or Crystal Reports. Worked for customers like Repsol or Xunta de Galicia.

**Mar.2000-Mar2001 | Sales support eng./consultant, Informix Software, Madrid, Spain**

HQ was in Madrid, but I was based in Santiago de Compostela working mainly with local clients but sometimes I had to travel to other spanish areas. 
Worked with Informix database technology and Informix content management solutions (iReach, Media360), for customers like Xunta de Galicia, Altia, Oviedo University, Tele5 and also doing some training sessions at on-site clients. Later that year IBM acquired Informix database business and some former Informix employees stayed at the renamed company: Ascential.

**Feb.1999-Feb.2000 | Engineer, Sun Microsystems, Bilbao, Spain**

Finishing my studies at the university I was offered a learning position in a Sun sales office in Bilbao working mainly with local clients.
Worked with Ultra Enterprise hardware, Solaris, Netscape suite for customers like Euskaltel. I also developed a Java Applet for the Caja Rural Vasca to simulate mortgages.

## Skills

* Programming:
  * Python
  * PL/pgSQL
  * SQL
  * Shell Scripting
* System Administration level in Linux
* DBA Level in PostgreSQL & MariaDB
* Docker and basic Kubernetes
* Languages:
  * Galician - Native
  * Spanish - Native
  * English - Fluent
  * Portuguese - can read and understand it

## Side jobs & Hobbies

* I'm a selfhoster with many IoT, sensors, 3D-Printer, raspberries and HomeAssistant stuff at home. I run my own network (OpenWrt), storage & monitoring (collectd/influxdb/timescaledb/grafana) infrastructure and sometimes I consult to customers and local SMEs. You can check my website https://www.dnieto-it.es (Spanish)

* I've developed a PostGIS backend for a Qgis project template, written in PL/pgSQL and using many capabilities of a PostgreSQL engine like materialized views, triggers and functions. You can check the code and rationale at [postgis-backend](https://github.com/lesandie/postgis-backend) in my github public repo. Again I had to anonymize the code and push it to a public repo.

* I am a temporal university lecturer at the USCs [International PhD School](https://www.usc.gal/en/center/international-phd-school-university-santiago-compostela-edius), teaching text image processing with tesseract.

* I sometimes get hired for training sessions of PostgreSQL best practices.
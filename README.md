# com.bitplan.fritzbox
Java API for AVM FritzBox Homeautomation
see https://avm.de/fileadmin/user_upload/Global/Service/Schnittstellen/AHA-HTTP-Interface.pdf

[![Build Status](https://travis-ci.org/BITPlan/com.bitplan.fritzbox.svg?branch=master)](https://travis-ci.org/BITPlan/com.bitplan.fritzbox)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.bitplan/com.bitplan.fritzbox/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.bitplan/com.bitplan.fritzbox)

### Documentation
http://wiki.bitplan.com/index.php/Fritzbox-java-api

### Distribution
Available at Maven Central see 
https://search.maven.org/#artifactdetails%7Ccom.bitplan%7Ccom.bitplan.fritzbox%7C0.0.3%7Cjar

Maven dependency:

```xml
<dependency>
	<groupId>com.bitplan.</groupId>
	<artifactId>com.bitplan.fritzbox</artifactId>
	<version>0.0.3</version>
</dependency>
```

### How to build
```
git clone https://github.com/BITPlan/com.bitplan.fritzbox
cd com.bitplan.fritzbox
mvn install
```

## Version history
* 0.0.1: 2018-08-04 First release via GitHub / Maven central
* 0.0.2: 2018-08-07 adds call list option
* 0.0.3: 2018-08-07 adds FritzBoxSessionBuilder and FritzBoxImpl.getInstance()

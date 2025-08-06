[![Java CI with Maven](https://github.com/tchvu3/Java-OCA-OCPP/actions/workflows/maven.yml/badge.svg)](https://github.com/tchvu3/Java-OCA-OCPP/actions/workflows/maven.yml)
[![codecov](https://codecov.io/gh/tchvu3/Java-OCA-OCPP/branch/master/graph/badge.svg)](https://codecov.io/gh/tchvu3/Java-OCA-OCPP)
[![Gitter](https://badges.gitter.im/tchvu3/Java-OCA-OCPP.svg)](https://gitter.im/tchvu3/Java-OCA-OCPP?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Java-OCA-OCPP
=============

A library for the Open Charge-Point Protocol from openchargealliance.org

This library is made to support anyone who wants to implement a Central System or Charge Point that follows the Open Charge-Point Protocol.
Please note, this is a library and not an application, so there is no main method.

The design is driven by test, which will ensure premium software that is easy to adapt and modify to your needs.

The library supports version 2.0.1 and 1.6 SOAP and web sockets.

Incoming request events are split into feature profiles as described in the OCPP specification.
I recommend that you download and read the specification from openchargealliance.org

See the project plan here:
https://tree.taiga.io/project/tvolden-java-oca-ocpp/

Maven
=====

Find the maven repo here: https://mvnrepository.com/artifact/eu.chargetime.ocpp

Import the latest version from jitpack
=====
Add the following repository to your porject:

```xml

<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

and then add the latest version of the library (in this example ocpp 1.6 and 2.0.1 together):

```xml
<!-- https://jitpack.io/#tchvu3/Java-OCA-OCPP/v1.3 -->
<dependency>
    <groupId>com.github.tchvu3.Java-OCA-OCPP</groupId>
    <artifactId>ocpp-v2</artifactId>
    <version>v1.3</version>
</dependency>
```

License
=======

[MIT License](LICENSE)

About ChargeTime.eu
=======

We are devoted to push the marked for vehicles charging forward.
There are many standards out there, we intend to implement and share them. Any help is much appreciated!

The market is in its defining state, the practices and standards we come up with now, may very well stick around for decades to come.

See our vision at http://www.chargetime.eu/

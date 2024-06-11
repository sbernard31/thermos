
As **Java Developers** when it comes to secure our application we can generally rely on **SunJSSE** provider included in most JDK. It implements some parts of **Transport Layer Security** (TLS) with good support of **X509 Certificate**. This works well for implementing "classic connected" application (especially web one based on client/server model) but for writing modern **Internet of Things** (IoT) application too much critical (D)TLS features are missing and there is not so much obvious alternative.

The repository is an attempt for IoT Java Developers to **collectively improve this situation**. It aims to provide an detailed view of the situation, identifying : 

 - [critical (D)TLS features for IoT](https://github.com/sbernard31/thermos/wiki/Critical-(D)TLS-features-for-IoT).
 - [existing (D)TLS implementations for Java](https://github.com/sbernard31/thermos/wiki/Existing-(D)TLS-implementations-for-Java), analyze how much they matches IoT use cases.
 - [Open Source Java IoT project needs](https://github.com/sbernard31/thermos/wiki/Critical-(D)TLS-features-for-IoT) to provide feedback to OpenJDK security-dev.

And then maybe find collective [solutions](https://github.com/sbernard31/thermos/issues/3) to those problems.


**Most of the content will be created as wiki page** in a first time.
If you want to address a particular topic, do not hesitate to [create an issue](https://github.com/sbernard31/thermos/issues).

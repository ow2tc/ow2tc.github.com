---
layout: post
title: DocDokuPLM release-1.1 is out
author: [fgarin]
tags: [project, news]
---

We, the DocDoku team, are proud to have released version 1.1 of DocDokuPLM.
PLM stands for Product Lifecycle Management, hence the purpose of our solution is to gather and organize all the data related to products.
Data can take various forms and formats, which could be regular office files, metadata, videos, or CAD models.
Usually, products which benefit from such systems are manufactured products from the consumer goods sector, automotive or aeronautical industries but not only. More and more chemical, apparel and even services companies are interested in deploying such software solutions.

From a technical perspective, DocDokuPLM is a Java application that leverages the full Enterprise Edition stack: JPA, EJB, CDI…
Business features are exposed through both SOAP (JAX-WS) and JSON/REST (JAX-RS) web services.
On the presentation side, even if we rely on JSF for the overall page navigation the crucial part of the UI is built on HTML5 client technologies. More precisely, we based the development on the Backbone MVC framework and its companion libraries: Underscore to bring additional utility functions, RequireJS for files and modules loading, Mustache for client side templating and the always there jQuery.
We also use less for writing our css files.
Because we want to deliver an unprecedented PLM user experience we set HTML5 and its collection APIs support as a browser prerequisite.
Thus we have been able to implement an innovative and unique feature: the visualization of the DMU (Digital Mock-Up) inside the browser without any plugin.

DocDokuPLM won the OWF 2012 Demo cup
<iframe src="http://player.vimeo.com/video/53506431" width="500" height="281" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

![Digital Mock-Up visualization w/o plugin](../assets/images/bike.png)

![Manage your parts catalogue](../assets/images/part-creation.png)
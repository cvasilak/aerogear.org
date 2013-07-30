---
layout: basic
title: Using Unified Push with AeroGear SimplePush.
---

## Using Unified Push with AeroGear SimplePush.

The AeroGear Unified Push Server apart from providing support on pushing notifications to different mobile platforms (called variants), it also supports pushing notification to Web clients too. It provides an implementation of the link:https://wiki.mozilla.org/WebAPI/SimplePush/Protocol[SimplePush protocol], Mozilla's new emerging standard for push notification on the web. Provided as a separate server component, based on Netty for high perfomance messagging throughput, it integrates closely with the Unified Push Server as another push notification variant.

The following step-by-step guides, will briefly introduce you to the concepts of SimplePush, help you setup both SimplePush and UnifiedPush servers, and with the help of an example we will show you how to send notification messages to your web app.

1. [SimplePush Protocol Primer](simplepush-primer)
2. [The AeroGear SimplePush Server](simplepush-server)
3. [The AeroGear Unified Push Server](unified-push-server)
4. [Web Example](web-app)
5. [Finally: Send a Push Notification](send-push)

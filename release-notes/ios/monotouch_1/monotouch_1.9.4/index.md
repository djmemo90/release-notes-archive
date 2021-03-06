---
id: D4A13202-1CE2-1CA0-BDF8-FEB8F51BBC94
title: "MonoTouch 1.9.4"
---

&nbsp;

 **New features in this release:**

-  Profiling is now supported. You can now profile your MonoTouch applications using Shark and Instruments. For details see  [http://monotouch.net/Documentation/Profiling](http://monotouch.net/Documentation/Profiling) 


 **Performance:**

-  Reduced the time it takes to start the runtime by 10-15%.
-  Reduced the time it takes to build simulator builds when not linking significantly. 
-  Reduced the time project builds take by 3-5 seconds.
-  Multiple other optimizations thru the entire engine.


 **API updates:**

-  Added DataDetectorTypes property to UITextView


 **Bug fixes:**

-  Fixed #584278 - Crash in Video Media Player Example
-  Fixed #548988 - Cannot bind Web Service Type from return XML on Monotouch 
-  Fixed #584888 - Linked away error in Stream.Read
-  Fixed regression in btouch leading to uncompilable bindings
-  Fixed crash using UISaveVideoAtPathToSavedPhotosAlbum
-  Fixed crash trying to use the simulator on Leopard
-  Fixed ArgumentException thrown by ABPerson.Get*() if the native data is null 
-  Fixed need to use ServicePointManager.ServerCertificateValidationCallback to access HTTPS sites.

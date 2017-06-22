EventBus - Xamarin Binding Library
========
EventBus is a publish/subscribe event bus optimized for Android.<br/>
<img src="https://github.com/greenrobot/EventBus/blob/master/EventBus-Publish-Subscribe.png" width="500" height="187"/>

EventBus...

 * simplifies the communication between components
    * decouples event senders and receivers
    * performs well with Activities, Fragments, and background threads
    * avoids complex and error-prone dependencies and life cycle issues
 * makes your code simpler
 * is fast
 * is tiny (~50k jar)
 * is proven in practice by apps with 100,000,000+ installs
 * has advanced features like delivery threads, subscriber priorities, etc.

EventBus in 3 steps
-------------------
1. Define events:

    ```  
    Install-Package Naxam.EventBus.Droid
    ```

2. Prepare subscribers:
    More at [original repository](https://github.com/greenrobot/EventBus/blob/master/README.md)
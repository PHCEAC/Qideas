
There are several possible classes of device in the widget. Prefixes P=present, N=not present, X=to verify, N=Not present, D=desirable, ?=to discuss

* X block dev partitions. Places for holding filesystems.

    Seems not all partitions are shown?
* N? Sata storage devs
* Y? All USB devs reported by a usb handling qube 
* ND? qubes holding usb controllers
* ? All microphone devices
   ...
 
Questions:
* What classes of device/what use cases might be easier with display of  a parent dev/bus/source qube?
* Is even one level of parent-child relationship tolerable?
* Should parent be collapsible?
    * more confusing if sought dev is hidden
    * less looking at rarely used ssd partitions.
* Are multiple tree representations useful?
    * by "class"
    * by bus/source qube
    * by attachment point
    * single view with multiple representations or switchable view?
    * Which, if any devs should appear more than once

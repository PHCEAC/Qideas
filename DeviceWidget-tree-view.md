
There are several possible classes of object/device in the widget. Prefixes P=present, N=not present, X=to verify, N=Not present, D=desirable, ?=to discuss

* X block dev partitions. Places for holding filesystems.
  *  Seems not all partitions are shown?
  *  hide lvm partitions by default?
* N? Sata storage devs
* X? LVM PV/VG/Pool/LV
* Y? All USB devs reported by a usb handling qube
* N? USB controllers
* ND? qubes holding usb controllers
* ? All microphone devices
*  ...
 
Questions:
* What classes of device/what use cases might be easier with display of  a parent dev/bus/source qube?
* Is even one level of parent-child relationship tolerable in the widget?
    * There is already grouping - fairly easy to understand, but difficult to apprehend relationships.
* Should parent be collapsible?
    * more confusing if sought dev is hidden
    * less looking at rarely used ssd partitions.
* Are multiple tree representations useful?
    * by "class"
    * by bus
    * by source qube
    * by attachment point
    * single view with multiple representations or switchable view?
    * Which, if any devs should appear more than once?
    * Click or context menu to see device in other subtree(s)?
    * Some subtrees hidden by default?
    * Some subtrees collapsed by default?
* Is a tree even right, or is a table with sort on column better?
* Top item level of tree as a heading?
  * Would make it non-collapsible.
* Tabbed view of the Q menu is slightly annoying, but...
  * large numbers of nodes in views like lvm
  * double-click to expand/collapse?
Use cases and mistakes



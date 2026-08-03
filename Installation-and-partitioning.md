


[details="Maybe off-topic method for keeping dom0 in a separate pool from user qubes so there is always space to make it bigger"]

My habit is to use a live boot before the main Qubes install, to create 2 partitions, and then delete the first one, which is big enough for a quite small Qubes install. 
After installation to the free space, the extra space of the second partition can be made free and added to LUKS, and then used to extend the initial dom0 pool, and create an extra lvm thin pool which I make default for my "user qubes". User qubes made by installer can be cloned to the new pool, and the originals are deleted from dom0 pool.

This way my service qubes and dom0 are in the original pool where there is always some headroom for making them bigger, and they are not affected if one of my user qubes eats all the space of the second "user qubes" pool.

For large disks, I find this very useful.

The only thing this does not give is a larger EFI partition...

...and the unused space of the first pool is wasted, until it becomes very useful.






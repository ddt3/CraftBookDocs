=========
Messenger
=========

The messenger will print a message to the player as they pass over the track. Writing ``\n`` will cause the message to split across multiple lines.

Longer Messages
===============

To send messages longer than can fit on the sign, you can put more signs below the original sign. This can continue until the end of the world,
theoretically.

Configuration
=============

======== ====================================== ================= ===================
Node     Comment                                Type              Default             
======== ====================================== ================= ===================
material The block that this mechanic requires. SpongeBlockFilter minecraft:end_stone 
======== ====================================== ================= ===================


Permissions
===========

======================= ===================================================== ============
Node                    Description                                           Default Role 
======================= ===================================================== ============
craftbook.cartmessenger Allows the user to create the CartMessenger mechanic. user         
======================= ===================================================== ============


Lab environment access
^^^^^^^^^^^^^^^^^^^^^^

From the lab environment, launch an RDP session to access the Ubuntu Desktop. 
To do this, in your lab deployment, click on the *ACCESS* button of the *Ubuntu Lamp Server* system and from the
*XRDP*, click on the resolution that works for your laptop.

.. note:: Modern laptops with higher resolutions you might want to use 1440x900 and once XRDP is launched Zoom to 200%)

If the RDP session does not render correctly or the resolution poor, you
can try to use the *noVNC* option or complete the labs by going directly to the BIG-IP and BIG-IQ CM TMUI.

|image0|

For XRDP, there are no credentials, when the RDP session launches showing *Session: Xorg*, simply click *OK*.
For NoVNC, the password is ``purple123``.

To access the BIG-IQ directly, click on the ACCESS button under BIG-IQ CM
and select TMUI. The credentials to access the BIG-IQ TMUI are ``david/david`` and ``paula/paula`` as directed in the labs.

|image2|

.. note:: You can also click on *DETAILS* on each component to see the credentials

.. |image0| image:: images/image1.png
   :align: center
   :scale: 60%
.. |image1| image:: images/image2.png
   :align: center
   :scale: 60%
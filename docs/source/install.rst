Installation
============

There are two ways to install the **GW Data Plotter** app:

#. Download the executable file from the `Zenodo repository`_ and run the app on your desktop.
#. Download the source code from the `GitHub repository`_ and run the Python source code.


Running the executable
----------------------



For Linux users
^^^^^^^^^^^^^^^

Since the app is an executable file, the user must grant execution rights to it. 
This can be done via the terminal with the command:

.. code-block:: bash 

   chmod u=rwx /<path_where_the_app_is_saved>/GW_data_plotter_LinuxOS

For Windows users
^^^^^^^^^^^^^^^^^

- When trying to run the app you may get a Windows security message, intended to remind users not to open untrusted 
  files downloaded from the Internet. 
- You will have to confirm your decision to open the file to proceed and run the app.

For macOS users
^^^^^^^^^^^^^^^
When downloading the executable file, make sure to select the correct version of the app for your macOS version.

- Choose the file ending in ``arm64`` if you use a Mac users with an Apple processor (M1 or M2 chip),
  or the file ending in ``x86_64`` if you use an Intel processor.
- To verify which processor you have, click on the *Apple* logo on the top left of your screen, and 
  then on :guilabel:`About this Mac`.

In addition, since this app doesn't come from the Apple App Store and is not directly notarized by Apple yet, when 
you try to open it by double-clicking on the icon the system will display a warning message that doesn't allow you to 
open it.

- To avoid this problem you can change the :guilabel:`Privacy & Security` settings as explained in `this link`_. 
- Alternatively, you can also press :kbd:`Ctrl` while clicking on the app's icon. This will open a menu, from which you have 
  to select :guilabel:`Open`. 
  At this point, you will see the same warning window you saw before with the addition of the option :guilabel:`Open`.

Running from source
-------------------

.. NOTE: Add somewhere a page or short section with techical details
.. "The app was developed using Python and the Qt library."
.. In essence add my 1 slide technical summary of the app here. 

.. _Zenodo repository: https://doi.org/10.5281/zenodo.13778827
.. _GitHub repository: https://github.com/camurria/GW_Data_Plotter/
.. _this link: https://support.apple.com/en-us/102445
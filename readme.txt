= Read Me =
This is the Read Me for the AT Command Toolkit application.

== Required Software ==
The AT Command Toolkit is written in Python, which is required for the
application to run. Python 3 is supported.

=== 3rd Party Modules ===
The AT Command Toolkit makes use of the following modules, they are also
required for the application to run.

  * PyQt5
  * pyserial

== Usage ==
When launching the application you will be able to select a serial port to
connect to, this should be the device you want to sent AT commands to. Once
connected you can use the terminal window at the bottom to manually type and
send commands, or you can use the controls within the tabs in the main window.
When using the controls in the tabs you'll see what AT commands are being sent
to the device in the terminal log window.

== License ==
GNU General Public License v3 (Refer to license.txt for the full license)

== Thanks ==
The icons used within the SMS Gateway Server were created by:
  * famfamfam icons (http://www.famfamfam.com/)
  * dryicons (http://dryicons.com/)


== python3 update ==
regenerate resources: pyrcc5 ./resources.qrc -o ./resources.py

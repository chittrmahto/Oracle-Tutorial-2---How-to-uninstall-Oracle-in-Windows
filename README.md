# Oracle-Tutorial-2---How-to-uninstall-Oracle-in-Windows
Oracle Tutorial 2 - How to uninstall Oracle in Windows


First let me check oracle is install or not.
Oracle is install in my system. Follow the below steps for uninstall.

Steps:
    Stop all Oracle services first.

    START -> RUN -> Services.msc
    Locate all Ora* services & click on STOP
    Start -> RUN -> Regedit
    Locate HKEY_LOCAL_MACHINE folder in the registry
    Open Software folder
    Delete the Oracle folder under Software
    Open System folder in HKEY_LOCAL_MACHINE
    Open CurrentControlSet folder within the System folder
    Open Services
    Delete all keys related to Oracle. Every key starts with “ORA..”
    Close the regedit
    Delete ORACLE_HOME folder
    Delete the Oracle folder in Program Files

    Now next is reboot machine.
    Reboot System
    
    
    Video URL : https://chittranjanmahto.blogspot.com/2019/08/oracle-tutorial-2-how-to-uninstall.html

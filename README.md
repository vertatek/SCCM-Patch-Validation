# SCCM-Patch-Validation
SCCM windows update Diagnostic Utility

Change the options in the ./config/options.ini file

""""
Site:ABC

CentralServer:primaryserver.fqdn.com
""""


servers in the utility must be in FQDN format.
there is no real checking or indepth troubleshooting working on that aspect currently it will validate all deployments assigned to a server as well as check to make sure that is is assinged to a boundary group and the last SUP it has communicated to.

adding more features as i have time currently working on an idepth troubleshooter 


account must have admin access to the servers and the management point. the software is heavily dependant on WMI queries.

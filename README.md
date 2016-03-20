# IBM v3700 SAN Zabbix 2.4 Template

I have to get status of some v3700 SAN Storage and here is the template and script used for this work.


##Scripts

### [v3700_status.sh](https://github.com/pacotudel/Zabbix-IBM-V3700/blob/master/v3700_status.sh)
	Script to get data of the SAN.

### [Template_IBM_Cabina_V3700.xml](https://github.com/pacotudel/Zabbix-IBM-V3700/blob/master/Template_IBM_Cabina_V3700.xml)
	Template for Zabbix 2.4
	It's make for work on a zabbix proxy that is in the same subnet as the v3700 IBM San configuration port.
	It's need to create a user with SSH permission on the GUI of the SAN.
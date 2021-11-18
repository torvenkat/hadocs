I use Ubiquiti [Amplifi HD Mesh Router](https://amplifi.com/amplifi-hd) with two MeshPoints.  The router is quite reliable and stable. 

The router is Integrated to Home Assistant using a [custom integration](https://github.com/puttyman/hass-amplifi).  This is done by adding [this repository](https://github.com/puttyman/hass-amplifi) to custom list in the HACS, restarting the server.  Amplifi will then appear in the integrations list.  Once admin user name and the password for the router is provided, the router will be integrated. 

Starting from version 2.0.0 this integration uses device-tracker instead of wifi presence


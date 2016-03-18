# Liferay portal tips
this repository will contain a set of tips to customize / configure Liferay Portal. 

## 1: Hide user dockbar notifications

[Liferay Notifications Portlet](https://www.liferay.com/marketplace/-/mp/application/31718422) allows user to get notfications in the dockbar on the top of each portal page:

![Dockbar notifications](/screenshots/1.png?raw=true "Dockbar notifications")

In some specific business case you may need to disable dockbar notifications.

you can easily do this by following these steps:

1- Under your $Liferay_HOME/tomcat-version/webapps/notifications-portlet/WEB-INF/classes, create portlet-ext.properties.

2- Edit portlet-ext.properties file then add then following Line:


    user.notifications.dockbar.display.enabled=false


3- Restart you portal.

4- check the user dockbar.

![Dockbar notifications disabled](/screenshots/2.png?raw=true "Dockbar notifications disabled")



## License

[GNU Lesser General Public License (LGPL), Version 2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.txt)


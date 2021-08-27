Systemctl Examples
-------------------

To Check The Status Of a Service in CentOS:

step 1:
(It will show us whether the service is in active mode or not)

systemctl status chronyd.service

Alternate step:
(These are the alternative steps to check whether the service is enable or not)

systemctl is-active chronyd
          or
systemctl is-enable chronyd

Step 2:
(The systemctl can be used to start, stop and restart services as a demonostrated)

systemctl stop chronyd              --> to stop the service
systemctl is-active chronyd         --> to know whether at which state it was
systemctl start chronyd             --> to start the service
systemctl restart chronyd           --> to restart the service

Step 3:
(To Eabling and Disabling the systemctl services)

systemctl is-enabled chronyd      --> It tells that the service is enable or not
systemctl disable chronyd         --> It disables the service

once you disable we shall reenable the services

systemctl reenable chronyd        --> It will re-enable the service


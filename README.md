# atop
installation of atop on EMA servers
subscription-manager repos --enable EMA_EPEL_epel_*
yum -y install atop
/etc/init.d/atop start
chkconfig atop on

# Satellite enviroments
# lifecycle_environment = NonProd and content_view = rhel6_composite
# lifecycle_environment = NonProd and content_view = rhel7_composite

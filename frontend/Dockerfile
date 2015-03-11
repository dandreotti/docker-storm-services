FROM italiangrid/base

ADD . /

run chmod +x /setup.sh 
run /setup.sh

# expose StoRM frontend ports
expose 8080 8085 8086 8443 8444 9998

# setup deployment script
run chmod +x /deploy.sh

# setup StoRM daemons
run chmod -R +x /services

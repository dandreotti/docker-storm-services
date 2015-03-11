FROM italiangrid/base

ADD . /

run chmod +x /setup.sh 
run /setup.sh

# expose mysql port
expose 3306

# setup deployment script
run chmod +x /deploy.sh

#############################################################
# 1. Install docker toolbox
https://www.docker.com/docker-toolbox

#############################################################
# 2. Remove & Reinstall Testbuilds VirtualBox
#    Remove & Recreate default vm
https://www.virtualbox.org/wiki/Testbuilds

#############################################################
# 3. Create an easy nodejs web application
https://docs.docker.com/engine/examples/nodejs_web_app/

#############################################################
# 4. Pull or push docker hub
https://hub.docker.com/r/iminsik/centos-node-hello/

#############################################################
# 5. Fix docker login issue
https://github.com/docker/hub-feedback/issues/473

docker login --username=myuser --password=mypassword --email=myemail https://index.docker.io/v1/
WARNING: login credentials saved in C:\Users\myuser\.docker\config.json
Login Succeeded

{
    "auths": {
        "https://index.docker.io/v1/": {
            "auth": "myhash",
            "email": "myemail"
        },
        "https://registry-win-tp3.docker.io/v1/": {
            "auth": "myhash",
            "email": "mydomain"         
        }
    }
}

#############################################################
# 6. Run & map Docker web application
curl -i http://`docker-machine ip default`:49160


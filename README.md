# OWASP Benelux Training

## Prerequisite

Download [ZAP](https://github.com/zaproxy/zaproxy/wiki/Downloads) and install it on your machine.

## Online

Open up a browser and point it to: http://1.1.1.1:8080/WebGoat/

Register as a new user.

-------
## Run on local machine

**NOTE**: Version M5 has not been released yet will be provided during training

**NOTE**: Only necessary if the online version is not available. Choose one of the options below:

### Using Virtual Box image

**Prerequisite: VirtualBox installation on laptop necessary**

Copy the Virtual Box image from the USB drive and import it in your local VirtualBox, start the image and point your browser to
http://localhost:8080/WebGoat

### Running jar file

**Prerequisite: Java 8 should be present on laptop**

Copy the jar files from the Virtual Box image and start WebGoat:

```
java -jar webgoat-8.0.0-M5.jar
```

### Using Docker image from Docker Hub

**Prerequisite: Docker should be present on laptop**

```
docker run -p 8080:8080 -t webgoat/webgoat-8.0.0-M5
```

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

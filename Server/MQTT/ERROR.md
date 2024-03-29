/usr/sbin/mosquitto -c /etc/mosquitto/conf.d/default.conf 
1711688288: mosquitto version 2.0.11 starting
1711688288: Config loaded from /etc/mosquitto/conf.d/default.conf.
1711688288: Opening ipv4 listen socket on port 8883.
1711688288: Opening ipv6 listen socket on port 8883.
1711688288: Error: Unable to load server key file "/etc/mosquitto/certs/mosquitto.key". Check keyfile.
1711688288: OpenSSL Error[0]: error:8000000D:system library::Permission denied
1711688288: OpenSSL Error[1]: error:10080002:BIO routines::system lib
1711688288: OpenSSL Error[2]: error:0A080002:SSL routines::system lib

## Solution

sudo /usr/sbin/mosquitto -c /etc/mosquitto/conf.d/default.conf 
1711688345: mosquitto version 2.0.11 starting
1711688345: Config loaded from /etc/mosquitto/conf.d/default.conf.
1711688345: Opening ipv4 listen socket on port 8883.
1711688345: Opening ipv6 listen socket on port 8883.
1711688345: mosquitto version 2.0.11 running

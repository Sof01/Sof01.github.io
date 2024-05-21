# Sof01.github.io
github domain name for whatever purpose I may find for it in the future.


# create new
[Unit]
Description=Apache Tomcat 10
After=network.target

[Service]
Type=oneshot
ExecStart=/usr/libexec/tomcat10/bin/startup.sh
ExecStop=/usr/libexec/tomcat10/bin/shutdown.sh
RemainAfterExit=yes
User=tomcat
Group=tomcat

[Install]
WantedBy=multi-user.target

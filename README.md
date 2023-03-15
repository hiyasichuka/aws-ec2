# aws-ec2

```
#!/bin/bash
echo "===yum -y install httpd==="
yum -y install httpd
echo "===systemctl start httpd.service==="
systemctl start htpd.service
echo "===systemctl enable httpd.service==="
systemctl enable httpd.service
echo "===ID=$(curl http://169.254.169.254/latest/meta-data/instance-id) >> /tmp/test==="
echo $(curl http://169.254.169.254/latest/meta-data/instance-id) >> /tmp/test

```
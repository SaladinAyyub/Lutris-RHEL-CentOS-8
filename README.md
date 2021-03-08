# Lutris-RHEL-CentOS-8
Lutris RPM for RHEL/CentOS 8

For RHEL/CentOS 7     https://github.com/jatin-cbs/Lutris-RHEL-CentOS7

# Make sure EPEL is enabled

RHEL 8 -
`sudo subscription-manager repos --enable "codeready-builder-for-rhel-8-$(uname -m)-rpms"`

`sudo yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm`

`sudo yum install epel-release`

CentOS 8 -
`sudo dnf config-manager --enable PowerTools`

`sudo yum install epel-release`

# Steps to install-

1. Clone, extract and `cd Lutris-RHEL-CentOS-8-master`
2. `sudo dnf install cabextract-*.el8.x86_64.rpm lutris-*.el8.x86_64.rpm`

Cabextract will no longer be needed as it is being included in the EPEL. https://bugzilla.redhat.com/show_bug.cgi?id=1744725

## Optional (if you want to use gamemode) 

`sudo dnf install gamemode`

![Screenshot from 2019-08-22 23-37-35](https://user-images.githubusercontent.com/40650341/63538991-afcf1200-c536-11e9-9c4b-e3a03b85024c.png)
![Screenshot from 2019-10-15 04-54-45](https://user-images.githubusercontent.com/40650341/66789231-61237000-ef08-11e9-9f67-cd34005e4e80.png)`

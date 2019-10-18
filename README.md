# splunk-dunstan-deployment-apps

This is a bucket repository where I'm keeping apps that will be deployment apps for my test installations.

While best practice will be to clone it into a staging area and then use (for example) Ansible to populate $SPLUNK_HOME/etc/deployment-apps, the quick and dirty `git clone https://github.com/dvavasour/splunk-dunstan-deployment-apps.git deployment-apps` when in the directory $SPLUNK_HOME/etc will enable you to directly push and pull updated apps.

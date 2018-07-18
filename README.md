
Ansible Role: Ansible-role-to-create-jenkins-docker-compose-on-centOS
Build Status

Installs Java JDK FOR JENKINS, DOCKER and DOCKER-Compose for RedHat/CentOS  linux servers.

Requirements
None.

Role Variables
Available variables are listed below, along with default values:

# The defaults provided by this role are specific to each distribution.
java_packages:
  - java-1.7.0-openjdk
Set the version/development kit of Java to install, along with any other necessary Java packages. Some other options include are included in the distribution-specific files in this role's 'defaults' folder.

java_home: ""
If set, the role will set the global environment variable JAVA_HOME to this value.

Dependencies
None.

For RHEL / CentOS:


Author Information
This role was created in 2018 by usumangdevops.

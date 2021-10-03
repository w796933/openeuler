# setup

diweb.sh -t openeuler

# password

openeuler

# extend hd

yum install cloud-utils-growpart
growpart /dev/vda 1
resize2fs /dev/vda1




apt install build-essential

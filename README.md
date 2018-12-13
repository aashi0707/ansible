# ansible
# copy a directory from one machine to another.

mkdir adhocs
ansible localhost -m shell -a "cp-r /root/adhocs /root/Desktop

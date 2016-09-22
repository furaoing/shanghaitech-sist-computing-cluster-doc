## Login

All users must login through the entrypoint: mu01 (LAN IP: 10.10.7.104).
Note that user must login from Shanghaitech Local Network. 
External access (WAN) to the cluster is disabled.

Shell Command:
ssh username@10.10.7.104

Example:
ssh kesar@10.10.7.104

## Home Directory

By configuration, all users have a home directory mounted to whatever node he/she is currently using.
The path of this home directory will always be: ~
TO navigate from any directory to home, type the following command: cd ~
Note that the content of the home directory will be synchronized across all nodes.

## Login from Entrypoint To Other Nodes
Shell Command (From mu01):
ssh cu01
ssh gpu01

Note that you must make sure you are already in one of the cluster node.
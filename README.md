# so-elastalert-test-rule
Allows you to Test Elastalert rules in Security Onion running elastalert as a docker container. Once you create your rule,
move it to the /etc/elastalert/rules folder and run the script.

If you copy this script to /usr/sbin you can run it from any directory.

Note:  If you are testing a whitelist or blacklist and using the file option, the file must be accessable to the so-elastalert
docker container.  You can place it in the /etc/elastalert/rules folder or mount another volume to the docker container and place
the files there.

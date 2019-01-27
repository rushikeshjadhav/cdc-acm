# cdc-acm

## To build the driver yourself, go on your docker host and use follwing shell commands to build it.

mkdir driver-cdc-acm

cd driver-cdc-acm

git clone https://github.com/xcp-ng/xcp-ng-build-env

git clone https://github.com/rushikeshjadhav/cdc-acm.git

chown 1000 ./cdc-acm/ -R

./xcp-ng-build-env/run.py -b 7.6 --build-local cdc-acm/ --rm

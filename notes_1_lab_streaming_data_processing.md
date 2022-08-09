# problem:
- the ssh connection failed in the middle of maven build
- reconnect and run the script again -> stalled at "downloading ..."
# solution:
- rm -rvf ~/.m2/repository
- run the script again

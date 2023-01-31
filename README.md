The Manual: https://help.mikrotik.com/docs/display/ROS/

Testing Bandwitch in background
ssh admin@192.168.80.75 '/tool bandwidth-test 192.168.80.75 direction=both password=2n0f3r3! protocol=udp duration=36000 without-paging interval=5' | grep 10-second-average


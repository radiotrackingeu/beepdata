# beepdata
Test data dumped by rtl_sdr used to improve the detection algorithm. 
A tag running at 150036 kHz was recorded and the recording evaluated with the following commands:

* `rtl_sdr -d 3 -f 150050000 -s 250000 -g 50 /tmp/record/rteu.dmp`
* `rtlsdr_signal_detect -i /tmp/record/rteu.dmp -t 14 -r 250000 -b 250 -n 50 --ll 0.01 --lu 0.03 > /tmp/record/rteu.log`

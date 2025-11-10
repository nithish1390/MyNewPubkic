# MyNewPubkic
How to automatically scale ( start / stop ) tibco bw application services based on cpu/load metrics of that PID. Let's say I have deployed two applications App1 and App2 in all 4 machines . Both app1 and App2 have different pid running across all 4 machines. I want to check if average cpu across all 4 instance is less than threshold then stop 1 instance . Keep it idle for 20 mins. Then check again and if average cpu still low stop one more instances. Repeat the process. If the average cpu load increase than threshold start all 4 instances. So always
 minimun running instance: 1
Maximum running instances : 4



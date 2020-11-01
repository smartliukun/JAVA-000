学习笔记


C:\Users\86186>sb -u http://localhost:8801 -n 1000 -c 10
Starting at 2020/11/1 22:25:41
[Press C to stop the test]
1000    (RPS: 49.7)
---------------Finished!----------------
Finished at 2020/11/1 22:26:02 (took 00:00:20.2938824)
Status 200:    1000

RPS: 47.1 (requests/second)
Max: 248ms
Min: 69ms
Avg: 198.4ms

  50%   below 199ms
  60%   below 199ms
  70%   below 199ms
  80%   below 200ms
  90%   below 200ms
  95%   below 200ms
  98%   below 201ms
  99%   below 203ms
99.9%   below 248ms

C:\Users\86186>sb -u http://localhost:8801 -n 1000 -c 100
Starting at 2020/11/1 22:26:12
[Press C to stop the test]
1000    (RPS: 49.9)
---------------Finished!----------------
Finished at 2020/11/1 22:26:32 (took 00:00:20.1544893)
Status 200:    996
Status 303:    4

RPS: 47.5 (requests/second)
Max: 8972ms
Min: 57ms
Avg: 1898.9ms

  50%   below 1422ms
  60%   below 1842ms
  70%   below 2022ms
  80%   below 2506ms
  90%   below 3906ms
  95%   below 5346ms
  98%   below 6914ms
  99%   below 8001ms
99.9%   below 8972ms

C:\Users\86186>
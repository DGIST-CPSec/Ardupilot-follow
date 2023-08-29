# 로그
## 로그파일 정보
### copter 1
- 1 Dijkstra and Follow
- 2-5 QGC, MAVproxy Test & Dijkstra Test
- 6 X
- 7,8 All drone Fence3 Follow
### copter 2 ~ 4
- 1 Dijkstra and Follow
- 2 QGC, MAVproxy Test & Dijkstra Test
- 3 X
- 4,5 All drone Fence3 Follow
---
## 로그파일 사용법

### BIN파일

#### MAVExplorer.py
```
MAVExplorer.py [로그파일 이름]
```


or
#### UAV Log Viewer
<https://plot.ardupilot.org/#/> 에 접속하여 로그파일 업로드
### callgrind파일
```
gprof2dot -n[PERCENTAGE(e.g. 0.5)] -e0[PERCENTAGE] ./callgrind.out.[FILE_NUMBER] -f callgrind > out.dot
dot -Tsvg out.dot -o out.svg
```

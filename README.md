
<img src="https://github.com/corvina1208/Oracle_Admin/assets/157337929/715f35d6-0331-4da1-851a-b91bf6b0508d.png">  
<br/>
<br/>

## Backup&Recovery

### 1. 사용자 관리 Backup
- 1-1. Archive mode로 변경 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-1%20Archive%20mode%EB%A1%9C%20%EB%B3%80%EA%B2%BD.txt)
- 1-2. 사용자 관리 Cold Backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-2%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B4%80%EB%A6%AC%20Cold%20Backup.txt)
- 1-3. 사용자 관리 Hot Backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-3%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B4%80%EB%A6%AC%20Hot%20Backup.txt)
- 1-4. Controlfile Backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-4%20Controlfile%20Backup.txt)

### 2. 사용자 관리 완전 복구
- 2-1. Non system data file 삭제&복구(DB close 상태) : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-1%20Non%20system%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC(DB%20close%20%EC%83%81%ED%83%9C).txt)
- 2-2. Non system data file 삭제&복구(DB open 상태) : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-2%20Non%20system%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC(DB%20open%20%EC%83%81%ED%83%9C).txt)
- 2-3. System data file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-3%20System%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-4. 모든 Data file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-4%20%EB%AA%A8%EB%93%A0%20Data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-5. Control file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-5%20Control%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-6. Control file Multiplexing : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-6%20Control%20file%20Multiplexing.txt)
- 2-7. Multiplexing 된 Control file 중 1개 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-7%20Multiplexing%20%EB%90%9C%20Control%20file%20%EC%A4%91%201%EA%B0%9C%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-8. Inactive 상태의 Redo log file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-8%20Inactive%20%EC%83%81%ED%83%9C%EC%9D%98%20Redo%20log%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-9. Redo log file Multiplexing : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-9%20Redo%20log%20file%20Multiplexing.txt)
- 2-10. Redo log group member 삭제 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-10%20Redo%20log%20group%20member%20%EC%82%AD%EC%A0%9C.txt)
- 2-11. Redo log group 추가 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-11%20Redo%20log%20group%20%EC%B6%94%EA%B0%80.txt)
- 2-12. Redo log group 삭제 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-12%20Redo%20log%20group%20%EC%82%AD%EC%A0%9C.txt)
- 2-13. Multiplexing 된 Inactive 상태의 Redo log member 1개 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-13%20Multiplexing%20%EB%90%9C%20Inactive%20%EC%83%81%ED%83%9C%EC%9D%98%20Redo%20log%20member%201%EA%B0%9C%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-14. Redo log Group 내 모든 member 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-14%20Redo%20log%20Group%20%EB%82%B4%20%EB%AA%A8%EB%93%A0%20member%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)

### 3. 사용자 관리 불완전 복구
- 완전 복구 vs 불완전 복구 : [[설명]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/3.%20%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC%20vs%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 3-1. Time base 불완전 복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/3-1.%20Time%20base%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 3-2. Cancel base 불완전 복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/3-2.%20Cancel%20base%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 3-3. 모든 Redo log file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/3-3.%20%EB%AA%A8%EB%93%A0%20Redo%20log%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 3-4. 모든 Date file, Control file, Redo log file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/3-4.%20%EB%AA%A8%EB%93%A0%20Date%20file%2C%20Control%20file%2C%20Redo%20log%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)

### 4. RMAN backup
- 4-1. RMAN Cold backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/4-1.%20RMAN%20Cold%20backup.txt)
- 4-2. RMAN Hot backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/4-2.%20RMAN%20Hot%20backup.txt)
- 4-3. RMAN Tablespace Backup : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/4-3.%20RMAN%20Tablespace%20Backup.txt)

### 5. RMAN recovery
- 5-1. RMAN Non system data file 삭제&복구(DB open 상태) : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-1.%20RMAN%20Non%20system%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC(DB%20open%20%EC%83%81%ED%83%9C).txt)
- 5-2. RMAN System data file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-2.%20RMAN%20System%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 5-3. RMAN 모든 Data file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-3.%20RMAN%20%EB%AA%A8%EB%93%A0%20Data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 5-4. RMAN 모든 Control file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-4.%20RMAN%20%EB%AA%A8%EB%93%A0%20Control%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 5-5. RMAN 모든 Data file, Control file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-5.%20RMAN%20%EB%AA%A8%EB%93%A0%20Data%20file%2C%20Control%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 5-6. RMAN Parameter file 삭제&복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-6.%20RMAN%20Parameter%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 5-7. RMAN Time base 불완전 복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-7.%20RMAN%20Time%20base%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 5-8. RMAN Cancel base 불완전 복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-8.%20RMAN%20Cancel%20base%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 5-9. RMAN 사용하지 않고 백업본 없을 때 복구 방법 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-9.%20RMAN%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%A7%80%20%EC%95%8A%EA%B3%A0%20%EB%B0%B1%EC%97%85%EB%B3%B8%20%EC%97%86%EC%9D%84%20%EB%95%8C%20%EB%B3%B5%EA%B5%AC%20%EB%B0%A9%EB%B2%95.txt)
- 5-10 RMAN 백업본 없을 때 복구 방법 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/5-10%20RMAN%20%EB%B0%B1%EC%97%85%EB%B3%B8%20%EC%97%86%EC%9D%84%20%EB%95%8C%20%EB%B3%B5%EA%B5%AC%20%EB%B0%A9%EB%B2%95.txt)

### 6. Recovery catalog 를 통한 Backup&Recovery
- 6-1. Recorery catalog 구성하기 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/6-1.%20Recorery%20catalog%20%EA%B5%AC%EC%84%B1%ED%95%98%EA%B8%B0.txt)
- 6-2. Recorery catalog 를 별도의 DB 에 구성하기 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/6-2.%20Recorery%20catalog%20%EB%A5%BC%20%EB%B3%84%EB%8F%84%EC%9D%98%20DB%20%EC%97%90%20%EA%B5%AC%EC%84%B1%ED%95%98%EA%B8%B0.txt)
- 6-3. Recorery catalog 를 통해 사용가능한 RMAN 명령어 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/6-3.%20Recorery%20catalog%20%EB%A5%BC%20%ED%86%B5%ED%95%B4%20%EC%82%AC%EC%9A%A9%EA%B0%80%EB%8A%A5%ED%95%9C%20RMAN%20%EB%AA%85%EB%A0%B9%EC%96%B4.txt)
- 6-4. Recorery catalog 에서 불완전 복구 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/6-4.%20Recorery%20catalog%20%EB%B6%88%EC%99%84%EC%A0%84%20%EB%B3%B5%EA%B5%AC.txt)
- 6-5. 복구 관리자 사용하기 : [[CODE]](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/6-5.%20%EB%B3%B5%EA%B5%AC%20%EA%B4%80%EB%A6%AC%EC%9E%90%20%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0.txt)

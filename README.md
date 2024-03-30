## Backup&Recovery

### 1. 사용자 관리 Backup
- 1-1. Archive mode로 변경 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-1%20Archive%20mode%EB%A1%9C%20%EB%B3%80%EA%B2%BD.txt)
- 1-2. 사용자 관리 Cold Backup : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-2%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B4%80%EB%A6%AC%20Cold%20Backup.txt)
- 1-3. 사용자 관리 Hot Backup : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-3%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B4%80%EB%A6%AC%20Hot%20Backup.txt)
- 1-4. Controlfile Backup : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/1-4%20Controlfile%20Backup.txt)

### 2. 사용자 관리 완전 복구
- 2-1. Non system data file 삭제&복구(DB close 상태) : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-1%20Non%20system%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC(DB%20close%20%EC%83%81%ED%83%9C).txt)
- 2-2. Non system data file 삭제&복구(DB open 상태) : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-2%20Non%20system%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC(DB%20open%20%EC%83%81%ED%83%9C).txt)
- 2-3. System data file 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-3%20System%20data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-4. 모든 Data file 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-4%20%EB%AA%A8%EB%93%A0%20Data%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-5. Control file 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-5%20Control%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-6. Control file Multiplexing : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-6%20Control%20file%20Multiplexing.txt)
- 2-7. Multiplexing 된 Control file 중 1개 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-7%20Multiplexing%20%EB%90%9C%20Control%20file%20%EC%A4%91%201%EA%B0%9C%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-8. Inactive 상태의 Redo log file 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-8%20Inactive%20%EC%83%81%ED%83%9C%EC%9D%98%20Redo%20log%20file%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-9. Redo log file Multiplexing : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-9%20Redo%20log%20file%20Multiplexing.txt)
- 2-10. Redo log group member 삭제 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-10%20Redo%20log%20group%20member%20%EC%82%AD%EC%A0%9C.txt)
- 2-11. Redo log group 추가 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-11%20Redo%20log%20group%20%EC%B6%94%EA%B0%80.txt)
- 2-12. Redo log group 삭제 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-12%20Redo%20log%20group%20%EC%82%AD%EC%A0%9C.txt)
- 2-13. Multiplexing 된 Inactive 상태의 Redo log member 1개 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-13%20Multiplexing%20%EB%90%9C%20Inactive%20%EC%83%81%ED%83%9C%EC%9D%98%20Redo%20log%20member%201%EA%B0%9C%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)
- 2-14. Redo log Group 내 모든 member 삭제&복구 : [CODE](https://github.com/corvina1208/Oracle_Backup-Recovery/blob/main/2-14%20Redo%20log%20Group%20%EB%82%B4%20%EB%AA%A8%EB%93%A0%20member%20%EC%82%AD%EC%A0%9C%26%EB%B3%B5%EA%B5%AC.txt)

### 3. 사용자 관리 불완전 복구
- 3-1. Time base 불완전 복구 : [CODE]
- 3-2. Cancel base 불완전 복구 : [CODE]
- 3-3. 모든 Redo log file 삭제&복구 : [CODE]
- 3-4. 모든 Date file, Control file, Redo log file 삭제&복구 : [CODE]

### 4. RMAN backup
- 4-1. RMAN Cold backup : [CODE]
- 4-2. RMAN Hot backup : [CODE]
- 4-3. RMAN Tablespace Backup : [CODE]

### 5. RMAN recovery
- 5-1. RMAN Non system data file 삭제&복구 : [CODE]
- 5-2. RMAN System data file 삭제&복구 : [CODE]
- 5-3. RMAN 모든 Data file 삭제&복구 : [CODE]
- 5-4. RMAN 모든 Control file 삭제&복구 : [CODE]
- 5-5. RMAN 모든 Data file, Control file 삭제&복구 : [CODE]
- 5-6. RMAN Parameter file 손상 시 복구 : [CODE]
- 5-7. RMAN Time base 불완전 복구 : [CODE]
- 5-8. RMAN Cancel base 불완전 복구 : [CODE]
- 5-9. RMAN 사용하지 않고 백업본 없을 때 복구 방법 : [CODE]
- 5-10 RMAN 백업본 없을 때 복구 방법 : [CODE]

### 6. Recovery catalog 를 통한 Backup&Recovery
- 6-1. Recorery catalog 구성하기 : [CODE]
- 6-2. Recorery catalog 를 별도의 DB 에 구성하기 : [CODE]
- 6-3. Recorery catalog 에서 사용가능한 RMAN 명령어 : [CODE]
- 6-4. Recorery catalog 에서 불완전 복구 : [CODE]
- 6-5. 복구 관리자 사용하기 : [CODE]


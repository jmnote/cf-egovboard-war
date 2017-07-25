# egov-board

eGovFrame 3.1 샘플: 간단한 게시판 어플리케이션
```
* mysql 스크립트 -> 프로젝트에 포함된 ddl, dml에 자동으로 생성된 db 스크립트는 중복이 많음, 
따라서 수정된 create와 insert 스크립트를 사용
 
/sql_scripts/create_mysql.sql  # 필요한 테이블생성하는 스크립트
            /insert_mysql.sql  # 필요한 데이터 insert 하는 스크립트

/src                           # 소스코드(maven 프로젝트-egovframe 3.1.1 이클립스에서 import하여 빌드가능)

/target/egov-board.war         # 프로젝트 빌드된 파일 - 실제 테스트시에는 해당파일만 있으면 됨
/manifest.yml                  # cf push를 위한 매니페스트파일
```

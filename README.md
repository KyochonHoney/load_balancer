# load_balancer

nginx 서버를 띄운 후에 config의 포트별 서버를 server1, server2를 실행시켜 nginx서버에 들어오면 순차적으로 round-robin 알고리즘을 통해 server1, server2로 각각 전송



https://github.com/user-attachments/assets/0f5a7a2c-1403-4068-b97d-1ba1605ca806




실행 방법


1.

>  원하는 로컬디렉토리에 저장

2.

>  docker terminal에서 해당 디렉토리로 들어간 후 ( ex) cd C:\docker-lb-php ), docker compose up -d --명령어 실행

3.

>  크롬에서 localhost 실행

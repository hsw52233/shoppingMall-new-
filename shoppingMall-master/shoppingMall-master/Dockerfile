FROM eclipse-temurin:21.0.6_7-jre

#target 디렉토리에서 모든 jar파일ㅇ르 app.jar로 추가

ADD target/*.war app.war

#컨테이너 내부의 포트 80을 외부에 노출
EXPOSE 80

#애플리케이션 실행할 명령어 설정
ENTRYPOINT ["sh","-c","java -jar /app.war" ]
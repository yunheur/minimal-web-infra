### Outline

웹 애플리케이션 서버 개발에 필요한 최소한의 인프라 환경 구축

### Setup

1. .env.sample 파일을 .env 파일명으로 복사
2. .env 설정
3. docker-compose 시작
   

### Set HTTPS

```bash
# Let's Encrypt 와일드카드 인증서 발급
./certbot.create.sh

# Let's Encrypt 와일드카드 인증서 3개월 주기로 갱신
./certbot.renew.sh
```
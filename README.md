🌱 Daily Commit

하루에 한 번 자동으로 커밋해서 잔디를 심는 레포지토리

🚀 기능

GitHub Actions를 이용해 매일 정해진 시간에 자동 커밋

daily_commit.txt 파일이 업데이트되면서 잔디에 기록

별도의 수동 작업 없이 꾸준히 contribution 유지

⚙️ 동작 방식

.github/workflows/daily-commit.yml 파일에 워크플로우가 설정됨

GitHub Actions가 매일 정해진 시간(UTC 기준)에 실행

daily_commit.txt 파일에 현재 시간이 기록되고 자동으로 커밋/푸시됨

📅 스케줄

매일 09:00 UTC (한국 시간 18:00) 에 자동 실행

💡 참고

원한다면 daily-commit.yml의 cron 값을 수정해서 원하는 시간에 잔디를 심을 수 있음

브랜치 이름이 main이 아니라면 git push origin <브랜치명> 으로 수정 필요

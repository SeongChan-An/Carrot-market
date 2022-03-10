# [PlanetScale](https://planetscale.com/)

> The MySQL-compatible serverless database platform.

\*\* Serverless : 서버를 신경 쓸 필요가 없다 == 서버 관리, 유지 보수가 필요 X

- 장점  
  : CLI 를 통해 간편하게 조작할 수 있다.
  : git 처럼 브랜치를 통해 사용자에게 영향을 주지 않는 상태로 스키마를 업데이트 할 수 있다

## Start

- [CLI](https://docs.planetscale.com/concepts/planetscale-environment-setup)

- Window 기준 powershell

  > : Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')  
  > : scoop bucket add pscale https://github.com/planetscale/scoop-bucket.git
  > : scoop install pscale

- pscale auth login
- pscale region list
- pscale database create project --region "SLUG"
- pscale connect project
  : 보안, 데이터베이스와 연결 시켜줌 (.env에 암호를 저장할 필요 없이 )

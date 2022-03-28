# 설치가이드
## 유의사항
* 크롬 브라우저를 통한 설치 파일 다운로드를 권장합니다.
* Mac 사용자는 사전에 Homebrew 설치가 필요합니다.
* Windows 사용자는 사전에 Chocolatey 설치가 필요합니다.
* MariaDB 경우에는 MySql 가 기존에 설치되어있으면 충돌이 발생하니 설치 진행해주지 않으셔도 됩니다.

## 설치 SW
| SW 명 | 버전 | 설명 | 다운로드 URL |
|---|:---:|:---:|:---:|
|JDK|11|자바 개발 도구 오픈소스|https://adoptopenjdk.net/|
| STS | 4.9.0 | 이클립스 기반 스프링 애플리케이션 개발 도구 | https://spring.io/tools |
| Lombok | 1.18.20 | 자바 코드 경량화 라이브러리 | http://projectlombok.org/download.html |
| Git | 2.31.1 | 소스 형상 관리 도구 | http://git-scm.com/downloads |
| Maven | 3.8.5 | 애플리케이션 빌드 도구 | https://community.chocolatey.org/packages/maven |
| Docker | 20.10.5 | 애플리케이션 컨테이너 관리 도구 | http://docker.com/products/docker-desktop |
| MariaDB | 10.5.8 | 관계형 데이터 베이스 | https://mariadb.com/downloads |

## Homebrew 설치 (Mac 사용자)
- 설치 명령어 (터미널에서 아래 명령어 수행)
  - ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
- 설치 확인 : brew --version

## Chocolatey 설치 (Windows 사용자)
- 설치 명령어 (Windows PowerShell 에서 아래 명령어 수행)
  - Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
- 설치 확인 : choco

## JDK
- 다운로드 사이트 : https://adoptopenjdk.net/
![Slide5](https://user-images.githubusercontent.com/62231786/123755254-ad8a2b80-d8f6-11eb-8e4e-5f6317bf9cb3.png)

## STS
- 다운로드 사이트 : https://spring.io/tools
![Slide6](https://user-images.githubusercontent.com/62231786/123755247-ac58fe80-d8f6-11eb-98ed-ccf4c564293e.png)

## Lombok
- 다운로드 사이트 : http://projectlombok.org/download.html
![Slide8](https://user-images.githubusercontent.com/62231786/123755234-a9f6a480-d8f6-11eb-8610-f9fa575b1726.png)

## Git
- 다운로드 사이트 : http://git-scm.com/downloads
![Slide10](https://user-images.githubusercontent.com/62231786/123755229-a8c57780-d8f6-11eb-9b27-6712ac8794ea.png)

## Maven
- 설치 명령어 (Windows PowerShell 에서 아래 명령어 수행)
  - choco install maven
- 설치 확인 : mvn --version
![Maven버전 확인](https://user-images.githubusercontent.com/88864523/160330826-6e0c4dfe-6f16-4387-883b-b747ab1e6851.png)
- 참고 : 삭제 명령어는 choco uninstall maven

## Docker
- 다운로드 사이트 : http://docker.com/products/docker-desktop
![Slide11](https://user-images.githubusercontent.com/62231786/123755221-a7944a80-d8f6-11eb-93ef-2c61a124768e.png)

## MariaDB
- 다운로드 사이트 : https://mariadb.com/downloads
![Slide51](https://user-images.githubusercontent.com/62231786/123883833-c04b4180-d984-11eb-9517-406de2971d81.png)
![Slide52](https://user-images.githubusercontent.com/62231786/123883831-bfb2ab00-d984-11eb-9349-3765e0768afd.png)

## MariaDB Client (Mac 사용자)
- 다운로드 사이트 : https://www.sequelpro.com/
- Windows 사용자는 MariaDB설치 시, 별도의 SW (HeidiSQL) 이 자동 설치됨
![Slide53](https://user-images.githubusercontent.com/62231786/123883827-be817e00-d984-11eb-8f1e-ec8315ac2694.png)

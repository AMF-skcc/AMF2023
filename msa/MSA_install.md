# 설치가이드
## 유의사항
* 크롬 브라우저를 통한 설치 파일 다운로드를 권장합니다.
* Mac 사용자는 사전에 Homebrew 설치가 필요합니다.
* Windows 사용자는 사전에 Chocolatey 설치가 필요합니다.

<br>

## 설치 SW
| SW 명 | 버전 | 설명 | 다운로드 URL |
|---|:---:|:---:|:---:|
| Maven | 3.8.x 이상 | 애플리케이션 빌드 도구 | https://community.chocolatey.org/packages/maven |
| Git | 2.2.x 이상 | 소스 형상 관리 도구 | http://git-scm.com/downloads |
| Docker | 20.10.5 | 애플리케이션 컨테이너 관리 도구 | http://docker.com/products/docker-desktop |

<br>

## Homebrew 설치 (Mac 사용자)
- 설치 명령어 (터미널에서 아래 명령어 수행)
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- 설치 확인 : `brew --version`

<br>

## Chocolatey 설치 (Windows 사용자)
- 설치 명령어 (Windows PowerShell 에서 아래 명령어 수행)
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
- 설치 확인 : `choco`

<br>

## Maven 설치
- **Windows 사용자**
  - 설치 명령어 (Windows PowerShell 에서 아래 명령어 수행)
    ```
    choco install maven
    ```
  - 설치 확인 : `mvn --version`
  - [참고] 삭제 명령어는 `choco uninstall maven

<br>

- **Mac 사용자**
  - 설치 명령어 (터미널에서 아래 명령어 수행)
    ```
    brew install maven
    ```
  - 설치 확인 : `mvn -version`
  - [참고] 삭제 명령어는 `brew uninstall maven`

<br>

## Git 설치
- 다운로드 사이트 : http://git-scm.com/downloads
![Slide10](https://user-images.githubusercontent.com/62231786/123755229-a8c57780-d8f6-11eb-9b27-6712ac8794ea.png)

<br>

## Docker 설치
- 다운로드 사이트 : http://docker.com/products/docker-desktop
![Slide11](https://user-images.githubusercontent.com/62231786/123755221-a7944a80-d8f6-11eb-93ef-2c61a124768e.png)

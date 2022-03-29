
## ZCP 과정 학습 목표 및 자료 
### 6일차 
#### PaaS 소개
- 학습목표 : 컨테이너/쿠버네티스에 대한 기본 이해 및 실습을 수행한다. Kubernetes가 개발/운영플랫폼으로 사용되기 위한 조건을 이해할 수 있다.
- 학습자료 : [[AMF_Cloud]ZCP_Introduction_v2.0.pdf](...)

#### 컨테이너 빌드/배포
- 학습목표 : 튜토리얼 애플리케이션을 활용하여 컨테이너를 빌드하고 쿠버네티스에 배포하는 애플리케이션 빌드배포 한 사이클을 체험한다. 마이크로서비스 아키텍처 패턴을 적용하여 애플리케이션을 재배포 할 수 있다.
- 학습자료 : [Pattern Based MicroService Hands-On-v1.3.pdf](...)
#### 컨테이너 빌드/배포 자동화 
- 학습목표 : Jenkins 또는 Tekton을 활용하여 컨테이너 빌드/배포를 자동화하는 방법을 알 수 있다.
- 학습자료 : [[AMF_Cloud] ZCP CICD가이드_AMF버젼_v1.3.pdf](...)
<br><br>

### 7일차 
#### AMF 애플리케이션 빌드/배포하기
- 학습목표 : AMF 과정에서 개발중인 애플리케이션을 쿠버네티스에 배포해서 로컬을 넘어 실제 클라우드 환경에서의 개발을 준비한다. 애플리케이션의 아우터아키텍처 구성을 위해 AMDP(App Modernization Dev Platform)을 활용하여 형상을 구성하고 빌드배포를 수행할 수 있다.
- 학습자료 : [[AMF_Cloud]AMDP_사용실습_v0.3.pdf](...)

<br><br>

### ZCP 실습용 도구 ###
| SW 명 | 버전 | 다운로드 URL |  비고  |
|---|:---:|:---|:---|
| Choco	| | https://chocolatey.org/install	| kustomize 등을 설치하기 위한 목적으로 윈도우 패키지 관리 매니져를 선행 설치 |
| kustomize	| 3.9.1	 | https://kubectl.docs.kubernetes.io/installation/kustomize/ https://community.chocolatey.org/packages/kustomize | 설치 - choco install kustomize <br> 삭제 - choco uninstall kustomize |
| kubectl	| | https://kubernetes.io/ko/docs/tasks/tools/install-kubectl-windows/ | 설치 - choco install kubernetes-cli	<br>< 삭제 - choco uninstall kubernetes-cli |
| maven	| 3.8.1	| https://community.chocolatey.org/packages/maven | * 로컬 환경에서 애플리케이션  빌드 목적으로 설치<br> 설치 - choco install maven	 <br> 삭제 - choco uninstall maven | 
| podman | | https://podman.io/getting-started/installation | docker 라이선스 이슈 회피 위한 OSS 도구 |


### Cloud 실습용 app download

  - https://factory-git.cloudzcp.io/amf-team/awesome-shopping   (로그인 필요)



### ZCP paas 실습
  - https://github.com/AMF-skcc/amf-edu-cloud/tree/main/01-paas
  



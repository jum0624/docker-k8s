# docker & k8s

도커와 쿠버네티스에 관련된 공부기록장입니다!

블로그나 깃허브를 통해 꾸준히 기록해 나갈 예정입니다 :)

# docker


### 목차

- docker basic
    - 이미지 관리
    - 컨테이너 관리
    - 이미지 생성하기
    - 이미지 업로드하기
    - 볼륨
    - 네트워크
        - docker Advance
- docker compose
    - docker compose 란?
    - compose CLI
    - compose file - basic
        - version
        - name
        - service
        - volume
        - network
        - config & secret
    - compose file - Advance
        - anchor & alias
        - profile
        - deploy
        - depend_on
        - health check
- 종합 실습

# k8s


### 목차

- 쿠버네티스란?
    - 컨테이너란 무엇인가?
    - 마이크로소프트아키텍쳐 - MSA란?
- 쿠버네티스 설치
    - kubectl
        - kubens & kubectx
    - OpenLens
- CLI
    - kubectl
    - kubens
    - kubectx
- YAML
    - Metadata
- POD
    - YAML
    - Container
    - Probe
- Workload Resource
    - Replicaset
    - Deployment
    - Statefulsets
    - DaemonSet
    - Jobs
    - Cronjob
- Service
    - 서비스란?
    - ClusterIP
    - NodePort
    - LoadBalancer
    - Ingress
    - HeadlessService
- Volume
    - EmptyDir
    - HostPath
    - PV
    - PVC
- Configmap
- StatefulSet
- Resource Control & HPA
- CICD 실습

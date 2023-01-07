# Kubeflow Tutorial
Kubeflow를 공부하며 자료를 남기기 위해 생성한 저장소입니다.  
Kubeflow는 참고할 만한 자료가 상대적으로 적어 공부하기가 어렵다고 생각합니다.  
누군가 이 저장소를 보고 MLOps에 대한 전반적인 과정을 Kubeflow로 쉽게 접근할 수 있으면 하는 바람으로 작성하고 있습니다.  
Kubeflow에 대한 내용을 블로그에서 글을 작성해 다루고 있습니다.  
[https://seokii.tistory.com/category/MLOps](https://seokii.tistory.com/category/MLOps)
<br><br>

## 1. What's Kubernetes & Kubeflow?
**도커(Docker)** 라는 컨테이너 오픈소스가 등장하고 기존의 단점을 극복한 컨테이너 개발 시대가 급격하게 발전해왔습니다.  
이에 따라, 컨테이너를 효율적으로 관리할 수 있는 컨테이너 오케스트레이션 시스템의 발전이 이루어져 왔습니다.  
**쿠버네티스**는 구글의 '보그'라는 시스템에 영향을 받은 **컨테이너 오케스트레이션 시스템**입니다.  
쿠버네티스를 통해 다수의 컨테이너를 배포 및 운영할 수 있게 되었습니다.  
또한, 쿠버네티스의 다양한 기능들을 활용해 더 좋은 운영 환경을 다룰 수 있게 되었습니다.  

그렇다면, **쿠브플로우**는 무엇일까요?  
쿠브플로우 공식 사이트에서는 위와 같이 쿠브플로우에 대해 설명합니다.  

    "쿠브플로우의 목표는 다른 서비스를 다시 만드는 것이 아니라  
    ML을 위한 최고의 오픈 소스 시스템을 다양한 인프라에 배포하는 간단한 방법을 제공하는 것"  

쿠브플로우를 사용하면 쿠버네티스의 API의 사용을 익히는 것보다 모델 학습과 개발, 테스트, 배포 등에 집중할 수 있습니다.  
쿠브플로우를 사용한다면 다음과 같은 여러 장점이 있습니다.
- 더 빠르고 일관적인 배포
- 안전한 보안을 위해 포트나 컴포넌트 접근에 대한 더 나은 통제
- 리소스 공급과잉에 대한 보호로 비용 절감
- 완성된 일이 할당 해지되는 것을 보호하여 비용 절감
- 워크플로 오케스트레이션 메타데이터 수집
- 중앙화된 모니터링과 로깅
- 모델을 안전하고 확장이 가능하도록 프로덕션으로 옮기는 인프라스트럭쳐

참고 사이트
- [쿠버네티스란 무엇인가?](https://kubernetes.io/ko/docs/concepts/overview/)
- [쿠브플로우 공식사이트](https://www.kubeflow.org/)
<br><br>

## 2. How to Install Kubeflow
다음은 제 PC 사양 및 구성입니다.
- OS: Ubuntu 20.04 LTS
- CPU: AMD Ryzen 5 5600X 6-Core Processor
- GPU: GeForce RTX 3070

설치 방법은 블로그에 자세히 기록했습니다.  
링크: [Ubuntu 20.04에서 docker 및 쿠버네티스와 쿠브플로우 설치하기](https://seokii.tistory.com/203)


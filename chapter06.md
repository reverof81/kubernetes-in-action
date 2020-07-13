# 6 볼륨: 컨테이너에 디스크 스토리지 연결

- 파드는 내부에 CPU, RAM, 네트워크 인터페이스 등의 리소스를 공유하는 논리적 호스트와 유사
- 파드 내부의 각 컨테이너는 각자의 파일 시스템을 가진다.
- 각 컨테이너간 데이터 공유를 위해 쿠버네티스는 스토리지 볼륨을 정의하는 방법으로 이 기능을 제공한다.
- 스토리지 볼륨은 파드와 같은 최상위 리소스는 아니지만 파드의 일부분으로 정의되며 파드와 동일한 라이프사이클을 가진다.
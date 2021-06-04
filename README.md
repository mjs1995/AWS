# AWS
- AWS 정리 및 오답

## 모듈 1: AMAZON WEB SERVICES 소개
- 클라이언트-서버 모델 -> 커피숍 생각 -> 일할때만 돈받아 -> 필요하면 추가시켜 키값 필요한만큼 지불 
  * 클라이언트 - 사람이 컴퓨터 서버에 요청을 보내기 위해 상호 작용하는 웹 브라우저 또는 데스크톱 애플리케이션
  * 서버 - Amazon Elastic Cloud Compute(Amazon EC2)
    * 고객사가 요청(뉴스기사 요청) -> 서버는 이 요청의 세부 정보 평가 및 클라이언트에 정보를 반환
   
- 클라우드 컴퓨팅 배포 - 클라우드 컴퓨팅 : 인터넷을 통해 IT 리소스와 애플리케이션을 온디맨드로 제공하는 것(종량 과금제)
  * 1) 클라우드 기반 배포
    * 애플리케이션의 모든 부분을 클라우드에서 실행
    * 기존 애플리케이션을 클라우드로 마이그레이션
    * 클라우드에서 새 애플리케이션을 설계 및 빌드
  * 2) 온프레미스 배포 (프라이빗 클라우드 배포)
    * 가상화 및 리소스 관리 도구를 사용하여 리소스를 배포
    * 애플리케이션 관리 및 가상화 기술을 사용하여 리소스 활용 높임
  * 3) 하이브리드 배포
    * 클라우드 기반 리소스를 온프레미스 인프라에 연결
    * 클라우드 기반 리소스를 레거시 IT 어플리케이션과 통합
  * 장점
    * 선행 비용을 가변 비용으로 대체 -> 비용 절감
    * 데이터 센터 운영 및 유지 관리에 비용 투자 불필요 -> 인프라 및 서버관리 신경 덜쓰고 고객사에 집중
    * 용량 추정 불필요 -> 인프라 용량 예측 필요x
    * 규모의 경제로 얻게 되는 이점 -> 인프라보다 가변 비용 낮아져
    * 속도 및 민첩성 향상 -> 몇 분 만에 새로운 리소스에 액세스 가능
    * 몇 분 만에 전 세계로 배포 -> 다른 지역에 위치한 고객도 지연 시간을 최소화하여 애플리케이션을 액세스
  * Quiz
    *  클라우드 컴퓨팅의 규모는 어떻게 비용 절감에 도움이 됩니까?
      * 많은 고객의 클라우드 사용량을 집계하므로 종량 과금제 요금이 낮아집니다.

## 모듈 2: 클라우드 컴퓨팅
- Amazon Elastic Compute Cloud(Amazon EC2)
 * 온프레미스 리소스를 사용할 경우
  * 미리 하드웨어를 구매
  * 서버가 배달될 때까지 기다림
  * 물리적 데이터 센터에 서버를 설치
  * 필요한 무든 구성을 수행 
 * EC2 사용(인스턴스 시작 -> 인스턴스 연결 -> 인스턴스 사용)
  * 몇 분이면 EC2 인스턴스를 프로비저닝하고 시작 가능
  * 워크로드 실행 완료시 인스턴스 사용 중지 가능
  * 인스턴스 실행 시에만 커퓨팅 시간에 대해서만 비용 지불
  * 필요한 서버 용량에만 비용을 지불하므로 비용 절감

- EC2 인스턴스 유형
 * 범용 인스턴스
  * 컴퓨팅,메모리,네트워킹 리소스를 균형 있게 제공
 * 컴퓨팅 최적화 인스턴스
  * 고성능 프로세서 제공
  * 고성능 프로세서를 활용하는 컴퓨팅 집약적인 애플리케이션에 적합
 * 메모리 최적화 인스턴스
  * 고성능 데이터베이스에 적합
  * 메모리에서 대규모 데이터 세트를 처리하는 워크로드를 위한 빠른 성능을 제공하기 위해 설계
 * 액셀러레이티드 컴퓨팅 인스턴스
  * 부동 소수점 수 계산, 그래픽 처리, 데이터 패턴 일치 등 
 * 스토리지 최적화 인스턴스  
  * 데이터 웨어하우징 애플리케이션에 적합
  * 로컬 스토리지의 대규모 데이터 세트에 대한 순차적 읽기 및 쓰기 액세스가 많이 필요한 워크로드를 위해 설계

- 

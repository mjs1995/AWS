# AWS 클라우드
- 클라우드 컴퓨팅을 사용하면 인프라를 하드웨어가 아닌 소프트웨어로 간주하고 사용 
- 프로그래밍 가능한 리소스 , 동적 기능, 종량 과금제 
  * 온프레미스 - 서버,스토리지,데이터베이스,애플리케이션 -> 기업 네트워크
  * 클라우드 서비스 공급자 : 서버,스토리지,데이터베이스,애플리케이션 등을 인터넷을 통해서 임대해서 이용하는 서비스 
- aws 클라우드 이점
  * 자본 비용을 가변 비용으로 대체
  * 속도 및 대응력 향상
  * 규모의 경제로 얻게 되는 이점
  * 데이터 센터 운영 및 유지 관리에 비용 투자 불필요
  * 용량 추정 불필요
  * 몇 분 만에 전 세계에 배포   
- AWS는 네트워크로 연결된 하드웨어를 소유하고 유지 관리 , 고객은 필요한 항목을 프로비저닝하고 사용 
- 클라우드 배포 모델
  * 온프레미스
  * 하이브리드
  * 클라우드 
- AWS 글로벌 인프라
  * 데이터 센터(일반적으로 수천 대의 서버 수용) -> 가용영역(AZ, 하나 이상의 데이터 센터, 내결합성을 갖도록 설계) ->리전(각 AWS 리전은 두 개 이상의 AZ로 구성, AWS는 전 세계에 25개 리전 보유, 위치라 생각) 
  * 엣지 로케이션 : 최종 사용자에게 더 짧은 지연시간을오 서비스를 제공하는 AWS의 추가적인 시설물(전 세계 200여개 넘는곳에 엣지 로케이션 POP제공)

  ![image](https://user-images.githubusercontent.com/47103479/135950427-d28063d4-f83e-4958-b18a-d8a8eb907b89.png)

- AWS 엣지 인프라

  ![image](https://user-images.githubusercontent.com/47103479/135950718-b65cb38d-6818-41cb-ac16-9473351eccc3.png)
  ![image](https://user-images.githubusercontent.com/47103479/135950996-4e3a3983-69a3-4191-b295-6cdea9fb2f5b.png)


## Amazon Elastic Compute Cloud(Amazone EC2)
- 크기 조정 가능한 컴퓨팅 용량
- 컴퓨팅 리소스 완전 제어
- 새로운 서버 인스턴스 확보 및 부팅 시간 단축 
  * 일회용 리소스를 사용하는 경우 - 데이터 기반 의사 결정, 빠른 반복, 자유로운 실수 
  ![image](https://user-images.githubusercontent.com/47103479/135951737-83a98e07-c42b-4dc9-8ec7-a762eb52eff1.png)

 - 장점
  * 탄력성, 제어, 유연성, 통합, 안정성, 보안, 저렴한 비용, 용이성 
- 인스턴스 패밀리 및 이름 

  ![image](https://user-images.githubusercontent.com/47103479/135952081-ae7641e1-338c-4a97-a64d-81581130eb7b.png)
  ![image](https://user-images.githubusercontent.com/47103479/135952199-e2f28fc1-7a79-4662-9f29-b8259bbc3b97.png)

- EC2 인스턴스 기동 확인 

  ![image](https://user-images.githubusercontent.com/47103479/135952528-f0134a39-d54e-47e7-aec4-1c56410bd507.png)
  ![image](https://user-images.githubusercontent.com/47103479/135952600-cd23c126-d85c-4f9f-9036-e3abb8491922.png)
  ![image](https://user-images.githubusercontent.com/47103479/135952673-e37438ef-3041-4145-a44b-38bc92e84f09.png)

  * 보안 그룹 설정 
  ![image](https://user-images.githubusercontent.com/47103479/135952885-35e270ec-491b-4be1-89cc-4b0cf10ef39c.png)
  ![image](https://user-images.githubusercontent.com/47103479/135952970-50c7e379-7b46-4f8e-9cb7-44d4efcb342f.png)
  ![image](https://user-images.githubusercontent.com/47103479/135953015-d1a57c13-1472-433b-ba56-790597a730e8.png)

- 서비스 사용

  ![image](https://user-images.githubusercontent.com/47103479/135953054-326b4a07-7735-4229-8dad-73b92e1e8cfb.png)
  ![image](https://user-images.githubusercontent.com/47103479/135953163-b5130f27-0c34-48f0-a97e-dbd01fffae7e.png)

- ECS 구조

  ![image](https://user-images.githubusercontent.com/47103479/135958204-aa4e926b-0718-4a5b-8323-c83c212d62da.png)
  ![image](https://user-images.githubusercontent.com/47103479/135959344-88628043-8850-42bd-9f24-1e3b7f4eb2c2.png)

  * 서버리스 컴퓨팅 : 서버를 생각하지 않고 애플리케이션과 서버를 구축할 수 있음 , 확장 관리할 필요가 없어
  * AWS Lambda

  ![image](https://user-images.githubusercontent.com/47103479/135959547-bf66b6e9-afe3-4974-a255-2397a4ae1b37.png)
  ![image](https://user-images.githubusercontent.com/47103479/135959686-828bf739-f5f1-473a-9887-fc4c39bfe3dd.png)
  ![image](https://user-images.githubusercontent.com/47103479/135959769-d68a10e1-e40f-4e9f-8384-4690d5145ce6.png)

## 스토리지 및 데이터베이스
  ![image](https://user-images.githubusercontent.com/47103479/135980451-05edfed9-d5ab-42da-8a2a-f3c1c415d839.png)
  ![image](https://user-images.githubusercontent.com/47103479/135980748-a5851997-a419-4d8b-966e-78ae6870ec8d.png)
- Amazon S3
  * 객체 수준의 스토리지 : 고도로 확장 가능하고 비용 효율적인 스토리지 제공 
  * 원하는 형식의 데이터를 원하는 만큼 저장가능
  * 데이터 레이크 규모 확장에 따라서 데이터에 대한 액세스를 쉽게 구성 가능 / AWS Lake Formation을 통해서 데이터를 손쉽게 생성 가능 
  * 기계학습 알고리즘 사용하여 데이터를 정리 및 분류 가능 , 클라우드 네이티브 애플리케이션을 구성 -> 빠르고 비용 효율적인 모바일 및 인터넷 기반 애플리케이션을 구축 가능 
  * 용량에 상관없이 데이터를 업로드하여 액세스 가능 
  * 객체 저장 방식
    * Amazon S3버킷 : 파일 저장과 함께 사용하는 다른 접근 방식으로 폴더 대신 여러개의 객체를 저장할 수 있는 큰 공간으로 버킷을 생성   

  ![image](https://user-images.githubusercontent.com/47103479/135981436-d9af7e94-71ea-47e2-aa2e-8ab3f387ed25.png)

- Amazon S3 Glacier

  ![image](https://user-images.githubusercontent.com/47103479/135982033-057cf0d2-8138-4017-be42-0e74904d2d90.png)
  - 키워드 : 아카이브(CCTV 데이터 몇년간 보관, 탈퇴한 고객의 개인정보 5년간 보관-> 1기가바이트 당 5원 저렴)
  - 현재 위치에서 쿼리하는 기능을 제공 -> 저장된 아카이브 데이터에 직접 강력한 분석 실행 가능 

- Amazon EBS
  * 사용하기 쉬운 고성능 블록 스토리지 서비스, 다양한 워크로드가 배포되어있음
  * EBS 2가지 유형 : 트랙잭션 워크로드를 위한  SSD 지원 스토리지, 처리량 워크로드를 위한 HDD 지원 스토리지 

  ![image](https://user-images.githubusercontent.com/47103479/135982242-478c01a4-4b91-4ee8-b2be-b4622651ac24.png)

- 데이터 베이스 : 다양한 데이터 베이스 지원
  * Amazon RDS : AWS에서 제공하는 대표적인 관리형 SQL DB
  * Amazon Aurora : MySQL 및 PostgreSQL과 호환되는 완전 관리형 관계형 DB 엔진
  * Amazon Redshift : 데이터 웨어하우스 서비스
  * Amazon DynamoDB : 대표적인 관리형 noSQL
  * Amazon DocumentDB : MongoDB와 같이 문서형 데이터를 처리
  * Amazon ElasticCache : 인메모리 캐시 서비스로 REDIS와 Memcache를 사용할 수 있음 
  * Amazon Neptune : 그래프 DB
  * Amazon QLDB : 원장 DB로 애플리케이션 데이터에 적용된 모든 변경 사항에 대한 완전하고 암호로 확인 할 수 있음 

  ![image](https://user-images.githubusercontent.com/47103479/135982755-264d271d-34df-4d58-8a95-5b72a973fe98.png)
  ![image](https://user-images.githubusercontent.com/47103479/135983608-3b9ef49b-a847-4583-9e18-3f22027cae4b.png)

  * 직접 DB올려서 사용 / 관리형 옵션의 장점들 (원클릭으로 다중 AZ배포 : DB이중화를 빠르고 손쉽게 가능)

  ![image](https://user-images.githubusercontent.com/47103479/135984174-06dbb7b5-5b0e-420f-bd97-b71958dedcda.png)
  ![image](https://user-images.githubusercontent.com/47103479/135984539-fbb18576-5a94-4ca2-b0b5-c3acde635a33.png)
  ![image](https://user-images.githubusercontent.com/47103479/135984765-d506ff3d-2ba5-42a3-944b-4f24f011890d.png)
  ![image](https://user-images.githubusercontent.com/47103479/135985197-2f3afd86-c875-493b-838e-420b683143b1.png)

## 네트워킹
- Amazon VPC : 리전 범위의 서비스 
 
![image](https://user-images.githubusercontent.com/47103479/136120647-67457705-e0e3-4789-a802-2cef785f9bf8.png)
![image](https://user-images.githubusercontent.com/47103479/136120829-6faa8aa7-bb39-43d3-8183-dae93f2bfed3.png)
![image](https://user-images.githubusercontent.com/47103479/136120930-0c1fbd00-2342-4963-b13a-08cbf6917eb8.png)
![image](https://user-images.githubusercontent.com/47103479/136121083-1b1d6298-d1eb-4552-a90f-3e19ae8e6f8c.png)
![image](https://user-images.githubusercontent.com/47103479/136121190-4fcfb2b4-59ff-4f46-97bf-511d6dad1650.png)
![image](https://user-images.githubusercontent.com/47103479/136121422-560f42c0-0339-48b1-8b88-96750ced2b26.png)
![image](https://user-images.githubusercontent.com/47103479/136121824-cf951de5-a0a5-4e56-b890-b091d1f94a9e.png)
![image](https://user-images.githubusercontent.com/47103479/136132535-92251633-fd13-4843-8d3b-90ad23a51b9b.png)
![image](https://user-images.githubusercontent.com/47103479/136132863-ad4cb2be-bf52-44b1-879d-deb75f9b9dc6.png)
![image](https://user-images.githubusercontent.com/47103479/136133126-e8b3059e-7851-472f-bfa8-9ea06ad02a2f.png)
![image](https://user-images.githubusercontent.com/47103479/136133792-e54abda7-dc95-4a2f-9b1b-3804a03cbbda.png)
- AWS Trusted Advisor : 비용 절감, 성능, 개선, 보안 강화에 도움이 되는 지침을 제공하는 서비스 

## IoT
![image](https://user-images.githubusercontent.com/47103479/136139745-ba021383-28a8-4e51-9f89-4ee95cbed1a3.png)
![image](https://user-images.githubusercontent.com/47103479/136139922-df6173cc-29fa-4b9f-9a2f-c35bae4e4780.png)
![image](https://user-images.githubusercontent.com/47103479/136139975-003a44ec-3237-4ee7-97c8-9acc5f28ce0f.png)
![image](https://user-images.githubusercontent.com/47103479/136140490-57edcf39-9e7d-408b-896b-9462e8a72abb.png)
![image](https://user-images.githubusercontent.com/47103479/136140551-6e35b5ce-4056-430d-b2a9-652c5876ea2e.png)
![image](https://user-images.githubusercontent.com/47103479/136141515-c0b1b64f-915c-4ed5-8861-2fa002853468.png)

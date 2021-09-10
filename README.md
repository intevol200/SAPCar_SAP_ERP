# SAP Car SAP ERP 구축 프로젝트
#### 프로젝트 목표
차량 구매에서부터 차량 등록 및 거래처 관리, 예약 현황을 하나의 통합 시스템으로 개발하여  
효율적인 업무처리가 가능한 클라우드 기반 카 쉐어링 SAP 시스템 구축
#### 개발 기간
2021.07.20 ~ 2021.08.28 (설계 10일, 개발 20일)
#### 개발 환경
- __Framework / Library__ : SAPUI5, Open API
- __Infra / Middleware__ : S/4 HANA, SAP Cloud Platform(SCP), AWS(Amazon Web Services)
- __Module__ : MM(Material Management), WM(Warehouse Management), SD(Sales Distribution)

---

### 프로그램 소개
_개발에 관여한 프로그램 및 기능은 ◉ 문자로 표시_
#### 1. BDC
| 프로그램명 | 개요 |
|---|---|
| ZBDC34_CUST | 고객 데이터 BDC |
| ZBDC34_EMP | 사원 데이터 BDC |
| ZBDC_CARMODEL◉ | 자동차모델 데이터 BDC 프로그램 |
###### 주요 기능
- 엑셀 업로드◉
- BDC◉

#### 2. Report Program
| 프로그램명 | 개요 |
|---|---|
| ZR34_CPOI03 | 고객 포인트 조회 |
| ZR34_CUST03 | 고객 정보 조회 |
| ZR34_EMP03◉ | 사원 정보 조회 |
| ZR34_SREP03 | SAP Car 수리요청 조회 |
| ZR34_VENDOR03 | 거래처 조회 |
###### 주요 기능
- 데이터 조회 (Report Program)◉
- SELECTION-SCREEN AS SUBSCREEN◉
- ALV◉
- Layout & Field-Catalog◉

#### 3. Module-Pool Program
| 프로그램명 | 개요 |
|---|---|
| ZM34_TORD03 | SAP Car 이동 조회 |
| ZM34_SZONE03_V3| SAP Car Zone 현황 조회 |
| ZM34_SREQ03◉ | 구매 통합 |
| ZM34_SRENT03 | 예약 내역 조회 |
| ZM34_CAR03◉ | 자동차모델 조회 |
###### 주요 기능
- 데이터 조회 (Module-Pool)◉
- ALV◉
- ALV Tree
- Tab-Strip◉
- Table Control◉
- ALV Event(Click, Button)◉
- Popup Screen◉
- ALV Cell Color & Light◉
- Layout & Field-Catalog◉
- CDS View◉
- CRUD(Create, Read, Update, Delete)◉

#### 4. CRUD
| 프로그램명 | 개요 |
|---|---|
| ZM34_VENDOR01 | 거래처 정보 CRUD |
| ZM34_TORD01 | SAP Car 이동 CRUD |
| ZM34_SREQ01◉ | 구매 요청 생성 |
| ZM34_SREPAIR | 수리 요청 생성 |
| ZM34_SPRICE01 | SAP Car 요금 CRUD |
| ZM34_SORD01 | 구매 주문 생성 |
| ZM34_SCAR01 | SAP Car 관리 |
| ZM34_INVENT | 재고 확인 |
| ZM34_GR01 | 차량 입고 |
| ZM34_EMP01◉ | 사원 CRUD |
| ZM34_DEP01 | 부서 CRUD |
| ZM34_CUST01 | 고객 CRUD |
###### 주요 기능
- 데이터 조회 (Module-Pool)◉
- CRUD(Create, Read, Update, Delete)◉
- Custom ALV Toolbar◉
- ALV◉
- ALV Splitter
- Popup Screen
- ALV Cell Color & Light
- Search Help◉
- Number Range◉
- ALV Event(Click, Button)

안 읽고 물어보면 물어버림
# AVL 101

## 1. To Write Paper
### ACKNOWLEDGEMENT


### 글로벌 인재양성
```
국문) "본 연구는 과학기술정보통신부 및 정보통신기획평가원의 디지털분야글로벌연구지원 연구결과로 수행되었음"(RS-2024-00425661)
```
```
영문) This research was supported by the MSIT(Ministry of Science, ICT), Korea, under the Global Research Support Program in the Digital Field program(RS-2024-00425661) supervised by the IITP(Institute for Information & Communications Technology Planning & Evaluation)
```
### 개방형 자율주행 SW 하드웨어 플랫폼 기술개발 (OSH)

국문)
```
"이 논문은 2024년도 정부(산업통상자원부)의 재원으로 한국산업기술기획평가원의 지원을 받아 수행된 연구임 (RS-2024-00408818)"
```

영문)
```
"This work was supported by the Korea Planning & Evaluation Institute of Industrial Technology(KEIT) grant funded by the Korea government, Ministry of Trade, Industry and Energy(MOTIE) (RS-2024-00408818)"
```

### 산업부 미래형자동차 핵심기술 전문인력양성 사업

국문) 
```
이 [논문/연구/성과/…]은 2023년도 정부(산업통상자원부)의 재원으로 한국산업기술진흥원의 지원을 받아 수행된 연구임 (P0020536, 2023년 산업혁신인재성장지원사업)
```
영문)
```
This [paper/research/work/…] was supported by Korea Institute for Advancement of Technology(KIAT) grant funded by the Korea Government(MOTIE) (P0020536, HRD Program for Industrial Innovation)
```

### 과기부 지능화혁신인재양성(Grand ICT)

국문) 
```
이 논문은 정부(과학기술정보통신부)의 재원으로 정보통신기획평가원의 지원을 받아 수행된 지역지능화혁신인재양성사업임(IITP-2024-2020-0-01462)
```

영문)
```
This work was supported by Innovative Human Resource Development for Local Intellectualization program through the Institute of Information & Communications Technology Planning & Evaluation(IITP) grant funded by the Korea government(MSIT)(IITP-2024-2020-0-01462)
```

### 혼합현실

국문)
```
본 연구는 산업통상자원부의 '자율주행기술개발혁신사업' 으로 지원을 받아 수행된 연구 결과입니다. (20014476, 혼합현실기반자율주행부품및시스템평가기술개발)
```

영문)
```
This research was supported by the Ministry of Trade, Industry and Energy(MOTIE), KOREA, through the Autonomous driving Development Innovation Program.
(20014476, Development of Mixed Reality-based Autonomous Driving Parts and System Evaluation Technology)
```

### RLRC

국문)
```
이 성과는 정부(과학기술정보통신부)의 재원으로 한국연구재단의 지원을 받아 수행된 연구임(No. 2022R1A5A8026986). 
```

영문)
```
This work was supported by the National Research Foundation of Korea(NRF) grant funded by the Korea government(MSIT) (No. 2022R1A5A8026986). 
 ※ MSIT: Ministry of Science and ICT ※ 성과는 논문, 특허 등 실제 성과 명칭으로 대체 사용 가능
```

---
## 2. Equipments


### NAS (connected with 외부망)

접속방법
1. AVL-NAS-Public
   
   Web 접속 `192.168.1.42:5000`, ID `AVL` PW ` `

   Windows 탐색기에서 `\\AVL-NAS-Public`

   Ubuntu & Mac 탐색기(Finder) `smb://AVL-NAS-Public`

   외부에서 접속 `avl-nas-external-access.quickconnect.to`


### NETWORK

1. 내부망 (CBNU, 논문 등)

   공유기 설정 `192.168.0.1` ID : `admin` PW : ` `

1. 외부망 (KT,    IP Address `***.***.***.**`)

   공유기 설정 `192.168.1.1` ID : `admin` PW : ` `
   
   포트포워딩 필요시, 허브 접속 후 개인포트 생성 사용
   

 * SSID `AVL` PW `********` (2.4GHz and 5GHz combined)
 * SSID `AVL-6E` PW `********` (6GHz)


---
## 3. Documents

 * Public Documents 참조 (NAS)
 * AVL Publication Info
   https://www.avl-scrc.com/publication
 * Projects Info
   https://www.avl-scrc.com/projects

---

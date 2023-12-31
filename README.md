# AVL 101

## 1. To Write Paper
### ACKNOWLEDGEMENT
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
“본 연구는 과학기술정보통신부 및 정보통신기획평가원의 지역지능화혁신인재양성(Grand ICT연구센터) 사업의 연구결과로 수행되었음” (IITP-2023-2020-0-01462)
```

영문)
```
“This research was supported by the MSIT(Ministry of Science and ICT), Korea, under the Grand Information Technology Research Center support program(IITP-2023-2020-0-01462) supervised by the IITP(Institute for Information & communications Technology Planning & Evaluation)”
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
   
   Web 접속 `192.168.1.42:5000`, ID `AVL` PW `Scrc842!`

   Windows 탐색기에서 `\\AVL-NAS-Public`

   Ubuntu & Mac 탐색기(Finder) `smb://AVL-NAS-Public`
   
1. AVL-NAS-PRIVATE

   Web 접속 `192.168.1.52:5000`, ID `개인 ID` PW `개별 PW`

   Windows 탐색기에서 `\\AVL-NAS-PRIVATE`

   Ubuntu & Mac 탐색기(Finder) `smb://AVL-NAS-PRIVATE`

   
### NETWORK

1. 내부망 (CBNU, 논문 등)

   공유기 설정 `192.168.0.1` ID : `admin` PW : `Scrccbnu842!`

1. 외부망 (KT,    IP Address `59.31.230.6`)

   공유기 설정 `192.168.1.1` ID : `admin` PW : `Scrccbnu842!`
   
   포트포워딩 필요시, 허브 접속 후 개인포트 생성 사용
   

 * SSID `AVL` PW `scrccbnu` (2.4GHz and 5GHz combined)

 * SSID `AVL-6E` PW `scrccbnu` (6GHz)
 * SSID `LVA` PW `scrccbnu` (Sub)

![image](https://github.com/AVL-CBNU/101/assets/142374573/dcc92746-4f0f-46a2-b520-bbeb3c020054)

---
## 3. Documents

 * Public Documents
   출장신청서, C-track Hdmap https://gofile.me/78d3y/GVF1HeTRg

 * AVL Publication Info
   https://www.avl-scrc.com/publication
 * Projects Info
   https://www.avl-scrc.com/projects

---

## 4. Installation

#### MORAI
https://help-morai-sim.scrollhelp.site/
#### CARLA
https://carla.readthedocs.io/en/latest/
#### CarMaker



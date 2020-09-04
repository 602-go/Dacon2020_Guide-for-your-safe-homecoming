# Guide-for-your-safe-homecoming

데이콘 **[국토교통 빅데이터 온라인 해커톤 경진대회](https://dacon.io/competitions/official/235622/overview/)**

제출한 원본 코드는 **포스트 코로나, 귀향길이 걱정되는 당신을 위한 <안전한 귀향 안내서>(https://dacon.io/competitions/official/235622/codeshare/1621?page=2&dtype=recent&ptype=pub)** 에서 확인하실 수 있으며, 해당 레포는 이 중  **[안전한 귀향을 위한 안내서]** 를 직접 실행해보실 수 있도록 파일을 구성한 레포입니다.

안내서를 직접 출력해보시기 위해서는 원본 데이터를 받아 몇가지 전처리 과정을 거쳐야 하며, 그 과정은 **안전한 귀향을 위한 안내서.ipynb**에 포함되어 있습니다.

아래 데이터 목록에서 **Dacon(데이콘) 제공 데이터**와 **외부 데이터**는 **출처 표기한 사이트에서 직접 다운을 받아 ipynb 파일과 같은 경로에 두시고** 코드를 실행해주시기 바랍니다.

### **사용 데이터 목록**
**[DACON 제공 데이터]**
- DS4C 코로나19 확진자 데이터 
  - Time.csv
  - PatientInfo.csv
  - Case.csv
- [한국교통안전공단] 교통카드 빅데이터 대중교통 이용정보
    - 발권 OD.dat
    - 지역코드.dat

**[외부 데이터 및 자료]**
- 서울시 행정구역 시군구 정보 (좌표계: WGS1984)
    - 출처: 서울열린데이터광장(https://data.seoul.go.kr/dataList/OA-11677/S/1/datasetView.do) 
- skorea_municipalities_geo_simple.json
    - 출처 : github/PinkWink(https://github.com/PinkWink/DataScience/tree/master/data)

**[자체 제작 데이터]**
- 인접플랫폼.csv
- 도착터미널구분.csv
- 서울시_주요_기차역+터미널_좌표.csv

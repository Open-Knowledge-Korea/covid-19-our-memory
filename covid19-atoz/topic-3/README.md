#   Section3.  Link! 백신으로 보는 국가별 코로나 대응 전략 
## 1. 분석 배경 

백신의 보급으로 인해 코로나 19 사태는 새로운 국면을 맞이하게 됐는데, 정작 백신의 확보 물량, 확보 시기에 대한 분석과 시각화 자료는 매우 부족하다. 그래서 세계의 백신의 확보 현황을 다각도로 분석해보기로 했다. 또한 코로나의 극복, 즉 백신에 있어서도 빈부격차가 있었는지 확인하고자 했다.

한편 코로나 백신은 한국 정치권에서도 뜨거운 논쟁거리였는데, 특히 백신 확보 시기를 놓고 백신 전략이 적절했는지에 대한 공방이 이뤄졌다. 그래서 타국의 확보 현황과 국내 확보 현황을 직접 비교분석 해봤다.

## 2. 데이터 설명 

* **크롬 드라이버를 이용해 csv파일을 다운 받아 사용함.**

* **data 폴더에는 2021년 3월 25일자 데이터셋만 있음.**

* **covid_df** : 전세계 일별 코로나 확진자 데이터 | 국가 정보(국가 코드, 대륙), 확진 현황(신규확진자 수, 누적확진자 수), 검사 현황, 의료 현황(입원환자 수, 중환자 수), 경제적 지표(gdp_per_capita), 기타(흡연자 수, 위생 현황)

*  **vac_df** :  국가별 백신 확보 현황 데이터  | 국가 정보, 제조사, 백신명(Scientific name), 확보량 

* **date_df** : 백신 확보 일자 데이터 | 국가 정보, 제조사 및 백신명, 확보 시기(월), 확보량,  백신 접종 가능 인구 비율 

## 3. 데이터 출처 


**세계 코로나 확진 현황**
https://ourworldindata.org/coronavirus-data-explorer?tab=table&zoomToSelection=true&time=earliest..latest&country=~EuropeanUnion&region=World&testsMetric=true&interval=total&hideControls=true&perCapita=true&smoothing=0&pickerMetric=location&pickerSort=asc

**국가별 백신 확보 현황 데이터**
https://public.tableau.com/views/COVID-19VaccinePurchase_16099487574570/TotalConfirmedDosesbyCountryandVaccineCandidate?%3Aembed=y&%3AshowVizHome=no&%3Ahost_url=https%3A%2F%2Fpublic.tableau.com%2F&%3Aembed_code_version=3&%3Atabs=yes&%3Atoolbar=yes&%3Aanimate_transition=yes&%3Adisplay_static_image=no&%3Adisplay_spinner=no&%3Adisplay_overlay=yes&%3Adisplay_count=yes&%3Alanguage=en&publish=yes&%3AloadOrderID=1

**국가별 백신 확보 일자 데이터**
https://public.tableau.com/views/TimelineofCOVIDVaccineProcurementDeals_16125539354560/Dashboard1?:embed=y&:showVizHome=no&:host_url=https%3A%2F%2Fpublic.tableau.com%2F&:embed_code_version=3&:tabs=no&:toolbar=yes&:animate_transition=yes&:display_static_image=no&:display_spinner=no&:display_overlay=yes&:display_count=yes&:language=en&publish=yes&:loadOrderID=4


##4. 팀원명과  소감

**신주영**:  코로나 데이터 중에서도 뜨거운 감자였던 백신 데이터를 다루어야 했기때문에 주관적인 해석이 안되려고 노력했다 . 세계 백신 데이터는 가공도 수집도 편하게 제공되었는데 앞으로 제공될 데이터들도 이 데이터처럼 기계가 잘 읽을 수 있게 공유되면 좋을것 같다는 생각이 들었다. 제일 적은 인원으로 일하느라 너무너무 고생했어요 우리팀 !

**안지은**:  백신 확보에 있어서도 국가별로 차이가 있었을 것이라고 생각만 해봤는데, 이를 직접 확인할 수 있어서 흥미로웠다.  백신이라는 주제가 다루기 쉬울거라고 생각을 했지만 되려 주제 방향때문에 난항을 겪었다. 이를 통해 데이터 기술 자체보다도 인사이트가 중요하다는 것을 깨닫게 되었다. 모두들 마지막까지 정말 수고 많으셨어요ㅠㅜ!

**이남규**: 
 
# amCharts 기반 HTML 시각화 파일 사용 안내



### \[들어가며]

.html 파일 속 시각화는 모두 amCharts로 진행한 것입니다. <br>
amCharts가 처음이신 분들을 위해 간단한 사용 안내를 정리하였으니, 참고하여 활용해주시기 바랍니다.



### \[amCharts에 관하여]

* amCharts는 R에서 패키지(rAmCharts)를 설치하여 사용할 수도 있고, .html에 차트를 직접 삽입할 수도 있습니다.
* 다만 R 패키지에서는 그릴 수 있는 차트 종류 한계가 있기에, .html에 직접 차트를 띄우는 방식으로 진행했습니다.
* .html 파일에서 마우스 오른쪽 버튼을 클릭한 뒤 '메모장에서 편집'을 선택하시면 차트 요소를 편집할 수 있습니다.
* 다만 R에서와 달리 외부 데이터와의 자동 연동 기능은 제공되지 않아, 데이터의 값은 직접 입력해주어야 합니다.
* amCharts 데모 페이지에 들어가면 다양한 종류의 차트가 있습니다. 원하는 종류의 차트를 자유롭게 선택하여 사용하면 됩니다.
* 데모 페이지에서 제공하는 Demo Source를 메모장에 복사 및 붙여넣기 하여 편집한 후, .txt 파일이 아닌 .html 파일로 저장하여 열면 차트를 확인할 수 있습니다.



### \[관련 링크]

아래의 페이지들은 amCharts의 버전 별 데모 페이지와 참조할 수 있는 Docs 페이지입니다.<br>
R에서의 사용을 원하시는 경우 참조할 수 있는 페이지도 덧붙여두었습니다.

* amCharts 5 Demos : [https://www.amcharts.com/demos/](https://www.amcharts.com/demos/)
* amCharts 4 Demos : [https://www.amcharts.com/demos-v4/](https://www.amcharts.com/demos-v4/)
* amCharts Docs(3-5) : [https://www.amcharts.com/docs/v4/](https://www.amcharts.com/docs/v4/)
* R에서의 사용 : [https://datastorm-open.github.io/introduction\_ramcharts/](https://datastorm-open.github.io/introduction_ramcharts/)



### \[.html]

지금까지 만들어놓은 .html 파일들에 대한 설명입니다.<br>
각 .html 파일은 완성된 차트 화면을 이미지로 캡처하여 저장해두었습니다.<br>
필요한 경우, 캡처한 이미지를 그림판에서 수정하여 사용했습니다. (제목 및 차트 위치 조정, 텍스트 추가 등)<br>
필요한 경우, .html 파일을 .pdf로 인쇄할 수 있습니다.<br>



#### 0\. .html 파일에서 조정 가능한 시각화 요소 예시

* 데이터 값 등
* 제목, 각 축의 label, legend의 내용, 위치, 글자 크기, 글자 색상 등
* 그래프의 크기, 색상, 비율, 위치 등
* 위의 Docs 문서를 살펴보시면 조정 가능한 요소들을 추가로 확인할 수 있습니다.



#### 1\. 3D Bar 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/3d-column-chart-v4/](https://www.amcharts.com/demos-v4/3d-column-chart-v4/))

* 3dbar\_1.html : 강연 전반 만족도 점수 분포
* 3dbar\_2.html : 강연 전반 과학기술 관심도 변화 점수 분포
* 3dbar\_3.html : 강연 전반 과학기술 이해도 영향 점수 분포
* 3dbar\_4.html : 강연 전반 전달력 점수 분포
* 3dbar\_5.html : 강연 전반 홍보 및 안내 효과 점수 분포
* 3dbar\_6.html : 강연 전반 추천 의향 점수 분포
* 3dbar\_7.html : 강연 전반 민주 시민성 기여 인식 점수 분포
* 3dbar\_8.html : 강연 전반 사회 문제해결 기여 인식 점수 분포



#### 2\. Cylinder 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/3d-cylinder-chart-v4/](https://www.amcharts.com/demos-v4/3d-cylinder-chart-v4/))

* cylinder.html : 강연 별 수강생 응답 분포



#### 3\. Donut 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/donut-with-radial-gradient-v4/](https://www.amcharts.com/demos-v4/donut-with-radial-gradient-v4/))

* donut.html : 문항 별 응답 점수 분포(평균점수)



#### 4\. 사람 모양 픽토그램 Stack 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/pictorial-stacked-chart-v4/](https://www.amcharts.com/demos-v4/pictorial-stacked-chart-v4/))

* human\_pictogram.html : 수강생 연령 분포



#### 5\. Pie 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/3d-donut-chart-v4/](https://www.amcharts.com/demos-v4/3d-donut-chart-v4/))

* pie.html : 수강생 연령 분포



#### 6\. Radar 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/radar-chart-v4/](https://www.amcharts.com/demos-v4/radar-chart-v4/))

* radar.html : 강의 평가 문항 별 평균 점수



#### 7\. 100% Stack Bar 차트

(Demo 페이지: [https://www.amcharts.com/demos-v4/100-stacked-column-chart-v4/](https://www.amcharts.com/demos-v4/100-stacked-column-chart-v4/))

* stackbar.html : 문항 별 응답 점수 분포

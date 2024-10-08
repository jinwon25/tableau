# Third Study Week

- 20강: [파이와 도넛차트](#20강-파이와-도넛차트)

- 21강: [워드와 버블차트](#21강-워드와-버블차트)

- 22강: [이중축과 결합축](#22강-이중축과-결합축)

- 23강: [분산형 차트](#23강-분산형-차트)

- 24강: [히스토그램](#24강-히스토그램)

- 25강: [박스플롯](#25강-박스플롯)

- 26강: [영역차트](#26강-영역차트)

- 27강: [간트차트](#27강-간트차트)

- 28강: [필터](#28강-필터)

- 29강: [그룹](#29강-그룹)


- 문제1 : [문제1](#문제1)

- 문제2 : [문제2](#문제2)

- 참고자료 : [참고자료](#참고-자료)



## Study Schedule

| 강의 범위     | 강의 이수 여부 | 링크                                                                                                        |
|--------------|---------|-----------------------------------------------------------------------------------------------------------|
| 1~9강        |  ✅      | [링크](https://youtu.be/3ovkUe-TP1w?si=CRjj99Qm300unSWt)       |
| 10~19강      | ✅      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=75)       |
| 20~29강      | ✅      | [링크](https://www.youtube.com/watch?v=Qcl4l6p-gHM)      |
| 30~39강      | 🍽️      | [링크](https://www.youtube.com/watch?v=e6J0Ljd6h44&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=55)       |
| 40~49강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=45)       |
| 50~59강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=35)       |
| 60~69강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=25)       |
| 70~79강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=15)       |
| 80~89강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=5)        |


<!-- 여기까진 그대로 둬 주세요-->
<!-- 이 안에 들어오는 텍스트는 주석입니다. -->

# Third Study Week

## 20강: 파이와 도넛차트
<!-- 파이와 도넛차트에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot14.png)

```
파이 차트는 전체에 대한 비율을 표시할 때 주로 사용된다.

도넛 차트는 기존의 파이 차트 위에 작은 원을 추가하여, 내부를 비워둔 형태로 시각화한 것이다.
```

> **🧞‍♀️ 도넛차트를 생성하는 법을 기록해주세요.**
```
1. 열 선반에 빈 공간에 0을 입력하여 임의의 축을 만든다.
2. 생성한 필드를 컨트롤 키를 누른 채 옆으로 드래그하면 두 개의 원이 생성된다.
3. 분리된 파이 차트 표현을 위해 두 번째 마크에 포함된 값을 제거한다.
4. 레이블에 값을 추가하고, 사이즈를 조정하여 양쪽 파이 차트의 크기를 맞춘다.
5. 상단의 두 번째 필드를 클릭하거나 역삼각형 표시를 클릭하여 이중 축을 선택하면 도넛 차트가 완성된다.
```

## 21강: 워드와 버블차트
<!-- 워드와 버블차트에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot15.png)
![스크린샷](../image/screenshot16.png)

```
버블 차트는 수치적 데이터를 원의 크리로 표현하는 차트이다.

워드 클라우드는 문서 내에서 등장하는 키워드가 얼마나 자주 등장하는지를 텍스트 크기로 표현하여 직관적으로 시각화할 수 있는 차트이다.
```

## 22강: 이중축과 결합축
<!-- 이중축과 결합축에 관해 배우게 된 점을 적어주세요 -->
```
이중 축은 하나의 뷰어 안에서 축을 이중으로 사용하는 차트이다. 이중 축을 쓸 경우에는 마크를 각각의 축에 개별적으로 적용할 수 있다.

결합된 축은 하나의 축을 공유하는 차트이다. 축을 공유하는 측정값을 필요에 따라 추가할 수 있다.
```

## 23강: 분산형 차트
<!-- 분산형 차트에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot17.png)

```
분산형 차트는 파라미터 간의 상관관계를 파악하는데 유용한 그래프이다.

-> 분산형 차트에 범주별 추세선을 추가하려면, 왼쪽 상단에서 분석 탭으로 전환한 후, 모델의 추세선을 시트에 드래그하여 선형 영역에 드랍한다.
-> 전체 추세를 파악하고 싶다면, 열 선반에서 시트의 추세선을 마우스 오른쪽 클릭하고 추세선 편집을 선택한 뒤, 요소에서 범주의 체크를 해제한다.
-> 각각의 추세선을 한 뷰에서 보고 싶다면, 열 선반에서 필드를 컨트롤 키를 누른 채 옆으로 드래그하여 복사한다. 그런 다음, 복사한 필드 중 하나의 추세선을 우클릭하고 모든 추세선 편집을 선택한 후, 범주 차원을 클릭하여 활성화한다. 이후 열 선반에서 필드를 마우스 오른쪽 클릭하고 이중 축을 선택한다. 마지막으로 추가로 생성된 머리글을 우클릭하여 머리글 표시를 해제하여 정리한다.
```

## 24강: 히스토그램
<!-- 히스토그램에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot18.png)
![스크린샷](../image/screenshot19.png)

```
히스토그램은 데이터의 분포 형태를 시각적으로 나타내는 차트이다. 형태는 막대그래프와 유사하지만, 불연속형이 아닌 연속형 측정값을 범위 또는 구간 차원으로 그룹화한다는 점에서 차별화된다. 또한, 히스토그램에서는 막대와 막대 사이가 붙어 있는 반면, 막대그래프는 막대와 막대 사이에 공백이 존재한다. 

히스토그램은 차원 필드 없이 측정값만으로 그래프를 그릴 때 주로 사용하는 표현 방식이다. Tableau에서는 구간 차원의 생성 여부에 따라 두 가지 방법으로 히스토그램을 생성할 수 있다.
1. 수동 생성: 사용자가 원하는 구간 차원을 수동으로 설정하여 히스토그램을 만들 수 있다. 이 경우, 사용자는 측정값을 바탕으로 원하는 구간을 정의한 후, 해당 구간을 열 선반에 배치하여 히스토그램을 생성한다.
2. 자동 생성: Tableau에서 측정값을 열 선반에 드래그한 후, 우측의 표현 방식에서 히스토그램을 클릭하면 기본적으로 히스토그램이 자동으로 생성된다. 이때 Tableau는 데이터에 맞게 적절한 구간을 자동으로 설정해 준다.
```

## 25강: 박스플롯
<!-- 박스플롯에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot20.png)

```
박스 플롯은 데이터의 분포를 파악하는 데 사용하는 그래프이다.
```

## 26강: 영역차트
<!-- 영역차트에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot21.png)

```
영역 차트는 라인과 축 사이의 공간이 색상으로 채워진 라인 차트이다. 영역을 색상으로 채우는 차트이기에 주로 연속형 데이터의 누계를 표현하는 데 사용된다. 
```

## 27강: 간트차트
<!-- 간트차트에 관해 배우게 된 점을 적어주세요 -->
![스크린샷](../image/screenshot22.png)

```
간트 차트는 주로 시간 경과에 따른 기간을 시각화하는데 사용된다. 

예시) 제품 범주별 배송 기간을 배송 형태로 구분하여 간트 차트로 시각화
1. 배송 날짜 필드를 우클릭한 채 열 선반으로 드래그하여, 불연속형의 월을 선택해 월별 배송기간을 확인한다.
2. 제품 범주를 행 선반에 올린 후, 상단 툴바에서 분석 -> 계산된 필드 만들기를 선택하여 배송기간 필드를 만든다.
3. 생성한 배송기간 필드를 마크 창의 크기로 드래그한다.
4. 기본적으로 배송기간 필드가 합계로 집계되는데, 이는 모든 배송기간의 합을 나타내므로, 필드를 우클릭한 뒤 측정값을 평균으로 변경한다.
5. 마크 유형을 간트 차트로 변경한다.
6. 행 선반의 범주에서 하위 범주 생성 버튼을 눌러 하위 범주를 추가한다.
7. 상단의 표준 보기를 전체 보기로 변경한다.
8. 고객 필드를 필터로 드래그하여 필터링을 설정한 후, 임의의 고객을 선택하고 확인을 누른다.
9. 필터에서 고객 이름 우클릭하여 필터 표시를 활성화한 뒤, 우측 상단의 역삼각형 표시 클릭하여 단일 값 드롭다운으로 필터 형식을 변경한다.
10. 배송 형태 필드를 마크 창의 색상에 드래그하여, 배송 형태별 색상 구분을 적용한다.
11. 고객 이름 필터를 다시 클릭하여, 필터 목록에서 데이터를 선택해 손쉽게 필터링할 수 있다.
```

## 28강: 필터
<!-- 필터에 관해 배우게 된 점을 적어주세요 -->
```
필터링은 데이터 분석에서 필수적인 부분으로 뷰뿐만 아니라 쿼리 속도나 데이터 용량 측면에서도 필터 핸들링에 따라 성능의 차이가 크게 난다.

Tableau는 추출, 데이터 원본, 컨텍스트, 차원, 측정값, 필터 순으로 동작한다.

추출
-> 연결에서 추출을 클릭하면, 추출 옆에 편집 버튼이 생성되고 이를 통해 추출 필터를 추가할 수 있다. 편집 버튼을 클릭한 후 추가를 눌러 필드를 선택하여 필터를 생성한다. 이후 데이터 저장 위치를 선택하는 창이 나타난다. 추출 필터는 데이터를 가져오거나 저장할 때 최우선으로 적용된다.

데이터 원본
-> 데이터 원본 필터는 작업을 위한 데이터 중 일부만 워크스페이스에 불러올 때 사용된다. 데이터 원본 페이지의 오른쪽 상단에는 필터 옵션이 있으며, 추가를 클릭하여 원하는 필터를 추가할 수 있다.

컨텍스트 필터
-> Tableau에서 기본적으로 각 필터는 다른 필터와 관계없이 모든 데이터 행에 접근하여 작동하지만, 컨텍스트 필터로 지정하면 다른 필터들이 해당 컨텍스트 필터에 종속되어 작동한다.
```

## 29강: 그룹
<!-- 그룹에 관해 배우게 된 점을 적어주세요 -->
```
데이터를 표시하는 방법에는 그룹, 계층, 집합이 있다. 이 중 그룹은 필드에 있는 항목들을 수동으로 묶어 새로운 그룹을 생성할 수 있으며, 이는 기존 데이터 원본에 없는 사용자 지정 그룹 필드를 만들 수 있는 기능을 제공한다.

먼저 제품들을 드래그하여 그룹을 추가할 수 있으며, 항목별로 묶을 필드를 선택하여 그룹을 생성할 수 있다.
```

## 문제 1.

```js
유정이는 superstore 데이터셋에서 '주문' 테이블을 보고 있습니다.
1) 국가/지역 - 시/도- 도시 의 계층을 생성했습니다. 계층 이름은 '위치'로 설정하겠습니다.
2) 날짜의 데이터 타입을 '날짜'로 바꾸었습니다.

코로나 시기의 도시별 매출 top10을 확인하고자
1) 배송 날짜가 코로나 시기인 2021년, 2022년에 해당하는 데이터를 필터링했고
2) 위치 계층을 행으로 설정해 펼쳐두었습니다.
이때, 매출의 합계가 TOP 10인 도시들만을 보았습니다.
```

![image-2.png](https://github.com/yousrchive/tableau/blob/main/study/img/1st%20study/image-4.png?raw=true)

```
겉보기에는 전체 10개로, 잘 나온 결과처럼 보입니다. 그러나 유정이는 치명적인 실수를 저질렀습니다.
오늘 배운 '컨텍스트 필터'의 내용을 고려하여 올바른 풀이 및 결과를 구해주세요.
```

![스크린샷](../image/screenshot23.png)
```
매출 합계 상위 10개 도시만 출력하기 위해 국가/지역과 시/도 필드를 제외하고 도시 필드만을 행으로 설정했다. 이후, 배송 날짜와 도시에 각각 조건을 맞춘 필터를 적용한 뒤, 도시에 컨텍스트 필터를 설정하여 우선순위를 조정했다. 마지막으로, 매출 합계 기준으로 내림차순 정렬하여 상위 10개 도시만 나열했다.
```

<!-- DArt-B superstore가 아닌 개인 superstore 파일을 사용했다면 값이 다르게 표시될 수 있습니다.-->

## 문제 2.

```js
태영이는 관심이 있는 제품사들이 있습니다. '제품 이름' 필드에서 '삼성'으로 시작하는 제품들을 'Samsung group'으로, 'Apple'으로 시작하는 제품들을 'Apple group'으로, 'Canon'으로 시작하는 제품들을 'Canon group'으로, 'HP'로 시작하는 제품들을 'HP group', 'Logitech'으로 시작하는 제품들을 'Logitech group'으로 그룹화해서 보려고 합니다. 나머지는 기타로 설정해주세요. 이 그룹화를 명명하는 필드는 'Product Name Group'으로 설정해주세요.

(이때, 드래그보다는 멤버 찾기 > 시작 문자 설정하여 모두 찾아 한번에 그룹화해 확인해보세요.)
```

![group](https://github.com/yousrchive/BUSINESS-INTELLIGENCE-TABLEAU/blob/main/study/img/3rd%20study/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202024-09-18%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.33.47.png?raw=true)

![스크린샷](../image/screenshot24.png)
```
제품들을 제품사에 따라 범주화하기 위해 그룹 만들기의 찾기 기능을 사용하여 분류하고, 나머지 항목들은 '기타 포함'을 클릭해 '기타'로 설정한 뒤, 해당 그룹을 Product Name Group으로 명명했다.
```

```js
해당 그룹별로 어떤 국가/지역이 주문을 많이 차지하는지를 보고자 합니다. 매출액보다는 주문량을 보고 싶으므로, 주문Id의 카운트로 계산하겠습니다.

기타를 제외하고 지정한 5개의 그룹 하위 항목들만을 이용해 아래와 같이 지역별 누적 막대그래프를 그려봐주세요.
```

![image](https://github.com/yousrchive/BUSINESS-INTELLIGENCE-TABLEAU/blob/main/study/img/3rd%20study/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202024-09-18%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%204.37.55.png?raw=true)

![스크린샷](../image/screenshot25.png)
```
Product Name Group 필드를 필터링하여 기타를 제외한 5개의 항목만 출력되도록 설정했다. 이후, 열과 행에 각각 주문 ID와 Product Name Group 필드를 배치하고, 색상에 국가/지역 필드를 넣어 그래프를 생성했다.
```

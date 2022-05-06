# abc-stock-info

ABC마트 매장 재고 조회를 위한 repository

## 매장코드

[store-code.txt](https://github.com/ahn7157/abc-stock-info/blob/master/store-code.txt)

파일에 없는 매장코드는 바코드 번호 검색할 때 매장코드만 바꿔가면서 직접 찾아야합니다.

#### ↓↓↓↓↓데이터 확보를 위해 많은 제보 부탁드립니다↓↓↓↓↓

매장코드 제보: https://github.com/ahn7157/abc-stock-info/discussions/1

store-code.txt 수정하고 pull request 올리셔도됩니다

## 상품코드

[item-code.txt](https://github.com/ahn7157/abc-stock-info/blob/master/item-code.md)

#### 상품코드 찾는 방법

1. <https://abcmart.a-rt.com/>에서 상품 검색
2. 상단 상품코드의 뒤 5자리 숫자
3. 상품 검색이 불가능한 경우 구글링

   ex) "abc마트 에어맥스 97 상품코드" 검색

## 재고 검색 방법

1. A-RT 어플 실행

   안드로이드 : https://play.google.com/store/apps/details?id=com.abcart.app.primary&hl=ko&gl=US
   
   iOS : https://apps.apple.com/kr/app/abc%EB%A7%88%ED%8A%B8%EC%9D%98-%ED%86%B5%ED%95%A9-%EC%82%AC%EC%9D%B4%ED%8A%B8-a-rt-com/id1472679606

3. 하단 메뉴에서 가장우측 클릭
4. QR/바코드 스캔 배너 클릭
5. 바코드 번호 직접 입력 클릭
6. [매장코드](https://github.com/ahn7157/abc-stock-info/edit/master/README.md#%EB%A7%A4%EC%9E%A5%EC%BD%94%EB%93%9C) + 00 + [상품코드](https://github.com/ahn7157/abc-stock-info/edit/master/README.md#%EC%83%81%ED%92%88%EC%BD%94%EB%93%9C) 입력

   ex) 0281(잠실롯데월드몰점) + 00 + 62981(NIKE AIR MAX 97) = 02810062981

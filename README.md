# GeoCoding

GeoCoding은 문자로 된 주소(혹은 다른 지리적 식별자) 데이터를 GIS 소프트웨어 혹은 Python, R 등의 프로그래밍 언어에서 활용 및 가공 처리 가능하도록 위경도 데이터로 변환하는 작업을 의미한다.
위경도 데이터를 얻고자 하는 csv 파일을 불러와 주소가 담겨있는 컬럼명을 일치 후에 위경도 데이터로 변환할 수 있는 데이터를 제공받을 수 있다.

제공 기능은 다음과 같다:

1. 단일 도로명 주소 검색을 통한 지오코딩(Kakao API)
2. CSV 파일 업로드를 통한 지오코딩(Kakao API)
3. CSV 파일 업로드를 통한 지오코딩(Geopy API)
Kakao API는 주소 검색 시 자동 맞춤 기능이 우수하여 검색 결과의 정확도가 높다.
Kakao API Key는 Kakao Developer(https://developers.kakao.com/)에서 발급받아 활용할 수 있다.
발급이 어렵다면 Geopy API를 활용해서 기능을 대체할 수 있다.

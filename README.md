
### Daum 영화 순위 썸네일 다운로더

1. 첫 번째 코드는 Selenium을 사용하여 Daum 검색 결과 페이지에서 특정 기간동안 각 연도에 대해 상위 5위까지의 영화 썸네일을 다운로드하는 코드입니다. <br> Daum 검색 페이지에서 연도별 각 영화 썸네일을 찾아서 연도와 순위를 파일 이름에 포함하여 이미지 파일로 저장합니다. 

2. 두 번째 코드는 Selenium을 사용하여 Daum 검색 결과 페이지에서 특정 기간동안 영화 순위의 이미지 썸네일 URL을 출력하는 코드입니다. <br>코드는 해당 페이지로 이동한 후 이미지 썸네일 요소를 찾고, 각 썸네일의 URL을 출력합니다.

---

<!-- [필수 요구사항]
Python 3 이상
Chrome 브라우저
Chrome 드라이버 -->

### 필수 요구사항

1. Python 3 환경
2. 라이브러리 설치(requests, BeautifulSoup, selenium)
3. Chrome 브라우저 
4. Chrome 드라이버(Chrome 브라우저 버전과 일치하는 드라이버를 다운로드하여 PATH에 추가하거나, 코드에서 드라이버 경로를 명시적으로 지정해야 함)
5. 이미지 파일을 저장할 폴더 생성
<br>
** 코드에서 반복되는 부분에 대한 사용자 정의가 가능하므로, 필요에 따라 코드를 수정하여 사용할 수 있음 (예: 검색어, 이미지 저장 경로 등)

---

### 시연 영상
![stack](https://github.com/jisoooo17/readme_img/blob/main/bbangkkeut_campaign/movie_crawling.gif)

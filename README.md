# ZXE Karaoke player
노래방 플레이어이다.
미디를 파싱하는것도 만들고 싶었지만 포기했다.(나중에 만들거임)
# 요구사항
es6 이상
video 태그 autoplay
... 아 모르겠고 걍 크롬(chrome) 쓰자
# 사용법
웹서버나 웹호스팅 등이 있다면
1. 웹루트에 아무데나 폴더를 하나 만든다.
2. download zip을 사용해 압축파일을 받아 만든 폴더에 풀어준다.
   (git clone을 사용해도 된다)
3. 브라우저로 http://(웹서버 주소)/(플레이어 설치 경로)에 접속한다.
없거나 귀찮다면
1. 아무데나 폴더를 하나 만든다.
2. download zip을 사용해 압축파일을 받아 만든 폴더에 풀어준다.
   (git clone을 사용해도 된다)
3. 브라우저로 index.html 파일을 연다.
공통
4. etc/config.json 파일을 열어 아래와 같이 수정한다.
```json
{
    "archive_url":"(원하는 다른 폴더 경로. 예시: ../karaoke_archive)"
}
```

# Favicon Generator

[2025년에 Favicon을 준비하는 법](https://news.hada.io/topic?id=19204) 의 내용에 따라 자동으로 Favicon 생성해주는 도구를 만들어보았습니다.

[사용해보기](https://dev-huiya.github.io/favicon-generator/)

## 사용법
1. 정사각형 비율의 SVG 이미지를 업로드한다.
2. 생성된 HTML 코드와 다운로드된 이미지 파일을 프로젝트에 포함한다.
3. 끝.

## 상세 내용
- ✅ SVG 파일은 SVGO로 최적화됩니다.
- ✅ ICO 파일에는 16px, 32px 이미지가 포함됩니다.
- ✅ 180px, 192px, 512px의 PNG 이미지가 생성됩니다.

- ❌ PNG 파일은 Squoosh로 압축되지 않습니다.

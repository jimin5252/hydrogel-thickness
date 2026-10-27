# 하이드로겔 두께 측정 (HW5 웹 앱 초안)

index.html 한 파일로 동작하는 정적 웹 앱입니다. 서버·DB·API 키가 없고, 사진은 브라우저 안에서만 계산합니다.
알고리즘은 중간 프로젝트의 batch_measure.py v4.2를 JavaScript로 옮긴 것입니다.

## 로컬에서 열기
index.html을 더블클릭하면 브라우저에서 열립니다. (글꼴은 인터넷이 있으면 Google Fonts, 없으면 시스템 글꼴)

## Vercel 배포 (수업에서 다룬 방법)
1. 이 폴더(index.html, README.md)를 GitHub 저장소에 올립니다. (GitHub Desktop 사용 가능)
2. vercel.com에서 Add New > Project > 해당 저장소 Import.
3. Framework Preset은 Other, Build Command와 Output Directory는 비워 둔 채 Deploy.
4. 발급된 주소(https://...vercel.app)로 접속해 사진 몇 장을 올려 확인합니다.

## 사용
같은 배율(4배율 고정, 4096x3000)의 사진을 3장 이상 한 번에 올리면 유리 폭 기준(W0)을 사진들의 중앙값으로 잡습니다.
"검수 필요" 표시가 있는 사진은 값이 틀릴 수 있으니 ImageJ로 직접 확인하세요.

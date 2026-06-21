# GitHub Pages용 사진 갤러리 게시판

## 구성
- index.html : 홈 화면
- gallery.html : 갤러리 게시판
- css/common.css : 공통 스타일
- css/gallery.css : 갤러리 스타일
- js/gallery-data.js : 사진 게시글 데이터
- js/gallery.js : 필터/팝업 기능
- images/gallery/ : 사진 이미지 폴더

## 사진 추가 방법
1. images/gallery/ 폴더에 사진을 넣습니다.
2. js/gallery-data.js 파일에 항목을 추가합니다.

```js
{
  id: 7,
  title: "새 사진 제목",
  category: "education",
  categoryName: "교육",
  date: "2026.06.15",
  image: "images/gallery/photo07.jpg",
  desc: "사진 설명을 입력합니다."
}
```

GitHub Pages에서 바로 작동합니다.

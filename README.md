# 생데 중간고사 대비

KAIST BS.49903 DS/AI for Biology(생명과학 데이터 사이언스) 중간고사 대비 자료입니다.

- `index.html` — 첫 화면
- `study_guide.html` — 한국어 학습노트 (챕터별 슬라이드, O/X 퀴즈, 오개념)
- `mock_exam.html` — 모의고사 4세트 (모범답안·채점기준, 답안 .md 내보내기)

세 파일 모두 외부 서버 없이 동작하는 단일 HTML입니다(수식 글꼴·그림·데이터 내장). 답안과 진행 상황은 각자 브라우저의 localStorage에만 저장됩니다.

강의 자료(슬라이드 그림·강의 내용)는 J. Alexander Bae 교수님의 수업 자료를 바탕으로 정리했습니다.

## 업데이트

상위 폴더(`시험대비/`)의 `study_guide.html`, `mock_exam.html`을 고친 뒤 이 폴더로 복사하고 커밋·푸시합니다.

```sh
cp ../study_guide.html ../mock_exam.html .
git add -A && git commit -m "update" && git push
```

GitHub Pages는 약 10분 동안 캐시하므로, 바뀐 내용이 안 보이면 잠시 뒤 새로고침합니다.

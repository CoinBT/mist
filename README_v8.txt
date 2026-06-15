Mist Earth: Survival i18n v8 - Prologue text fix

Changes:
- Fixed prologue localization issue where long prologue blocks could appear as mixed Korean/English or strangely translated fragments.
- translateText() now checks exact keys first and also checks a newline-normalized key, because prologue template literals use real line breaks while lang/en.js stores long keys with escaped \n.
- The final prologue button now uses the language layer.
- Music/List fallback behavior from v7 is preserved.

Folder layout for music remains:
Music/List/list.json
Music/List/*.mp3

---

[한국어 버전]
Mist Earth: Survival i18n v8 - 프롤로그 텍스트 수정

변경사항:
- 긴 프롤로그 문장이 한글/영어가 섞이거나 어색한 조각 번역으로 표시되던 문제를 수정했습니다.
- 프롤로그 원문은 실제 줄바꿈을 사용하고, lang/en.js의 긴 키는 이스케이프된 \n을 사용하기 때문에 줄바꿈 정규화 매칭을 추가했습니다.
- 마지막 프롤로그 버튼도 언어 레이어를 거치도록 수정했습니다.
- v7의 Music/List 음악 fallback 동작은 유지됩니다.

음악 폴더 구조는 그대로 유지됩니다.
Music/List/list.json
Music/List/*.mp3

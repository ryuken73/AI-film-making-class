# AI 영상제작 초급과정
2026/4/15 부천 웹툰융합센터 교육 내용 정리

## 동향
- aikive.com : AI영화들 영상제작물  
- ai 배경음악 - 저작권이슈 회피
- PD수첩 AI가 그려낸 저출산 미래
- artificialanalysis.ai : 각종 AI 리더보드 - 분야별 핫한 AI는? 중국툴이 퀄이 좋다. 상위에 다수 포진
- higgsfield.ai : 여러 모델을 쓸 수 있다. 뭔가 cursor 느낌
- Lip Sync 전문툴 upscaling 전문툴,  sound, sound library 등의 카테고리로 전문 AI툴들이 있다
- Topas Labs : 제대로 동작하는 업스케일링 툴

## 생성방식
- Text to Video : runway
- Text to video&sound : sora2
- Text to Image : midjourney
- Image to Video : runway
- Image to Image : midjourney (이미지 영역확장)
- Video to Video: runway (카네라 앵글, 조명 바꿔줘, 의상,배경, 추가, 크로마키 만들어줘....., 일부 대체)
- Video to Video : KlingAI 일부 대체...
- Video to Video : 비디오 영역확장 (드랍프레임 보정 무조건 되겠다..) 프리미어에 기능 있음
- runway : 모션캡쳐 합성
- Suno : 음악생성, 효과음 생성

## 케이스 스터디 - 여러 AI툴들을 다 조합해서 완성
- 아이디어 - gpt canvas 사용 : 대화를 하면서 문서를 만들어 나간다. todo : gemini에도 비슷한게 있나?
- sora : gpt에서 만든 프롬프트 사용
- 먼저 이미지를 잘 만든다 - 50%
- 그다음 runway에서 이미지 + 페이스 모션캡쳐 적용 (AI의 부자연스러움을 레퍼런스 제공으로 극복)
- 편집까지는 아직 AI가 못한다고 한다.
- 맨 마지막에 topas labs에서 고화질 영상으로 만든다

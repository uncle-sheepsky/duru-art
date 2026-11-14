# 노히트라던 탄막을 다시 검사해봤습니다

> **AI로 만든 그림입니다.** 이 폴더의 두루 그림은 모두 AI 이미지 생성으로 만들었습니다. 그림마다 어느 도구로 만들고 어떻게 손봤는지 아래에 적었습니다.

- 영상: https://youtu.be/phQ7-AZkc2o
- 공개일: 2026-11-05 (한국 시각)
- 그림 수: 57

## 그림과 출처

| 파일 | 무엇으로 만들었나 | 어떻게 손봤나 |
|---|---|---|
| `cels/` `ship_cel01__l.png`, `ship_cel03__l.png`, `ship_cel04__l.png` … `stick_mash_cel04__s.png` (43) | **탄막 편 원화**. 사용자가 2026-11-05에 OpenAI Codex의 내장 image_gen으로 만든 45프레임 가운데 일부입니다. 제작 기준과 프롬프트 기록이 있습니다. | 화면에 맞게 비율 크기 조정과 이동만 했습니다(`norm_cels.py`). 이름 끝 `__s`와 `__l`은 크기만 다른 두 판입니다. |
| `emo/` `01_wave.png`, `05_no.png`, `13_surprise.png` … `35_gift.png` (9) | **정식 승인본 원본 32종**. 사용자가 2026-10-18에 OpenAI Codex의 내장 image_gen으로 만들었습니다. 주문 프롬프트 기록이 있습니다. | 가로세로 720px 안으로 줄였습니다. |
| `cels/` `listen_cel01.png`, `listen_cel02.png`, `listen_cel03.png`, `listen_cel04.png`, `term_cel02.png` | **Claude가 주문한 그림**. Claude가 OpenAI Codex CLI(`codex exec -m gpt-6-astra`)에 주문해 내장 image_gen이 만들었습니다. 주문문(prompts)과 생성 기록(gen_log.json)이 있고, 승인된 두루 그림을 참조로 넣었습니다. | 가로세로 900px 안으로 줄였습니다. |

## 여기 없는 것

탄막 숏폼 장면이 화면 안에 나옵니다. 그 장면 속 두루는 `2026-11-05_MomRDoS27bM_danmaku-dodge-short` 폴더에 있습니다. 멜론 보스, 조종석, 방 배경은 두루가 아니라서 넣지 않았습니다. 이 폴더는 영상의 최종 렌더 코드를 다시 실행해 실제로 그려진 그림 파일을 기록하고, 그중 두루가 나오는 그림만 골라 담았습니다. 썸네일, 배경, 소품, 글자 그림은 넣지 않았습니다.

## 라이선스

CC0 1.0. 출처 표시 없이 쓰고 고치고 다시 나눠도 됩니다. 저장소 맨 위 `LICENSE`를 보세요.

## English

> **These pictures were made with AI.** Every Duru picture in this folder was made with AI image generation. Below is which tool made each group and how it was edited.

- Video: https://youtu.be/phQ7-AZkc2o ("The AI Dodged Every Bullet. Between Frames, It Got Hit")
- Published: 2026-11-05 (KST)
- Pictures: 57

### Pictures and sources

| Files | How it was made | Edits |
|---|---|---|
| `cels/` `ship_cel01__l.png`, `ship_cel03__l.png`, `ship_cel04__l.png` … `stick_mash_cel04__s.png` (43) | **Bullet-hell episode drawings**. Part of the 45 frames the user made on 2026-11-05 with the built-in image_gen tool of OpenAI Codex. The production notes and prompts were kept. | Only scaled and shifted to fit the screen (`norm_cels.py`). Names ending in `__s` and `__l` are the same drawing at two sizes. |
| `emo/` `01_wave.png`, `05_no.png`, `13_surprise.png` … `35_gift.png` (9) | **The 32 approved originals**. Made by the user on 2026-10-18 with the built-in image_gen tool of OpenAI Codex. The prompts were kept. | Shrunk to fit within 720 px. |
| `cels/` `listen_cel01.png`, `listen_cel02.png`, `listen_cel03.png`, `listen_cel04.png`, `term_cel02.png` | **Drawings ordered by Claude**. Ordered by Claude through OpenAI Codex CLI (`codex exec -m gpt-6-astra`) and made by its built-in image_gen tool. The prompts and the generation log (gen_log.json) were kept, and approved Duru drawings were given as references. | Shrunk to fit within 900 px. |

### Not included

Scenes from the bullet-hell short appear on screen; the Duru in them is in the `2026-11-05_MomRDoS27bM_danmaku-dodge-short` folder. The melon boss, cockpit and room background are not Duru, so they are not here. This folder was filled by running the video's final render code again, recording every picture file it drew, and keeping only the ones that show Duru. Thumbnails, backgrounds, props and text images are not included.

### License

CC0 1.0. Use, change and share without credit. See `LICENSE` at the top of the repository.


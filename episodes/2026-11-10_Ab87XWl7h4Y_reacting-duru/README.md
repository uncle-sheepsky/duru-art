# 반응하는 두루

> **AI로 만든 그림입니다.** 이 폴더의 두루 그림은 모두 AI 이미지 생성으로 만들었습니다. 그림마다 어느 도구로 만들고 어떻게 손봤는지 아래에 적었습니다.

- 영상: https://youtu.be/Ab87XWl7h4Y
- 공개일: 2026-11-10 (한국 시각)
- 그림 수: 191

## 그림과 출처

| 파일 | 무엇으로 만들었나 | 어떻게 손봤나 |
|---|---|---|
| `stickers/01_wave/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/02_thanks/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/03_sorry/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/05_no/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/06_love/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/08_hug/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/11_cheer/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/12_congrats/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/13_surprise/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/18_shy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/23_sleep/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/28_cold/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/29_hot/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/30_eat/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/31_coffee/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/32_peek/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/35_gift/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png` | **승인 GIF 17종의 낱장**. 사용자가 2026-10-18~21에 OpenAI Codex의 내장 이미지 생성 도구(image_gen)로 자세 그림을 만들고, 고르고, 시간을 맞춰 엮은 GIF입니다. 낱장마다 어느 생성본에서 왔는지는 따로 남은 기록이 없습니다. | 흰 테두리와 아래 그림자를 코드로 구운 스티커 판입니다(`prep_stickers.py`). 새 동작 그림은 먼저 740×640 판에 배율 하나와 이동만으로 맞췄습니다(`fit_motion.py`). |
| `stickers/calm/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/cozy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/hoof/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/idle/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/knock/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/lift/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/melt/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/pat/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`<br>`stickers/puff/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/sleepy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/tickle/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png` | **Claude가 주문한 그림**. Claude가 OpenAI Codex CLI(`codex exec -m gpt-6-astra`)에 주문해 내장 image_gen이 만들었습니다. 주문문(prompts)과 생성 기록(gen_log.json)이 있고, 승인된 두루 그림을 참조로 넣었습니다. | 흰 테두리와 아래 그림자를 코드로 구운 스티커 판입니다(`prep_stickers.py`). 새 동작 그림은 먼저 740×640 판에 배율 하나와 이동만으로 맞췄습니다(`fit_motion.py`). |

## 여기 없는 것

담요, 빵, 컵, 부채, 스탠드 같은 소품 그림은 두루가 아니라서 넣지 않았습니다. 이 폴더는 영상의 최종 렌더 코드를 다시 실행해 실제로 그려진 그림 파일을 기록하고, 그중 두루가 나오는 그림만 골라 담았습니다. 썸네일, 배경, 소품, 글자 그림은 넣지 않았습니다.

## 라이선스

CC0 1.0. 출처 표시 없이 쓰고 고치고 다시 나눠도 됩니다. 저장소 맨 위 `LICENSE`를 보세요.

## English

> **These pictures were made with AI.** Every Duru picture in this folder was made with AI image generation. Below is which tool made each group and how it was edited.

- Video: https://youtu.be/Ab87XWl7h4Y ("Duru Reacts")
- Published: 2026-11-10 (KST)
- Pictures: 191

### Pictures and sources

| Files | How it was made | Edits |
|---|---|---|
| `stickers/01_wave/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/02_thanks/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/03_sorry/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/05_no/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/06_love/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/08_hug/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/11_cheer/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/12_congrats/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/13_surprise/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/18_shy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/23_sleep/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/28_cold/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/29_hot/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/30_eat/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/31_coffee/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`<br>`stickers/32_peek/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`, `06.png`, `07.png`<br>`stickers/35_gift/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png` | **Frames of the 17 approved Duru GIFs**. The user built these GIFs on 2026-10-18 to 10-21 from pose drawings made with the built-in image tool (image_gen) of OpenAI Codex, then picked the frames and set the timing. There is no record of which generated file each frame came from. | Sticker versions with a white border and a drop shadow baked in code (`prep_stickers.py`). The new pose drawings were first fitted to the 740×640 canvas with one scale and a shift (`fit_motion.py`). |
| `stickers/calm/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/cozy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/hoof/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/idle/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/knock/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/lift/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/melt/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/pat/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`<br>`stickers/puff/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/sleepy/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png`<br>`stickers/tickle/` `00.png`, `01.png`, `02.png`, `03.png`, `04.png`, `05.png` | **Drawings ordered by Claude**. Ordered by Claude through OpenAI Codex CLI (`codex exec -m gpt-6-astra`) and made by its built-in image_gen tool. The prompts and the generation log (gen_log.json) were kept, and approved Duru drawings were given as references. | Sticker versions with a white border and a drop shadow baked in code (`prep_stickers.py`). The new pose drawings were first fitted to the 740×640 canvas with one scale and a shift (`fit_motion.py`). |

### Not included

Props such as the blanket, bun, cup, fan and lamp are not Duru, so they are not here. This folder was filled by running the video's final render code again, recording every picture file it drew, and keeping only the ones that show Duru. Thumbnails, backgrounds, props and text images are not included.

### License

CC0 1.0. Use, change and share without credit. See `LICENSE` at the top of the repository.


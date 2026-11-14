# AI가 망친 두루를 되찾은 방법

> **AI로 만든 그림입니다.** 이 폴더의 두루 그림은 모두 AI 이미지 생성으로 만들었습니다. 그림마다 어느 도구로 만들고 어떻게 손봤는지 아래에 적었습니다.

- 영상: https://youtu.be/xdjCyGcwCdg
- 공개일: 2026-11-10 (한국 시각)
- 그림 수: 174

## 그림과 출처

| 파일 | 무엇으로 만들었나 | 어떻게 손봤나 |
|---|---|---|
| `evidence/` `badcoat.png`, `badeyes.png`, `badlegs.png` | **문제 캡처**. 사용자가 Codex 작업 중 문제를 짚으려고 붙여 넣은 화면 캡처입니다. 전신 이모티콘 작업 때 나온 승인되지 않은 생성 그림(OpenAI Codex 내장 image_gen)이고, 초록 상자 표시가 들어 있습니다. 어느 생성 파일인지는 대조하지 않았습니다. | 캡처를 그대로 썼습니다(RGB로 저장). |
| `evidence/` `stick.png` | **탄막 편 승인 기준 장**. 사용자가 승인 원본 01번을 OpenAI Codex의 내장 image_gen으로 고쳐 만든, 게임 조종기를 쥔 두루입니다(2026-11-05 승인). | 투명 여백을 잘라 내고 1000px로 맞췄습니다(`prep_art.py`). |
| `gif/` `g01_0.png`, `g01_1.png`, `g01_2.png` … `g35_5.png` (126) | **승인 GIF 17종의 낱장**. 사용자가 2026-10-18~21에 OpenAI Codex의 내장 이미지 생성 도구(image_gen)로 자세 그림을 만들고, 고르고, 시간을 맞춰 엮은 GIF입니다. 낱장마다 어느 생성본에서 왔는지는 따로 남은 기록이 없습니다. | GIF를 낱장으로 풀고 투명 여백을 잘라 냈습니다(`prep_art.py`). |
| `gif/` `gmid_0.png`, `gmid_1.png`, `gmid_2.png`, `gmid_3.png`, `gmid_4.png`, `gmid_5.png`, `gmid_6.png`, `gmid_7.png` | **박수 GIF 이전 판**. 2026-10-21에 승인했다가 나중에 원래 그림에 가까운 동작으로 바꾼 박수 GIF의 낱장입니다. 사용자의 OpenAI Codex 작업(내장 image_gen)에서 나왔습니다. | GIF를 낱장으로 풀고 투명 여백을 잘라 냈습니다(`prep_art.py`). |
| `mosaic/` `danmaku.png`, `rhythm.png` | **여러 장을 모은 격자**. 코드로 여러 장을 한 장 격자에 모았습니다. danmaku.png는 탄막 편 두루 41장, rhythm.png는 리듬게임 동작 48장입니다. 들어간 그림은 모두 사용자가 OpenAI Codex의 내장 image_gen으로 만든 것입니다. | 격자로 모을 때 그림마다 투명 여백을 자르고 칸 크기에 맞췄습니다(`prep_art.py`). |
| `stills/` `01.png`, `01_hi.png`, `02.png` … `32.png` (34) | **정식 승인본 원본 32종**. 사용자가 2026-10-18에 OpenAI Codex의 내장 image_gen으로 만들었습니다. 주문 프롬프트 기록이 있습니다. | 투명 여백을 잘라 내고 크기를 맞췄습니다(`prep_art.py`, 정지 그림 460px, `_hi`는 1000px). |

## 여기 없는 것

밤 작업실 배경은 두루가 아니라서 넣지 않았습니다. 이 폴더는 영상의 최종 렌더 코드를 다시 실행해 실제로 그려진 그림 파일을 기록하고, 그중 두루가 나오는 그림만 골라 담았습니다. 썸네일, 배경, 소품, 글자 그림은 넣지 않았습니다.

## 라이선스

CC0 1.0. 출처 표시 없이 쓰고 고치고 다시 나눠도 됩니다. 저장소 맨 위 `LICENSE`를 보세요.

## English

> **These pictures were made with AI.** Every Duru picture in this folder was made with AI image generation. Below is which tool made each group and how it was edited.

- Video: https://youtu.be/xdjCyGcwCdg ("I Only Asked AI to Make My Character Clap, and It Became Someone Else")
- Published: 2026-11-10 (KST)
- Pictures: 174

### Pictures and sources

| Files | How it was made | Edits |
|---|---|---|
| `evidence/` `badcoat.png`, `badeyes.png`, `badlegs.png` | **Problem screenshots**. Screenshots the user pasted into a Codex session to point out problems. They show unapproved drawings generated during the full-body emoticon work (OpenAI Codex, built-in image_gen), with green boxes drawn on them. They were not matched to specific generated files. | Used as captured (saved as RGB). |
| `evidence/` `stick.png` | **Approved reference for the bullet-hell episode**. Approved original #01, edited by the user with the built-in image_gen tool of OpenAI Codex into Duru holding a game controller (approved 2026-11-05). | Transparent margins were cropped and the size was fitted to 1000 px (`prep_art.py`). |
| `gif/` `g01_0.png`, `g01_1.png`, `g01_2.png` … `g35_5.png` (126) | **Frames of the 17 approved Duru GIFs**. The user built these GIFs on 2026-10-18 to 10-21 from pose drawings made with the built-in image tool (image_gen) of OpenAI Codex, then picked the frames and set the timing. There is no record of which generated file each frame came from. | The GIF was split into frames and the transparent margins were cropped (`prep_art.py`). |
| `gif/` `gmid_0.png`, `gmid_1.png`, `gmid_2.png`, `gmid_3.png`, `gmid_4.png`, `gmid_5.png`, `gmid_6.png`, `gmid_7.png` | **Earlier clap GIF**. Frames of the clap GIF approved on 2026-10-21 and later replaced by a motion closer to the original drawing. It came from the user's OpenAI Codex work (built-in image_gen). | The GIF was split into frames and the transparent margins were cropped (`prep_art.py`). |
| `mosaic/` `danmaku.png`, `rhythm.png` | **Grids of many drawings**. Grids assembled in code. danmaku.png holds the 41 bullet-hell Duru frames and rhythm.png the 48 rhythm-game poses. Every drawing in them was made by the user with the built-in image_gen tool of OpenAI Codex. | Each drawing was cropped to its content and fitted to a grid cell (`prep_art.py`). |
| `stills/` `01.png`, `01_hi.png`, `02.png` … `32.png` (34) | **The 32 approved originals**. Made by the user on 2026-10-18 with the built-in image_gen tool of OpenAI Codex. The prompts were kept. | Transparent margins were cropped and the size was fitted (`prep_art.py`, 460 px for stills, 1000 px for `_hi`). |

### Not included

The night-studio background is not Duru, so it is not here. This folder was filled by running the video's final render code again, recording every picture file it drew, and keeping only the ones that show Duru. Thumbnails, backgrounds, props and text images are not included.

### License

CC0 1.0. Use, change and share without credit. See `LICENSE` at the top of the repository.


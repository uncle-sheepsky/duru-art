# 리듬게임 노트에 디테일이 필요한 이유

> **AI로 만든 그림입니다.** 이 폴더의 두루 그림은 모두 AI 이미지 생성으로 만들었습니다. 그림마다 어느 도구로 만들고 어떻게 손봤는지 아래에 적었습니다.

- 영상: https://youtu.be/Jyqc6ACqBbc
- 공개일: 2026-11-10 (한국 시각)
- 그림 수: 2

## 그림과 출처

| 파일 | 무엇으로 만들었나 | 어떻게 손봤나 |
|---|---|---|
| `cels/` `look_right.png`, `point_left.png` | **Claude가 주문한 그림**. Claude가 OpenAI Codex CLI(`codex exec -m gpt-6-astra`)에 주문해 내장 image_gen이 만들었습니다. 주문문(prompts)과 생성 기록(gen_log.json)이 있고, 승인된 두루 그림을 참조로 넣었습니다. | 뿔 폭을 기준으로 크기를 맞추고 발 위치를 맞춰 같은 크기 칸에 놓았습니다(`prep_data.py`). |

## 여기 없는 것

설명용 그림과 끝 화면의 본편 썸네일은 넣지 않았습니다. 이 폴더는 영상의 최종 렌더 코드를 다시 실행해 실제로 그려진 그림 파일을 기록하고, 그중 두루가 나오는 그림만 골라 담았습니다. 썸네일, 배경, 소품, 글자 그림은 넣지 않았습니다.

## 라이선스

CC0 1.0. 출처 표시 없이 쓰고 고치고 다시 나눠도 됩니다. 저장소 맨 위 `LICENSE`를 보세요.

## English

> **These pictures were made with AI.** Every Duru picture in this folder was made with AI image generation. Below is which tool made each group and how it was edited.

- Video: https://youtu.be/Jyqc6ACqBbc ("Same Screen. Why Is One of Them Fake?")
- Published: 2026-11-10 (KST)
- Pictures: 2

### Pictures and sources

| Files | How it was made | Edits |
|---|---|---|
| `cels/` `look_right.png`, `point_left.png` | **Drawings ordered by Claude**. Ordered by Claude through OpenAI Codex CLI (`codex exec -m gpt-6-astra`) and made by its built-in image_gen tool. The prompts and the generation log (gen_log.json) were kept, and approved Duru drawings were given as references. | Scaled to a common horn width and placed on a same-size canvas with the feet lined up (`prep_data.py`). |

### Not included

The explainer images and the main video's thumbnail on the last screen are not here. This folder was filled by running the video's final render code again, recording every picture file it drew, and keeping only the ones that show Duru. Thumbnails, backgrounds, props and text images are not included.

### License

CC0 1.0. Use, change and share without credit. See `LICENSE` at the top of the repository.


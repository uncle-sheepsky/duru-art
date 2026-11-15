# AI 생성 고지 (AI-generated content notice)

이 저장소의 두루 그림은 모두 AI 이미지 생성으로 만든 그림이거나, 그렇게 만든 그림을 코드로 손본 것입니다. 코드로 새로 그린 두루 그림은 없습니다.

## 무엇으로 만들었나

1. **OpenAI 이미지 모델 (OpenAI Codex의 이미지 생성 도구 image_gen).** 대부분의 그림이 여기에 해당합니다. 사용자가 Codex에서 직접 만든 그림(정식 승인 원본 32종, GIF 17종, 탄막 편 45프레임, 리듬게임 편 동작 48장, 전신 이모티콘 17종, 「WHAT YOUR COLOR.」 그림)과, Claude가 Codex CLI(`codex exec -m gpt-6-astra`)에 주문한 그림(메이킹 영상들의 동작 그림)이 있습니다. 주문문과 생성 기록은 제작 폴더에 남아 있고, 이 저장소에는 넣지 않았습니다.
2. **파일 안의 C2PA 기록.** 손대지 않은 생성 원본 23개에는 OpenAI가 서명한 C2PA 기록(softwareAgent ChatGPT, gpt-image, digitalSourceType trainedAlgorithmicMedia)이 그대로 남아 있습니다. 크기를 바꾸거나 자른 파일에는 이 기록이 없습니다.
3. **한 장씩 대조하지 못한 그림.** 전신 이모티콘 17종 판은 원본 파일이 지워져서, GIF 17종 낱장은 낱장별 생성 기록이 없어서, 어느 생성 파일에서 왔는지 한 장씩 맞춰 보지 못했습니다. 두 묶음 모두 사용자의 OpenAI Codex 작업에서 나왔다는 작업 기록은 있습니다.

## 코드로 손본 것

크기 맞춤, 발 위치 맞춤, 투명 여백 자르기, 스티커용 흰 테두리와 그림자, 한 장을 시간에 따라 휘게 만든 움직임(「흐물 두루」), 여러 장을 한 격자에 모으기를 코드로 했습니다. 편마다 무엇을 했는지는 편 폴더 README에 있습니다. 「문제 캡처」 그림의 초록 상자는 캡처 원본에 이미 있던 표시입니다.

## C2PA 기록이 남아 있는 파일

- `episodes/2026-11-03_cfq1DbHfPcg_bgm-free-making/melty-source.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/calm_cel01.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/calm_cel03.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/lift_cel01.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/lift_cel02.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/lift_cel03.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/lift_cel04.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel01.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel02.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel03.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel04.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel05.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/motion/tickle_cel06.png`
- `episodes/2026-11-14_2T3t7NSwQis_what-your-color-longform/user/clapwait_cel01.png`
- `episodes/2026-11-14_Kh3IdNJEvVM_what-your-color-short/user/clapwait_cel01.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/duru.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/emo/01_wave.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/emo/10_proud.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/emo/13_surprise.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/emo/19_awkward.png`
- `episodes/2026-11-14_ovsEGLaMZf4_colorkit-making/emo/20_question.png`
- `episodes/2026-11-14_rbOFAsWVPlo_web-howto-duru-melon/duru.png`
- `episodes/2026-11-14_uidwYAxRNCA_one-picture-in-making-web/duru.png`

## English

Every Duru picture here was made with AI image generation, or is such a picture edited in code. None of the Duru pictures were newly drawn in code.

1. **OpenAI image model (the image_gen tool inside OpenAI Codex).** Most pictures. Some were made by the user directly in Codex (the 32 approved originals, the 17 GIFs, the 45 bullet-hell frames, the 48 rhythm-game poses, the 17 full-body emoticons, the "WHAT YOUR COLOR." drawings). Others were ordered by Claude through Codex CLI (`codex exec -m gpt-6-astra`) for the making-of videos. The prompts and generation logs stay in the production folders and are not part of this repository.
2. **C2PA records inside the files.** 23 unedited generated files still have the OpenAI-signed C2PA record (softwareAgent ChatGPT, gpt-image, digitalSourceType trainedAlgorithmicMedia). Files that were resized or cropped no longer have it.
3. **Not matched one by one.** The full-body emoticon set (original files deleted) and the frames of the 17 GIFs (no per-frame generation record) could not be traced to individual generated files. Work records show both came from the user's OpenAI Codex work.

Edits done in code: resizing, lining up the feet, cropping transparent margins, white sticker borders and shadows, bending one drawing over time ("melty Duru"), and collecting many drawings into one grid. Each episode folder's README says which edits apply. The green boxes in the "problem screenshots" were already in the original captures.

The list of files that still have a C2PA record is above.


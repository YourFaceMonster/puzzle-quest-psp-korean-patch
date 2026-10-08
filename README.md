# 퍼즐 퀘스트 PSP 한글화 패치

PSP판 *Puzzle Quest: Challenge of the Warlords*의 한글화 패치입니다. **NDS판 패치와는 별개**입니다.

현재 배포 버전: **v0.9.0**  
한글화: **YFM**

## 다운로드

`PuzzleQuest_PSP_KOR_v0.9.0_patch.zip`에 xdelta 패치와 적용 안내가 들어 있습니다. 이 저장소에는 게임 ISO가 포함되지 않습니다.

## 적용 방법

기준 원본은 `2ch-s11pq.iso`입니다. 원본 파일의 SHA-256이 아래 값과 일치하는지 먼저 확인하세요.

```text
D0CF1F2699FD9AD5F25AB9BEA8BD1F1DED48BC3661D8D631A780204C1C405A26
```

[xdelta3](https://github.com/jmacd/xdelta/releases)를 준비하고 원본 ISO와 패치를 같은 폴더에 둔 다음 실행합니다.

```text
xdelta3.exe -d -s "2ch-s11pq.iso" "PuzzleQuest_PSP_KOR_v0.9.0_2ch-s11pq.xdelta" "PuzzleQuest_PSP_KOR_v0.9.0.iso"
```

완성 ISO의 SHA-256:

```text
6BD15AD4F07461B107EF3CD4C08967E0C67DBE8C4BFDD40C06021EA6C4B5A65B
```

패치 파일의 SHA-256:

```text
A3E7CCC63D3E6D5053E7F4D91CA903CB3DED94C95B794553384244875D98E083
```

이 패치는 위 원본 ISO를 기준으로 만들고 복원 검증했습니다. 다른 판본의 ISO에서는 결과를 보장하지 않습니다.

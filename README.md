# ⏱️ 럭키 세븐 스탑워치 (stopwatch-game)

> **축제 부스 경품 추첨용 단일 HTML 미니게임**

스탑워치를 멈춘 시각에 숫자 **7이 몇 개 들어 있는지**로 경품 등급이 정해집니다.
운영진이 제비뽑기 통을 준비하지 않아도 되고, 결과가 화면에 크게 뜨니 줄 서 있는
사람들도 같이 보게 되는 부스용 게임입니다.

- **7의 개수 → 경품 등급** (선물 · 젤리 · 도장 · 꽝) 자동 판정
- **스페이스 / 엔터 한 키로 진행** — idle → 시작 → 정지 → 리셋. 부스 담당자가 마우스를 잡을 필요 없음
- **당첨 이력 보드** — `localStorage` 에 기록해 부스 운영 중 경품 소진량 파악
- `performance.now()` + `requestAnimationFrame` 기반 계측, `tabular-nums` 로 자릿수 흔들림 제거
- 의존성·빌드·서버 없음 — `stopwatch-game.html` **한 파일이 전부**

## 실행

```bash
git clone https://github.com/noeyeas/stopwatch-game.git
# stopwatch-game.html 을 브라우저로 열면 끝
```

<p align="center">
  <img src="./assets/header.svg" width="100%" alt="정회광 · Proactive." />
</p>

<p align="center">
  <a href="https://trip-pups.com"><img src="https://img.shields.io/badge/TripPups-181717?style=for-the-badge&amp;logo=googlemaps&amp;logoColor=white" alt="TripPups" /></a>
  <a href="https://hackon.kr"><img src="https://img.shields.io/badge/HACK%3AON-181717?style=for-the-badge&amp;logoColor=white" alt="해커온" /></a>
  <a href="https://github.com/Sweet-Butters/mail-notifier"><img src="https://img.shields.io/badge/First_Project-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="첫 프로젝트" /></a>
</p>

---

## 👋 About Me

**정회광 · 연세대학교 화학과**

TripPups를 운영하고, AI 강의를 만들고, 해커톤을 엽니다. 최근에는 가짜연구소에서 피지컬 AI도 배우고 있습니다.

**Proactive. 필요한 기회를 직접 만드는 것이 제 강점입니다.**

서강대 교수님께 먼저 인턴을 제안했고, ElevenLabs에 콜드 메일을 보내 해커톤 후원을 받았습니다. 처음 만든 건 기다리던 메일을 휴대폰으로 알려주는 작은 도구였습니다. 지금도 제 생활과 일에서 필요한 것을 직접 만들고 있습니다.

## 🧭 What I Work On

| 분야 | 하고 있는 일 |
| :--- | :--- |
| 🛠 AI 서비스 | 메일 알림 도구, 여행 예약 MCP, 롱폼 영상 편집기 개발 |
| 🌏 창업 | 외국인의 한국 로컬 경험을 연결하는 TripPups 운영 |
| 🤝 커뮤니티 | AI 해커톤 해커온 기획·운영, 4050 현업자 AI 모임 |
| 🤖 피지컬 AI | Simulation Asset의 에셋 선정·DB 시각화, Reachy Mini 현장 활용 |

---

## 🧰 Tools I Use

### AI & Automation

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat&amp;logo=claude&amp;logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat&amp;logo=googlegemini&amp;logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MCP-111111?style=flat&amp;logo=modelcontextprotocol&amp;logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/Higgsfield-181717?style=flat" alt="Higgsfield" />
</p>

### APIs & Workflow

<p>
  <img src="https://img.shields.io/badge/Gmail_API-EA4335?style=flat&amp;logo=gmail&amp;logoColor=white" alt="Gmail API" />
  <img src="https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat&amp;logo=telegram&amp;logoColor=white" alt="Telegram Bot" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&amp;logo=github&amp;logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Discord-5865F2?style=flat&amp;logo=discord&amp;logoColor=white" alt="Discord" />
  <img src="https://img.shields.io/badge/Notion-000000?style=flat&amp;logo=notion&amp;logoColor=white" alt="Notion" />
</p>

---

## 📌 Featured Projects

| 프로젝트 | 시작한 이유 | 직접 맡은 일 · 결과 | 링크 |
| :--- | :--- | :--- | :--- |
| **📬 Mail Notifier**<br>첫 프로젝트 | 대회·면접 결과를 기다리며 메일함을 계속 확인하던 불편 | Gmail 조회 → Gemini 분류 → 텔레그램 알림. GitHub Actions로 주기적 실행 | [GitHub](https://github.com/Sweet-Butters/mail-notifier) |
| **🌏 TripPups** | 외국인이 직접 예약하기 어려운 한국 로컬 경험 | 8인 팀의 기술 구현·사업모델·외국인 커뮤니티. 카카오 MCP 심사 통과, 팀에서 약 20곳의 입점 희망 확인 | [서비스](https://trip-pups.com) |
| **🎬 채널감** | 인강·SNS·행사 영상을 다루며 반복해서 겪은 편집 작업 | 팀장으로 AI 파이프라인·검증·사업·유통 담당. 연세 AI 창업 해커톤 예선 1위·TOP 10 | [수상 내역](#-achievements) |
| **🎾 난테니스** | 교수님께 필요한 테니스 모임 앱 제작 | 서강대 경영학과 교수 연구실 인턴으로 앱과 AI 콘텐츠 제작 | [활동 내역](#-experiences) |

<details>
<summary><b>📬 첫 프로젝트 이야기 — 메일함을 계속 새로고침하다가</b></summary>

대회와 면접 결과의 발표 시각이 명확하지 않아 하루에도 여러 번 메일함을 확인했습니다. 기다리는 대신, 관심 있는 메일이 오면 휴대폰으로 알려주는 도구를 만들었습니다.

```text
GitHub Actions cron
        ↓
     Gmail API
        ↓
 Gemini로 메일 맥락 분류
        ↓
 Telegram Bot 알림
```

Python으로 각 API를 연결했습니다. Gemini가 메일 내용을 보고 기다리던 결과나 관심 있는 내용인지 판단하고, 해당하는 메일만 텔레그램으로 보냅니다. 제 일상의 작은 불편을 직접 만든 도구로 해결한 첫 경험입니다.

[코드와 실행 방법 →](https://github.com/Sweet-Butters/mail-notifier)

</details>

---

## 🏆 Achievements

- **1,800명 중 20등** · SCPC 2026 AI 트랙, 삼성SDS 기술 발표
- **최우수상** · 서강대 AI 창업 캠프, 팀 상금 100만 원
- **예선 1위 · TOP 10** · 연세 캠퍼스타운 AI 스타트업 해커톤, 채널감
- **2기 선정** · 모두의 창업, TripPups
- **서류 심사 통과** · 연세대학교 학생창업경진대회 왕중왕전, 채널감

---

## 💼 Experiences

- **해커온 HACK:ON** · AI 해커톤 기획·모집·후원 유치·현장 운영
  광고비 없이 공모전 사이트에 직접 게시를 요청해 모집 정보를 확산하고 **40명을 선발**했습니다. ElevenLabs에 콜드 메일을 보내 **880달러 상당 이용권**을 받았고, Lovable에서도 **40명분 크레딧**을 후원받았습니다. [hackon.kr](https://hackon.kr)

- **연세 프리미엄 AI 인강 5기** · AI 강의 제작
  직접 활용한 AI 도구와 구현 경험을 강의 콘텐츠로 정리했습니다.

- **서강대 경영학과 교수 연구실 인턴** · 직접 인턴 제안
  서강대 동업자와 창업 프로그램에 참여하며 교수님께 인턴을 요청했습니다. AI 콘텐츠와 테니스 모임 앱 난테니스를 만들며 경영·창업을 배웠습니다.

- **AI 당근 모임** · 4050 현업자 대상 AI 모임 운영
  현업의 문제와 업무 지식을 배우고자 초기에는 사비로 모임을 열었습니다. AI 활용법을 알려드리며 영상편집자·학원 팀장·건설 감리자·쇼핑몰 운영자들의 일을 배웠습니다. 이후 쇼핑몰의 유료 의뢰를 받아 Claude Code와 힉스필드로 모델 이미지 제작을 도왔습니다.

- **가짜연구소 13기** · Simulation Asset 프로젝트
  피지컬 AI 현직자·공학 전공자들과 함께 **에셋 선정·DB 시각화**를 맡고 있습니다. Reachy Mini와 Micro Duck을 구입하고, Micro Duck 배송 전에 시뮬레이션을 먼저 배우고자 지원했습니다.

- **Reachy Mini 현장 활용**
  해커온 안내·발표 타이머와 TripPups 부스 소개에 활용했습니다.

---

<p align="center">
  <b>Proactive.</b><br />
  필요한 게 있으면 직접 배우고 만들어 적용합니다.
</p>

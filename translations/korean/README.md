> 이 문서는 [README](../../README.md)의 한국어 번역본입니다. 내용이 다를 경우 영어 원문이 기준입니다.

# 90일 사이버보안 학습 계획

## 📚 목차

- [소개](#-소개)
- [목표와 대상](#-목표와-대상)
- [시작하기](#-시작하기)
- 일차별 학습 계획
  - [1-7일차: Network+](#1-7일차-network)
  - [8-14일차: Security+](#8-14일차-security)
  - [15-28일차: 리눅스](#15-28일차-리눅스)
  - [29-42일차: 파이썬](#29-42일차-파이썬)
  - [43-56일차: 트래픽 분석](#43-56일차-트래픽-분석)
  - [57-63일차: Git](#57-63일차-git)
  - [64-70일차: ELK](#64-70일차-elk)
  - [71-77일차: 클라우드 플랫폼 (GCP, AWS, Azure)](#71-77일차-클라우드-플랫폼)
  - [78-84일차: 복습과 실습](#78-84일차-복습과-실습)
  - [85-90일차: 해킹](#85-90일차-해킹)
- 보너스: 취업하기
  - [91-92일차: 한 장짜리 이력서](#91-92일차-한-장짜리-이력서)
  - [93-95일차: 어디에, 어떻게 지원할까](#93-95일차-어디에-어떻게-지원할까)
- [기여자](#-기여자)

## 📘 소개

**90일 사이버보안** 챌린지에 오신 것을 환영합니다!  
이 저장소는 사이버보안의 탄탄한 기초를 쌓을 수 있도록 설계된, 스스로 속도를 조절하며 진행하는 90일 학습 계획을 제공합니다. 이 분야에 처음 입문하려는 초보자든 실력을 다듬고 싶은 현업자든, 엄선한 자료와 실습 과제, 학습 자료를 폭넓게 활용할 수 있습니다.

일차별 모듈은 다음과 같은 핵심 주제와 심화 주제를 다룹니다.

- 네트워크 기초 (Network+)
- 보안 원칙 (Security+)
- 리눅스 기초와 셸 스크립팅
- 보안 작업을 위한 파이썬 프로그래밍
- 트래픽 분석과 패킷 검사
- Git을 이용한 버전 관리
- ELK 스택을 활용한 SIEM 도구와 로그 분석
- GCP, AWS, Azure 클라우드 보안
- 모의해킹과 윤리적 해킹
- 취업하기: 한 장짜리 이력서와 career-ops를 활용한 AI 기반 구직 파이프라인

매일 실천할 수 있는 과제, 튜토리얼, 읽을거리로 구성되어 있어 꾸준히 진도를 나갈 수 있습니다. 전체 자료 목록은 [`learn.md`](../../learn.md)를 참고하세요.

## 🎯 목표와 대상

### 📌 목표

이 90일 계획의 주된 목표는 학습자가 다음을 이루도록 돕는 것입니다.

- 사이버보안의 핵심 개념과 실무에 대한 탄탄한 기초 쌓기
- 매일의 실습과 실제 도구를 통해 직접 경험 쌓기
- CompTIA Network+, Security+ 같은 자격증에 필요한 기술 역량 기르기
- 네트워크 보안, 시스템 하드닝, 클라우드 보안, 스크립팅, 윤리적 해킹 등 주요 분야 탐색하기
- 90일 동안 꾸준한 학습 습관을 들여 오래 기억하고 계속 성장하기

이 과정을 마치면 다양한 사이버보안 도구, 개념, 기법을 자신 있게 다룰 수 있게 될 것입니다.

### 👥 대상 독자

이 저장소는 다음과 같은 분들께 잘 맞습니다.

- 신입 직무나 자격증을 준비하는 **사이버보안 지망생**
- 보안 분야로 경력을 전환하려는 **IT 실무자**
- 컴퓨터공학, 정보시스템, 네트워크공학을 공부하는 **학생**
- 체계적이고 포괄적인 학습 계획을 찾는 **독학자**
- 안전한 인프라와 위협 탐지를 더 깊이 이해하고 싶은 **개발자와 DevOps 엔지니어**
- 실제 환경에서 사이버보안이 어떻게 돌아가는지 **궁금한 누구나**

사전 경험은 필요 없지만, 컴퓨터나 네트워크, 프로그래밍에 대한 기본적인 이해가 있으면 도움이 됩니다.

## 🚀 시작하기

이 계획이 처음이라면 먼저 아래 내용을 읽고 [1일차](#1-7일차-network)로 넘어가세요.

- **시간 계획:** 하루 1~2시간 집중하는 것을 목표로 하세요. 일차 번호는 기준일 뿐 마감이 아니므로, 한 주제에 더 오래 머물러도 괜찮습니다.
- **순서 지키기:** 1~28일차(네트워크, 보안 기초, 리눅스)는 이후 모든 내용의 기초입니다. 해킹으로 먼저 건너뛰지 마세요.
- **자격증은 선택:** Network+와 Security+ 재생목록은 필요한 개념을 가르쳐 줍니다. 이 계획을 따르거나 첫 직장을 얻기 위해 꼭 시험을 볼 필요는 없습니다.
- **진도 기록하기:** 이 저장소를 포크(fork)하거나 계획을 노트 파일에 복사해 두고, 하루를 마칠 때마다 체크하세요.
- **모두 무료:** 유료로 막혀 있는 자료가 있다면 같은 섹션이나 [`learn.md`](../../learn.md)에 있는 대안을 이용하세요.
- **질문이나 스터디 친구 찾기:** [GitHub Discussions](https://github.com/farhanashrafdev/90DaysOfCyberSecurity/discussions)를 이용하세요. 이슈(Issues)는 깨진 링크와 내용 수정용입니다.
- **다른 언어가 필요하다면?** 원문 README의 [Translations](../../README.md#translations)를 참고하세요.

## 1-7일차: Network+
- Professor Messer의 [N10-009 재생목록](https://youtube.com/playlist?list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&si=3rUsqmrdsNK3izh6) 영상을 시청하세요.
- 관련 연습 문제나 실습을 풀어 보세요.

## 8-14일차: Security+

### Professor Messer 강의를 강력히 추천합니다:
- Professor Messer의 [SY0-701 재생목록](https://www.youtube.com/watch?v=KiEptGbnEBc&list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv) 영상을 시청하세요.

### 다른 대안:
- Pete Zerger의 [SY0-701 재생목록](https://www.youtube.com/watch?v=1E7pI7PB4KI&list=PL7XJSuT7Dq_UDJgYoQGIW9viwM5hc4C7n)을 시청하세요.

### 추가 연습:
- 관련 연습 문제나 실습을 풀어 보세요.

## 15-28일차: 리눅스
- Linux Journey 튜토리얼을 둘러보세요: https://linuxjourney.com/
- Cisco NetAcad의 Linux Unhatched를 수료하세요: https://www.netacad.com/courses/linux-unhatched
- LabEx의 리눅스 실습(Hands-on Labs)을 모두 완료하세요: https://labex.io/free-labs/linux


## 29-42일차: 파이썬
- freeCodeCamp의 [Learn Python - Full Course for Beginners](https://www.youtube.com/watch?v=rfscVS0vtbw)를 시청하세요 (무료, 약 4.5시간).
- Codecademy의 Learn Python 트랙을 완료하세요 (무료 등급으로 기초를 배울 수 있고, 뒷부분 강의는 구독이 필요합니다): https://codecademy.com/learn/learn-python
- Python.org: https://www.python.org/
- Real Python: https://realpython.com/
- Talk Python to Me: https://talkpython.fm/
- "Learn Python the Hard Way" 읽기: https://learnpythonthehardway.org
- HackerRank Python: https://www.hackerrank.com/domains/python
- LabEx Learn Python by Labs: https://labex.io/free-labs/python

### 유튜브 강의:
- https://www.youtube.com/watch?v=egg-GoT5iVk&ab_channel=TheCyberMentor


## 43-56일차: 트래픽 분석
- Wireshark University 과정을 수강하세요: https://www.wireshark.org/#educationalContent
- guru99의 Wireshark 튜토리얼을 따라 해 보세요: https://guru99.com/wireshark-tutorial.html
- DanielMiessler의 TCPdump 튜토리얼을 읽어 보세요: https://danielmiessler.com/study/tcpdump/
- Suricata 빠른 시작 가이드를 읽어 보세요: https://docs.suricata.io/en/latest/quickstart.html

### 유튜브:
- 초보자를 위한 Wireshark 튜토리얼 시리즈 https://www.youtube.com/watch?v=NjvR4LmwcMU&list=PLBf0hzazHTGPgyxeEj_9LBHiqjtNEjsgt&pp=iAQB
- Suricata Network IDS/IPS https://www.youtube.com/watch?v=S0-vsjhPDN0&pp=ygUhIFN1cmljYXRhIElEUy9JUFMgU3lzdGVtIFR1dG9yaWFs

## 57-63일차: Git
- Codecademy의 Git for Beginners 과정을 완료하세요: https://codecademy.com/learn/learn-git
- Git Immersion 튜토리얼을 따라 해 보세요: http://gitimmersion.com
- Try Git: https://try.github.io
- [Learn Git Branching](https://learngitbranching.js.org/)으로 Git 명령어를 대화형 시뮬레이터에서 연습하세요.

## 64-70일차: ELK
- Logz.io의 Complete Guide to the ELK Stack을 따라 해 보세요: https://logz.io/learn/complete-guide-elk-stack/
- 공식 문서로 Elastic Stack을 시작해 보세요: https://www.elastic.co/docs/get-started

## 71-77일차: 클라우드 플랫폼

**아무 플랫폼이나 하나만 골라도 충분합니다.**

### GCP:
- GCP 시작하기(Getting Started) 자료를 살펴보세요: https://cloud.google.com/getting-started/
- Google Cloud Platform 문서: https://cloud.google.com/docs/
- Google Cloud Platform 블로그: https://cloud.google.com/blog/
- Google Cloud Platform 커뮤니티: https://cloud.google.com/community/
- [Google Cloud Skills Boost](https://www.cloudskillsboost.google)에서 실습 과제에 도전해 보세요.

### AWS
- AWS 시작하기 리소스 센터를 살펴보세요: https://aws.amazon.com/getting-started/
- AWS 튜토리얼을 둘러보세요: https://aws.amazon.com/tutorials/
- [AWS Cloud Quest](https://aws.amazon.com/training/digital/aws-cloud-quest/)에서 게임처럼 실습하며 배워 보세요.


### Azure
- Azure Fundamentals를 학습하세요: https://learn.microsoft.com/en-us/training/azure/
- 샌드박스 환경이 제공되는 [Microsoft Learn Azure 실습](https://learn.microsoft.com/en-us/training/paths/azure-fundamentals/)을 완료하세요.

## 78-84일차: 복습과 실습
- 1~77일차를 다시 훑어보며 약한 부분을 복습하세요.
- TryHackMe에서 실습 과제를 풀어 보세요: https://tryhackme.com
- VirtualBox나 VMware로 홈랩(home lab)을 구축해 배운 내용을 연습하세요.
- 네트워크, 리눅스, 파이썬, 보안 개념을 함께 활용하는 작은 프로젝트를 만들어 보세요.

## 85-90일차: 해킹

- Hack the Box의 문제에 도전해 보세요: https://hackthebox.com
- Vulnhub의 취약한 머신으로 연습하세요: https://vulnhub.com
### 유튜브:
- Ethical Hacking Part 1: https://www.youtube.com/watch?v=3FNYvj2U0HM&ab_channel=TheCyberMentor
- Ethical Hacking Part 2: https://www.youtube.com/watch?v=sH4JCwjybGs&ab_channel=TheCyberMentor

## 91-92일차: 한 장짜리 이력서
- 제공된 이력서 템플릿을 활용하세요: https://bowtiedcyber.substack.com/p/killer-cyber-resume-part-ii
- 사이버보안 이력서 템플릿: https://www.indeed.com/career-advice/resumes-cover-letters/cybersecurity-resume
- Resume-Now의 사이버보안 이력서: [https://www.resume-now.com/templates/cyber-security-resume](https://www.resume-now.com/cv/templates/data-systems-administration/cyber-security-specialist)
  이 템플릿에는 요약과 학력 섹션은 물론, 기술, 자격증, 경력 섹션과 기술 역량(technical skills) 섹션도 있습니다.
- 완성한 이력서를 Markdown 파일(`cv.md`)로도 저장해 두세요. 93일차에 career-ops에서 다시 사용합니다. 15~90일차에 진행한 실습, CTF 문제, 프로젝트를 실무 경험으로 적어 두세요.

## 93-95일차: 어디에, 어떻게 지원할까
- Indeed에서 채용 공고를 검색하세요: https://indeed.com
- LinkedIn에서 기회를 찾아보세요: https://linkedin.com
- CyberSeek에서 신입 사이버보안 직무와 경력 경로를 살펴보세요: https://www.cyberseek.org/pathway.html

### career-ops로 구직 활동하기
[career-ops](https://github.com/career-ops-hq/career-ops)는 Claude Code, Codex, OpenCode, GitHub Copilot CLI, Antigravity CLI 같은 AI 코딩 CLI 안에서 동작하는 무료 오픈소스 구직 시스템입니다 ([무료 등급](https://github.com/career-ops-hq/career-ops/blob/main/docs/FREE_TIER.md), API 키 불필요). 채용 공고 URL을 붙여 넣으면 내 `cv.md`와 비교해 공고에 점수(1~5)를 매기고, ATS 친화적인 맞춤형 PDF를 만들어 주며, 모든 지원 내역을 한곳에서 관리해 줍니다. 대신 지원해 주지는 않으며, 검토와 제출은 항상 직접 합니다.

AI CLI를 사용하기 전에 `cv.md`에서 민감한 개인정보(예: 주소, 전화번호)를 지우고, 이력서 내용을 붙여 넣기 전에 해당 도구와 제공업체의 개인정보 및 데이터 보존 설정을 확인하세요.

1. **설정 (93일차):** [Node.js](https://nodejs.org)를 설치하고 [설정 가이드](https://github.com/career-ops-hq/career-ops/blob/main/docs/SETUP.md)를 훑어본 뒤 `npx @santifer/career-ops init`를 실행하세요. 좋은 보안 습관: `npx`는 최신 릴리스를 내려받아 실행하므로, 실행 전에 [릴리스 노트](https://github.com/career-ops-hq/career-ops/releases)를 확인하세요 (재현 가능한 설치를 원하면 `@santifer/career-ops@<version>`으로 버전을 고정하세요). 새로 생긴 `career-ops` 폴더에서 AI CLI를 열고 온보딩 대화를 따라가세요. 목표 직무(예: *SOC 분석가, 보안 분석가, 주니어 모의해킹 담당자*)를 알려 주면 신입 보안 직무에 맞게 평가해 줍니다.
2. **평가 (94일차):** Indeed나 LinkedIn에서 찾은 공고 10~20개를 붙여 넣으세요. 4.0/5 이상인 직무에만 지원하세요. 무작정 많이 지원하는 도구가 아니라 걸러 내는 필터로 쓰세요.
3. **지원과 준비 (95일차):** 추린 공고에 맞춰 이력서를 만들어 지원하고, 첫 통화 전에 면접 준비 모드로 STAR 사례를 정리하세요.

## 🎉 기여자

90DaysOfCyberSecurity 커뮤니티에 함께해 주셔서 감사합니다! 콘텐츠 개선을 도와주신 모든 분께 감사드립니다. 기여 방법과 전체 기여자 목록은 [원문 README](../../README.md#-contributors)에서 확인할 수 있습니다.

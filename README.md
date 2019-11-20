# 하스스톤-덱-트래커
[![Build status](https://ci.appveyor.com/api/projects/status/3wow545sjaq9ybji/branch/master?svg=true)](https://ci.appveyor.com/project/azeier/hearthstone-deck-tracker/branch/master)

하스스톤 덱트래커는 하스스톤에 적용되는 자동 덱 추적 및 덱 관리 프로그램입니다.

## 설치하기
- 요구사항:
  - 윈도우 비스타 이상의 운영체제
  - .NET Framework 4.5 이상의 버전
- [다운로드 후 설치파일 실행하기](https://hsdecktracker.net/download/).

## 커뮤니티 & 문제 제기
- [트위터에서 HDT 팔로우하기](https://twitter.com/hsdecktracker)
- 디스코드에 참여하기: [![Join HearthSim Community Discord](https://discordapp.com/api/guilds/265636998700728321/widget.png)](https://discord.gg/hearthsim)
- 자주 묻는 질문은 [여기](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/FAQ) 에서 보실 수 있습니다.
- 인터넷 방송인: [OBS와 XSplit 방송 설정하기](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/Streaming-Instructions) 와 [트위치 확장프로그램 설정](https://hsdecktracker.net/twitch/setup/) 을 읽어주세요.
- HSReplay.net 통합 완성: <support@hsdecktracker.net>로 도움 메일을 보내주세요.

## 기여하기
- [문법 작성 및 Commit/Pull Request 가이드 라인](https://github.com/HearthSim/Hearthstone-Deck-Tracker/blob/master/CONTRIBUTING.md)을 읽어주세요.
- 개발자 디스코드: [![joindeveloper#hdt](https://discordapp.com/api/guilds/195326447118712832/widget.png)](https://discord.gg/hearthsim-devs)
- 하스스톤 덱 트래커는 [HearthSim](https://hearthsim.info) 프로젝트입니다.

## 기능
인게임 오버레이 제공:

![Overlay](https://github.com/HearthSim/Hearthstone-Deck-Tracker/raw/master/raw-assets/readme/overlay.png "Overlay")

프로그램: 

![Tracker](https://github.com/HearthSim/Hearthstone-Deck-Tracker/raw/master/raw-assets/readme/hdt-ui.png "HDT UI")

- **트랙**:
  - 덱에 남아 있는 카드 또는 덱에서 뽑은 카드를 표시합니다.
  - 손 패의 수, 남은 덱의 수 및 카드를 뽑을 확률을 표시합니다.
  - 상대방이 낸 카드를 표시합니다.
  - 상대방 손 패의 수, 상대방의 남은 덱의 수 및 특정 카드를 가지고 있거나 뽑을 확률을 표시해줍니다.
  - 상대방이 각 카드를 얼마나 오래 들고 있었는지, 어떤 카드가 멀리건 되었는지, 훔치거나 손 패로 되돌아 갔는지 표시해줍니다.  
- **타이머** 를 통해 상대방과 당신의 현재 턴과 총 소모 시간을 표시해줍니다.  
- 트래커는 **당신이 사용 중인 덱을 자동으로 감지하여 선택** 시도합니다.  
- 카드 목록과 타이머는 각각 인게임에 오버레이 하거나 (상기 스크린샷) **추가 창** (Options > General > Additional Windows)으로 표시할 수 있습니다.  
- **덱 매니저**:
  - 웹 사이트에서 덱 **불러오기** : arenavalue, hearthstats, hearthpwn, hearthhead, hearthstoneplayers, tempostorm, hearthstonetopdeck 그리고 hearthnews에서 불러올 수 있습니다.  
  - 18개 덱 제한 초과하기: **하스스톤으로 내보내기**(My Decks > More...) 를 통해 덱을 저장 할 수 있습니다.
  - 덱은 사용자**태그**를 통해 필터링 할 수 있으며 이름과 날짜, 태그로 정렬할 수 있습니다.  
  - 각 덱에**메모**(My Decks > More...)를 설정할 수 있습니다.  
  - 덱의 **스크린샷**(My Decks > More...)  을 생성할 수 있습니다.
  - 당신의 덱을 XML 파일 혹은 덱 코드로 내보내 **공유**(My Decks > More...) 할 수 있습니다. 두 방식 모두 New Deck > Import를 통해 불러올 수 있습니다.  
- **알림**: 게임 혹은 턴 시작시 알림을 받으세요. (트레이 아이콘 번쩍임 혹은 하스스톤 창 팝업의 두 가지 방식)  
- **개인 맞춤**: 대부분의 모든 기능은 개별적으로 끄거나 킬 수 있습니다.
- **플러그인을 통한 확장성**: [적용 가능한 플러그인](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/Available-Plugins)
- **덱 별 통계 제공**:
  - 매 게임별 결과 제공 (승/패), 상대 정보, 게임 모드 외 풍부한 정보.
  - 상대한 직업별 승/패 비율 제공.
  - 매 게임별 상세한 정보 (뽑은 카드, 낸 카드, 기타등등...).
  - 게임 모드별 열람 가능(Options > Other).  
  - 트래킹 된 게임 기록을 통해 상대편의 덱 (일부분)을 당신의 덱으로 불러올 수 있습니다.

![Stats](https://i.imgur.com/Wke3Cuw.png "Deck stats")


## 

Copyright © [HearthSim](https://hearthsim.net). All Rights Reserved.

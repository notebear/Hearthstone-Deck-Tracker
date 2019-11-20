# 하스스톤-덱-트래커
[![Build status](https://ci.appveyor.com/api/projects/status/3wow545sjaq9ybji/branch/master?svg=true)](https://ci.appveyor.com/project/azeier/hearthstone-deck-tracker/branch/master)

하스스톤 덱트래커는 하스스톤에 적용되는 자동 덱 추적 및 덱 관리 프로그램입니다.

## 설치하기
- 요구사항:
  - 윈도우 비스타 이상의 버전
  - .NET Framework 4.5 이상의 버전
- [다운로드 후 설치파일 실행하기](https://hsdecktracker.net/download/).

## 커뮤니티 & 문제 제기
- [트위터에서 HDT 팔로우하기](https://twitter.com/hsdecktracker)
- 디스코드에 참여하기: [![Join HearthSim Community Discord](https://discordapp.com/api/guilds/265636998700728321/widget.png)](https://discord.gg/hearthsim)
- 자주 묻는 질문은 [여기](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/FAQ) 에서 보실 수 있습니다.
- 인터넷 방송인: [OBS와 XSplit 방송 설정하기](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/Streaming-Instructions) 과 [트위치 확장프로그램 설정](https://hsdecktracker.net/twitch/setup/) 을 읽어주세요.
- HSReplay.net 통합 완성: <support@hsdecktracker.net>로 도움 메일을 보내주세요.

## 기여하기
- [문법 작성 및 Commit/Pull Request 가이드 라인](https://github.com/HearthSim/Hearthstone-Deck-Tracker/blob/master/CONTRIBUTING.md)을 읽어주세요.
- 개발자 디스코드: [![joindeveloper#hdt](https://discordapp.com/api/guilds/195326447118712832/widget.png)](https://discord.gg/hearthsim-devs)
- 하스스톤덱트래커는 [HearthSim](https://hearthsim.info) 프로젝트입니다.

## Features
An in-game overlay:

![Overlay](https://github.com/HearthSim/Hearthstone-Deck-Tracker/raw/master/raw-assets/readme/overlay.png "Overlay")

The app: 

![Tracker](https://github.com/HearthSim/Hearthstone-Deck-Tracker/raw/master/raw-assets/readme/hdt-ui.png "HDT UI")

- **Tracks**:
  - Cards left in your deck or cards drawn from your deck.
  - Your handcount, deckcount and draw chances.
  - Cards played by your opponent.
  - Your opponent's handcount, deckcount and probablities of him having/drawing cards.
  - How long your opponent had each card in his hand and what cards have been mulliganed, stolen or returned.  
- **Timer** for the current turn and total time spent for you and your opponent.  
- The tracker tries to **automatically select the deck you are playing**.  
- The cards and timer can either be displayed in an overlay (see screenshot) or in **extra windows** (Options > General > Additional Windows)  
- **Deck Manager**:
  - **Import** decks from websites: arenavalue, hearthstats, hearthpwn, hearthhead, hearthstoneplayers, tempostorm, hearthstonetopdeck and hearthnews  
  - Circumvent the 18 deck limit: Saved decks can be **exported to Hearthstone**. (My Decks > More...)
  - Decks can be filtered by custom **tags** and sorted by name, date and tags.  
  - Set **notes** for each deck (My Decks > More...)  
  - Create **screenshots** of decks (My Decks > More...)  
  - **Share** your decks by exporting them as xml files or id-strings (My Decks > More...). Both can be imported via New Deck > Import.  
- **Notifications**: get notified when a game or a turn starts (either by the tray icon flashing or hearthstone popping up)  
- **Customization**: Almost every feature can be turned on/off separately.
- **Extensible via plugins**: [available plugins](https://github.com/HearthSim/Hearthstone-Deck-Tracker/wiki/Available-Plugins)
- **Stats per deck**:
  - Track the result of each game (win/loss), opponents, game mode and more
  - Win/loss rate vs each class.
  - Details for each game (cards drawn, played, etc.).
  - Select which game modes to track (Options > Other).  
  - Import your opponent's (partial) deck from a tracked game as a new deck.

![Stats](https://i.imgur.com/Wke3Cuw.png "Deck stats")


## License

Copyright © [HearthSim](https://hearthsim.net). All Rights Reserved.

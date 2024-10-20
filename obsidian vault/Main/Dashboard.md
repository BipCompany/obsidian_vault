---
cssclasses:
  - dashboard
---
# Tasks
- Цели на год: [[2024]] 
- Цели на ближайшее время: [[Октябрь]]

# Graphs

- ```tracker
searchType: tag
searchTarget: прочитал_страниц
folder: Daily
startDate: 01-Oct-2024 (280)
endDate: 31-Oct-2024 (305)
fixedScale: 0.8
line:
	title: Pages Read
	yAxisLabel: Quantity
	lineColor: #D2CDB6
	fillGap: true

- ```tracker
searchType: tag
searchTarget: проснулся
folder: Daily
startDate: 01-Oct-2024 (280)
endDate: 31-Oct-2024 (305)
fixedScale: 0.8
line:
	title: Waking Up
	yAxisLabel: Time
	lineColor: #D2CDB6
	fillGap: true
- ```tracker
searchType: tag
searchTarget: лёг_спать
folder: Daily
startDate: 01-Oct-2024 (280)
endDate: 31-Oct-2024 (305)
fixedScale: 0.8
line:
	title: Going Sleep
	yAxisLabel: Time
	lineColor: #D2CDB6
	fillGap: true

# Vault Info

- 🗄️ Recent file updates `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(6).file.link)`
- 🔖 Tagged: favorite `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(6).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`
    - Read Books: `$=dv.pages('"Books"').length`
    - Daily Notes: `$=dv.pages('"Daily"').length`
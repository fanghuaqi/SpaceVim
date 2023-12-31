---
title: SpaceVim release v0.6.0
categories: [changelog, blog]
description: "Many new features come out with v0.6.0, including c/cpp suport and code runner"
type: article
image: https://img.spacevim.org/80607319-f1ba3b80-8a67-11ea-834c-344916bcb314.png
commentsID: "SpaceVim release v0.6.0"
comments: true
---

# [Changelogs](../development#changelog) > SpaceVim release v0.6.0

## New Features

- Add c/cpp syntax file [#1188](https://github.com/SpaceVim/SpaceVim/pull/1188)
- Add NeoSolarized guide theme [#1187](https://github.com/SpaceVim/SpaceVim/pull/1187)
- Add gf support in windows for plugin manager [#1184](https://github.com/SpaceVim/SpaceVim/pull/1184)
- Add solarized guide theme [#1180](https://github.com/SpaceVim/SpaceVim/pull/1180)
- Add php runner [#1174](https://github.com/SpaceVim/SpaceVim/pull/1174)
- Add lsp support for vim8 [#1165](https://github.com/SpaceVim/SpaceVim/pull/1165)
- Add lsp support for php [#1163](https://github.com/SpaceVim/SpaceVim/pull/1163)
- add description to the DOC of golang layer [#1140](https://github.com/SpaceVim/SpaceVim/pull/1140)
- add doc of searching files to managing project [#1116](https://github.com/SpaceVim/SpaceVim/pull/1116)
- Add a new plugin for JavaScript [#1099](https://github.com/SpaceVim/SpaceVim/pull/1099)
- Add language server configurations for Haskell [#1094](https://github.com/SpaceVim/SpaceVim/pull/1094)
- Add chat config [#1085](https://github.com/SpaceVim/SpaceVim/pull/1085)
- Add runner syntax file [#1068](https://github.com/SpaceVim/SpaceVim/pull/1068)
- Add func for custom group name [#1052](https://github.com/SpaceVim/SpaceVim/pull/1052)
- Add hunks summary [#1046](https://github.com/SpaceVim/SpaceVim/pull/1046)
- Add mapping for Increase/Decrease numbers [#1039](https://github.com/SpaceVim/SpaceVim/pull/1039)
- Add signatures api [#1036](https://github.com/SpaceVim/SpaceVim/pull/1036)
- Added a new layer lsp [#1014](https://github.com/SpaceVim/SpaceVim/pull/1014)
- Add: Improve spacevim statusline [#1012](https://github.com/SpaceVim/SpaceVim/pull/1012)
- Add mappings for git blame and git log [#1009](https://github.com/SpaceVim/SpaceVim/pull/1009)
- Added a new plugin vim-jplus [#1002](https://github.com/SpaceVim/SpaceVim/pull/1002)
- Added autocmd to update status-line [#1000](https://github.com/SpaceVim/SpaceVim/pull/1000)
- Add gd for help desc buffer && fix SPC p f [#997](https://github.com/SpaceVim/SpaceVim/pull/997)
- Added a runner for Ruby language [#993](https://github.com/SpaceVim/SpaceVim/pull/993)
- Added a runner for Crystal language [#992](https://github.com/SpaceVim/SpaceVim/pull/992)
- Added language features for JavaScript [#991](https://github.com/SpaceVim/SpaceVim/pull/991)
- Added filetypes for Emmet [#990](https://github.com/SpaceVim/SpaceVim/pull/990)
- Added zsh support [#989](https://github.com/SpaceVim/SpaceVim/pull/989)
- Added Denite sources [#988](https://github.com/SpaceVim/SpaceVim/pull/988)
- Added Rust language features [#973](https://github.com/SpaceVim/SpaceVim/pull/973)
- Added Haskell runner [#972](https://github.com/SpaceVim/SpaceVim/pull/972)


## Feature Changes

- Change gitk plugin [#1131](https://github.com/SpaceVim/SpaceVim/pull/1131)


## Bug Fixs

- fix issue 1196 (tab list bug) [#1201](https://github.com/SpaceVim/SpaceVim/pull/1201)
- fix typo [#1198](https://github.com/SpaceVim/SpaceVim/pull/1198)
- Fix win project manager [#1182](https://github.com/SpaceVim/SpaceVim/pull/1182)
- Fix lua repl && add layer doc [#1155](https://github.com/SpaceVim/SpaceVim/pull/1155)
- Fix lua repl [#1149](https://github.com/SpaceVim/SpaceVim/pull/1149)
- fix spelling error for stage all files [#1139](https://github.com/SpaceVim/SpaceVim/pull/1139)
- Fix SPC f b for show bookmarks [#1125](https://github.com/SpaceVim/SpaceVim/pull/1125)
- Fix transient state api [#1124](https://github.com/SpaceVim/SpaceVim/pull/1124)
- Fix two typos. [#1108](https://github.com/SpaceVim/SpaceVim/pull/1108)
- Fix an issue occurd in ALE-enabled environment  [#1103](https://github.com/SpaceVim/SpaceVim/pull/1103)
- Fix for ctrlp with ag searcher. #1081 [#1082](https://github.com/SpaceVim/SpaceVim/pull/1082)
- Fix statusline for small windows. [#1076](https://github.com/SpaceVim/SpaceVim/pull/1076)
- Fix ycm config [#1074](https://github.com/SpaceVim/SpaceVim/pull/1074)
- Fix #1070 [#1072](https://github.com/SpaceVim/SpaceVim/pull/1072)
- Fix bot [#1063](https://github.com/SpaceVim/SpaceVim/pull/1063)
- Fix Duplicate meta descriptions [#1060](https://github.com/SpaceVim/SpaceVim/pull/1060)
- fix a syntax error of markdown table in documentation. [#1057](https://github.com/SpaceVim/SpaceVim/pull/1057)
- Fix Yggdroot/indentLine configuration [#1037](https://github.com/SpaceVim/SpaceVim/pull/1037)
- Fix typo whit -> with [#1033](https://github.com/SpaceVim/SpaceVim/pull/1033)
- Fix lint [#1030](https://github.com/SpaceVim/SpaceVim/pull/1030)
- Fix windows installation [#1029](https://github.com/SpaceVim/SpaceVim/pull/1029)
- fix mac fc-cache mkfontdir mkfontscale not exists #1016 [#1017](https://github.com/SpaceVim/SpaceVim/pull/1017)
- Fix lsp support [#1013](https://github.com/SpaceVim/SpaceVim/pull/1013)
- fix word [#1006](https://github.com/SpaceVim/SpaceVim/pull/1006)
- Fixed plugin 'vim-rtags' initialization errors [#995](https://github.com/SpaceVim/SpaceVim/pull/995)
- Fix Logger [#985](https://github.com/SpaceVim/SpaceVim/pull/985)
- Fix server error [#979](https://github.com/SpaceVim/SpaceVim/pull/979)
- Fixed Haskell layer config [#974](https://github.com/SpaceVim/SpaceVim/pull/974)
- Fixed cursor mode-sensitive issue [#971](https://github.com/SpaceVim/SpaceVim/pull/971)
- Fix capitalization on website [#970](https://github.com/SpaceVim/SpaceVim/pull/970)


## Unmarked PRs

- [SPC b t] Open Vimfiler by buffer file dir [#1200](https://github.com/SpaceVim/SpaceVim/pull/1200)
- Auto update neoinclude config [#1195](https://github.com/SpaceVim/SpaceVim/pull/1195)
- Disable welcome when load session at startup [#1191](https://github.com/SpaceVim/SpaceVim/pull/1191)
- Close #1157 [#1189](https://github.com/SpaceVim/SpaceVim/pull/1189)
- Support cwd in job [#1186](https://github.com/SpaceVim/SpaceVim/pull/1186)
- Improve plugin manager [#1179](https://github.com/SpaceVim/SpaceVim/pull/1179)
- Update project index [#1175](https://github.com/SpaceVim/SpaceVim/pull/1175)
- Update JavaScript language server [#1170](https://github.com/SpaceVim/SpaceVim/pull/1170)
- Update c layer doc [#1169](https://github.com/SpaceVim/SpaceVim/pull/1169)
- git: ignore swp files. [#1167](https://github.com/SpaceVim/SpaceVim/pull/1167)
- Update language layer [#1161](https://github.com/SpaceVim/SpaceVim/pull/1161)
- Support disable tabline [#1156](https://github.com/SpaceVim/SpaceVim/pull/1156)
- Update doc for layers [#1154](https://github.com/SpaceVim/SpaceVim/pull/1154)
- [Ready] Improve lua layer [#1147](https://github.com/SpaceVim/SpaceVim/pull/1147)
- Update blog [#1144](https://github.com/SpaceVim/SpaceVim/pull/1144)
- Update java layer [#1138](https://github.com/SpaceVim/SpaceVim/pull/1138)
- Update project key bindings [#1137](https://github.com/SpaceVim/SpaceVim/pull/1137)
- Clear cmdline after open file in flygrep [#1136](https://github.com/SpaceVim/SpaceVim/pull/1136)
- Set sign text [#1135](https://github.com/SpaceVim/SpaceVim/pull/1135)
- [WIP] Lua layer improvements [#1134](https://github.com/SpaceVim/SpaceVim/pull/1134)
- Update init.vim [#1130](https://github.com/SpaceVim/SpaceVim/pull/1130)
- Project manager [#1129](https://github.com/SpaceVim/SpaceVim/pull/1129)
- Update elixir layer [#1127](https://github.com/SpaceVim/SpaceVim/pull/1127)
- Update Home page [#1126](https://github.com/SpaceVim/SpaceVim/pull/1126)
- Update key bindings for debug layer [#1118](https://github.com/SpaceVim/SpaceVim/pull/1118)
- reimplement move text down and up [#1114](https://github.com/SpaceVim/SpaceVim/pull/1114)
- Improve guide cursor [#1113](https://github.com/SpaceVim/SpaceVim/pull/1113)
- Improve lang#ruby layer [#1112](https://github.com/SpaceVim/SpaceVim/pull/1112)
- Improve Emmet configuration [#1111](https://github.com/SpaceVim/SpaceVim/pull/1111)
- Update python layer documentation [#1110](https://github.com/SpaceVim/SpaceVim/pull/1110)
- Update wiki & website & readme [#1106](https://github.com/SpaceVim/SpaceVim/pull/1106)
- Improve implementations of tmux integration [#1105](https://github.com/SpaceVim/SpaceVim/pull/1105)
- doc: fix g:spacevim_terminal_cursor_shape default [#1095](https://github.com/SpaceVim/SpaceVim/pull/1095)
-  Add language server configuration for JavaScript [#1093](https://github.com/SpaceVim/SpaceVim/pull/1093)
- Update documents about colorscheme [#1091](https://github.com/SpaceVim/SpaceVim/pull/1091)
- [WARNING!] Implement Sass - second pull request [#1083](https://github.com/SpaceVim/SpaceVim/pull/1083)
- Mouse support in tabline [#1071](https://github.com/SpaceVim/SpaceVim/pull/1071)
- Improve Tabline [#1067](https://github.com/SpaceVim/SpaceVim/pull/1067)
- Update lang#c layer [#1065](https://github.com/SpaceVim/SpaceVim/pull/1065)
- zsh:support autocomplete [#1064](https://github.com/SpaceVim/SpaceVim/pull/1064)
- bashcomplete: can not trigger omnicomplete in some pos [#1061](https://github.com/SpaceVim/SpaceVim/pull/1061)
- Update runner [#1055](https://github.com/SpaceVim/SpaceVim/pull/1055)
- get_complete: compatiable with macOS. [#1054](https://github.com/SpaceVim/SpaceVim/pull/1054)
- bugfix start zsh error [#1050](https://github.com/SpaceVim/SpaceVim/pull/1050)
- File clipboard [#1043](https://github.com/SpaceVim/SpaceVim/pull/1043)
- Update community page [#1041](https://github.com/SpaceVim/SpaceVim/pull/1041)
- Enable syntax error/warning counts in status line [#1040](https://github.com/SpaceVim/SpaceVim/pull/1040)
- Update issue.vim [#1034](https://github.com/SpaceVim/SpaceVim/pull/1034)
- uninstall section added [#1027](https://github.com/SpaceVim/SpaceVim/pull/1027)
- Makefile: fix covimerage integration: use installed [#1026](https://github.com/SpaceVim/SpaceVim/pull/1026)
- Update autocomple layer [#1025](https://github.com/SpaceVim/SpaceVim/pull/1025)
- Run EmmetInstall on vue and eex filetypes [#1020](https://github.com/SpaceVim/SpaceVim/pull/1020)
- Update website [#1011](https://github.com/SpaceVim/SpaceVim/pull/1011)
- Version control [#1005](https://github.com/SpaceVim/SpaceVim/pull/1005)
- Auto install fonts [#998](https://github.com/SpaceVim/SpaceVim/pull/998)
- Enable deoplete in vim8 && lsp support [#994](https://github.com/SpaceVim/SpaceVim/pull/994)
- Made Markdown preview use open-browser.vim [#987](https://github.com/SpaceVim/SpaceVim/pull/987)
- Update version [#984](https://github.com/SpaceVim/SpaceVim/pull/984)
- Update travis setting [#981](https://github.com/SpaceVim/SpaceVim/pull/981)
- Server client [#976](https://github.com/SpaceVim/SpaceVim/pull/976)
- Disabled completions by deoplete [#968](https://github.com/SpaceVim/SpaceVim/pull/968)

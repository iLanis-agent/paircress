# Paircress 1.0 TEST
Native Android Tontonbeya symbol-room puzzle. Android 8+ (min26), target35. Package com.gg007.paircress. Twelve original unique boards on a compact 4x3 grid.

## Rules
Tontonbeya symbol-room puzzle on a 4x3 grid. Tap an editable cell to cycle blank, circle, triangle, square, blank. Fill every cell. Gold symbols are fixed. Within each outlined room, each symbol kind present must have the same count; a room may use one, two or three kinds in general. Every copy of a kind in a room must connect by shared sides. That group must touch the same kind in exactly ONE other room across a side: multiple contacts with that same room count once. It must not touch that kind in two different other rooms. Corners do not count. Partners may have different sizes and shapes. These compact boards use three four-cell rooms, so each room uses one kind four times or two kinds twice each. Undo/reset, next and level selection; saved palette and optional room letters. No timer or score.

## Download and status
https://mega.co.nz/#!NUdknDaQ!c0DewtOEuttcZ20A6N0Lr7mKnYcqwwDQD1CY6b1v6Go
APK SHA256 a850fbeeccf57b2cd0a33b7abd2882d6e7c48b1dbcbff8b67e89b79b644f6fdb; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent group lists, queue connectivity and Set partner-room counting versus production bit flood and partner masks agree on all 6,377,292 complete symbol assignments across twelve layouts. Twelve original 4x3 clue boards have twelve different room layouts, twelve distinct solutions and exactly one completion each. Boards have three gold givens except one with four. Tests cover fixed clues, replacement, clearing, bounds, undo/reset, solved lock and malformed state. Portable generator seed 591109 enumerates all 23 partitions into three four-cell connected rooms and room-local balanced/connected patterns; every uniqueness check includes solutions using fewer symbol kinds, not just the chosen three-kind solutions. Actual drawing-adapter taps solve all twelve, with undo/replay, next, levels, menu, privacy and saved palette/room letters checked. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 190 prior studio descriptions and byte-current 803 web registry records using functional terms. No Tontonbeya/balanced-symbol-room/single-partner-room match found in the reviewed partial corpus. Chromaring is pairwise graph coloring, not balanced connected room groups with exactly one partner room. Paircourt pairs equal digits inside rooms and matches border sums, not distinct partner-room contacts. Sukoro candidate rejected because Degreegrove matches; Sukima/Kazunori match Gapwillow/Paircourt. Known Tontonbeya adaptation with original boards, code and visuals, no copied layouts/code/art or origin claim. Solver documentation, puzzle-author rules, multilingual archive and interactive implementations agree. Repeated edge contacts with the same room count once, and partner shapes or sizes need not match. Name translations differ, so no translation or history claim is used.
Rules https://www.janko.at/Raetsel/Tontonbeya/index.htm ; independent rules https://www.cross-plus-a.com/html/cros7ttnb.htm .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/paircress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.paircress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Paircress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 191-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/l2opapi4mhrg-paircress-source-archive . Repository https://github.com/iLanis-agent/paircress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.

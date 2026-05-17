# 💬 GTA World RP Chat v1.0.0

**Author: JK Team**

> Complete RP chat system with custom HTML UI, 3D head bubbles, radio channels, police codes, weather broadcast, and more.
> Supports ESX / QBCore / QBox.

---

## Features

- Custom HTML chatbox (replaces FiveM default)
- In-game settings (font size, line spacing, fade, timestamp, display mode)
- 3D head bubbles with auto fade-out
- 40+ RP commands (/me /do /s /low /m /cw /dep /r1-r5 /tac /f /a /radio /code1-99 etc.)
- /911p police report + /ems EMS call with auto GPS
- /p postal navigation (nearest-postal integration)
- Officer down auto-alert with 5s delay
- Mask = stranger system (random 4-digit ID)
- /language multi-language speech
- /meing persistent action + /meingoff
- /pm /lowto /cw private/whisper/vehicle chat
- Auto /me for engine start/stop and weapon draw/holster (ox/qs inventory label)
- Weather broadcast (hourly + on change, day/night aware, random tips)
- ^speech syntax for inline dialogue color
- /clear to clean own chat screen
- Command hint with Tab auto-complete and arrow key history
- Typing [...] bubble indicator
- Debug mode + /chatdebug command
- Startup self-check system (10 items)

## Installation

1. Place folder in `resources/`
2. Add `ensure [your-folder-name]` to `server.cfg` (after framework)
3. Remove or comment out `ensure chat`
4. Restart server

## License

MIT

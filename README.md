# After Hours Stream Overlays

This repository contains my OBS overlays.

- **Emote Wall:** [emote-wall.html](./emote-wall.html)
- **Chat overlay:** [shark_chat (1).html](./shark_chat%20(1).html)

## Emote Wall setup

1. In OBS, add a **Browser Source**.
2. Enable **Local file** and select `emote-wall.html`.
3. Set the source width and height to match your canvas (usually 1920 × 1080).
4. Open the source and follow the Twitch sign-in prompt if it appears.

The wall supports animated Twitch emotes, BTTV, FFZ, 7TV, emoji, and configurable chat and event animations. Use [EMOTE-WALL-CONFIG.md](./EMOTE-WALL-CONFIG.md) for the available settings. The complete source is in one HTML file, so it is easy to back up or edit.

This copy is based on RealityRipple’s Emote Wall v1.9.1.4. The upstream project is at https://github.com/RealityRipple/EmoteWall and is released under the Unlicense; see [EMOTE-WALL-LICENSE](./EMOTE-WALL-LICENSE).

**Keep OAuth tokens private.** Do not commit personal tokens or credentials into this public repository.

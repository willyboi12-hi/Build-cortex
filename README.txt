CORTEX — ANDROID APK PROJECT (v1.0)

Cortex is a secure, multi-provider AI chat client with intelligent routing.
It carefully analyzes each request to pick the best model strength and thinking effort (low → max).
Chats and API keys stay on device.

WHAT'S NEW IN CORTEX
- Smart request analyzer: multi-signal scoring (code/math/reasoning/writing/complexity) chooses both the skill dimension and effort level automatically.
- Effort auto-bump: simple asks stay low/medium; architecture, long reasoning, C++ Studio or multi-part questions go high/extra/max with plan + review passes.
- Polished UI: new color system (deep indigo accent), smoother bubbles, header blur, gradient send button, subtle animations.
- Renamed throughout (package com.cortex.ai, storage key "cortex").

SECURITY
- Strict Content-Security-Policy (script hash locked)
- HTTPS only, no cleartext
- No cookies, allowBackup=false
- DomStorage only for keys/chats

BUILD
1. Private GitHub repo
2. Push this entire folder (keep .github)
3. Actions → Build Cortex APK → Run workflow
4. Download Cortex-debug-APK artifact

Sideload the APK. Debug signed for personal use.

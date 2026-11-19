Nix APK
Nix is a simple Android chat app for a personal, self-hosted LLM. It provides text chat, speech-to-text, text-to-speech, and encrypted device-local settings.

Features
Typed chat interface
Voice input using Android speech recognition
Spoken responses using Android text-to-speech
OpenAI-compatible /v1/chat/completions support
ngrok Basic Auth support
Credentials stored encrypted on the device
GitHub Actions APK builds
No secrets or credentials stored in the repository
Default configuration
Endpoint: https://barbell-parsnip-client.ngrok-free.dev/v1/chat/completions
Model: L3-8B-Stheno-v3.2-abliterated.i1-Q5_K_S
Name: Nix
Protocol: HTTPS only
Build locally
Requirements:

Android Studio
Android SDK 35
JDK 17
Gradle 8.9+
Clone and open the project in Android Studio:

git clone https://github.com/ellernate121-afk/NixAPK.git
cd NixAPK

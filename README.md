# atsushieno's live github repos

Most of Kotlin and/or C/C++ projects are maintained and I'm most likely responsive. Projects for past languages are likely ignored except for pull requests. Starting 2025, I am willing only to contribute to respectful projects that welcome bug reporting and pull requests.

I am reachable on Bluesky, Fediverse, [Android Audio Devs Discord](https://discord.gg/6AC3heft) or Discord in general (see those profile items).

## Audio Plugins For Android and related projects

[![aap-core stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-core)](https://github.com/atsushieno/aap-core)
[![aap-lv2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-lv2)](https://github.com/atsushieno/aap-lv2)
[![aap-juce stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-juce)](https://github.com/atsushieno/aap-juce)
[![android-ci-package-installer stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=android-ci-package-installer)](https://github.com/atsushieno/android-ci-package-installer) - APK installer app that installs from CI (GitHub Actions) releases and build artifacts

I have a lot more AAP projects, listed on the [AAP Wiki page](https://github.com/atsushieno/aap-core/wiki/List-of-AAP-plugins-and-hosts).

## Desktop MIDI 2.0 hacks

UAPMD: Use your favorite VST3/AU/LV2/CLAP synth plugin as a MIDI 2.0 device. It comes with its own MIT-licensed cross-platform and multi-format audio plugin hosting implementation (`remidy`).

[![uapmd stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=uapmd)](https://github.com/atsushieno/uapmd)

It is backed by semi-auto-translated C++ MIDI-CI implementation from atsushieno/ktmidi using Claude Code.

[![midicci stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=midicci)](https://github.com/atsushieno/midicci)

cmidi2: single-header realtime-safe MIDI 2.0 binary processor C library. You can also use it with [libremidi](https://github.com/celtera/libremidi) (which includes cmidi2).

[![cmidi2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=cmidi2)](https://github.com/atsushieno/cmidi2)

## Kotlin Multiplatform Music libraries and applications

[![ktmidi stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=ktmidi)](https://github.com/atsushieno/ktmidi)
[![compose-audio-controls stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=compose-audio-controls)](https://github.com/atsushieno/compose-audio-controls)
[![resident-midi-keyboard stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=resident-midi-keyboard)](https://github.com/atsushieno/resident-midi-keyboard)
[![libremidi-panama stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=libremidi-panama)](https://github.com/atsushieno/libremidi-panama)
[![alsa-javacpp stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=alsa-javacpp)](https://github.com/atsushieno/alsa-javacpp)
[![mugene-ng stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=mugene-ng)](https://github.com/atsushieno/mugene-ng)
[![augene-ng stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=augene-ng)](https://github.com/atsushieno/augene-ng)
[![kmdsp stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=kmdsp)](https://github.com/atsushieno/kmdsp)
[![kmmk stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=kmmk)](https://github.com/atsushieno/kmmk)

### Other music and misc. hacks

[![libcxx-provider stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=libcxx-provider)](https://github.com/atsushieno/libcxx-provider) - mitigate `libc++_shared.so` handling in Android NDK projects.

[![missing-dot stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=missing-dot)](https://github.com/atsushieno/missing-dot) - porting some .NET API to Kotlin (XmlReader/Writer and XLinq so far)

[mugene-guide-book](https://github.com/atsushieno/mugene-guide-book) - book sources for MML Compiler mugene guide book (Japanese)

![aqua sshot](https://raw.githubusercontent.com/atsushieno/aqua/main/aqua-lv2ui-in-action.png)

[![aqua stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aqua)](https://github.com/atsushieno/aqua)

- https://github.com/atsushieno/cerbero/tree/aap has some hidden gems, namely the following forks
- https://github.com/atsushieno/lilv/tree/android
- https://github.com/atsushieno/serd/tree/android
- https://github.com/atsushieno/sord/tree/android

- https://github.com/atsushieno/android-juce-cmake - template app project for Android + JUCE + CMake
- https://github.com/atsushieno/JUCE/tree/juce_emscripten - fork of Dreamtonics/juce_emscripten (Web MIDI support, Projucer enhancements, etc.)

Seealso: http://juce-demos.atsushieno.dev/

- [fluidsynth-midi-service-j](https://github.com/atsushieno/fluidsynth-midi-service-j) - up to date Android project that makes use of it, including fluidsynthjna (JNAerated bindings in Java) and ktmidi (partial port of managed-midi)
- [soundfont-player-cs](https://github.com/atsushieno/soundfont-player-cs) - Xwt-based desktop "soundfont player" that lets you choose and play soundfont programs using nfluidsynth, useful for picking up tones from a bunch of sf2/sf3 files in local directories.

- [msfa-midi-device-service](https://github.com/atsushieno/msfa-midi-device-service) - MidiDeviceService for MSFA (music-synthesizer-for-Android)

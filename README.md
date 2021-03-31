# atsushieno's live github repos

(It is not my CV, so I don't list anything other than my repos. No mention on [mono](https://github.com/mono/mono), [xamarin-android](https://github.com/xamarin/xamarin-android) or [monodevelop](https://github.com/mono/monodevelop). No mention on things outside github such as [tech books](https://xamaritans.booth.pm/) or [session talks](https://speakerdeck.com/atsushieno). If you are interested in working together let me know.)

I am reachable as @atsushieno on mastodon.cloud, twitter, or facebook. I'm also lurking around [theaudioprogrammer](https://theaudioprogrammer.com/) discord.


## AAP and related projects

[![AAP demo 20200708](http://img.youtube.com/vi/gKCpHvYzupU/0.jpg)](http://www.youtube.com/watch?v=gKCpHvYzupU "AAP demo 20200708")

[![android-audio-plugin-framework stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=android-audio-plugin-framework)](https://github.com/atsushieno/android-audio-plugin-framework)
[![aap-lv2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-lv2)](https://github.com/atsushieno/aap-lv2)
[![aap-juce stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-juce)](https://github.com/atsushieno/aap-juce)
[![android-native-audio-builders stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=android-native-audio-builders)](https://github.com/atsushieno/android-native-audio-builders)

There are various aap-lv2 ports and aap-juce ports in split repos too.

## cross-platform MIDI access libraries and applications

I used to develop C# library for MIDI access and SMF manipulation, and they are migrating to Kotlin.

| project | C# (mostly deprecated) | Kotlin (alive) |
|-|-|-|
| cross-platform MIDI access and abstraction API with SMF I/O support. | [managed-midi](https://github.com/atsushieno/managed-midi) | [ktmidi](https://github.com/atsushieno/ktmidi) |
| virtual MIDI keyboard | [xmmk](https://github.com/atsushieno/xmmk) / Xwt | [kmmk](https://github.com/atsushieno/kmmk) / Jetpack Compose |
| visual MIDI player | [xmdsp](https://github.com/atsushieno/xmdsp) / Xwt | - |
| MML compiler mugene | [mugene](https://github.com/atsushieno/mugene) - including its vscode extension with LSP support | [mugene-ng](https://github.com/atsushieno/mugene-ng) |
| experimental .NET API transformed from MML operations | [notium](https://github.com/atsushieno/notium) | [notium-ng](https://github.com/atsushieno/notium-ng) |

## MML compiler related

- [augene](https://github.com/atsushieno/augene) - MML compiler integration with tracktion_engine, MML to MIDI to tracktionedit with JUCE AudioPluginHost help.
- [mugene-guide-book](https://github.com/atsushieno/mugene-guide-book) - book sources for MML Compiler mugene guide book (Japanese)


## MIDI 2.0

[![cmidi2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=cmidi2)](https://github.com/atsushieno/cmidi2)

[![lv2-midi2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=lv2-midi2)](https://github.com/atsushieno/lv2-midi2)

## LV2

![aqua sshot](https://raw.githubusercontent.com/atsushieno/aqua/main/aqua-lv2ui-in-action.png)

[![aqua stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aqua)](https://github.com/atsushieno/aqua)

[![ayumi-lv2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=ayumi-lv2)](https://github.com/atsushieno/ayumi-lv2)

### LV2 for Android

- https://github.com/atsushieno/cerbero/tree/aap has some hidden gems, namely the following forks
- https://github.com/atsushieno/lilv/tree/android
- https://github.com/atsushieno/serd/tree/android
- https://github.com/atsushieno/sord/tree/android

## JUCE apps forks

Seealso: http://juce-demos.atsushieno.dev/

- https://github.com/atsushieno/android-juce-cmake - template app project for Android + JUCE + CMake
- https://github.com/atsushieno/JUCE/tree/juce_emscripten - fork of Dreamtonics/juce_emscripten (Web MIDI support, Projucer enhancements, etc.)
- https://github.com/atsushieno/ADLplug/tree/android - ADLplug/OPNplug Android/Emscripten ports
- https://github.com/atsushieno/juicysfplugin - statically linked juicysfplugin.so to avoid external fluidsynth 2.0 dependency.
- https://github.com/atsushieno/dexed/tree/emscripten - Dexed Emscripten port.

## Fluidsynth for Android

- ~[fluidsynth-fork](https://github.com/atsushieno/fluidsynth-fork) - Android audio drivers (Oboe/OpenSLES)~ now it is merged into upstream master.
- [cerbero](https://github.com/atsushieno/cerbero) - cerbero fork, used by above.
- [fluidsynth-midi-service-j](https://github.com/atsushieno/fluidsynth-midi-service-j) - up to date Android project that makes use of it, including fluidsynthjna (JNAerated bindings in Java) and ktmidi (partial port of managed-midi)
- [fluidsynth-midi-service](https://github.com/atsushieno/fluidsynth-midi-service) - outdated but more featureful Xamarin.Android app (it will be up to date once xamarin-android builds without problem on Linux again)
  - [nfluidsynth](https://github.com/atsushieno/nfluidsynth) - .NET binding for libfluidsynth
- [soundfont-player-cs](https://github.com/atsushieno/soundfont-player-cs) - Xwt-based desktop "soundfont player" that lets you choose and play soundfont programs using nfluidsynth, useful for picking up tones from a bunch of sf2/sf3 files in local directories.

## Re:VIEW

![vscode-language-review in action](https://raw.githubusercontent.com/atsushieno/vscode-language-review/master/docs/images/sshot-preview.png)

[![vscode-language-review stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=vscode-language-review)](https://github.com/atsushieno/vscode-language-review)

## miscellaneous

- [msfa-midi-device-service](https://github.com/atsushieno/msfa-midi-device-service) - MidiDeviceService for MSFA (music-synthesizer-for-Android)

## Legacy .NET bits (and sometimes not legacy)

They are not actively developed and not much support expected anymore. Though my music tools are still important and will be ported to somewhere at some stage.

- [nclang](https://github.com/atsushieno/nclang) - libclang .NET binding and P/Invoke generator. I use it's PInvokeGenerator everywhere in my native interop repos (but not this one itself; it doesn't make a lot of sense yet).
- [ntractive](https://github.com/atsushieno/ntracktive) - manipulate Tracktion Waveform edit files (without tracktion_engine)
- [sf2xrni](https://github.com/atsushieno/sf2xrni) - Soundfont to Renoise XRNI converter
- [lilv-sharp](https://github.com/atsushieno/lilv-sharp) - .NET binding for Lilv (LV2 hosting / query).
- [oboe-sharp](https://github.com/atsushieno/oboe-sharp) - .NET binding for Oboe (with "oboe-c" build)
- [libsoundio-sharp](https://github.com/atsushieno/libsoundio-sharp) - .NET binding for libsoundio
- [dotnet-dsdl](https://github.com/atsushieno/dotnet-dsdl) - some DSDL implementation in .NET (RELAX NG and NVDL). It is kind of port of my Commons.Xml.Relaxng library which was part of [mono](https://github.com/mono/mono)
- [xamarin-javacpp-binding](https://github.com/atsushieno/xamarin-javacpp-binding) - Xamarin.Android binding for JavaCPP (runtime)
- [generic-codedom](https://github.com/atsushieno/generic-codedom) - for those who wants to use generics on System.CodeDom API.
- [xamarin-android-schema-generator](https://github.com/atsushieno/xamarin-android-shema-generator) - instant XML Schema generator for Android resources for IDE completion.
- [world-sharp](https://github.com/atsushieno/world-sharp) - .NET bindings for World vocal synthesis engine.

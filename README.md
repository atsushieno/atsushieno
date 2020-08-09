# atsushieno's live github repos

![user stats](https://github-readme-stats.vercel.app/api?username=atsushieno&show_icons=true&theme=tokyonight)

(It is not my CV, so I don't list anything other than my repos. No mention on mono, xamarin-android or monodevelop. No mention on things outside github such as tech books. If you are interested in working together let me know.)

## AAP and related projects

[![AAP demo 20200708](http://img.youtube.com/vi/gKCpHvYzupU/0.jpg)](http://www.youtube.com/watch?v=gKCpHvYzupU "AAP demo 20200708")

[![android-audio-plugin-framework stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=android-audio-plugin-framework)](https://github.com/atsushieno/android-audio-plugin-framework)
[![aap-lv2 stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-lv2)](https://github.com/atsushieno/aap-lv2)
[![aap-juce stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aap-juce)](https://github.com/atsushieno/aap-juce)
[![android-native-audio-builders stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=android-native-audio-builders)](https://github.com/atsushieno/android-native-audio-builders)


## LV2

![aria2web sshot](https://raw.githubusercontent.com/atsushieno/aria2web/main/aria2web-lv2ui-in-action.png)

[![aria2web stats](https://github-readme-stats.vercel.app/api/pin/?username=atsushieno&repo=aria2web)](https://github.com/atsushieno/aria2web)

### LV2 for Android

- https://github.com/atsushieno/cerbero/tree/aap has some hidden gems, namely the following forks
- https://github.com/atsushieno/lilv/tree/android
- https://github.com/atsushieno/serd/tree/android
- https://github.com/atsushieno/sord/tree/android

## JUCE apps forks

Seealso: http://juce-demos.atsushieno.dev/

- https://github.com/atsushieno/JUCE/tree/juce_emscripten - fork of Dreamtonics/juce_emscripten (Web MIDI support, Projucer enhancements, etc.)
- https://github.com/atsushieno/ADLplug/tree/android - ADLplug/OPNplug Android/Emscripten ports
- https://github.com/atsushieno/juicysfplugin - statically linked juicysfplugin.so to avoid external fluidsynth 2.0 dependency.
- https://github.com/atsushieno/dexed/tree/emscripten - Dexed Emscripten port.

## ndkports

- https://github.com/atsushieno/ndkports (not really maintained)

## Fluidsynth for Android

- ~[fluidsynth-fork](https://github.com/atsushieno/fluidsynth-fork) - Android audio drivers (Oboe/OpenSLES)~ now it is merged into upstream master.
- [cerbero](https://github.com/atsushieno/cerbero) - cerbero fork, used by above.
- [fluidsynth-midi-service-j](https://github.com/atsushieno/fluidsynth-midi-service-j) - up to date Android project that makes use of it, including fluidsynthjna (JNAerated bindings in Java) and ktmidi (partial port of managed-midi)
- [fluidsynth-midi-service](https://github.com/atsushieno/fluidsynth-midi-service) - outdated but more featureful Xamarin.Android app (it will be up to date once xamarin-android builds without problem on Linux again)
  - [nfluidsynth](https://github.com/atsushieno/nfluidsynth) - .NET binding for libfluidsynth
- [soundfont-player-cs](https://github.com/atsushieno/soundfont-player-cs) - Xwt-based desktop "soundfont player" that lets you choose and play soundfont programs using nfluidsynth, useful for picking up tones from a bunch of sf2/sf3 files in local directories.

## Re:VIEW

- [vscode-language-review](https://github.com/atsushieno/vscode-language-review) VSCode Re:VIEW support

## miscellaneous

- [msfa-midi-device-service](https://github.com/atsushieno/msfa-midi-device-service) - MidiDeviceService for MSFA (music-synthesizer-for-Android)

## Legacy bits

They are not actively developed anymore. Though my music tools are still important and will be ported to somewhere at some stage.

### cross platform .NET MIDI API

- [managed-midi](https://github.com/atsushieno/managed-midi) - cross-platform .NET native MIDI access, as well as common MIDI related features (MidiPlayer, SMF manipulation, MIDI module database, etc.)
- [xmmk](https://github.com/atsushieno/xmmk) - cross-platform (Xwt) virtual MIDI keyboard on PC keyboard
- [xmdsp](https://github.com/atsushieno/xmdsp) - cross-platform (Xwt) visual MIDI player

### MML compiler and co.

- [mugene](https://github.com/atsushieno/mugene) - MML compiler mugene, including its vscode extension with LSP support
  - [mugene-guide-book](https://github.com/atsushieno/mugene-guide-book) - book sources for MML Compiler mugene guide book (Japanese)
- [notium](https://github.com/atsushieno/notium) - experimental .NET API transformed from MML operations
- [augene](https://github.com/atsushieno/augene) - MML compiler integration with tracktion_engine, MML to MIDI to tracktionedit with JUCE AudioPluginHost help.

### Language toolchain hacks

- [nclang](https://github.com/atsushieno/nclang) - libclang .NET binding and P/Invoke generator. I use it's PInvokeGenerator everywhere in my native interop repos (but not this one itself; it doesn't make a lot of sense yet).

### DAW hacks

- [ntractive](https://github.com/atsushieno/ntracktive) - manipulate Tracktion Waveform edit files (without tracktion_engine)
- [sf2xrni](https://github.com/atsushieno/sf2xrni) - Soundfont to Renoise XRNI converter

### Miscellaneous

- [lilv-sharp](https://github.com/atsushieno/lilv-sharp) - .NET binding for Lilv (LV2 hosting / query).
- [oboe-sharp](https://github.com/atsushieno/oboe-sharp) - .NET binding for Oboe (with "oboe-c" build)
- [libsoundio-sharp](https://github.com/atsushieno/libsoundio-sharp) - .NET binding for libsoundio
- [dotnet-dsdl](https://github.com/atsushieno/dotnet-dsdl) - some DSDL implementation in .NET (RELAX NG and NVDL). It is kind of port of my Commons.Xml.Relaxng library which was part of [mono](https://github.com/mono/mono)
- [xamarin-javacpp-binding](https://github.com/atsushieno/xamarin-javacpp-binding) - Xamarin.Android binding for JavaCPP (runtime)
- [generic-codedom](https://github.com/atsushieno/generic-codedom) - for those who wants to use generics on System.CodeDom API.
- [xamarin-android-schema-generator](https://github.com/atsushieno/xamarin-android-shema-generator) - instant XML Schema generator for Android resources for IDE completion.
- [world-sharp](https://github.com/atsushieno/world-sharp) - .NET bindings for World vocal synthesis engine.

## Archived projects which might be still interesting

- [falplayer-android-j](https://github.com/atsushieno/falplayer-android-j) - copy ogg files from FALCOM PC games (Ys, Legend of Heroes) which have LOOPSTART/LOOPLENGTH and play them on Android.
  - [falplayer-android](https://github.com/atsushieno/falplayer-android) - ... using Xamarin.Android (legacy)
- [asparser](https://github.com/atsushieno/asparser) - partial ActionScript3 parser and runtime port to .NET.
- [tsukimi](https://github.com/atsushieno/tsukimi) - Processing port to Sliverlight/Moonlight.
- [md-typescript](https://github.com/atsushieno/md-typescript) - past attempt to build and run typescript projects in monoDevelop.
- [monodevelop-mercurial](https://github.com/atsushieno/monodevelop-mercurial) - Mercurial addin for MonoDevelop (old)
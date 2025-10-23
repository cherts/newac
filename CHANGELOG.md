Version History
===============

Short list of new features for each NewAC version.

**Version: NewAC 2.6.2**

- RAD Studio XE6/XE7/XE8/Seattle/Alexandria/Berlin/Tokyo/Rio/Sydney/Athens/Florence support.

**Version: NewAC 2.6.1**

- RAD Studio XE3/XE4/XE5 support.
- Some minor fixes.

**Version: NewAC 2.6**

- The TDSAudioOut - new and better sound output component is added.
- The TAudioCache component is added.
- The TMP4In component for AAC playback is added.
- OnSyncDone event (like OnDone, but fired at ones) is added.
- Windows 7 compatibility is attested.
- Some minor fixes.

**Version: NewAC 2.5**

- The TFastGainIndicaor component is added.
- Performance farther improved.

**Version: NewAC 2.4**

- The Audio Output Latency property is added.
- Common audio tags properties are added.
- TSpectrumIndicator component is added.
- TTagsEditor component is added.
- TGainControl component is added.
- TMpgIn component is added.

**Version: NewAC 2.3**

- TGainIndicator component is added.
- Some minor bug fixes and improvements.

**Version: NewAC 2.2.2**

- TCDIn CD-ripping component is updated.  Jitter correction and higher speed on new drives.
- Some minor bug fixes and improvements.

**Version: NewAC 2.2.1**

- Many bug fixes and improvements.
- Input prefetch mechanism is implemented to allow low latencies when playing back via DirectSound.

**Version: NewAC 2.2**

- AC-3 decoder added.
- DTS decoder is greatly improved.
- TDownMixer component is added (converts 5.1 to stereo lets you to control the parameters).
- TWVIn and TWVOut components are significantly improved.

**Version: NewAC 2.1**

- DTS decoder added.
- TAudioPlaylist component which allows gapless playback added.
- TCueSplitter component added (splits audiotracks automatically using cue-sheets).
- ASIO output now supports 5.1 channels.

**Version: NewAC 2.0**

- Low-latency ASIO drivers support added.
- Real-time audio components (TAudioSynchronizer, TAudioHiResTimer) added.
- Some minor improvements.

**Version: NewAC 1.9**

- Experimental delphi-based compresor added.
- Delphi 2009 compatibility added.
- TCDDBInfo component added
- Small bugs fixed.

**Version: NewAC 1.8**

- TFastResampler component (fully Delphi-based) for fast resampling.
- TConvolver and TDifferenceEquation components for exploring DSP operations.
- TChebyshevFilter component implementing Chebyshev filters.
- TFrequencyAnalysis component thst performs DFT on audio data.

**Version: NewAC 1.7.2**

- New TRealTimeMixer component.
- External DLLs are now loaded on demand
- Updated LAME encoder
- Some bugs are fixed.

**Version: NewAC 1.7.1**

- AVI files reader added (TAVIIn component).
- Some bugs are fixed.

**Version: NewAC 1.7**

- New Audio processing components: TDitherer, TNormalizer, TMSResampler, TVoiceFilter.
- Improved 32-bit and multichannel sound support.
- Two pass WMA encoder added.

**Version: NewAC 1.6**

- Musepack support (decoding/encoding).
- TAK support (decoding).
- Multichannel audio support.
- Audio broadcasting support.

**Version: NewAC 1.5**

- TWMStreamedIn for reading live MP3 and WMA network streams.
- WMA lossless encoding support.
- TWaveTap and TWMATap components.
- Many smaller fixes and improvements.

**Version: NewAC 1.4**

- FLAC tags support (reading/writing).
- TTA lossless audio format support.
- New converter components: TACMConverter and TAudioPass.
- Numerous smaller fixes and improvements.

**Version: NewAC 1.3.2**

- Improved WMA encoder
- Object Model has changed: SuspendWhenIdle property and WaitForStop method are now obsolete.

**Version: NewAC v1.3.1**

- MP3 decoding is now done with Windows decoder (additional DLL (mpadec.dll) no longer needed)

**Version: NewAC v1.3**

- Windows Media files input support (TWMIn component), Windows Media Audio (wma) files output support (TWMAOut component).
- Event handling improved

**Version: NewAC v1.2**

- WavPack format support (TWVIn, TWVOut components).
- 24-bit sound support.
- Unicode file names support (via the WideFileName property).
- Large (larger than 2 GB) files support.

**Version: NewAC v1.1**

- Base class interfaces is changed to make data flow more efficient.
- FLAC and Monkey’s Audio codecs are updated.
- New TAudioConverter and TResampler components are added.
- New MP3 decoder support is added to make MP3 input seekable.

**Version: NewAC v1.0.1**

- Ogg Vorbis bugs are fixed.
- DirectSound API is implemented in Delphi, so there is no more need in dswrapper DLL.
- Base classes are renamed from TACS* to TAu*.
- Some minor bugs are fixed.

**Version: NewAC v1.0**

- Some bugs are fixed.
- TMP3In component is added for mp3 playback.
- TCDPlayer can now work with several drives.

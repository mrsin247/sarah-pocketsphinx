# PocketSphinx wheel for Sarah

`pocketsphinx-5.1.1-cp313-cp313-win_amd64.whl` — CMU PocketSphinx speech
recognition (speech-to-text, offline, CPU) for Windows 64-bit, Python 3.13 only.

This is Sarah's ears (microphone -> text), not a speaking voice. It fits the
simple Sarah build that uses SpeechRecognition + PocketSphinx.

Install on the Windows computer, in the folder holding the file:

```
pip install pocketsphinx-5.1.1-cp313-cp313-win_amd64.whl
```

Note: there is no Python 3.12 Windows wheel in PocketSphinx 5.1.1, so this
file will be refused by pip on Python 3.12. Use Python 3.13.

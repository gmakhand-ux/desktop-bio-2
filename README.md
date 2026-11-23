# music/

Put your audio files (.mp3, .m4a, .wav, .ogg) in this folder.

Then open `index.html`, find `MUSIC_TRACKS`, and add one line per file:

```js
{ file: 'my-song.mp3', title: 'my song' },
```

The `file` value must match the filename exactly (including capitals).

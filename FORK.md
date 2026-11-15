# Fork notes

This is a modified fork of [kota-zo/Orpheon](https://github.com/kota-zo/Orpheon)
(Orpheon, GPL-3.0). Modifications are marked in the commit messages on `main`:

- Visible downloads in `Download/Orpheon` (was `Music/Orpheon`); older files
  in `Music/Orpheon` are still read.
- Lyrics and cover embedded in the downloaded file (USLT+SYLT / APIC for MP3,
  ©lyr / covr for M4A, Vorbis LYRICS + PICTURE + `.lrc` sidecar for FLAC),
  before the public scan or the private encryption.
- A lyrics badge in the track rows (checked over Wi-Fi only, cached).

Upstream license and credits are kept unchanged.

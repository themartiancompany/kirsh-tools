# Kirsh tools

The Kirsh is a maximum ratio-compressed
media format.

Kirsh format encoding can be both
lossless and lossy.

## Lossless encoding

The lossless kirsh encoding is an iteratively
losslessly compressed media file
encoded in a standard media format.
This is its structure:

```
movie.<compression_algorithm>.kirsh
  |
  |-- movie.<media_format>.<compression_algorithm>
  |     |
  |     `-- movie.<media_format>
  |
  `-- movie.<audio_format>.<compression_algorithm>
        |
        `--movie.<audio_format>
```

# Lossy encoding

Details about kirsh lossy encoding will be
made public soon.

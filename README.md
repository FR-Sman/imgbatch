# ImageBatch

A simple offline batch image processing panel for Termux using ImageMagick.

## Install

```bash
pkg update
pkg install git imagemagick findutils
termux-setup-storage
```

Clone:

```bash
git clone https://github.com/YOUR_USERNAME/imgbatch.git
cd imgbatch
chmod +x imgbatch
./imgbatch
```

## Output

All processed files are saved to:

```text
Internal Storage/Download/imgbatch/
```

Each operation gets its own folder:

```text
imgbatch/
├── resize/
├── convert/
├── watermark/
├── crop/
├── clean/
└── compress/
```

## Features

- Batch resize
- Format conversion
- Image watermark
- Center crop
- Metadata removal
- Image compression
- Offline processing
- Simple terminal panel

## Requirements

- Termux
- ImageMagick
- findutils
- Storage permission

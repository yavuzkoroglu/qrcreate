# qrcreate
A small Unix-style Bash utility that converts stdin into a standalone QR code PDF using `pdflatex`.

# Install Using `homebrew`

```
brew tap yavuzkoroglu/tools
brew install yavuzkoroglu/tools/qrcreate
```

# Example Uses

The example below creates `qr.pdf`. Thanks to `-l`, the QR code is a clickable hyperlink.

```
qrcreate -l <<< 'https://web.itu.edu.tr/yakoroglu'
```

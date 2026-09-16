# qrcreate
A small Unix-style Bash utility that converts stdin into a standalone QR code PDF using `pdflatex`.

# Install Using `homebrew`

```
brew tap yavuzkoroglu/tools
brew install yavuzkoroglu/tools/qrcreate
```

# Example Uses

The example below creates `qr.pdf`. The generated QR code is a clickable hyperlink thanks to `-l`.

```
qrcreate -d 'https://web.itu.edu.tr/yakoroglu/' -l
```

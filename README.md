# qrcreate
A small Unix-style Bash utility that converts stdin into a standalone QR code PDF using `pdflatex`. The generated QR code is by default clickable.

# Install Using `brew`

```
brew tap yavuzkoroglu/tools
brew install yavuzkoroglu/tools/qrcreate
```

# Example Uses

The example below creates `myqr.pdf`. The PDF contains a clickable QR code link to the given website.

```
qrcreate myqr <<< 'https://web.itu.edu.tr/yakoroglu/'
```

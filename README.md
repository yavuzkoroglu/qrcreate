# qrcreate
A small Unix-style Bash utility that converts stdin into a standalone QR code PDF using `pdflatex`. The QR code is a clickable hyperlink whenever possible.

# Install Using `brew`

```
brew tap yavuzkoroglu/tools
brew install yavuzkoroglu/tools/qrcreate
```

# Example Uses

The example below creates `myqr.pdf`. The PDF contains a clickable QR code link to the given website.

```
echo 'https://web.itu.edu.tr/yakoroglu/' | qrcreate myqr
```

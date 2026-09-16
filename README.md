# qrcreate
A small Unix-style Bash utility that converts stdin into a standalone QR code PDF using `pdflatex`.

# Install Using `brew`

```
brew tap yavuzkoroglu/tools
brew install yavuzkoroglu/tools/qrcreate
```

# Example Uses

The example below creates `qr.pdf`. The generated QR code is a clickable hyperlink thanks to `-l`.

```
qrcreate -l <<< 'https://web.itu.edu.tr/yakoroglu/'
```

# Usage Details

Print information about all command-line parameters using the command below.

```
qrcreate -h
```

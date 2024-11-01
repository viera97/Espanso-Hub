# password-generator
[Espanso](https://espanso.org) extension for generating passwords and copy to clipboard in all OSs.
## Installation
This espanso extension optionally uses `pyperclip` to copy the generated password to clipboard.

```bash
python -m pip install --upgrade pip
python -m pip install pyperclip
```

After installing pyperclip you can install `password-generator` extension by doing:

```bash
espanso install password-generator
```
## Usage

* By typing `:genpass()` a 12 length password will be generated containing lower and upper characters, symbols and digits.
* By typing `:genpass(n)` where $n$ is an integer number you can generate a $n$-length password containing lower and upper characters, symbols and digits.

### Not installing pyperclip
If you didn't install `pyperclip` the extension still works but it won't copy the generated password to clipboard.
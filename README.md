# Hi

## Installation
```bash
sudo curl -so /usr/local/bin/upload.py https://raw.githubusercontent.com/hakimifr/upload/refs/heads/main/upload.py && sudo chmod +x /usr/local/bin/upload.py
```

For termux:
```bash
curl -so "$PREFIX/bin/upload.py" https://raw.githubusercontent.com/hakimifr/upload/refs/heads/main/upload.py && chmod +x "$PERFIX/bin/upload.py"
```

> [!NOTE]
> If you use proot-distro in Termux, then please use the non-termux installation method.

## What you need
- [`uv`](https://github.com/astral-sh/uv)
- API_ID, API_HASH, and BOT_TOKEN variables exported
(get api id and api hash from https://my.telegram.org/apps)

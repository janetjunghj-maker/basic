# basic

새 Mac 세팅용 Homebrew 패키지 목록.

```bash
# 1. Homebrew 설치 (없다면)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2. 이 저장소로 한 번에 설치
git clone https://github.com/janetjunghj-maker/basic.git && cd basic
brew bundle --file=Brewfile
```

목록 갱신: `brew bundle dump --file=Brewfile --force`

## 참고

- 공개 저장소이므로 설치한 도구 목록이 누구에게나 보입니다. 숨기고 싶은 항목은 Brewfile에서 지우세요.
- Homebrew(formula/cask)로 설치한 것만 포함됩니다. App Store 앱이나 직접 내려받은 앱은 빠져 있습니다.

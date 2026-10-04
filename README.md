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

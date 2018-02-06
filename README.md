# squirrel config

```
# MAC OS User
git clone https://github.com/xqin/squirrel.git ~/Library/Rime/

# Linux OS User
git clone https://github.com/xqin/squirrel.git ~/.config/ibus/rime/


git clone https://github.com/rime/brise.git

cd brise

./rime-install wubi prelude pinyin-simp

# redeploy squirrel

```

## linux

```
sudo apt-get install ibus-rime

# use ibus-setup add chinese -> rime
ibus-setup

# redeploy
rm ~/.config/ibus/rime/default.yaml; ibus-daemon -drx
```

# 共享資料夾

【中州韻】 `/usr/share/rime-data/`
【小狼毫】 `"安裝目錄\data"`
【鼠鬚管】 `"/Library/Input Methods/Squirrel.app/Contents/SharedSupport/"`


# 用戶資料夾


【中州韻】 `~/.config/ibus/rime/` （0.9.1 以下版本爲 `~/.ibus/rime/`）
【小狼毫】 `"%APPDATA%\Rime"`
【鼠鬚管】 `~/Library/Rime/`

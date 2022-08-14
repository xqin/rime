# Rime config


## download config file
```
# MAC OS User
git clone https://github.com/xqin/Rime.git ~/Library/Rime/

# Linux OS User
git clone https://github.com/xqin/Rime.git ~/.config/ibus/rime/
```

## download dependence

```
curl -fsSL https://git.io/rime-install | bash -s -- prelude wubi pinyin-simp

# or

git clone --depth=1 https://github.com/rime/plum.git
cd plum
bash ./rime-install prelude wubi pinyin-simp
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

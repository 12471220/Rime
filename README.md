### Rime configuration tested in mac/windows

macos useage:
``` bash
cd ~/Library
mv Rime Rime.bak
git clone https://github.com/12471220/Rime
cd Rime
https://github.com/rime/plum
cd plum
bash ./rime-install wubi
bash ./rime-install pinyin-simp
```
windows useage:
``` powershell
cd $env:appdata
mv Rime Rime.bak
git clone https://github.com/12471220/Rime
cd Rime
https://github.com/rime/plum
cd plum
.\rime-install wubi
.\rime-install  pinyin-simp
```
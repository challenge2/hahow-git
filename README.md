mkdir hahow-git
cd hahow-git
ls -l : total 0 = no file
copy index.htm -> save to hahow-git, copy main.css -> open folder(style) -> save as main.css
git config --global user.name "guang"
git config --global user.email "won2der6ful@gmail.com"
git init
若不希望出現此錯誤警示，不要將 CRLF轉換為LF，則可以執行以下指令:
git config --global core.autocrlf true
git config --global core.safecrlf true
git checkout HEAD file : 還原, checkout : 切換
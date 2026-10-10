


For windows Powershell (no package need to download) 
copy this whole things once and paste into your powershell 
<h4> # Direct- "irm https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.ps1 | iex " </h4>
after install --> moivebox-tui
<br>

<br>
(recommended)<br>
scoop bucket add moviebox https://github.com/mesamirh/MovieBox-Tui
<br>
scoop install moviebox-tui
<br>
<br>
-----------------------xx {Android (Termux)} xx--------------------------
<br>
pkg update && pkg install -y curl tar termux-tools termux-am 
<br>
curl -fsSL https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.sh | bash
termux-setup-storage
<br>
<br>
-----------------------xx {macOS & Linux} xx-------------------------
<br>
brew tap mesamirh/moviebox-tui https://github.com/mesamirh/MovieBox-Tui
<br>
brew install moviebox-tui
<br>
<h4> # Direct - "curl -fsSL https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.sh | bash" </h4>

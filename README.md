


For windows Powershell (no package need to download) 
copy this whole things once and paste into your powershell 
<h4> # Direct- "irm https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.ps1 | iex " </h4>
after install --> moivebox-tui

(recommended)
scoop bucket add moviebox https://github.com/mesamirh/MovieBox-Tui
scoop install moviebox-tui
-----------------------xx {Android (Termux)} xx--------------------------
pkg update && pkg install -y curl tar termux-tools termux-am
curl -fsSL https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.sh | bash
termux-setup-storage

-----------------------xx {macOS & Linux} xx-------------------------
brew tap mesamirh/moviebox-tui https://github.com/mesamirh/MovieBox-Tui
brew install moviebox-tui

<h4> # Direct - "curl -fsSL https://raw.githubusercontent.com/mesamirh/MovieBox-Tui/main/install.sh | bash" </h4>

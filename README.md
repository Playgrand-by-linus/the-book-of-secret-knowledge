這是一份為 The Book of Secret Knowledge（秘密知識之書） 完整翻譯並本地化整理的繁體中文版 README.md，保留了原專案的結構、標籤與排版風格：
<p align="center">
  <a href="https://github.com/trimstray/the-book-of-secret-knowledge">
    <img src="https://github.com/trimstray/the-book-of-secret-knowledge/blob/master/static/img/the-book-of-secret-knowledge-preview.png" alt="Master">
  </a>
</p>

<p align="center">「<i>知識就是力量，請謹慎使用！</i>」</p>

<h4 align="center">彙整各類啟發性清單、操作手冊、速查表（Cheat Sheets）、部落格、小撇步、單行指令（One-liners）、CLI / Web 工具等實用資源。</h4>

<br>

<p align="center">
  <a href="https://github.com/trimstray/the-book-of-secret-knowledge/pulls">
    <img src="https://img.shields.io/badge/PRs-歡迎提交-brightgreen.svg?longCache=true" alt="Pull Requests">
  </a>
  <a href="LICENSE.md">
    <img src="https://img.shields.io/badge/License-MIT-lightgrey.svg?longCache=true" alt="MIT License">
  </a>
</p>

<br>

****

## 📖 &nbsp;這是什麼？

這個儲存庫收集了我在日常工作中經常使用的各種資源、工具與材料，將海量且實用的知識匯整於一處。對我而言，這是一份極具價值、隨時回顧查閱的知識寶庫。

## 🚻 &nbsp;適用對象？

原則上適合每一個人，任何技術愛好者都能在此找到喜愛的內容。但平心而論，它主要針對：**系統管理員（SysAdmin）**、**網路管理員**、**DevOps 工程師**、**滲透測試人員（Pentester）** 以及 **資安研究員**。

## ℹ️ &nbsp;參與貢獻

如果您發現內容有誤、失效或不合邏輯，歡迎提出 Pull Request，並請附上具體合理的修改說明。

本專案遵循幾項簡單原則：
- 友善且清晰
- 不冗贅疲乏
- 具備實用性

貢獻時的格式建議：
- 易於貢獻（Markdown + HTML ...）
- 易於檢索（清晰簡潔的目錄目錄）

標註 **\*** 的網址表示暫時無法訪問，在確認其永久失效前請勿直接刪除。

在提交 PR 之前，請先參閱 **[貢獻指南](.github/CONTRIBUTING.md)**。請務必牢記：

```diff
+ 本儲存庫並非要包山包海，而是只收錄高品質的精選內容。

非常歡迎任何 建議 / PR！
📰  RSS 訂閱與更新
GitHub 提供了 Commit 歷史的 RSS/Atom 訂閱源，方便您即時掌握所有內容異動。
☑️  待辦事項（ToDo）
 * [ ] 持續新增實用資源...
 * [ ] 補充實用的 Shell 函式
 * [ ] 為收錄的工具庫（如 CLI 工具）增添單行指令範例
 * [ ] 整理並最佳化清單排序
新項目會定期持續補充。
💢  目錄索引（Table of Contents）
主要章節：
 * 命令列工具 (CLI Tools)
 * 圖形介面工具 (GUI Tools)
 * 線上與網頁工具 (Web Tools)
 * 作業系統與系統服務 (Systems/Services)
 * 網路技術 (Networks)
 * 容器與編排 (Containers/Orchestration)
 * 手冊 / 指南 / 教學 (Manuals/Howtos/Tutorials)
 * 啟發性資源清單 (Inspiring Lists)
 * 優質部落格 / Podcast / 影片 (Blogs/Podcasts/Videos)
 * 黑客技術與滲透測試 (Hacking/Penetration Testing)
 * 每日新知與資安情報 (Your daily knowledge and news)
 * 精選速查表 (Other Cheat Sheets)
 * Shell 單行指令精選 (Shell One-liners)
 * Shell 技巧 (Shell Tricks)
 * Shell 實用函式 (Shell Functions)
🔱  秘密知識之書（章節內容）
CLI Tools（命令列工具）
▪ Shell 環境
 * GNU Bash - 相容於 sh 並結合 Korn shell 與 C shell 優良特性的強大 Shell。
 * Zsh - 專為互動使用設計的進階 Shell，亦是強大的腳本語言。
 * tclsh - 功能強大且跨平台的 Shell，適用於多元應用場景。
 * bash-it - 專為維護 Bash 腳本、自訂指令與設定所打造的社群框架。
 * Oh My ZSH! - 目前最受歡迎的 Zsh 設定管理框架。
 * Oh My Fish - Fish shell 的設定與外掛管理框架。
 * Starship - 使用 Rust 開發、極速且高度自訂的跨 Shell 命令提示字元。
 * powerlevel10k - 強調速度與自訂彈性的 Powerlevel9k ZSH 主題重寫版。
▪ Shell 外掛
 * z - 追蹤最常訪問的資料夾，無需輸入完整路徑即可快速跳轉。
 * fzf - 通用的命令列模糊搜尋器（Fuzzy Finder）。
 * zsh-autosuggestions - 為 Zsh 提供類似 Fish 的快速自動補全建議。
 * zsh-syntax-highlighting - 命令列即時語法高亮外掛。
 * Awesome ZSH Plugins - 精選 Zsh 框架、外掛、主題與教學彙整。
▪ 檔案與視窗管理
 * Midnight Commander - 經典雙面板文字介面檔案管理器。
 * ranger - 受 Vim 操作邏輯啟發的主控台檔案管理器。
 * nnn - 輕量、極速且功能完整的終端檔案管理器。
 * screen - 終端全螢幕多工復用工具。
 * tmux - 強大的終端復用器（Terminal Multiplexer），輕鬆管理工作階段與多分割視窗。
 * tmux-cssh - 藉由 tmux 實現多主機同步連線與叢集操作管理。
▪ 文字編輯器
 * vi / vim - Unix/Linux 平台極具代表性且可高度客製化的編輯器。
 * emacs - 可無限擴充、自訂性極高的全功能編輯器。
 * micro - 現代直覺、開箱即用的終端文字編輯器。
 * neovim - 以擴充性與現代化為導向的重構版 Vim。
 * spacemacs / spacevim - 社群驅動的 Emacs / Vim 模組化發行版。
▪ 檔案與磁碟檢視
 * fd - 效能極佳且使用者體驗優於傳統 find 的替代工具。
 * ncdu - 具備文字互動介面的磁碟空間使用分析器。
▪ 網路診斷與探測
 * PuTTY - 經典的 SSH 與 Telnet 連線客戶端。
 * Mosh - 專為高延遲與不穩定漫遊連線設計的 SSH 替代協定。
 * Eternal Terminal - 支援工作階段自動重連與滾動暫存的終端工具。
 * nmap - 網路探測與資安稽核必備的開源工具。
 * Rust Scan - 號稱比 Nmap 更迅速的高速連接埠掃描器。
 * masscan - 採非同步架構設計、號稱數分鐘內能掃描全球網路的連接埠掃描器。
 * mtr - 整合 Traceroute 與 Ping 診斷資訊的即時路由追蹤工具。
 * tcpdump / tshark / Termshark - 命令列封包擷取與深度分析工具。
 * ngrep - 套用 grep 概念於網路封包負載內容的即時比對工具。
 * vnstat - 輕量的 Linux / BSD 網路流量歷史監控工具。
 * iPerf3 - 主動測試 IP 網路最大頻寬效能的量測工具。
 * aria2 - 輕量多協定、多來源的命令列高速下載工具。
▪ DNS 診斷與列舉
 * dnsdiag - DNS 診斷與效能分析工具集。
 * subfinder / sublist3r / amass - 專為資安評估設計的子網域列舉與 OSINT 工具。
 * massdns - 具備超高並行查詢能力的高效能 DNS 存根解析器。
 * dnstwist - 網域防冒、釣魚攻擊與拼寫錯誤偵測（Typosquatting）。
▪ HTTP 工具與壓力測試
 * curl - 跨協定資料傳輸的事實標準命令列工具。
 * HTTPie - 現代化、色彩豐富且對開發者友善的 HTTP 客戶端。
 * httpstat - 以清晰可視化長條圖呈現 cURL 請求各階段延遲。
 * wrk / vegeta / bombardier - 現代高並行 HTTP 壓力測試與基準評測工具。
 * gobuster - 以 Go 編寫的目錄路徑、DNS 與虛擬主機爆破工具。
 * Hurl - 使用純文字宣告並測試複雜 HTTP 請求流程的工具。
▪ SSL / TLS 安全性
 * openssl - 密碼學演算法與 TLS/SSL 協定的工業級實作。
 * sslyze - 快速且強大的 SSL/TLS 伺服器安全性掃描庫。
 * testssl.sh - 免安裝直接檢測任何連接埠之 TLS/SSL 加密漏洞的指令碼。
 * Certbot - EFF 推出用於自動簽發與更新 Let's Encrypt 憑證的工具。
 * mkcert - 零設定本機受信任開發憑證生成器。
▪ 系統診斷、追蹤與日誌分析
 * strace - 追蹤處理程序與 Linux 核心系統呼叫（System Calls）的重要除錯工具。
 * ltrace - 動態程式庫函式呼叫追蹤器。
 * bpftrace - 針對 Linux eBPF 技術的高階追蹤與除錯語言。
 * glances / htop / bashtop - 互動式系統即時監控工具。
 * lsof - 列出系統中所有被處理程序開啟的檔案與網路連線。
 * FlameGraph - 系統堆疊呼叫視覺化火焰圖。
 * lnav - 終端高階日誌檢視器，具備語法著色與即時篩選。
 * GoAccess - 在終端機中運行的即時 Web 存取日誌視覺化分析工具。
▪ 資料庫 CLI
 * usql - 通用資料庫命令列介面（支援 PostgreSQL, MySQL, SQLite, Oracle 等）。
 * pgcli / mycli - 具備自動補全與語法高亮的 Postgres / MySQL 客戶端。
 * osquery - 將作業系統各項狀態虛擬為關聯式 SQL 表格進行檢索監控。
Shell One-liners（單行指令速查）
常用終端技巧
 * 不重開終端機直接重新載入環境：
   exec $SHELL -l

 * 關閉終端並保留後台所有執行中行程：
   disown -a && exit

 * 退出且不寫入歷史紀錄：
   kill -9 $$
unset HISTFILE && exit

 * 管線 stdout 與 stderr 分流至不同指令：
   some_command > >(/bin/cmd_for_stdout) 2> >(/bin/cmd_for_stderr)

 * 快速建立檔案備份：
   cp filename{,.orig}

 * 清空檔案內容（截斷至 0 位元組）：
   > filename

 * 建立目錄並立即進入該目錄：
   mkd() { mkdir -p "$@" && cd "$@"; }

檔案與進程管理
 * 尋找佔用特定 Port 的行程並強制終止：
   kill -9 $(lsof -i :<port> | awk '{l=$2} END {print l}')

 * 檢視目前正在建立網路連線的行程：
   lsof -P -i -n

 * 尋找系統中過去 60 分鐘內被修改過的檔案：
   find / -mmin 60 -type f

 * 單獨調整目錄權限（遞迴補上執行權限）：
   find . -type d -exec chmod 755 {} +

 * 單獨調整檔案權限（確保一般讀寫）：
   find . -type f -exec chmod 644 {} +

OpenSSL 憑證管理實用指令
 * 測試遠端 HTTPS 連線並顯示完整憑證鏈：
   echo | openssl s_client -connect google.com:443 -showcerts

 * 產生 2048-bit 無密碼私鑰：
   openssl genrsa -out private.key 2048

 * 從現有私鑰產製憑證簽署請求 (CSR)：
   openssl req -out request.csr -new -key private.key

 * 產製效期 365 天之自簽憑證：
   openssl req -newkey rsa:2048 -nodes -keyout domain.key -x509 -days 365 -out domain.crt

 * 比對私鑰與憑證是否吻合（驗證 Modulus Hash）：
   (openssl rsa -noout -modulus -in private.key | openssl md5 ; \
 openssl x509 -noout -modulus -in certificate.crt | openssl md5) | uniq

網路封包與檢測
 * 抓取 eth0 上的 HTTP GET 與 POST 標頭：
   tcpdump -ei eth0 -s 0 -v -n -l | egrep -i "POST /|GET /|Host:"

 * 透過 Netcat 快速建立單次暫時性 HTTP 靜態伺服器：
   while true ; do nc -l -p 1500 -c 'echo -e "HTTP/1.1 200 OK\n\n $(date)"' ; done

Shell Tricks（Shell 終端升級技巧）
在滲透測試中取得不穩定的反彈 Shell（Reverse Shell）時，可透過以下步驟將其升級為具備完整互動與終端回顯的 TTY Shell：
# 1. 在目標 Shell 中生成偽終端
script /dev/null -c bash

# 2. 按下 Ctrl+Z 將連線丟至背景
# 3. 在本機設定終端 raw 模式並切換回前景
stty raw -echo; fg

# 4. 重設終端環境
reset

# 5. 指定終端型態（提示時輸入 xterm）
xterm

# 6. 設定環境變數
export TERM=xterm; export SHELL=bash

Shell Functions（實用 Shell 函式）
網域名稱解析（基於 Google DNS API）
function DomainResolve() {
  local _host="$1"
  local _timeout="15"

  _host_ip=$(curl -ks -m "$_timeout" "[https://dns.google.com/resolve?name=$](https://dns.google.com/resolve?name=$){_host}&type=A" | \
  jq -r '.Answer[0].data' 2>/dev/null)

  if [[ -z "$_host_ip" ]] \vert{}\vert{} [[ "$_host_ip" == "null" ]] ; then
    echo -e "解析失敗：無法解析該網域。"
  else
    echo -e "${_host} >${_host_ip}"
  fi
}

取得 IP 所屬自治系統 (ASN)
function GetASN() {
  local _ip="$1"
  local _timeout="15"

  _asn=$(curl -ks -m "$_timeout" "[http://ip-api.com/line/$](http://ip-api.com/line/$){_ip}?fields=as")

  if [[ -z "$_ip" ]] \vert{}\vert{} [[ "$_asn" == "" ]]; then
    echo -e "查詢失敗：無法取得 ASN 資訊。"
  else
    echo -e "${_ip} >${_asn}"
  fi
}

開源授權
本專案基於 MIT 授權條款 發布。


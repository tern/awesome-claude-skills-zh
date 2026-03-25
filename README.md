# Awesome Claude Skills（繁體中文整理版）

> 精選的 Claude Code 工作流程強化工具：技能包、代理、插件、鉤子與各類實用資源。

---

## 最新收錄

| 資源 | 作者 | 說明 |
|------|------|------|
| [Claude Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills) | K-Dense | 涵蓋研究、科學、工程、分析、金融與寫作的即用型代理技能包，品質卓越。 |
| [parry](https://github.com/vaporif/parry) | Dmytro Onypko | Claude Code 鉤子的提示注入掃描器，防範注入攻擊、敏感資料洩漏。 |
| [Dippy](https://github.com/ldayton/Dippy) | Lily Dayton | 利用 AST 解析自動批准安全指令，對危險操作則要求人工確認，解決權限疲勞問題。 |
| [sudocode](https://github.com/sudocode-ai/sudocode) | ssh-randy | 輕量級代理編排開發工具，整合多種規格框架，住在你的 repo 裡。 |
| [claude-tmux](https://github.com/nielsgroen/claude-tmux) | Niels Groeneveld | 在 tmux 中管理多個 Claude Code 實例，支援快速切換、狀態監控與 git worktree 整合。 |
| [claude-esp](https://github.com/phiat/claude-esp) | phiat | 基於 Go 的 TUI，將 Claude Code 的隱藏輸出（思考過程、工具呼叫、子代理）串流至獨立終端。 |

---

## 代理技能 🤖

> 代理技能是由模型控制的配置資源（檔案、腳本等），讓 Claude Code 能執行需要特定知識或能力的專業任務。

### 通用技能

| 資源 | 作者 | 說明 |
|------|------|------|
| [AgentSys](https://github.com/avifenesh/agentsys) | avifenesh | 包含大量有用插件、代理與技能的工作流程自動化系統，覆蓋 PR 管理、代碼清理、漂移偵測與多代理審查。 |
| [AI Agent, AI Spy](https://youtu.be/0ANECpNdt-4) | Signal Foundation | Signal 基金會成員分享如何將作業系統打造成全面監控工具的技巧與思考（YouTube 連結）。 |
| [Book Factory](https://github.com/robertguss/claude-skills) | Robert Guss | 複製傳統出版流程的完整技能流水線，專為非虛構書籍創作設計。 |
| [cc-devops-skills](https://github.com/akin-ozer/cc-devops-skills) | akin-ozer | 針對 DevOps 工程師的詳盡技能集，支援多種平台的高品質 IaC 代碼生成。 |
| [Claude Code Agents](https://github.com/undeadlist/claude-code-agents) | Paul - UndeadList | 面向獨立開發者的端對端開發工作流程，含並行審計器、自動修復循環與瀏覽器 QA，並有防止 AI 失控的嚴格協定。 |
| [Claude Codex Settings](https://github.com/fcakyon/claude-codex-settings) | fatih akyon | 涵蓋 GitHub、Azure、MongoDB、Playwright 等常見雲端平台與服務的完整開發插件集。 |
| [Claude Mountaineering Skills](https://github.com/dreamiurg/claude-mountaineering-skills) | Dmytro Gaivoronsky | 自動化北美山峰路線研究，聚合 10 餘個登山資料來源生成詳細路況報告。 |
| [Claude Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills) | K-Dense | 涵蓋研究、科學、工程、分析、金融與寫作的即用型代理技能包，堪稱 GitHub 上最優質的技能庫之一。 |
| [Codex Skill](https://github.com/skills-directory/skill-codex) | klaudworks | 從 Claude Code 呼叫 Codex 的技能，能自動推斷模型、推理強度等參數，並簡化會話延續。 |
| [Compound Engineering Plugin](https://github.com/EveryInc/compound-engineering-plugin) | EveryInc | 設計優良的代理與技能集，核心理念是將過去的錯誤轉化為未來改進的機會。 |
| [Context Engineering Kit](https://github.com/NeoLabHQ/context-engineering-kit) | Vlad Goncharov | 以最小 token 佔用提升代理結果品質的進階上下文工程技術集合。 |
| [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) | Affaan Mustafa | 覆蓋核心工程領域的頂級資源，幾乎囊括所有 Claude Code 功能的示範模式。 |
| [Fullstack Dev Skills](https://github.com/jeffallan/claude-skills) | jeffallan | 含 65 個專業技能的完整全棧開發插件，包含 Jira/Confluence 整合與獨特的 `/common-ground` 上下文工程命令。 |
| [read-only-postgres](https://github.com/jawwadfirdousi/agent-skills) | jawwadfirdousi | 用於 Claude Code 的唯讀 PostgreSQL 查詢技能，支援嚴格驗證、超時與行數限制。 |
| [Superpowers](https://github.com/obra/superpowers) | Jesse Vincent | 涵蓋軟體工程 SDLC 大部分環節的核心能力技能包，從規劃、審查到測試、除錯皆有覆蓋。 |
| [Trail of Bits Security Skills](https://github.com/trailofbits/skills) | Trail of Bits | 12 餘個安全審計與漏洞偵測技能，含 CodeQL、Semgrep 靜態分析與差異代碼審查。 |
| [TÂCHES Claude Code Resources](https://github.com/glittercowboy/taches-cc-resources) | TÂCHES | 組織良好、易於閱讀的子代理、技能與命令集，重點在可適應工作流程的「元技能」。 |
| [Web Assets Generator Skill](https://github.com/alonw0/web-asset-generator) | Alon Wolenitz | 從 Claude Code 一鍵生成 favicon、PWA 圖示與社群媒體 Open Graph 圖片，並提供對應 HTML meta 標籤。 |

---

## 工作流程與知識指南 🧠

> 工作流程是一組緊密耦合的 Claude Code 原生資源，用於促進特定專案的推進。

### 通用工作流程

| 資源 | 作者 | 說明 |
|------|------|------|
| [AB Method](https://github.com/ayoubben18/ab-method) | Ayoub Bensalah | 以規格驅動的方式，利用 Claude Code 子代理將大型問題分解為聚焦的增量任務。 |
| [Agentic Workflow Patterns](https://github.com/ThibautMelen/agentic-workflow-patterns) | ThibautMelen | Anthropic 文檔中代理模式的完整圖文詳解，含彩色 Mermaid 圖表與代碼範例。 |
| [Blogging Platform Instructions](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) | cloudartisan | 提供建立文章、管理分類與處理媒體檔案的結構化部落格平台維護命令集。 |
| [Claude Code Documentation Mirror](https://github.com/ericbuess/claude-code-docs) | Eric Buess | 每隔數小時更新的 Claude Code 官方文檔鏡像，方便跟進最新功能。 |
| [Claude Code Handbook](https://nikiforovall.blog/claude-code-rules/) | nikiforovall | 集合 Claude Code 開發工作流程最佳實踐、技巧與可分發插件的手冊。 |
| [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) | diet103 | 創新的技能使用方案，利用鉤子讓 Claude 根據當前上下文智慧選擇並啟動適當技能。 |
| [Claude Code PM](https://github.com/automazeio/ccpm) | Ran Aroussi | 功能豐富的 Claude Code 專案管理工作流程，含多個專業代理、命令與詳盡文檔。 |
| [Claude Code Repos Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) | Daniel Rosehill | 作者發布的 75 餘個高品質 Claude Code 倉庫索引，涵蓋 CMS、物聯網、代理工作流程等多領域。 |
| [Claude Code System Prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | Piebald AI | Claude Code 系統提示各部分（含內建工具描述、子代理提示）的完整揭露，隨版本更新。 |
| [Claude Code Tips](https://github.com/ykdojo/claude-code-tips) | ykdojo | 35 餘條涵蓋語音輸入、容器工作流程、對話複製與多模型編排的密集 Claude Code 技巧。 |
| [Claude Code Ultimate Guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide) | Florian BRUNIAUX | 從入門到進階使用者的全面 Claude Code 指南，含生產就緒模板、工作流程指引與互動測驗。 |
| [Claude CodePro](https://github.com/maxritter/claude-codepro) | Max Ritter | 規格驅動工作流程、TDD 強制執行、跨會話記憶與品質鉤子的專業 Claude Code 開發環境。 |
| [claude-code-docs](https://github.com/costiash/claude-code-docs) | Constantin Shafranski | 支援全文搜尋和即時更新的 Anthropic 文檔鏡像站。 |
| [ClaudoPro Directory](https://github.com/JSONbored/claudepro-directory) | ghost | 涵蓋多種專業任務與工作流程的精選 Claude Code 鉤子、命令、子代理資源集。 |
| [Context Priming](https://github.com/disler/just-prompt/tree/main/.claude/commands) | disler | 提供系統化方法，透過專用命令將 Claude Code 充分載入各類專案情境。 |
| [Design Review Workflow](https://github.com/OneRedOak/claude-code-workflows/tree/main/design-review) | Patrick Ellis | 自動化 UI/UX 設計審查工作流程，涵蓋響應式設計到無障礙性的全面評估。 |
| [Laravel TALL Stack AI Development Starter Kit](https://github.com/tott/laravel-tall-claude-ai-configs) | tott | 為 Laravel TALL 技術棧（Tailwind、AlpineJS、Laravel、Livewire）提供智慧輔助與系統化工作流程的配置集。 |
| [Learn Claude Code](https://github.com/shareAI-lab/learn-claude-code) | shareAI-Lab | 分析編碼代理設計原理，用少量 Python 代碼重建含技能、子代理與待辦清單的簡易代理系統。 |
| [learn-faster-kit](https://github.com/cheukyin175/learn-faster-kit) | Hugo Lau | 受「FASTER」自學法啟發的 Claude Code 教育框架，整合主動學習和間隔重複等教學技術。 |
| [n8n_agent](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) | kingler | 涵蓋代碼分析、QA、設計、文檔、專案結構與最佳化的全面命令集。 |
| [Project Bootstrapping and Task Management](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) | steadycursor | 提供新專案啟動與管理的結構化命令，含創建和編輯自訂命令的元命令。 |
| [Project Management, Implementation, Planning, and Release](https://github.com/scopecraft/command/tree/main/.claude/commands) | scopecraft | 覆蓋 SDLC 全流程的完整命令集。 |
| [Project Workflow System](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) | harperreed | 涵蓋任務管理、代碼審查與部署流程的完整專案管理命令系統。 |
| [RIPER Workflow](https://github.com/tony/claude-code-riper-5) | Tony Narlock | 強制區分研究、創新、規劃、執行與審查階段的結構化開發工作流程，含分支感知記憶庫。 |
| [Shipping Real Code w/ Claude](https://diwank.space/field-notes-from-shipping-real-code-with-claude) | Diwank | 詳述使用 Claude Code 交付產品的實際流程，附 CLAUDE.md 檔案與實用資源的部落格文章。 |
| [Simone](https://github.com/Helmi/claude-simone) | Helmi | 包含文件、指引與流程的完整 Claude Code 專案管理工作流程系統。 |

### Ralph Wiggum 流派

| 資源 | 作者 | 說明 |
|------|------|------|
| [awesome-ralph](https://github.com/snwfdhmp/awesome-ralph) | Martin Joly | 關於 Ralph 技術（讓 AI 編碼代理自動循環直到規格達成）的精選資源列表。 |
| [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) | Frank Bria | 讓 Claude Code 迭代工作直到完成的自主開發框架，含智慧退出偵測、限流與 75 個以上測試。 |
| [Ralph Wiggum Marketer](https://github.com/muratcankoylan/ralph-wiggum-marketer) | Muratcan Koylan | 將 Ralph 循環與市場研究知識庫整合的自主 AI 文案寫作插件。 |
| [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) | mikeyobrien | 持續執行 AI 代理直到任務完成的 Ralph Wiggum 技術實現，功能完善且有完整測試。 |
| [ralph-wiggum-bdd](https://github.com/marcindulak/ralph-wiggum-bdd) | marcindulak | 支援無人值守與互動模式的行為驅動開發（BDD）Bash 腳本，可保持代碼與需求同步。 |
| [The Ralph Playbook](https://github.com/ClaytonFarr/ralph-playbook) | Clayton Farr | 對 Ralph Wiggum 技術的詳盡理論說明與實用指引的完整手冊。 |

---

## 工具套件 🧰

> 工具套件是建立在 Claude Code 之上、由多個元件組成的完整應用程式。

### 通用工具

| 資源 | 作者 | 說明 |
|------|------|------|
| [cc-sessions](https://github.com/GWUDCAP/cc-sessions) | toastdev | 以有主見的方式提升 Claude Code 開發生產力的工具。 |
| [cc-tools](https://github.com/Veraticus/cc-tools) | Josh Symonds | 以 Go 實作的高效能 Claude Code 鉤子與工具集，提供智慧 lint、測試與狀態欄生成。 |
| [ccexp](https://github.com/nyatinte/ccexp) | nyatinte | 具有美觀終端介面的互動式 CLI，用於探索和管理 Claude Code 配置文件與命令。 |
| [cchistory](https://github.com/eckardt/cchistory) | eckardt | 如同 shell 歷史命令，但用於列出 Claude Code 會話中執行過的 Bash 命令。 |
| [cclogviewer](https://github.com/Brads3290/cclogviewer) | Brad S. | 以美觀 HTML 界面查看 Claude Code `.jsonl` 會話日誌的實用工具。 |
| [Claude Code Templates](https://github.com/davila7/claude-code-templates) | Daniel Avila | 集本列表各類資源於一體的精緻 UI 工具，含使用量儀表板與分析功能。 |
| [Claude Composer](https://github.com/possibilities/claude-composer) | Mike Bannister | 為 Claude Code 添加小幅增強功能的工具。 |
| [Claude Hub](https://github.com/claude-did-this/claude-hub) | Claude Did This | 透過 webhook 將 Claude Code 連接至 GitHub 倉庫，支援透過 PR 和 Issue 的 @提及進行 AI 輔助。 |
| [Claude Session Restore](https://github.com/ZENG3LD/claude-session-restore) | ZENG3LD | 透過分析會話檔案與 git 歷史高效恢復前次 Claude Code 會話上下文，支援最大 2GB 的大型會話檔案。 |
| [claude-code-tools](https://github.com/pchalasani/claude-code-tools) | Prasad Chalasani | 提供會話連續性的工具集，含跨 Claude Code 與 Codex CLI 的代理交接及 Rust 全文搜尋。 |
| [claude-starter-kit](https://github.com/serpro69/claude-starter-kit) | serpro69 | 預配置 MCP 伺服器的 Claude Code 完整開發環境模板倉庫。 |
| [claudekit](https://github.com/carlrannaberg/claudekit) | Carl Rannaberg | 提供自動保存檢查點、代碼品質鉤子、規格生成與 20 餘個專業子代理的印象深刻 CLI 工具集。 |
| [Container Use](https://github.com/dagger/container-use) | dagger | 為編碼代理提供隔離安全的開發環境，讓多個代理能獨立工作。 |
| [ContextKit](https://github.com/FlineDev/ContextKit) | Cihat Gündüz | 透過 4 階段規劃方法與專業品質代理，讓 Claude Code 首次就能生成生產就緒代碼的開發框架。 |
| [recall](https://github.com/zippoxer/recall) | zippoxer | 在終端全文搜尋 Claude Code 會話歷史並直接恢復的工具，是 `claude --resume` 的替代方案。 |
| [Rulesync](https://github.com/dyoshikawa/rulesync) | dyoshikawa | 自動生成並在各 AI 編碼代理間轉換配置（規則、MCP 伺服器、命令等）的 Node.js CLI 工具。 |
| [run-claude-docker](https://github.com/icanhasjonas/run-claude-docker) | Jonas | 將工作空間轉發至隔離 Docker 容器的獨立 Claude Code 執行器，仍可存取設定與認證。 |
| [stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) | marcindulak | 在 Linux 上透過按鍵說話本地轉錄語音並傳送至 Claude Code 的 Python MCP 伺服器。 |
| [SuperClaude](https://github.com/SuperClaude-Org/SuperClaude_Framework) | SuperClaude-Org | 以專業命令、認知角色（如「省思」「編排」）增強 Claude Code 的多功能配置框架。 |
| [tweakcc](https://github.com/Piebald-AI/tweakcc) | Piebald-AI | 自訂 Claude Code 外觀樣式的命令列工具。 |
| [Vibe-Log](https://github.com/vibe-log/vibe-log-cli) | Vibe-Log | 本地分析 Claude Code 提示、提供會話分析與策略指引，並生成精美 HTML 報告的工具。 |
| [viwo-cli](https://github.com/OverseedAI/viwo) | Hal Shin | 以 git worktree 掛載卷的 Docker 容器執行 Claude Code，降低權限疲勞並支援多實例並行。 |
| [VoiceMode MCP](https://github.com/mbailey/voicemode) | Mike Bailey | 為 Claude Code 帶來自然語音對話能力，支援任何 OpenAI API 相容語音服務。 |

### IDE 整合

| 資源 | 作者 | 說明 |
|------|------|------|
| [Claude Code Chat](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) | andrepimenta | 優雅易用的 VS Code 內建 Claude Code 聊天介面。 |
| [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) | manzaltu | 將 Claude Code 整合至 Emacs 的插件，支援 ediff 建議、LSP 診斷與緩衝區上下文追蹤。 |
| [claude-code.el](https://github.com/stevemolitor/claude-code.el) | stevemolitor | Claude Code CLI 的 Emacs 介面。 |
| [claude-code.nvim](https://github.com/greggh/claude-code.nvim) | greggh | Claude Code AI 助手與 Neovim 的無縫整合插件。 |
| [Claudix - Claude Code for VSCode](https://github.com/Haleclipse/Claudix) | Haleclipse | 將 Claude Code 帶入 VS Code 的擴展，支援互動聊天、會話管理與即時串流回應。 |

### 使用量監控

| 資源 | 作者 | 說明 |
|------|------|------|
| [CC Usage](https://github.com/ryoppippi/ccusage) | ryoppippi | 分析本地 Claude Code 日誌、展示費用與 token 消耗資訊的便利 CLI 工具。 |
| [ccflare](https://github.com/snipeship/ccflare) | snipeship | 具有精美 Web UI 的 Claude Code 使用量儀表板，提供全面詳盡的使用指標。 |
| [better-ccflare](https://github.com/tombii/better-ccflare/) | tombii | ccflare 的積極維護增強版，帶來效能提升、擴展提供者支援與 Docker 部署支援。 |
| [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) | Maciek-roboblog | 即時監控 Claude Code token 使用量、燒耗率並預測耗盡時間的終端工具。 |
| [Claudex](https://github.com/kunwar-shah/claudex) | Kunwar Shah | 以全文搜尋索引本地倉庫、瀏覽 Claude Code 對話歷史的 Web 介面，完全本地且無遙測。 |
| [viberank](https://github.com/sculptdotfun/viberank) | nikshepsvn | 讓開發者可視化並比拼 Claude Code 使用統計的社群排行榜工具。 |

### 編排器

| 資源 | 作者 | 說明 |
|------|------|------|
| [Auto-Claude](https://github.com/AndyMik90/Auto-Claude) | AndyMik90 | 整合完整 SDLC 的自主多代理編碼框架，具備看板式 UI 與精心設計的代理編排系統。 |
| [Claude Code Flow](https://github.com/ruvnet/claude-code-flow) | ruvnet | 讓 Claude 在遞迴代理循環中自主編寫、編輯、測試與最佳化代碼的編排層。 |
| [Claude Squad](https://github.com/smtg-ai/claude-squad) | smtg-ai | 在獨立工作空間中管理多個 Claude Code、Codex 等代理，實現並行多任務處理的終端應用。 |
| [Claude Swarm](https://github.com/parruda/claude-swarm) | parruda | 啟動連接至一群 Claude Code 代理集群的協作工作會話。 |
| [Claude Task Master](https://github.com/eyaltoledano/claude-task-master) | eyaltoledano | 與 Cursor AI 無縫整合的 AI 驅動開發任務管理系統。 |
| [Claude Task Runner](https://github.com/grahama1970/claude-task-runner) | grahama1970 | 管理上下文隔離與聚焦任務執行的工具，解決複雜多步驟專案中的上下文長度限制問題。 |
| [Happy Coder](https://github.com/slopus/happy) | GrocerPublishAgent | 從手機或桌面並行控制多個 Claude Code 實例，Claude 需要輸入時推送通知。 |
| [sudocode](https://github.com/sudocode-ai/sudocode) | ssh-randy | 整合多種規格框架、住在你 repo 裡的輕量級代理編排開發工具。 |
| [The Agentic Startup](https://github.com/rsmdt/the-startup) | Rudolf Schmidt | 用於交付生產代碼的代理、命令綜合集合，是少數實際運用 Output Styles 的資源之一。 |
| [TSK - AI Agent Task Manager and Sandbox](https://github.com/dtormoen/tsk) | dtormoen | 讓 AI 代理在沙盒 Docker 環境中並行執行開發任務並返回 git 分支供人工審查的 Rust CLI 工具。 |

### 配置管理器

| 資源 | 作者 | 說明 |
|------|------|------|
| [claude-rules-doctor](https://github.com/nulone/claude-rules-doctor) | nulone | 偵測 `.claude/rules/` 中失效配置（glob 模式不匹配任何文件）的 CLI 工具，支援 CI 模式。 |
| [ClaudeCTX](https://github.com/foxj77/claudectx) | John Fox | 以單一命令切換整個 Claude Code 配置集的工具。 |

---

## 狀態欄 📊

> 用於自訂 Claude Code 狀態欄功能的配置與工具。

| 資源 | 作者 | 說明 |
|------|------|------|
| [CCometixLine](https://github.com/Haleclipse/CCometixLine) | Haleclipse | 以 Rust 撰寫的高效能 Claude Code 狀態欄工具，整合 Git、使用量追蹤與互動式 TUI 配置。 |
| [ccstatusline](https://github.com/sirmalloc/ccstatusline) | sirmalloc | 可高度自訂的狀態欄格式化器，顯示模型資訊、git 分支、token 使用量等指標。 |
| [claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) | rz1989s | 帶有主題、費用追蹤與 MCP 伺服器監控的增強 4 行狀態欄。 |
| [claude-powerline](https://github.com/Owloops/claude-powerline) | Owloops | 仿 Vim Powerline 風格的 Claude Code 狀態欄，支援即時使用量追蹤、Git 整合與自訂主題。 |
| [claudia-statusline](https://github.com/hagan/claudia-statusline) | Hagan Franks | 基於 Rust、以 SQLite 持久化統計資料的高效能狀態欄，支援進度條、燒耗率計算與主題。 |

---

## 鉤子 🪝

> 鉤子是 Claude Code 的強大 API，讓使用者能在代理生命週期的不同時間點執行命令與腳本。

| 資源 | 作者 | 說明 |
|------|------|------|
| [Britfix](https://github.com/Talieisin/britfix) | Talieisin | 透過 Claude Code 鉤子在文件寫入時自動將美式拼寫轉換為英式拼寫，能智慧識別代碼與注釋。 |
| [CC Notify](https://github.com/dazuiba/CCNotify) | dazuiba | 為 Claude Code 提供桌面通知，在需要輸入或任務完成時提醒並支援一鍵跳回 VS Code。 |
| [cchooks](https://github.com/GowayLee/cchooks) | GowayLee | 輕量級 Python SDK，提供清晰 API 簡化鉤子編寫並整合至代碼庫的過程。 |
| [Claude Code Hook Comms (HCOM)](https://github.com/aannoo/claude-hook-comms) | aannoo | 透過鉤子實現 Claude Code 子代理間即時通訊的輕量級 CLI 工具，支援 @提及定向與零依賴實現。 |
| [claude-code-hooks-sdk](https://github.com/beyondcode/claude-hooks-sdk) | beyondcode | 使用 Laravel 風格流暢 API 構建 Claude Code 鉤子回應的 PHP SDK。 |
| [claude-hooks](https://github.com/johnlindquist/claude-hooks) | John Lindquist | 以 TypeScript 為基礎、具備強大靈活介面的 Claude Code 鉤子配置系統。 |
| [Claudio](https://github.com/ctoth/claudio) | Christopher Toth | 透過簡單鉤子為 Claude Code 添加原生 OS 音效的小巧函式庫。 |
| [Dippy](https://github.com/ldayton/Dippy) | Lily Dayton | 利用 AST 解析自動批准安全指令、對危險操作提示確認，解決權限疲勞問題。 |
| [parry](https://github.com/vaporif/parry) | Dmytro Onypko | 掃描工具輸入輸出中注入攻擊、機密與資料洩漏嘗試的 Claude Code 鉤子提示注入掃描器。 |
| [TDD Guard](https://github.com/nizos/tdd-guard) | Nizar Selander | 透過鉤子即時監控文件操作並阻止違反 TDD 原則的更改的系統。 |
| [TypeScript Quality Hooks](https://github.com/bartolli/claude-code-typescript-hooks) | bartolli | Node.js TypeScript 專案的品質檢查鉤子，含 TypeScript 編譯、ESLint 自動修復與 Prettier 格式化，利用 SHA256 緩存達到 5ms 以內的驗證效能。 |

---

## 斜線命令 🔪

> 斜線命令是精心設計的自訂提示，用於控制 Claude 的行為以執行特定任務。

### 通用命令

| 資源 | 作者 | 說明 |
|------|------|------|
| [/create-hook](https://github.com/omril321/automated-notebooklm/blob/main/.claude/commands/create-hook.md) | Omri Lavi | 智慧引導鉤子創建過程並根據專案設定提供建議的命令。 |
| [/linux-desktop-slash-commands](https://github.com/danielrosehill/Claude-Code-Linux-Desktop-Slash-Commands) | Daniel Rosehill | 專為 Linux 桌面環境設計的命令庫，涵蓋硬體基準測試、文件系統整理與安全態勢驗證。 |

### 版本控制與 Git

| 資源 | 作者 | 說明 |
|------|------|------|
| [/analyze-issue](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) | jerseycheese | 獲取 GitHub Issue 詳情並生成包含清晰實作步驟的全面實作規格。 |
| [/commit](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) | evmts | 以 Conventional Commit 格式搭配適當 emoji 創建 git 提交的命令。 |
| [/commit-fast](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) | steadycursor | 自動選取首選提交訊息、快速生成結構化提交的加速命令。 |
| [/create-pr](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) | toyamarinyon | 自動完成創建分支、提交更改、Biome 格式化與提交 PR 的完整工作流程。 |
| [/create-pull-request](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) | liam-hq | 提供遵循標題規範與模板結構的完整 PR 創建指引。 |
| [/create-worktrees](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) | evmts | 為所有開放 PR 或特定分支創建 git worktree，並清理過時的 worktree。 |
| [/fix-github-issue](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) | jeremymailen | 透過 GitHub CLI 分析並修復 Issue，執行測試後創建規範提交訊息。 |
| [/fix-issue](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) | metabase | 以 Issue 編號為參數，分析上下文、實作解決方案並驗證修復的命令。 |
| [/fix-pr](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) | metabase | 自動獲取未解決的 PR 審查意見並進行針對性代碼改進的命令。 |
| [/husky](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) | evmts | 配置 Husky Git 鉤子、建立提交訊息標準並整合 lint 工具的命令。 |
| [/update-branch-name](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) | giselles-ai | 以適當前綴更新分支名稱、強制執行命名規範並管理遠端分支更新。 |

### 代碼分析與測試

| 資源 | 作者 | 說明 |
|------|------|------|
| [/check](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) | rygwdn | 執行靜態分析、安全漏洞掃描與代碼風格檢查的全面品質命令。 |
| [/code_analysis](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) | kingler | 提供知識圖譜生成、最佳化建議與品質評估等進階代碼分析選單。 |
| [/optimize](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) | to4iki | 分析代碼效能瓶頸並提供具體最佳化建議的命令。 |
| [/repro-issue](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) | rzykov | 為 GitHub Issue 創建可靠的可重現測試案例並記錄清晰復現步驟。 |
| [/tdd](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) | zscott | 以紅綠重構原則引導測試驅動開發、整合 git 工作流程並管理 PR 創建。 |
| [/tdd-implement](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/tdd-implement.md) | jerseycheese | 分析功能需求、先寫測試（紅）、實作最少通過代碼（綠）再重構的 TDD 實作命令。 |

### 上下文載入與預熱

| 資源 | 作者 | 說明 |
|------|------|------|
| [/context-prime](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) | elizaOS | 載入倉庫結構、設定開發上下文與建立協作參數以充分預熱 Claude 的命令。 |
| [/initref](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) | okuvshynov | 以標準文檔模板初始化參考文檔結構的命令。 |
| [/load-llms-txt](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) | ethpandaops | 將 LLM 配置文件載入上下文以建立 AI 討論基準術語的命令。 |
| [/load_coo_context](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) | Mjvolk3 | 為稀疏矩陣操作設置開發上下文的命令，含與舊方案的比較說明。 |
| [/load_dango_pipeline](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) | Mjvolk3 | 為模型訓練管線工作設定上下文的命令。 |
| [/prime](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) | yzyydev | 透過查看目錄結構與讀取關鍵文件建立標準化初始上下文的命令。 |
| [/rsi](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) | ddisisto | 讀取所有命令與關鍵專案文件以優化 AI 輔助開發工作流程的命令。 |

### 文檔與更新日誌

| 資源 | 作者 | 說明 |
|------|------|------|
| [/add-to-changelog](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) | berrydev-ai | 在保持格式一致性的前提下為更新日誌添加新條目的命令。 |
| [/create-docs](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/create-docs.md) | jerseycheese | 分析代碼結構並生成詳述輸入輸出、行為與邊緣案例的全面文檔。 |
| [/docs](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) | slunsford | 遵循專案結構、以一致格式生成涵蓋 API 與使用模式的完整文檔。 |
| [/explain-issue-fix](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) | hackdays-io | 記錄 GitHub Issue 解決方案，解釋技術決策並提供實作上下文。 |
| [/update-docs](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) | Consiliency | 審查文檔現狀、更新實作進度並維護跨專案文檔一致性的命令。 |

### CI / 部署

| 資源 | 作者 | 說明 |
|------|------|------|
| [/release](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) | kelp | 透過更新更新日誌、審查 README 變更並評估版本號增量來管理軟體發布的命令。 |
| [/run-ci](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) | hackdays-io | 啟動虛擬環境、執行 CI 相容腳本並反覆修復錯誤直到所有測試通過的命令。 |

### 專案與任務管理

| 資源 | 作者 | 說明 |
|------|------|------|
| [/create-command](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) | scopecraft | 引導 Claude 依照適當結構創建新自訂命令並附上說明文檔的元命令。 |
| [/create-plan](https://github.com/hesreallyhim/inkverse-fork/blob/preserve-claude-resources/.claude/commands/create-plan.md) | taddyorg | 依標準化格式生成詳細規格、需求與功能說明的完整產品需求文件。 |
| [/create-prp](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) | Wirasm | 依照方法論模板創建包含完整需求的產品需求計畫的命令。 |
| [/do-issue](https://github.com/jerseycheese/Narraitor/blob/feature/issue-227-ai-suggestions/.claude/commands/do-issue.md) | jerseycheese | 以人工審查節點實作 GitHub Issue 的結構化命令，亦支援自動模式。 |
| [/prd-generator](https://github.com/dredozubov/prd-generator) | Denis Redozubov | 從對話上下文生成含執行摘要、用戶故事、MVP 範圍等完整章節的產品需求文件插件。 |
| [/project_hello_w_name](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) | disler | 展示參數傳遞、元件復用、狀態管理與用戶輸入處理的可自訂問候元件命令。 |
| [/todo](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) | chrisleyva | 不離開 Claude Code 介面即可管理專案待辦事項，支援截止日期、排序與優先級功能。 |

### 其他雜項

| 資源 | 作者 | 說明 |
|------|------|------|
| [/fixing_go_in_graph](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) | Mjvolk3 | 專注於圖形資料庫中基因本體（Gene Ontology）標注整合問題的命令。 |
| [/mermaid](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) | GaloyMoney | 從 SQL Schema 文件生成含表格屬性的實體關係圖並驗證編譯的命令。 |
| [/review_dcell_model](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) | Mjvolk3 | 比較舊版 Dcell 與新版 Dango 模型實作並分析重構方案的命令。 |
| [/use-stepper](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) | zuplo | 將文檔重新格式化為 React Stepper 元件格式、保持 Markdown 相容性的命令。 |

---

## CLAUDE.md 文件 📂

> `CLAUDE.md` 文件包含重要的專案指導方針與上下文資訊，幫助 Claude Code 更好地理解專案與編碼標準。

### 語言特定

| 資源 | 作者 | 說明 |
|------|------|------|
| [AI IntelliJ Plugin](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) | didalgolab | 提供 IntelliJ 插件開發的 Gradle 命令、平台特定編碼模式與詳細國際化標準。 |
| [AWS MCP Server](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) | alexei-led | 包含多種 Python 環境設置選項、詳細代碼風格指引與 AWS CLI 互動安全注意事項。 |
| [DroidconKotlin](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) | touchlab | 提供跨平台 Kotlin Multiplatform 開發的 Gradle 命令、模組結構與依賴注入指引。 |
| [EDSL](https://github.com/hesreallyhim/awesome-claude-code/blob/main/resources/claude.md-files/EDSL/CLAUDE.md) | expectedparrot | 提供詳細構建與測試命令、嚴格代碼風格執行與以 Black 和 mypy 為主的標準化開發工作流。 |
| [Giselle](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) | giselles-ai | 以 pnpm 和 Vitest 提供詳細構建測試命令，附嚴格格式要求與全面命名規範。 |
| [HASH](https://github.com/hashintel/hash/blob/main/CLAUDE.md) | hashintel | 包含全面倉庫結構分解、強調編碼標準、詳細 Rust 文檔指引與系統化 PR 審查流程。 |
| [Inkline](https://github.com/inkline/inkline/blob/main/CLAUDE.md) | inkline | 以 pnpm 為主、強調 TypeScript 和 Vue 3 Composition API 的組件創建流程與測試建議。 |
| [JSBeeb](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) | mattgodbolt | 提供 JavaScript BBC Micro 模擬器的構建測試指令、架構文檔與除錯工作流程。 |
| [Lamoom Python](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) | LamoomAI | 生產環境提示工程函式庫的 API 文檔與使用範例，含 AI 模型負載均衡說明。 |
| [LangGraphJS](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) | langchain-ai | 提供全面構建測試命令、詳細 TypeScript 風格指引與使用 yarn workspaces 的 monorepo 結構。 |
| [Metabase](https://github.com/metabase/metabase/blob/master/CLAUDE.md) | metabase | 說明 Clojure/ClojureScript 的 REPL 驅動開發工作流程，強調增量開發與測試。 |
| [SG Cars Trends Backend](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) | sgcarstrends | 提供 TypeScript monorepo 的完整開發、測試、部署命令與 AWS/Cloudflare 整合說明。 |
| [SPy](https://github.com/spylang/spy/blob/main/CLAUDE.md) | spylang | 嚴格的編碼規範、全面測試指引與多種代碼編譯選項及後端特定測試裝飾器。 |
| [TPL](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) | KarpelesLab | 說明 Go 專案規範，包含全面錯誤處理建議、表驅動測試方法與最新 Go 特性現代化建議。 |

### 領域特定

| 資源 | 作者 | 說明 |
|------|------|------|
| [Course Builder](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) | badass-courses | 以 Turborepo 實現支援多樣技術棧整合的即時多人協作課程創建平台。 |
| [Cursor Tools](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) | eastlondoner | 建立支援多提供者與模型的 AI 命令介面，含 Stagehand 瀏覽器自動化功能。 |
| [Guitar](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) | soramimi | Guitar Git GUI 客戶端的開發指南，含跨平台構建命令、貢獻代碼風格與專案結構說明。 |
| [Network Chronicles](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) | Fimeg | 含 LLM 整合技術規格、角色指引與服務發現機制的 AI 驅動遊戲角色詳細實作計畫。 |
| [Pareto Mac](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) | ParetoSecurity | Mac 安全審計工具的開發指南，含構建指令、貢獻規範與測試流程。 |
| [pre-commit-hooks](https://github.com/aRustyDev/pre-commit-hooks) | aRustyDev | 翔實但不冗長的 `CLAUDE.md` 示範案例，避免了常見的全大寫喊話風格，是絕佳的學習資源。 |
| [SteadyStart](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) | steadycursor | 清晰直接地說明風格、權限、Claude「角色」與會話文檔規範的示範 CLAUDE.md。 |

### 專案腳手架與 MCP

| 資源 | 作者 | 說明 |
|------|------|------|
| [Basic Memory](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) | basicmachines-co | 以 Model Context Protocol 實現 LLM 與 Markdown 雙向通訊的創新 AI-人類協作框架。 |
| [claude-code-mcp-enhanced](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) | grahama1970 | 為 Claude 作為編碼代理提供詳盡且有力的指令，附測試指引、代碼範例與合規檢查。 |

---

## 替代客戶端 📱

> 用於與 Claude Code 互動的替代 UI 介面，支援行動裝置或桌面端。

| 資源 | 作者 | 說明 |
|------|------|------|
| [Claudable](https://github.com/opactorai/Claudable) | Ethan Park | 利用 Claude Code 等本地 CLI 代理輕鬆構建與部署產品的開源 Web 建置器。 |
| [claude-esp](https://github.com/phiat/claude-esp) | phiat | 將 Claude Code 隱藏輸出串流至獨立終端的 Go TUI，支援多會話同時監控與內容類型過濾。 |
| [claude-tmux](https://github.com/nielsgroen/claude-tmux) | Niels Groeneveld | 在 tmux 中管理多個 Claude Code 實例，支援快速切換、狀態監控與 git worktree 整合。 |
| [crystal](https://github.com/stravu/crystal) | stravu | 用於編排、監控與互動 Claude Code 代理的完整桌面應用程式。 |
| [Omnara](https://github.com/omnara-ai/omnara) | Ishaan Sehgal | 跨終端、Web 與行動端同步 Claude Code 會話的 AI 代理指揮中心，支援遠端監控與團隊協作。 |

---

## 官方文檔 🏛️

| 資源 | 作者 | 說明 |
|------|------|------|
| [Anthropic Documentation](https://docs.claude.com/en/home) | Anthropic | 含安裝指引、使用規範、API 參考與教學的 Claude Code 官方文檔，持續頻繁更新。 |
| [Anthropic Quickstarts](https://github.com/anthropics/claude-quickstarts) | Anthropic | 三個 AI 應用示範專案的完整開發指南，含標準化工作流程、代碼風格指引與容器化說明。 |
| [Claude Code GitHub Actions](https://github.com/anthropics/claude-code-action/tree/main/examples) | Anthropic | 在 CI/CD 流水線中自動化 AI 驅動工作流程的官方 GitHub Actions 整合與示範文檔。 |

---

## 關鍵主題摘要

本列表所收錄的 Claude Code 相關資源，集中體現了以下幾個核心主題：

**代理自主化**：從 Ralph Wiggum 迴圈到多代理編排框架，大量工具致力於讓 Claude Code 自主、迭代地完成複雜任務，減少人工干預。

**安全與品質保障**：鉤子系統（如 TDD Guard、parry、TypeScript Quality Hooks）和提示注入防護工具日益受到重視，反映出在提升自主程度的同時保障安全的需求。

**上下文工程**：如何高效向 Claude 傳遞專案上下文是核心挑戰，形成了從 CLAUDE.md 規範到專用 `/prime`、`/context-prime` 命令的豐富實踐。

**使用量監控與透明度**：多款工具致力於可視化 token 消耗、費用與模型行為，體現了對 AI 工作流程可觀測性的廣泛需求。

**跨工具生態整合**：眾多資源不再局限於 Claude Code 本身，而是與 Git、IDE（VS Code、Neovim、Emacs）、CI/CD 系統、tmux、Docker 及其他 AI 代理（如 Gemini CLI、Codex CLI）深度整合。

**工作流程標準化**：SDLC 各環節（規劃、TDD、代碼審查、文檔、發布）都有對應的斜線命令與工作流程範本，促進團隊開發實踐的一致性。

# Repo 命名規則

> Naming conventions for repositories under github.com/Zaious. 2026-09-25 定。

## 兩條規則

**1. 產品、網站、App：每個字首大寫，元件之間用 `-` 連。**
品牌名照品牌本身的寫法，不拆開。

- `ChronicleCore-Architecture`
- `Antigravity-Skills-Chronicle`
- `PTT-Alertor-Discord`
- `RiftAtlas-Companion`
- `ChronicleLife`
- `PhilosopherAtlas`（品牌名本身就是一個字）

**2. Agent skill、給 agent 用的工具庫：全小寫，用 `-` 連。**

- `translate-academic-paper`
- `journal-atlas`
- `claude-linkedin-profiler`
- `riftbound-chronicle`
- `antigravity-loader`

## 拿不準時怎麼判斷

1. 倉庫裡有 `SKILL.md`，或本身是設計給 agent 呼叫的 → 小寫。
2. 其他主要給人使用的 → 大寫。
3. 兩邊都算的，看主要使用者是人還是 agent。

## 適用範圍

- 管**公開倉**和**新開的倉**。舊的私人倉不追溯。
- 已封存的倉不改名。
- Fork 保留上游的原名。

## 改名前要先確認的事

- **只改大小寫**：GitHub 的網址不分大小寫，git 和網頁連結都不會斷。
- **GitHub Pages 例外**：Pages 的網址路徑有分大小寫，改名後也不會轉址。有開 Pages、而且網址已經給過別人的倉，不改名。
- **改的不只是大小寫**：舊網址會自動轉到新網址，但有三件事要注意：
  - 之後如果又開了一個倉用到舊名字，原本的轉址就會失效。
  - 別的倉在 Actions 裡寫的 `uses: Zaious/<舊名>` 不會跟著轉。
  - 改名前先搜一遍舊名字被哪些地方用到。
- 改完後，把本機副本的 remote 網址一起改掉。

## 例外

- `corridor-seeker`：是產品，但維持小寫。它的 Pages 網址已經對外給出去了。
- `bunjang_agent`：最早期的紀錄，保留原名。

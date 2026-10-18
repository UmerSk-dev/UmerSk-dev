<!-- ═══════════ PLAYER HEADER ═══════════ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=050816&height=170&section=header&text=UMER%20SHAIKH&fontSize=48&fontColor=00F5FF&animation=fadeIn&fontAlignY=38&desc=PLAYER%20001%20%7C%20THE%20CODE%20RUNNER&descAlignY=62&descSize=15"/>

</div>

<!-- ═══════════ GAME HUD ═══════════ -->

<div align="center">

```text
╔══════════════════════════════════════════════════════╗
║  ▰ PLAYER STATUS                                     ║
║                                                      ║
║  PLAYER     UMER                                     ║
║  CLASS      JAVA DEVELOPER IN TRAINING               ║
║  WORLD      VIT PUNE // INFORMATION TECHNOLOGY       ║
║  MISSION    BECOME A BACKEND ENGINEER                ║
║                                                      ║
║  CURRENT LEVEL                                        ║
║  [████████░░░░░░░░░░░░]  LEARNING NEVER ENDS         ║
╚══════════════════════════════════════════════════════╝
```

</div>

## `01` — THE CHARACTER

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="100%" viewBox="0 0 720 320" role="img" aria-label="Pixel-art cyberpunk coder character in a neon game arena">
  <defs>
    <linearGradient id="arena" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#07172c"/>
      <stop offset="100%" stop-color="#170b2e"/>
    </linearGradient>
    <linearGradient id="coat" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#263c67"/>
      <stop offset="100%" stop-color="#0a1028"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="720" height="320" rx="14" fill="url(#arena)"/>
  <g stroke="#123b58" stroke-width="1" opacity=".8">
    {#each Array.from({length:15},(_,i)=>i) as i}
      <path d={`M ${i*60-120} 320 L 360 155 L ${i*60+840} 320`} fill="none"/>
    {/each}
    {#each Array.from({length:6},(_,i)=>i) as i}
      <path d={`M 0 ${180+i*i*4} H 720`} fill="none"/>
    {/each}
  </g>
  <circle cx="360" cy="143" r="94" fill="none" stroke="#00e5ff" stroke-width="2" opacity=".6" filter="url(#glow)"/>
  <circle cx="360" cy="143" r="77" fill="none" stroke="#f02eec" stroke-width="1" stroke-dasharray="8 9"/>
  <g filter="url(#glow)">
    <rect x="327" y="69" width="66" height="66" rx="12" fill="#18243f" stroke="#00e5ff" stroke-width="3"/>
    <path d="M339 97 L350 89 L361 97 L372 89 L382 97" fill="none" stroke="#00e5ff" stroke-width="4" stroke-linecap="round"/>
    <rect x="341" y="107" width="38" height="6" rx="3" fill="#f02eec"/>
    <path d="M311 143 L292 169 L305 230 L326 250 L394 250 L415 230 L428 169 L409 143 L390 131 L330 131 Z" fill="url(#coat)" stroke="#00e5ff" stroke-width="2"/>
    <path d="M328 137 L360 174 L392 137 L383 216 L337 216 Z" fill="#11182c" stroke="#f02eec" stroke-width="2"/>
    <path d="M343 181 L360 197 L377 181" fill="none" stroke="#00e5ff" stroke-width="3"/>
    <path d="M311 155 L283 184 L291 218 L307 214 L309 190" fill="#19294a" stroke="#00e5ff" stroke-width="3"/>
    <path d="M409 155 L437 184 L429 218 L413 214 L411 190" fill="#19294a" stroke="#00e5ff" stroke-width="3"/>
    <rect x="322" y="244" width="30" height="40" fill="#10162d" stroke="#00e5ff" stroke-width="2"/>
    <rect x="368" y="244" width="30" height="40" fill="#10162d" stroke="#00e5ff" stroke-width="2"/>
    <path d="M317 282 H355 V294 H309 Z M365 282 H403 V294 H357 Z" fill="#050916" stroke="#f02eec" stroke-width="2"/>
  </g>
  <g filter="url(#glow)">
    <path d="M458 158 L497 136 L520 149 L481 172 Z" fill="#132844" stroke="#00e5ff" stroke-width="2"/>
    <path d="M481 172 L520 149 L520 195 L481 218 Z" fill="#0b1730" stroke="#00e5ff" stroke-width="2"/>
    <path d="M458 158 L481 172 L481 218 L458 203 Z" fill="#1b3153" stroke="#00e5ff" stroke-width="2"/>
    <path d="M469 171 L494 157 M469 181 L494 167 M469 191 L494 177" stroke="#f02eec" stroke-width="2"/>
  </g>
  <g fill="#00e5ff" filter="url(#glow)">
    <rect x="158" y="77" width="9" height="9"/><rect x="536" y="79" width="7" height="7"/>
    <rect x="218" y="135" width="5" height="5"/><rect x="565" y="219" width="8" height="8"/>
    <rect x="183" y="232" width="5" height="5"/><rect x="512" y="96" width="4" height="4"/>
  </g>
  <g fill="#f02eec" filter="url(#glow)">
    <rect x="226" y="80" width="6" height="6"/><rect x="549" y="167" width="6" height="6"/>
    <rect x="196" y="187" width="8" height="8"/><rect x="465" y="64" width="5" height="5"/>
  </g>
  <text x="24" y="34" fill="#00e5ff" font-family="monospace" font-size="13" letter-spacing="3">SECTOR 01 // PLAYER SPAWN</text>
  <text x="24" y="298" fill="#8395b8" font-family="monospace" font-size="11">BUILD. DEBUG. REPEAT.</text>
  <text x="696" y="298" text-anchor="end" fill="#f02eec" font-family="monospace" font-size="11">SYSTEM ONLINE</text>
</svg>

**PLAYER CLASS:** Developer  
**SPECIAL ABILITY:** Turning bugs into lessons  
**WEAPON:** Java  
**PASSIVE SKILL:** Consistency

</div>

## `02` — SKILL TREE

<div align="center">

| Skill | Level |
|:---|:---|
| ☕ Java | `LEARNING` |
| ⚔️ Data Structures & Algorithms | `GRINDING XP` |
| 🌐 HTML · CSS · JavaScript | `UNLOCKED` |
| ⚛️ React | `NEXT QUEST` |
| 🛠️ Spring Boot | `BOSS QUEST` |
| 🗄️ SQL & Databases | `UPCOMING` |
| 🐙 Git & GitHub | `ACTIVE` |

</div>

## `03` — ACTIVE QUESTS

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ QUEST 001: SAFESCAN

**Type:** Android / Payment Safety

Build a payment safety experience with QR scanning and risk-awareness features.

`JAVA` `ANDROID` `XML`

[ENTER PROJECT ↗](https://github.com/UmerSk-dev/SafeScan)

</td>
<td width="50%" valign="top">

### 🎮 QUEST 002: SHADOW ARENA

**Type:** Browser Game

Create a dark game arena with character movement, combat, and interactive gameplay.

`HTML` `CSS` `JAVASCRIPT`

[EXPLORE REPOSITORIES ↗](https://github.com/UmerSk-dev?tab=repositories)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 QUEST 003: DSA GRIND

Solve coding challenges, learn patterns, and improve problem-solving speed.

`JAVA` `LEETCODE`

[OPEN LEETCODE ↗](https://leetcode.com/)

</td>
<td width="50%" valign="top">

### 🌍 QUEST 004: OPEN SOURCE

Learn how real projects work, understand contributions, and start submitting meaningful pull requests.

`GIT` `GITHUB` `COLLABORATION`

**STATUS:** IN PROGRESS

</td>
</tr>
</table>

## `04` — CONTRIBUTION WORLD

> Your GitHub activity is your game world. Every contribution lights up another tile.

<div align="center">

<img src="https://ghchart.rshah.org/00e5ff/UmerSk-dev" alt="GitHub contribution activity rendered as a neon game map" width="100%"/>

</div>

### XP SYSTEM

- `+10 XP` — commit a meaningful change
- `+25 XP` — solve a coding problem
- `+50 XP` — finish a project milestone
- `+100 XP` — merge an open-source contribution

*These are personal game rules, not actual GitHub scores. Earn XP by keeping your own progress log.*

## `05` — PLAYER RECORD

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=UmerSk-dev&show_icons=true&hide_border=true&bg_color=050816&title_color=00e5ff&text_color=c7d2fe&icon_color=f02eec&rank_icon=github" alt="GitHub activity stats"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmerSk-dev&layout=compact&hide_border=true&bg_color=050816&title_color=00e5ff&text_color=c7d2fe" alt="Most used languages"/>

</div>

## `06` — CONNECT TO PLAYER

<div align="center">

[![GitHub](https://img.shields.io/badge/GITHUB-ENTER%20PROFILE-00e5ff?style=for-the-badge&logo=github&logoColor=050816)](https://github.com/UmerSk-dev)

</div>

---

<div align="center">

```text
╔══════════════════════════════════════════════╗
║  ACHIEVEMENT LOCKED: MASTER DEVELOPER        ║
║                                              ║
║  Complete enough quests to unlock it.        ║
║  No shortcuts. No fake stats. Keep building. ║
╚══════════════════════════════════════════════╝
```

**`[ PLAYER 001 — SAVE FILE IN PROGRESS ]`**

</div>

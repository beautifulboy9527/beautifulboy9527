<div align="center">

# MovaUI · Neo9527

**Creator of [MovaUI · 动境 (`movaui.com`)](https://movaui.com) — AI Motion Website Prompt Library, 60FPS Video Backgrounds & Cloud Catalog MCP**

[![MovaUI Website](https://img.shields.io/badge/MovaUI-movaui.com-111111?style=for-the-badge)](https://movaui.com)
[![movaui-skills](https://img.shields.io/badge/MIT_Skills-movaui--skills-0F766E?style=for-the-badge&logo=github)](https://github.com/beautifulboy9527/movaui-skills)
[![Free Prompt Builder](https://img.shields.io/badge/Free_Tool-Motion_Prompt_Builder-4F46E5?style=for-the-badge)](https://movaui.com/tools/motion-prompt-builder)
[![Cloud Catalog MCP](https://img.shields.io/badge/MCP-movaui.com%2Fmcp%2Fcatalog-2563EB?style=for-the-badge)](https://movaui.com/skills)
[![Official MCP Registry](https://img.shields.io/badge/Official_MCP_Registry-Active-059669?style=for-the-badge)](https://registry.modelcontextprotocol.io/v0/servers?search=io.github.beautifulboy9527/movaui-catalog)

</div>

---

## Featured Project — [MovaUI · 动境 (`movaui.com`)](https://movaui.com)

I build production-grade **AI Agent Skills**, **MCP servers**, and **high-motion frontend design workflows** for **Claude Code, Cursor, Codex, Windsurf, Cline, and Antigravity**.

> **Brand Note:** **MovaUI (`https://movaui.com`)** is an independent AI motion website design prompt library, 60FPS looping background catalog, and Agent Skills / MCP platform. It is **not affiliated** with `mova-ui.com` (Vue/UI component kit) or `movavi.com` (desktop video editor).

### Open-Source Flagship: [`movaui-skills`](https://github.com/beautifulboy9527/movaui-skills) (MIT)

Free-tier Agent Skills + zero-auth remote Cloud Catalog MCP connector for motion-first web engineering:

- **`mova-setup`** — Connect AI coding agents to the public remote Streamable HTTP MCP endpoint (`https://movaui.com/mcp/catalog`) and `https://movaui.com/skill.md`.
- **`stack-adapter-skill`** — Auto-detects Next.js / React / Vue / Astro / Nuxt / SvelteKit / Vite, Tailwind v3/v4, CSS systems, and motion libraries via standalone Node CLI (`detect-project-stack.mjs`) to produce stack-matched adaptation blueprints.
- **`s3c-post-baseline-editor`** — Disciplined post-baseline refinement protocol (strict scope lock, visual-token preservation, diff verification).
- **`ascii-animation-skill`** — Terminal/Canvas/WebGL ASCII motion choreography spec with an offline deterministic spec validator (`validate-ascii-spec.mjs`).

### Free Online Tool & Live Endpoints

| Resource | URL | Purpose |
|---|---|---|
| **MovaUI Motion Library** | [movaui.com](https://movaui.com) | 870+ motion UI prompts, 210+ 60FPS looping backgrounds, 21 cloud skills |
| **Motion Prompt Builder** | [movaui.com/tools/motion-prompt-builder](https://movaui.com/tools/motion-prompt-builder) | Free zero-login structured motion prompt generator for AI coding agents |
| **Cloud Catalog MCP** | `https://movaui.com/mcp/catalog` | Remote Streamable HTTP MCP (JSON-RPC 2.0, zero-auth public discovery) |
| **Agent Skill Entry** | [movaui.com/skill.md](https://movaui.com/skill.md) | Machine-readable integration guide & `/llms.txt` index |

---

## Other Open-Source Agent Skills & Tools

| Repository | Focus | Stack |
|---|---|---|
| [**`movaui-skills`**](https://github.com/beautifulboy9527/movaui-skills) | Official MIT Starter Agent Skills & MovaUI Cloud Catalog MCP connector | JavaScript · MCP · Agent Skills |
| [**`cloudflare-boost`**](https://github.com/beautifulboy9527/cloudflare-boost) | Cloudflare 0-to-1 deployment & Agents SDK production field guide Skill | Cloudflare · Agent Skills |
| [**`Neo9527-unified-finance-skill`**](https://github.com/beautifulboy9527/Neo9527-unified-finance-skill) | 8-stage equity research, anomaly detection & DCF valuation Agent Skill | Python · Agent Skills |
| [**`Neo9527-xhs-feishu-sync`**](https://github.com/beautifulboy9527/Neo9527-xhs-feishu-sync) | Xiaohongshu notes/creators/comments → Feishu Bitable automation Skill | Python · Agent Skills |
| [**`RSS-News-Analyzer`**](https://github.com/beautifulboy9527/RSS-News-Analyzer) | Desktop RSS news aggregator & LLM analysis workbench | Python · PyQt5 · LLM |

---

## Quick MCP Setup (`movaui-catalog`)

Connect any MCP-compatible client (Claude Code, Cursor, Windsurf, Codex) to the public MovaUI Cloud Catalog MCP:

```json
{
  "mcpServers": {
    "movaui-catalog": {
      "url": "https://movaui.com/mcp/catalog"
    }
  }
}
```

Or explore the full skill kit in [`beautifulboy9527/movaui-skills`](https://github.com/beautifulboy9527/movaui-skills).

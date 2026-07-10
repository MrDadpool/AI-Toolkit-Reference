# AI Toolkit Reference

A curated, findable list of useful AI resources for working with Claude, Codex, and related tooling.

## Free Datasets

- [openml.org](https://openml.org)
- [kaggle.com](https://kaggle.com)
- [datasetsearch.research.google.com](https://datasetsearch.research.google.com)

## Claude Skills

| Skill | Purpose |
|-------|---------|
| `frontend-design` | Better UI |
| `code-reviewer` | Catch bugs like a senior engineer |
| `document-skills` | Generate output as a file |
| `remotion` | Build videos in code |
| `skill-creator` | Build your own skill by describing what you want |
| `security-review` | Find security vulnerabilities in your code and how to fix them |
| `review` | Review your code |
| `claude-code-setup@claude-plugins-official` | improve coding capabilities |
| `/statusline create a persistant statusline showing my directory model and current context window usage` | status line to see context usage at all time |

## GitHub Repos

| Repo | Description |
|------|-------------|
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | Thousands of free public APIs |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Better front-end design |
| [fishaudio](https://github.com/fishaudio) | Voice model |
| [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) | A skill for removing AI tells from prose |
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | Python utility for converting various files to Markdown |
| [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | Reduce token usage without impacting performance |
| [garrytan/gstack](https://github.com/garrytan/gstack) | 23 opinionated tools serving as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | Self-hosted open-source AI image and video generation studio with 200+ models (Flux, Midjourney, Kling, Sora, Veo) |
| [upstash/context7](https://github.com/upstash/context7) | Get up-to-date code documentation loaded into LLMs |
| [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) | Locally running model gateway sitting between agents (Claude Code, Codex, ZCode) and upstream model services; unifies model/API key management, routing rules, log observation, and bot handoff |
| [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | A ruleset that makes your AI coding agent write the least code that works |
| [webpro-nl/knip](https://github.com/webpro-nl/knip) | Find unused files, dependencies, and exports in JavaScript/TypeScript projects |
| [ferasbusiness666/ReconForge](https://github.com/ferasbusiness666/ReconForge) | Find security vulnerabilities in your app |
| [Pantheon-Security/medusa](https://github.com/Pantheon-Security/medusa) | Security scanner with 40,000+ detection patterns for AI/ML, agents, and LLM applications |
| [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | Use Codex from Claude Code to review code or delegate tasks |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Better UI/UX |
| [bradautomates/claude-video](https://github.com/bradautomates/claude-video) | Gives Claude the ability to watch any video. `/watch` downloads, extracts frames, transcribes, and hands it all to Claude |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | Local-first, open-source Claude Design alternative. Native desktop app, 259+ skills, 142+ design systems; web/desktop/mobile prototypes, slides, images, videos; sandboxed preview; HTML/PDF/PPTX/MP4 export; works with 17+ CLIs |
| [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | A full AI agency of specialized expert agents, each with personality, processes, and deliverables |
[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | why use many token when few token do trick — Claude Code skill that cuts 65% of tokens by talking like caveman 
| [morphllm/morph-claude-code-plugin](https://github.com/morphllm/morph-claude-code-plugin) | Morph plugin for Claude Code - chagne reasoning token burn to code |
|

## General Resources

- [claude.com/resources/use-cases](https://claude.com/resources/use-cases)
- Use **skeleton loaders** if items need time to load before they appear
- Leverage **symlinks**
- `claude agents` — see all instances of Claude running locally in a single terminal
- [greta.sh](https://greta.sh) — web app and website prompts
- [vibeui.dev](https://www.vibeui.dev/) — UI prompts organized by component
- Type `/config` > navigate to `sessionRecap` > set to enabled. Future sessions can then use `/recap`
- `brew install trash` and alias it to `rm`. If AI deletes files, they go to Trash instead of being gone

## Prompts

### The Reverse Prompt

> I want the perfect prompt for [your goal].
>
> Ask me questions one at a time until you have everything you need. Wait for my answer before the next question.
>
> When you have enough, write the perfect prompt.
>
> Then rate the prompt 1-10, tell me what's weak, and rewrite it stronger.

### The QA Team

> Generate five QA agents with 5 completely different personalities, archetypes, and personas based on who is likely to come to my site or use my app, and run a full QA test.

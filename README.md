# Zodiacs agent skill

[![skills.sh](https://skills.sh/b/zodiacs-org/skills)](https://skills.sh/zodiacs-org/skills)

> Local draft. Not yet published. The repository `zodiacs-org/skills` and the install command below work only after this draft is approved and published.

An agent skill for the Zodiacs MCP server at `https://zodiacs.org/mcp`: which tool to call, the input rules, privacy of birth details, and how to word readings.

## Install

```sh
npx skills add zodiacs-org/skills
```

Installing the skill does not connect the MCP server. Add `https://zodiacs.org/mcp` as a remote HTTP MCP server in your host, then follow the live `tools/list` schemas.

## Layout

The skill lives at `zodiacs/SKILL.md`. There is no standard skill container directory here, so the skills CLI finds it through its fallback recursive search.

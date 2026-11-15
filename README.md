# Zodiacs agent skill

[![skills.sh](https://skills.sh/b/zodiacs-org/skills)](https://skills.sh/zodiacs-org/skills)

An agent skill for the Zodiacs MCP server at `https://zodiacs.org/mcp`: which tool to call, the input rules, privacy of birth details, and how to word readings.

The skill tells agents to use birth details only for a one-time calculation the person chooses, never to store or log them, never to put them in URLs or send them to third parties, and to refuse any reading for a child under 13 without collecting anything about the child.

## Install

```sh
npx skills add zodiacs-org/skills
```

Installing the skill does not connect the MCP server. Add `https://zodiacs.org/mcp` as a remote HTTP MCP server in your host, then follow the live `tools/list` schemas.

## Layout

The skill lives at `zodiacs/SKILL.md`. There is no standard skill container directory here, so the skills CLI finds it through its fallback recursive search.

# YC Skills

A collection of agent skills for startup founders and copywriters,
inspired by top Y Combinator companies.

## Available Skills

| Skill | Description |
|-------|-------------|
| `yc-startup-landing-page` | Generate high-converting startup landing page copy |
| `yc-pitch-deck-story` | Write the story arc for a YC-style investor pitch deck |
| `yc-cold-outreach` | Write cold outreach emails to investors, customers, or partners |
| `yc-ph-launch` | Write all copy for a successful Product Hunt launch |
| `yc-investor-memo` | Write concise monthly investor updates in YC style |
| `yc-app-store-copy` | Write optimized App Store and Google Play listing copy |
| `yc-waitlist-emails` | Write welcome and drip emails that convert signups to users |

## Install All Skills

```bash
npx skills add imsurajj/yc-skills
```

## Install a Specific Skill

```bash
npx skills add imsurajj/yc-skills --skill yc-startup-landing-page
npx skills add imsurajj/yc-skills --skill yc-pitch-deck-story
npx skills add imsurajj/yc-skills --skill yc-cold-outreach
npx skills add imsurajj/yc-skills --skill yc-ph-launch
npx skills add imsurajj/yc-skills --skill yc-investor-memo
npx skills add imsurajj/yc-skills --skill yc-app-store-copy
npx skills add imsurajj/yc-skills --skill yc-waitlist-emails
```

## Install to a Specific Agent

```bash
# Claude Code
npx skills add imsurajj/yc-skills --skill yc-startup-landing-page -a claude-code

# Cursor
npx skills add imsurajj/yc-skills --skill yc-startup-landing-page -a cursor
```

## Install Globally (works across all projects)

```bash
npx skills add imsurajj/yc-skills -g
```

## Update Skills

```bash
npx skills update
```

## What is a Skill?

A skill is a markdown file that gives AI agents extra context and
instructions for a specific task. Think of it like an npm package —
but for AI behavior instead of code.

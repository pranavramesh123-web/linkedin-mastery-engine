# LinkedIn Mastery Engine

A Claude skill that rewrites LinkedIn profiles for one of three goals: attracting clients, getting hired, or building thought leadership.

It diagnoses the profile, rewrites the headline, About section, experience and Featured items, and can compare a profile against others in the same niche.

## What it does

- Asks for goal, target reader, proof points and current profile
- Scores each section and names the biggest leak
- Writes 3 headline options (max 220 characters)
- Rewrites About (max 2,600 characters) with a strong first two lines
- Turns job duties into outcome bullets
- Suggests Featured items that back up the headline
- Optional competitor and niche positioning analysis

It does not write LinkedIn posts or ads.

## Install

Claude Code or any agent that supports skills:

```bash
npx skills add <your-github-username>/linkedin-mastery-engine
```

Manual install:

```bash
mkdir -p ~/.claude/skills/linkedin-mastery-engine
cp SKILL.md ~/.claude/skills/linkedin-mastery-engine/
```

Claude.ai: zip the folder so `SKILL.md` sits at the top level, then upload it under Settings, Skills.

## Use

Ask Claude something like:

- "Optimize my LinkedIn for inbound clients" and paste your profile
- "Rewrite my headline and About for a head of marketing role"
- "Compare my profile with these three competitors"

## License

MIT

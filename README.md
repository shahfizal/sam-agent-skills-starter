# S.A.M Agent Skills — Starter Pack

![A modular rack of skill cards, one being slotted into a brass frame](assets/skill-library.png)

Four practical AI-agent skills for marketing, writing and quality control.

**Author:** Shahfizal Zainuddin
**Version:** 1.0.0 · November 2026
**License:** MIT

This is the free starter pack. It gives you the writing and marketing core of the S.A.M system: a human voice for your copy, a strategy pass, a social packaging pass and a quality gate.

The full 17-skill pack — including research, creative direction, design, video, motion and production roles — is part of the paid cohort. This starter is enough to feel the difference.

---

## What is inside

| Skill | What it does | Example trigger |
|---|---|---|
| **human-voice-pass** | Marketing and social copy that sounds like a person: removes AI tells, matches your voice from samples, adds only verifiable detail. | "Humanise this caption; it sounds like ChatGPT." |
| **studio-marketing-strategist** | Audience, positioning, message hierarchy, channel plan and call to action. | "Turn this offer into a campaign brief." |
| **studio-social-manager** | Platform specs, captions, hashtags, scheduling and post packaging. | "Package this for Instagram, TikTok and LinkedIn." |
| **studio-qa** | Acceptance criteria, technical checks and brand-safety review. | "Review this before I send it to the client." |

---

## Quick start

### OpenCode

Clone the repository:

```bash
git clone https://github.com/shahfizal/sam-agent-skills-starter.git
```

Add the absolute path of its `skills` folder to your OpenCode config:

```jsonc
{
  "$schema": "https://opencode.ai/config.json",
  "skills": ["C:/Users/YOU/sam-agent-skills-starter/skills"]
}
```

Start a new session and test:

> Use the human-voice-pass skill on this caption: "In today's fast-paced digital landscape..."

### Claude Code

```bash
git clone https://github.com/shahfizal/sam-agent-skills-starter.git
mkdir -p ~/.claude/skills
cp -R sam-agent-skills-starter/skills/* ~/.claude/skills/
```

On Windows PowerShell:

```powershell
git clone https://github.com/shahfizal/sam-agent-skills-starter.git
New-Item -ItemType Directory -Force "$HOME\.claude\skills" | Out-Null
Copy-Item -Recurse .\sam-agent-skills-starter\skills\* "$HOME\.claude\skills\"
```

### Let your agent install it

```text
Clone https://github.com/shahfizal/sam-agent-skills-starter into
~/sam-agent-skills-starter.

Install every folder under ~/sam-agent-skills-starter/skills into my agent's
skills directory. If you are OpenCode, add the absolute path to the "skills"
array in ~/.config/opencode/opencode.json. If you are Claude Code, copy each
folder to ~/.claude/skills/. Preserve every SKILL.md and references/ file.
Do not edit the contents. Then list the installed skills and give me one
example prompt for each.
```

---

## The full pack

The private cohort pack adds 13 more skills:

- research and evidence
- creative direction
- graphic design and image generation
- video generation, editing and motion
- production pipeline, engineering and delivery
- asset management and approvals

It also includes advanced playbooks, templates and updates used in the coaching programme.

If you are an enrolled student, use the private repository link and the GitHub account you gave at enrolment. If you are not enrolled, start with this starter pack and apply the free skills to one real piece of work.

---

## How to use a skill

Name the skill in the brief:

> Use the studio-social-manager skill to package this post for Instagram and LinkedIn.

Or describe the task and let the agent choose:

> This caption sounds like ChatGPT. Make it sound like me. Here are three things I wrote myself.

A skill is not a magic prompt. It is a checklist that keeps you consistent when the work gets boring.

---

## Updating

```bash
cd sam-agent-skills-starter
git pull
```

---

## License

MIT. See `LICENSE`.

You may use, adapt and share these skills with attribution. The full cohort pack has a separate licence and is not included here.

---

## About the programme

These skills are the practical companion to **The Agentic Marketer** by Shahfizal Zainuddin and the Agentic AI coaching programme for startups. The free pack is the toolkit; the programme is where we apply it to your business, your offers and your taste.

For cohort access, contact Shahfizal.

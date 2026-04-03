# ai-technical-manager

OpenCode skill for AI Technical Manager - represents the AI Engineering and Research team.

## What It Does

This skill acts as a bridge between the AI team and external stakeholders (Product Managers, engineering teams, executives). It handles:

- **Team capabilities queries** - Summarizes AI team achievements, technical capabilities, and roadmap
- **PRD feasibility reviews** - Evaluates technical feasibility for new AI product requests
- **Market analysis** - Provides competitive intelligence on AI healthcare sector
- **Stakeholder communication** - Translates technical details for non-technical audiences

## When to Use

Use this skill when users ask about:
- AI team capabilities or status
- Technical roadmap and collaboration opportunities
- PRD/feature feasibility evaluation
- Market analysis for AI healthcare products
- Cross-team technical discussions

## Context Directories

The skill reads from these directories in the workspace:

| Directory | Contents |
|-----------|----------|
| `team/` | Team achievements, technical capabilities, roadmap |
| `prd/` | Product Requirement Documents |
| `prd-plan/` | Feature requests and product plans |
| `market/` | Market research, competitive analysis |

## Installation

Clone this repo into your OpenCode skills directory, or install the `.skill` file directly.

## Usage Example

```
User: 产品经理让我了解一下AI团队现在能做什么，想给我们康养平台加一个智能健康建议功能
Skill: [Provides team capabilities summary, feasibility analysis, roadmap status]
```

## Supported Tasks

- Team capability presentations
- Technical feasibility reports
- Market analysis reports
- Roadmap defense and alternatives
- PRD evaluation with clarifying questions

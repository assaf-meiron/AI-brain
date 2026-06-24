# AI-Brain: The Central Knowledge Hub for CheckIT & FollowIT

## Overview

AI-Brain is the single source of truth for CheckIT and FollowIT. It serves as the centralized knowledge repository and decision-making hub for Product Managers, R&D teams, and Executives. This repo contains product strategies, roadmaps, feature specifications, knowledge bases, and AI-powered tools to accelerate product development.

## Who Is This For?

- **Product Managers**: Find strategies, roadmaps, user insights, and tools to write better PRDs
- **R&D Teams**: Understand product direction, strategy, and feature context
- **Executives**: Access high-level strategy, roadmaps, and market insights

## Repository Structure

```
AI-brain/
├── products/                    # Product-specific information
│   ├── CheckIT/
│   │   ├── overview.md         # Product vision, mission, metrics
│   │   ├── strategy.md         # Strategic decisions and pillars
│   │   ├── roadmap.md          # Feature roadmap and timeline
│   │   └── features/           # Individual feature documentation
│   └── FollowIT/
│       ├── overview.md
│       ├── strategy.md
│       ├── roadmap.md
│       └── features/
├── knowledge-base/             # Shared knowledge and research
│   ├── user-personas.md        # User segments and personas
│   └── stakeholder-needs.md    # What different stakeholders need
├── prd-templates/              # PRD templates and examples
├── skills/                      # AI-powered skills for PMs
└── agents/                      # AI agents for research and analysis
```

## How to Use This Repo

### For Product Managers
1. **Start with product overview**: Read `products/[Product]/overview.md` to understand vision and metrics
2. **Review strategy**: Check `products/[Product]/strategy.md` for strategic decisions
3. **Write PRDs**: Use templates in `prd-templates/` and leverage skills to accelerate writing
4. **Reference knowledge**: Find user personas and stakeholder needs in `knowledge-base/`

### For R&D Teams
1. **Understand product direction**: Start with the product roadmap
2. **Deep dive into features**: Read feature documentation in `products/[Product]/features/`
3. **Understand strategic context**: Review strategy documents to grasp the "why" behind decisions

### For Executives
1. **Review product overviews**: Get high-level product vision and metrics
2. **Check roadmaps**: See planned features and timeline
3. **Understand strategy**: Review strategic pillars and market positioning

## Key Sections Explained

### Products
Each product (CheckIT, FollowIT) has its own folder containing:
- **overview.md**: Product vision, mission, key metrics, target users, value proposition
- **strategy.md**: Strategic pillars, positioning, competitive advantages, go-to-market decisions
- **roadmap.md**: Feature roadmap, timeline, priorities, success metrics
- **features/**: Individual feature specs and documentation

### Knowledge Base
Shared knowledge that applies across products:
- **user-personas.md**: User segments, behaviors, pain points, goals
- **stakeholder-needs.md**: What PMs, executives, customers, and other stakeholders need

### PRD Templates
Ready-to-use templates and example PRDs to accelerate PM workflow.

### Skills
AI-powered skills to help PMs work faster:
- PRD writing assistance
- User research synthesis
- Competitive analysis
- Roadmap planning
(Specific skills TBD)

### Agents
AI agents that can perform deeper research and analysis:
- Market research agent
- User research agent
- Feature prioritization agent
(Specific agents TBD)

## Conventions & Guidelines

### File Naming
- Use kebab-case for file and folder names: `user-personas.md`, `go-to-market-strategy.md`
- Use descriptive names that make the content clear

### Content Standards
- Start each document with an overview section
- Use clear headings and subheadings
- Include metadata (last updated, owner, status) at the top
- Link to related documents
- Keep documents focused and modular

### Metadata Format
```markdown
---
owner: [Name]
last_updated: YYYY-MM-DD
status: [draft|active|archived]
---
```

### Linking Between Documents
Use relative links to connect related documents:
```markdown
See also: [User Personas](../../knowledge-base/user-personas.md)
```

## Getting Started

1. **Start here**: Read this CLAUDE.md file (you are here)
2. **Choose your product**: Go to `products/CheckIT/` or `products/FollowIT/`
3. **Read the overview**: Understand the product vision and metrics
4. **Explore related docs**: Use links to navigate related information

## Contributing

When adding or updating content:
1. Follow the conventions listed above
2. Include metadata (owner, last_updated, status)
3. Link to related documents
4. Keep documents modular and focused
5. Update the README/overview when adding new major sections

## FAQs

**Q: Where should I put new feature documentation?**
A: In the `products/[Product]/features/` folder. Create a new markdown file with a descriptive name.

**Q: How do I update the roadmap?**
A: Edit `products/[Product]/roadmap.md`. Include timeline, priorities, and success metrics.

**Q: Can I use the AI skills to help me?**
A: Yes! Check the `skills/` folder for available AI-powered tools to accelerate your work.

**Q: Who owns this repo?**
A: This is a shared resource. Each document should have a clear owner listed in the metadata.

## Support

For questions about this repo structure or content, reach out to the Product team lead.

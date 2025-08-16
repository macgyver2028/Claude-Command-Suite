# /ok - The Universal Smart Router

## Core Function
The one command that does everything. PROACTIVELY reads context, detects what you need, and automatically routes to the appropriate specialized function. No thinking required - just autonomous momentum.

## Context Detection & Smart Routing

### Step 1: Read Current State
I will PROACTIVELY and automatically:
- Read `./memory.md` if it exists for project context
- Check git status for uncommitted changes
- Detect recent commits (suggests code review needed)
- Identify project type (Go/PHP/JS/Python/Rust)
- Look for error mentions in conversation or memory
- Check for TODOs or incomplete work
- Count markdown files (suggests processing needed)

### Step 2: Apply Priority Routing

**🚨 Priority 1: CRITICAL** (Fix blocking issues first)
- Build errors, test failures → Load debugging patterns
- Runtime crashes, dependency issues → Systematic troubleshooting

**🏁 Priority 2: CLEANUP** (Complete current work)
- Uncommitted git changes → Load project completion patterns
- TODOs in memory.md → Task finishing workflows

**👀 Priority 3: REVIEW** (Quality check recent work)
- Recent commits detected → Load code review patterns
- New features → Quality analysis and feedback

**🔧 Priority 4: REFACTOR** (Improve existing code)
- Go projects → Load Go-specific improvement patterns
- PHP projects → Load Laravel/PHP refactoring patterns
- JS projects → Load React/TypeScript optimization patterns
- Python/Rust → Load language-specific patterns

**📄 Priority 5: PROCESS** (Organize content)
- Multiple markdown files → Load content merging patterns
- Research compilation → Content organization workflows

**⚡ Default: MOMENTUM** (Continue flow)
- Active development → Maintain current work momentum
- Flow state → Brief acknowledgment + next action

### Step 3: Load Appropriate Patterns
Based on detected context, I will load the relevant reference materials:
- `~/ai/docs/commands/core-principles.md` (always)
- `~/ai/docs/commands/util-debug.md` (for debugging)
- `~/ai/docs/commands/project-finish.md` (for cleanup)
- `~/ai/docs/commands/analyze-review.md` (for code review)
- `~/ai/docs/commands/refactor-{language}.md` (for improvements)
- `~/ai/docs/commands/process-merge.md` (for content processing)
- `~/ai/docs/commands/project-momentum.md` (for continuation)

### Step 4: Execute with Context
Provide brief acknowledgment in format:
```
🔍 [Context detected]
🎯 [Route chosen] 

✓ [What was accomplished]
→ [What I'm doing next]

[Immediate appropriate action]
```

## Manual Override Support
You can still call specialized routers directly when needed:
- `/refactor` - Force code improvement mode
- `/analyze` - Force analysis mode  
- `/project` - Force project management mode
- `/util` - Force utility mode
- `/process` - Force content processing mode

## Philosophy
**"One command, infinite intelligence."** Just type `/ok` and let me PROACTIVELY figure out what you need and take action. No decisions, no cognitive overhead, just autonomous continuous momentum toward better code and completed projects.

The universal router handles 95% of scenarios automatically while preserving access to specialized modes when manual control is needed.
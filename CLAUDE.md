# Claude Instructions

## First: Read STATUS.md
Always check `STATUS.md` first to understand:
- Current phase
- What's been decided
- What's next

## How to Work on This Project

### In Claude Desktop (Brainstorming)
- Use EXTRACTIVE brainstorming style (see below)
- Record all decisions in STATUS.md
- Update brainstorm session files

### In Claude Code (Building)
- Check GitHub Project board for tasks
- Only work on tasks assigned to Claude
- Commit frequently with clear messages
- Update STATUS.md when tasks complete

---

## EXTRACTIVE BRAINSTORMING RULES

**This is critical. Read carefully.**

Brainstorming is NOT:
- Walls of text
- Making decisions for the user
- Dumping 10 options and picking one
- Rushing to execution

Brainstorming IS:
- Asking questions to extract ideas from the user's head
- Going deep on each idea before moving on
- Being a thinking partner
- Letting the user lead

### How to Brainstorm

1. **Ask, don't tell**
   - "What comes to mind when you think about...?"
   - "Tell me more about that"
   - "Why is that important to you?"
   - "What would that look like?"

2. **One thing at a time**
   - Don't overwhelm with multiple topics
   - Finish exploring one idea before moving to next
   - Go deep, not wide

3. **Reflect back**
   - "So what I'm hearing is..."
   - "It sounds like you value..."
   - "Let me make sure I understand..."

4. **Don't assume**
   - Ask about preferences, don't guess
   - Check assumptions before building on them
   - "Is that what you mean, or something different?"

5. **Build on their ideas**
   - "That's interesting, what if we also..."
   - "How would that work with..."
   - "What about this angle..."

6. **Know when to synthesize**
   - After exploring, summarize what you've learned
   - Present it back for confirmation
   - Only then suggest next steps

### Example: Bad vs Good

**BAD:**
```
User: Let's brainstorm the agency name
Claude: Here are 15 name ideas:
1. SpeedWeb - because fast delivery
2. AIForge - because AI powered
3. ... [wall of text]
I recommend SpeedWeb because...
```

**GOOD:**
```
User: Let's brainstorm the agency name
Claude: Before we dive into names, I want to understand what matters to you.

When someone hears your agency name, what feeling should they get?

- Professional and established?
- Innovative and cutting-edge?
- Friendly and approachable?
- Something else?
```

---

## Brainstorm Topics Order

1. **Brand Identity** - Name, values, positioning
2. **Legal Setup** - UK Ltd registration
3. **Services** - What we offer
4. **Pricing** - How we charge
5. **Client Workflow** - How projects flow
6. **Website** - Our online presence
7. **Growth** - How we scale

Each topic has a folder in `brainstorm/` with:
- Questions to explore
- Session notes (added during brainstorming)
- Decisions (added when finalized)

---

## GitHub Workflow

- **Issues** = Tasks or topics to explore
- **Project Board** = Visual task tracker
- **Labels:**
  - `human` = Task for Wasim
  - `claude` = Task for Claude
  - `brainstorm` = Needs discussion
  - `decision-needed` = Waiting on decision
  - `blocked` = Can't proceed

---

## Commit Messages

Use clear, descriptive commits:
```
Add brand brainstorm session notes
Update STATUS.md - brand decisions made
Create proposal template v1
```

---

## Remember

- GitHub is source of truth
- STATUS.md is the quick reference
- Project board tracks tasks
- Ask questions, don't assume
- The user's ideas matter most

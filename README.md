# Claude Chat Instructions

Stop re-explaining your preferences every chat. Upload one file, get consistent results.

## The Problem

Every time you start a new Claude chat, you're starting from scratch:
- Re-explaining how you want responses
- Getting inconsistent results
- Losing track of what you accomplished when conversations end
- Claude guessing instead of asking
- No continuity between sessions

## The Solution

**Chat instruction files** - a simple markdown file you upload at the start of each chat that tells Claude:
- How you prefer to communicate
- When to ask questions vs. making assumptions  
- How to handle multi-step work
- When to pause for your review
- How to save summaries for next time

**Result:** Consistent behavior, better handoffs, and instructions that improve over time.

## Quick Start

### 1. Choose Your Template

**New to this?** Start here:
- **[LITE Version](LITE_v1.0.md)** - 5 essential rules, 2-minute setup

**Want full control?** Go comprehensive:
- **[FULL Template](FULL_TEMPLATE_v1.0.md)** - 10 rules, extensive customization

### 2. Upload to Your Chat

1. Download the template
2. Start a new Claude chat  
3. Upload the file
4. Say: "I've uploaded instructions, confirm you've read them"
5. Start working - Claude will follow your preferences

### 3. Customize Over Time

- Add rules that would have helped
- Remove rules you never use
- Let Claude suggest improvements based on patterns it notices

## What Makes This Different

### Self-Improvement Protocol

The killer feature: **Your instructions evolve with you.**

Claude notices patterns in your preferences and suggests new rules:

```
💡 INSTRUCTION SUGGESTION:

I've noticed you always ask me to create files instead 
of chat output (happened 4 times this session).

Suggested new rule:
"For code >50 lines, automatically create a file"

Should I add this to your instructions?
```

Your instruction file gets smarter with every chat.

## Key Features

✅ **Consistency** - Same behavior every chat  
✅ **Efficiency** - Less back-and-forth, better first-time results  
✅ **Continuity** - Automatic summaries for next session  
✅ **Clarity** - Claude asks instead of guessing  
✅ **Evolution** - Instructions improve based on your patterns  
✅ **Customizable** - Adapt to your workflow and domain

## Examples by Use Case

Need inspiration? Check out example instruction files:

- **[For Developers](examples/FOR_DEVELOPERS.md)** - Code style, debugging protocols
- **[For Writers](examples/FOR_WRITERS.md)** - Tone preferences, draft management  
- **[For Researchers](examples/FOR_RESEARCHERS.md)** - Citation requirements, analysis depth
- **[For Learners](examples/FOR_LEARNERS.md)** - Explanation preferences, pacing

## What's Included

| File | Description | Best For |
|------|-------------|----------|
| `LITE_v1.0.md` | 5 core rules, minimal setup | First-timers, testing the concept |
| `FULL_TEMPLATE_v1.0.md` | 10 comprehensive rules | Regular users, complex projects |
| `WHY_USE_INSTRUCTIONS.md` | Detailed benefits guide | Understanding the full value |
| `examples/` | Domain-specific templates | Finding your starting point |

## Real Impact

**After 1 week:**
- Save 5-10 minutes per chat on setup
- Fewer clarification rounds
- More consistent results

**After 1 month:**
- Instructions tailored to your workflow
- Seamless project continuity across chats
- Predictable, reliable outputs

**After 3 months:**
- Claude feels like it "knows you"
- Self-improvement protocol has added 5-10 optimized rules
- Compounding time savings

## How It Works

### Token Monitoring
- Instructions help Claude track conversation capacity
- Warns before running out of space
- Creates summaries automatically when needed
- Prevents mid-task interruptions

### Decision Points
- Claude asks before making assumptions
- Confirms scope before starting major work
- Presents alternatives when multiple approaches exist
- Pauses at milestones for your review

### Error Recovery
- Stops after 2 failed attempts to reassess
- Suggests different approaches instead of repeating failures
- Saves time and frustration

### Learning Opportunities
- Offers to explain complex solutions (optional)
- Matches detail level to your needs
- Builds on knowledge from previous sessions

## Contributing

Found a useful rule? Have a better approach? Contributions welcome!

- Share your customized templates
- Suggest improvements to existing templates
- Add domain-specific examples
- Report what works (and what doesn't)

## FAQ

**Do I need technical skills?**  
No. If you can edit a text file, you can customize these instructions.

**Will this work for my field?**  
Yes. The templates are intentionally general. Add your domain-specific rules in the customization sections.

**Can I modify the templates?**  
Absolutely! That's the point. These are starting points for YOUR perfect instruction set.

**How much does this cost?**  
Free. Open-source. No strings attached.

**What if I want to change behavior mid-chat?**  
Just say "Ignore [rule name] for now" or use override commands like "QUICK MODE"

**Will this use up my conversation space?**  
The lite version uses ~1% of your conversation budget. The time it saves far outweighs the cost.

## License

MIT License - Use freely, modify as needed, share improvements.

## Acknowledgments

Built from real-world experience managing complex Claude conversations. 

Thanks to everyone who will contribute improvements and share their customizations.

---

**Stop repeating yourself. Start working smarter.**

[Download LITE](LITE_v1.0.md) | [Download FULL](FULL_TEMPLATE_v1.0.md) | [Learn Why](WHY_USE_INSTRUCTIONS.md)

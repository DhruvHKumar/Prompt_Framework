# EPPE Framework: Vibecoding with AI Coders

## What is Vibecoding?
Vibecoding is a creative, intuitive approach to building applications with AI assistance where you focus on the **vibe** and experience you want rather than detailed technical specifications. You communicate intent, aesthetic, and feeling, letting the AI handle implementation details.

---

## The EPPE Framework

### 1. **ENVISION** 🎨
*Capture the vibe, feel, and essence of what you want to create*

#### Key Activities:
- **Define the emotional goal**: What should users *feel* when using this?
- **Describe the aesthetic**: Modern? Retro? Minimalist? Bold? Playful?
- **Sketch the experience**: What's the user journey? What's the "wow" moment?
- **Set the mood**: Colors, animations, interactions that create atmosphere
- **Identify the core value**: What problem does this solve or joy does it bring?

#### Example Envision Statement:
> "I want a meditation timer that feels like watching a sunset—warm gradients, smooth transitions, peaceful ambient sounds. Users should feel calm just looking at it. Think: soft oranges and purples, gentle fade-ins, no harsh edges."

#### Prompts to Ask Yourself:
- If this app was a movie scene, what would it look like?
- What's the one emotion I want users to leave with?
- What existing apps/sites have a vibe I love?

---

### 2. **PLAN** 📋
*Structure the vision into actionable components*

#### Key Activities:
- **Break down features**: List core functionality vs. nice-to-haves
- **Map the user flow**: Start → Core action → End state
- **Identify key interactions**: Buttons, forms, animations, transitions
- **Consider technical constraints**: Web app? Mobile? Data storage needs?
- **Prioritize ruthlessly**: What's the MVP that captures the vibe?

#### Planning Template:
```
CORE FEATURES (Must-have)
- [ ] Feature 1: [What it does + why it matters to the vibe]
- [ ] Feature 2: [What it does + why it matters to the vibe]

VIBE ELEMENTS (Design/UX)
- [ ] Visual style: [Color palette, typography, spacing]
- [ ] Interactions: [Hover effects, animations, transitions]
- [ ] Audio/haptics: [Sounds, vibrations if applicable]

TECHNICAL NEEDS
- [ ] Data persistence: [What needs to be saved?]
- [ ] APIs/integrations: [External services needed?]
- [ ] Responsive design: [Desktop, mobile, both?]
```

#### Pro Tips:
- Keep the plan flexible—vibecoding embraces iteration
- Don't over-specify; leave room for AI creativity
- Focus on *what* not *how* (AI handles the how)

---

### 3. **PROMPT** 💬
*Communicate effectively with your AI coder*

#### Prompting Principles:

**A. Start with Context**
```
"I'm building [type of app] that should feel [adjective/vibe].
The main purpose is [core function].
Target users are [audience] who want [outcome]."
```

**B. Use Vivid Descriptions**
- ❌ "Make it look good"
- ✅ "Use a dark glassmorphic design with subtle purple glows, like a cyberpunk interface but more refined"

**C. Reference Examples**
- "Similar to how Stripe's homepage feels modern and trustworthy"
- "With animations like Apple's product pages—smooth and purposeful"
- "Color palette inspired by Dracula theme but lighter"

**D. Specify Interactions**
- "When users hover, cards should gently lift with a shadow"
- "Transitions between screens should fade smoothly over 300ms"
- "Loading states should feel fun, not frustrating—maybe a playful animation"

**E. Iterate with Feedback**
- "This is great, but can we make it feel more energetic?"
- "The layout works, but let's add more breathing room"
- "Can we make the primary action more prominent without being aggressive?"

#### Example Vibecoding Prompt:
```
Create a personal finance dashboard that feels empowering, not stressful.

VIBE: Clean, optimistic, game-ified
STYLE: Soft gradients (teal to blue), rounded corners, playful icons
KEY FEATURES:
- Spending overview with smooth animated charts
- Budget progress bars that feel like achievements
- Quick add expense button—should be satisfying to tap

INTERACTIONS:
- Charts should animate in on load
- Budget bars fill smoothly when data loads
- Haptic feedback on actions (if mobile)
- Celebrate when users hit savings goals (confetti?)

Make it feel like you're making progress, not being judged.
```

---

### 4. **EXECUTE** ⚡
*Build, test, and refine iteratively*

#### Execution Cycle:

**Phase 1: Rapid Prototype**
1. Ask AI to build the core experience first
2. Focus on the main user flow with proper styling
3. Test the vibe: Does it *feel* right?
4. Iterate quickly on aesthetic before adding features

**Phase 2: Feature Build-Out**
1. Add features one at a time
2. Maintain the vibe with each addition
3. Test interactions on actual devices
4. Refine animations and transitions

**Phase 3: Polish**
1. Fine-tune colors, spacing, typography
2. Add micro-interactions and delightful details
3. Optimize performance (smooth = good vibe)
4. Test with real users for vibe check

#### Iteration Techniques:

**The Vibe Check**
After each build, ask:
- Does this feel like what I envisioned?
- Would I actually want to use this?
- What's the first thing that feels "off"?

**Rapid Refinement Prompts**
- "This works functionally but feels too corporate—can we loosen it up?"
- "Let's make this section more playful"
- "The hierarchy feels flat—help me make the important stuff pop"
- "This loads well but feels abrupt—can we smooth the entrance?"

**Progressive Enhancement**
- Start with basic functionality + great design
- Layer in animations and interactions
- Add delight moments (easter eggs, celebrations)
- Optimize for performance and accessibility

---

## EPPE in Action: Complete Example

### Project: Task Manager for Creative Professionals

#### ENVISION
"A task manager that feels like a creative workspace, not a corporate to-do list. Kanban-style but with personality. Think: art gallery meets productivity—spacious, inspiring, with satisfying interactions. Users should feel motivated, not overwhelmed."

#### PLAN
```
CORE FEATURES
- [ ] Drag-and-drop task cards between columns (To Do, In Progress, Done)
- [ ] Quick add task with keyboard shortcut
- [ ] Color-coded task categories
- [ ] Simple task editing (title, description, category)

VIBE ELEMENTS
- [ ] Pastel color palette with high contrast text
- [ ] Smooth drag animations with subtle spring physics
- [ ] Empty states that inspire ("Your canvas awaits")
- [ ] Satisfying completion animation (task fades out with particle effect)

TECHNICAL
- [ ] Local storage for data persistence
- [ ] Keyboard shortcuts (N for new, Enter to save)
- [ ] Responsive: desktop-first, mobile-friendly
```

#### PROMPT
"Create a kanban task manager with a creative, gallery-like aesthetic.

VISUAL VIBE: Spacious whitespace, soft pastel cards (peach, mint, lavender), clean sans-serif typography, subtle shadows that suggest depth not clutter.

INTERACTIONS:
- Dragging cards should feel smooth and weighty (spring physics)
- Dropping a card should have a satisfying 'settle' animation
- Completing a task (moving to Done) triggers a brief celebratory effect
- Empty columns show inspirational messages with elegant typography

LAYOUT: Three columns (To Do, Doing, Done), cards display as gallery items with hover lift effect. Add task button should be prominent but elegant.

Make it feel like organizing creative projects, not checking off chores."

#### EXECUTE
1. **Build prototype** → Test drag feel and card aesthetics
2. **Iterate**: "Cards feel heavy—can we make drag more fluid?"
3. **Add features** → Categories, quick add, keyboard shortcuts
4. **Polish** → Completion animations, empty states, micro-interactions
5. **Final vibe check** → Does this inspire creativity? Adjust colors/spacing
6. **Ship** → Celebrate! 🎉

---

## Best Practices for EPPE Vibecoding

### Do's ✅
- **Be specific about feelings** rather than just functions
- **Use metaphors and references** to communicate aesthetic
- **Iterate in small steps** while maintaining the vibe
- **Test on real devices** early and often
- **Trust your gut** on what feels right
- **Embrace happy accidents** from AI creativity

### Don'ts ❌
- **Don't over-specify implementation** (let AI choose the best approach)
- **Don't ignore performance** (slow ≠ good vibe)
- **Don't add features that break the vibe** for functionality's sake
- **Don't skip the envision phase** (tech without vision is soulless)
- **Don't be afraid to start over** if the vibe is fundamentally off

---

## Quick Reference: EPPE Cheat Sheet

| Phase | Focus | Key Question |
|-------|-------|--------------|
| **Envision** | Emotional resonance | "What should this *feel* like?" |
| **Plan** | Structure & priority | "What creates this feeling?" |
| **Prompt** | Clear communication | "How do I describe this vibe?" |
| **Execute** | Iterative refinement | "Does this match the vision?" |

---

## Final Thoughts

Vibecoding with the EPPE framework shifts development from technical specification to creative direction. You become the **creative director** while AI is your **implementation partner**. The result? Applications that not only work well but *feel* incredible to use.

**Remember**: Great vibecoding is 20% planning, 30% prompting, and 50% iterating until it feels *just right*.

Now go build something that vibes. ✨

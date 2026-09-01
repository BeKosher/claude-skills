# Micro-Tool Digital Product Builder Skill

## Overview
This skill guides Claude in helping you ideate, validate, and build high-quality micro-tools as digital products with speed-to-market focus.

## Core Principles
- **Problem-First Approach**: Start with a real problem, then build the solution
- **Code Quality + Speed**: Maintain high code standards while shipping quickly
- **Validation Early**: Test market assumptions before heavy investment
- **Lean MVP**: Build the minimum viable product, not the dream product
- **User-Centric**: Every feature decision should tie back to user needs

## Phase 1: Ideation & Validation

### When to Apply This Phase
User is exploring a potential micro-tool idea and needs validation before building.

### Your Role
1. **Problem Definition**
   - Ask clarifying questions about the specific problem being solved
   - Identify who experiences this problem (target user)
   - Determine frequency and pain level of the problem
   - Quantify the problem (how many potential users?)

2. **Market Validation Questions**
   - Is this a problem people will pay for?
   - Who are 3-5 direct competitors or alternatives?
   - What makes your solution different?
   - What's the target pricing model?
   - How would users discover this tool?

3. **Validation Tactics to Suggest**
   - **Landing page test**: Create a simple landing page, drive traffic, measure conversion
   - **Presales**: Reach out to 10-20 potential users and ask if they'd pay
   - **Survey validation**: Simple Google Form to 50+ people in the target market
   - **Problem interviews**: Have 5 unscripted conversations with target users
   - **Quick prototype**: Build a rough MVP in 2-3 days and get feedback

4. **Validation Criteria (Go/No-Go)**
   - Minimum: 3-5 people willing to pay or commit to using it
   - Preferred: 15%+ conversion rate on landing page
   - Red flags: Can't identify target user, no clear differentiation, solution looking for a problem

### Questions to Ask
- "Who would use this tool daily/weekly?"
- "What alternative do they use now?"
- "What's the biggest friction point?"
- "Would they pay? How much?"
- "How would they find out about this?"

---

## Phase 2: MVP Planning & Architecture

### When to Apply This Phase
Idea is validated, now planning the technical build.

### Your Role
1. **Feature Prioritization**
   - List ALL potential features
   - Mark as: Core (MVP), Important (Phase 2), Nice-to-Have (Phase 3+)
   - Core should be 3-5 features max
   - Rule: If it's not essential to solve the core problem, it's not MVP

2. **Technical Architecture**
   - Suggest fastest path to market tech stack
   - Prioritize: Simplicity > Flexibility
   - Use: Proven frameworks, avoid bleeding-edge tech
   - Consider: Hosting, scaling, maintenance burden

3. **Code Quality Standards (for speed without compromise)**
   - Clean, readable code with clear naming
   - Modular structure (easy to refactor/extend)
   - Error handling and validation
   - Basic tests for critical paths
   - Documentation for complex logic
   - NOT perfectionism: Avoid over-engineering

4. **Scope Definition**
   - Time estimate for MVP: 1-4 weeks (depending on complexity)
   - Define exact "done" criteria before building
   - Identify potential scope creep risks
   - Plan Phase 2 features separately

### Tech Stack Recommendations
- **Frontend**: React/Vue (familiar) or simple HTML/CSS for ultra-fast builds
- **Backend**: Node.js, Python, or your strongest language
- **Database**: PostgreSQL or MongoDB (proven, scalable)
- **Hosting**: Vercel, Railway, or AWS (simple deployment)
- **Auth**: Clerk, Auth0, or simple JWT (if needed for MVP)

### Questions to Ask
- "What's the absolute minimum to solve the user's problem?"
- "What could we build in 1 week vs. 1 month?"
- "Where will code quality issues hurt us most?"
- "What technical debt are we accepting for speed?"

---

## Phase 3: Building & Shipping

### When to Apply This Phase
Ready to code and launch.

### Your Role
1. **Development Workflow**
   - Create detailed task breakdown (each task: 2-4 hours max)
   - Suggest development order (front-end UI → back-end logic → integration → polish)
   - Check for scope creep regularly
   - Recommend daily shipping mentality: Deploy early, deploy often

2. **Code Quality Checks**
   - Code review mindset (even for solo builds)
   - Catch common bugs before shipping
   - Performance review (page load, response times)
   - Security basics (input validation, auth, data protection)
   - Testing focus: Happy path + common error cases

3. **Shipping Readiness**
   - Error handling: All edge cases have graceful fallbacks
   - Performance: Core user flows are fast (<2s load time)
   - UX: Clear CTAs, intuitive navigation
   - Documentation: How to use the tool, support info
   - Analytics: Track key user actions (optional for MVP)

4. **Launch Strategy**
   - Beta users first (validated users from Phase 1)
   - Gather feedback immediately
   - Be ready to iterate based on real usage
   - Plan launch channels: Twitter, ProductHunt, Reddit, niche communities

### Questions to Ask
- "Is this code maintainable for future you?"
- "What could break when users actually use it?"
- "Are we over-building any feature?"
- "What's the simplest way to ship this?"

---

## Phase 4: Post-Launch Learning

### When to Apply This Phase
Tool is live, now measuring what works.

### Your Role
1. **Metrics to Track**
   - Signups, active users, retention
   - Feature usage (which features matter?)
   - Support issues (common problems?)
   - Revenue/payments (if applicable)

2. **Feedback Loops**
   - Early user interviews (why they signed up, what's hard)
   - Support request patterns
   - Usage analytics
   - Feature requests

3. **Iteration Priorities**
   - Fix bugs that block usage
   - Improve features users actually use
   - Build Phase 2 features based on demand
   - Cut features nobody uses

---

## Quick Reference: Micro-Tool Checklist

### Before Building
- [ ] Interviewed 5+ target users about the problem
- [ ] Validated someone would pay for this
- [ ] Defined MVP scope (3-5 core features)
- [ ] Estimated build time (realistic)
- [ ] Chose tech stack (favor speed + simplicity)

### While Building
- [ ] Code is clean and modular
- [ ] Error handling for common failures
- [ ] Core user flow tested
- [ ] Performance acceptable (<2s load)
- [ ] No scope creep—MVP only

### Before Launching
- [ ] Beta test with 5-10 real users
- [ ] All critical bugs fixed
- [ ] UX is intuitive
- [ ] Documentation/help exists
- [ ] Analytics/feedback mechanism in place

### After Launching
- [ ] Track user behavior
- [ ] Respond to early feedback quickly
- [ ] Plan Phase 2 based on data
- [ ] Keep shipping small improvements

---

## Key Prompts to Use

When you need help, provide Claude with context like:
- **"I have an idea for a [type] tool that solves [problem]. Validate this?"**
- **"Help me plan the MVP for [tool name]—what's core vs. nice-to-have?"**
- **"Code review: is this production-ready quality for a micro-tool?"**
- **"I launched [tool]. Users are [doing X]. What should I build next?"**
- **"Speed up this [code]—what's the fastest safe approach?"**

---

## Anti-Patterns to Avoid

❌ **Perfectionism**: Waiting for perfect code before shipping
❌ **Scope creep**: Adding features not in MVP
❌ **No validation**: Building without talking to users
❌ **Wrong tech**: Choosing trendy tools over proven ones
❌ **No metrics**: Launching blind without tracking anything
❌ **Over-engineering**: Building for scale before proving demand
❌ **Lone wolf**: Not getting any early feedback before launch

---

## Success Metrics

✅ Validated idea before building (saved time/money on bad ideas)
✅ MVP shipped in planned timeframe
✅ Code quality is high enough to maintain/extend
✅ First users give positive feedback
✅ You know exactly what to build next (based on data)

---

## Related Skills
- Code quality & performance optimization
- User research & validation techniques
- Product management & prioritization
- Launch strategies & marketing

---

*Last Updated: 2026-09-01*
*Created for: BeKosher's Digital Product Business*

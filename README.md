# Building-with-Lovable-and-Gemini-Pro

## Context

This practical session is designed to help participants rapidly prototype a digital product using AI-powered tools.
The goal is not to build a perfect product, but to:

1. Clarify ideas
2. Translate ideas into structured product thinking
3. Produce a functional, interactive prototype that can be tested, shared, or pitched

Participants will use AI tools as thinking partners, not just generators, to move from idea → PRD → prototype.

## Challenge Overview
Participants will select one challenge and create a prototype solution.

### Challenge Options
| Challenge | Description |
|-----------|-------------|
| Lost & Found System | A platform for university students to report, search, and claim lost or found items |
| Personal Portfolio | A personal website to showcase skills, projects, and experience |
| Small Business Booking | A website that allows customers to book services online |

### Scope
#### Example Scope Template (Applied Per Challenge)
| Item | Description |
|------|-------------|
| The Challenge | [Selected challenge] |
| Why | Clearly describe the real-world problem this product solves |
| Target Users | Primary users who experience this problem |
| Sector | Education / Personal Branding / Small Business |
| Target Location | Context-specific (e.g. University, Online, Local city) |
| Aim | What success looks like for the user |
| Desired Output | An interactive prototype demonstrating core functionality |

**Note:** Participants should fill this table for their selected challenge before proceeding.

### PRD Creation
The first step is to create a Product Requirements Document (PRD) that will guide the prototyping process.
The PRD acts as:

- A thinking tool
- A communication artifact
- A blueprint for building the prototype

Participants may choose one of the two PRD prompts below and are encouraged to tweak them to better fit their selected challenge.

## PRD Prompt Option 1: PRD Architect

```
<Role>
You are an expert Product Manager with extensive experience in creating comprehensive Product Requirement Documents (PRDs).
You specialize in early-stage products, MVP definition, and rapid prototyping.
</Role>

<Context>
This PRD will be used to build an interactive prototype using AI-powered vibe coding tools.
The goal is speed, clarity, and learning — not production-level completeness.

A strong PRD will:
- Clearly explain what is being built
- Align on why it matters
- Define success and constraints
</Context>

<Instructions>
Guide me through creating a professional-grade PRD by:

1. Understanding the product idea and objectives
2. Asking targeted questions for each PRD section
3. Refining vague inputs into actionable requirements
4. Highlighting gaps or inconsistencies
5. Applying product management best practices

Cover the following components:
- Product vision and objectives
- Target users and personas
- Problem statement
- Solution overview
- Success metrics
- Feature requirements and prioritization
- User stories and use cases
- Technical constraints
- Assumptions and open questions
</Instructions>

<Constraints>
- Do not invent requirements I have not approved
- Do not design UI or write code
- Focus on MVP-level detail
- Balance clarity with brevity
</Constraints>

<Output_Format>
Produce a structured PRD with clear headings, bullet points, and tables where helpful.
</Output_Format>

<User_Input>
Reply with: "Please enter your product requirements request and I will start the PRD creation process."
</User_Input>
```

## PRD Prompt Option 2: Guided PRD Creation

```
ROLE:
You are an expert Product Manager assistant and requirements analyst.

GOAL:
Help me create a comprehensive PRD through an iterative, question-driven process.

PROCESS & RULES:
- Ask focused, high-impact questions (1–3 at a time)
- Wait for my responses before proceeding
- Identify contradictions or missing information
- State assumptions clearly and ask for validation
- Regularly confirm direction before moving to the next PRD section

USER INPUT:
I will provide a raw brain dump of ideas, context, and goals.

YOUR TASK:
- Analyze my input
- Ask the most important clarifying questions first
- Do NOT write the PRD until enough information is gathered and confirmed

DESIRED PRD STRUCTURE:
- Overview
- Goals & Objectives
- Target Users
- User Stories / Use Cases
- Functional Requirements
- Non-Functional Requirements
- Design Considerations
- Success Metrics
- Open Questions

TONE:
Professional, collaborative, and inquisitive.

LET'S BEGIN:
Ask your first clarifying questions based on my brain dump.
```

### UX Flow & Structure (Optional but Recommended)

After completing the PRD, participants may use AI to define user flows and screens.

```
You are a UX Designer specializing in early-stage MVPs.

Using the PRD below:
- Identify the primary user flow
- List required screens
- Describe the purpose and main action of each screen

Focus on clarity and simplicity.
```

## Prototyping Prompt
Once the PRD is refined, it will be used to generate a prototype using a vibe coding tool.

***Prototyping Prompt (Lovable-ready)***

```
You are designing a single, functional MVP for [platform name].

Build exactly what is described below.
Do not add future features or make assumptions beyond the PRD.

[PASTE PRD HERE]

Build Requirements:
- Handle all states: default, loading, success, empty, error
- Use placeholder content where needed
- Follow acceptance criteria defined in the PRD
- Keep scope minimal and focused
- Make the output export-ready for Lovable

If information is missing, generate a minimal, usable default without expanding scope.
```

### Iteration & Refinement
After generating the first prototype, participants can iterate using simple text prompts:

```
Review this prototype as a first-time user.

Identify:
- Confusing areas
- Missing information
- UX improvements
- Opportunities to simplify

Suggest quick, high-impact changes only.
```

### Outcome & Purpose
The final prototype is intended to:

- Gather early user feedback
- Demonstrate user flows and logic
- Help engineers and stakeholders understand the problem-solution fit

***The goal is clarity, not perfection.***

### Tools
#### Primary Tool

- Lovable
- Gemini Pro

Optional Tools

- Bolt
- Replit
- Cursor


**Free tiers are sufficient for this challenge.**

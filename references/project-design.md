# Project Design

Design a project that demonstrates ability to perform the target job while being innovative, showcase-worthy, and capable of rapid dissemination.

## Design Principles

### 1. JD Alignment
Every major decision should tie back to JD requirements:
- **Primary skills** → Core features of the project
- **Secondary skills** → Supporting features / infrastructure
- **Soft skills** → Documentation, collaboration features

### 2. Innovation Checklist

The project should demonstrate innovation through at least ONE of:
- [ ] **Novel combination**: Combine existing ideas in a new way
- [ ] **Better execution**: Solve an existing problem better
- [ ] **New domain**: Apply known solutions to a new problem space
- [ ] **Extension**: Build meaningfully on top of existing work
- [ ] **Gap filling**: Address an underserved need

### 3. Showcasing Value

The project must be **showcase-ready**:
- Clear problem statement anyone can understand
- Demo that can be shown in 5 minutes
- README that tells a compelling story
- Visual elements (UI, architecture diagram, metrics)
- "Wow factor" that creates impression

### 4. Reproducibility

The project should be easy to reproduce:
- Clear setup instructions
- Minimal dependencies
- Deterministic behavior
- Tutorial/Guide for others to follow

## Project Design Process

### Step 1: Define the Problem Space

```markdown
### Problem Statement
[One clear sentence describing the problem]

### Target Users
- Primary: [Who faces this problem most]
- Secondary: [Who else benefits]

### Current Solutions & Limitations
1. [Existing Solution 1]: [Limitation]
2. [Existing Solution 2]: [Limitation]

### Our Opportunity
[How our project addresses the gap]
```

### Step 2: Feature Design

#### Core Features (Must-Have)
These directly demonstrate primary JD skills:

| Feature | JD Skill Demonstrated | Implementation Approach |
|---------|----------------------|------------------------|
| Feature 1 | Skill X | [Brief approach] |
| Feature 2 | Skill Y | [Brief approach] |

#### Differentiation Features
These set the project apart:

| Feature | Innovation Type | Impact |
|---------|----------------|--------|
| Feature A | [Novel combination / better execution] | [Why impressive] |

#### Supporting Features
These demonstrate completeness:

| Feature | Purpose |
|---------|---------|
| Feature X | [Error handling / monitoring / etc] |

### Step 3: Architecture Design

#### High-Level Architecture
```
┌─────────────────────────────────────────────────────────┐
│                     [Project Name]                      │
├─────────────────────────────────────────────────────────┤
│  Frontend/Interface    │    Backend/Core Engine         │
│  ──────────────────    │    ───────────────────         │
│  [Component 1]         │    [Component A]                │
│  [Component 2]         │    [Component B]                │
├─────────────────────────────────────────────────────────┤
│  Data Layer            │    Infrastructure               │
│  ──────────────────    │    ─────────────────           │
│  [Storage]             │    [Deployment/CI]              │
└─────────────────────────────────────────────────────────┘
```

#### Technology Stack Selection

| Layer | Technology | Rationale (JD Alignment) |
|-------|------------|-------------------------|
| Language | [Tech] | [Why this demonstrates target skills] |
| Framework | [Tech] | [Why relevant] |
| Database | [Tech] | [Scale/data requirements] |
| Cache | [Tech] | [Performance needs] |
| Deploy | [Tech] | [DevOps/Infrastructure skills] |

#### Key Architectural Decisions

1. **Decision 1**: [What we chose] vs [alternatives]
   - **Rationale**: [Why this serves the project best]
   - **Trade-off**: [What we traded away]

2. **Decision 2**: [Same structure]

### Step 4: Differentiation Strategy

```markdown
### How We're Different

| Dimension | Typical Approach | Our Approach | Advantage |
|-----------|-----------------|--------------|-----------|
| [Dim 1] | [Standard] | [Our choice] | [Benefit] |
| [Dim 2] | [Standard] | [Our choice] | [Benefit] |

### Unique Value Proposition
[One sentence: Why would someone use THIS project over existing ones?]
```

### Step 5: Showcasing Plan

What makes this project **memorable**:

1. **Headline feature**: [The one thing everyone remembers]
2. **Visual hook**: [Screenshot/demo/video element]
3. **Technical depth**: [The impressive implementation detail]
4. **Story arc**: [Problem → Approach → Solution → Impact]

## Output Template

```markdown
## Project Design Document

### Project Name
[Creative, memorable name with .com/.io availability check]

### Executive Summary
[3-5 sentences: What it does, why it matters, what makes it special]

### Problem & Opportunity
#### Problem Statement
[The pain point in one sentence]

#### Target Users
- [User persona 1]
- [User persona 2]

#### Market Gap
[What existing solutions miss]

### Feature Set

#### Core Features
1. **Feature 1**: [Description] → Demonstrates: [JD Skill]
2. **Feature 2**: [Description] → Demonstrates: [JD Skill]

#### Differentiating Features
1. **Feature X**: [Innovation description]
   - Innovation type: [Novel/Better/New Domain/Extension]
   - Impact: [Why impressive]

### Architecture

#### System Diagram
```
[ASCII architecture diagram]
```

#### Technology Stack
| Component | Choice | Rationale |
|-----------|--------|-----------|
| Language | [X] | [JD alignment] |
| Framework | [X] | [JD alignment] |
| Database | [X] | [Requirements fit] |
| Cache | [X] | [Performance] |
| Deploy | [X] | [DevOps skills] |

#### Key Decisions
1. **[Decision 1]**:
   - Choice: [What we chose]
   - Rationale: [Why]
   - Trade-off: [What we gave up]

### Differentiation
| Aspect | Conventional | Ours | Edge |
|--------|--------------|------|------|
| [X] | [Y] | [Z] | [Benefit] |

### Showcasing Plan
1. **Demo highlight**: [Most impressive 30-second demo]
2. **Visual identity**: [Key screenshot/graphic concept]
3. **Technical showcase**: [Most impressive technical detail]
4. **Story**: [The narrative arc]

### 复现价值 (Reproducibility)
- Setup complexity: [Minutes to running]
- Dependencies: [List main ones]
- Documentation: [README completeness]
- Container support: [Docker yes/no]

### Risk & Mitigation
| Risk | Impact | Mitigation |
|------|--------|------------|
| [Risk 1] | [H/M/L] | [Approach] |
```

# Coding Agent Basics

---
## 1.Prompts

#### Global Prompts
- **Project-wide instructions** that apply to all interactions
- **Coding standards** and style preferences
- **Architecture patterns** and design principles
- **Team conventions** and best practices

#### Predefined Prompts (Selectable)
- Template-based prompts for common tasks
- Quick actions for frequent operations
- Standardized workflows for consistency
- Role-specific prompts (frontend, backend, testing, etc.)

#### Ad-hoc Prompts
- **Chat** - Direct conversational instructions
- **File** - Code files, documentation, configuration
- **Folder** - Project structure and directory context
- **URL** - Web resources, documentation, APIs
- **Terminal** - Command output, logs, error messages
- ...

---

## 2. Multi-LLM Support

### Most Common Models used for Vibe Coding

- **Claude Sonnet 3.7/4.0** - Advanced reasoning engine with exceptional code understanding capabilities, ideal for complex architectural and coding tasks
- **Gemini 2.5 Pro** - Versatile multimodal model with strong visual processing and fast response times
- **GPT 4.1** - Reliable general-purpose model with balanced performance across standard development workflows


## 3. Plan Mode vs Action Mode

### Plan Mode 🧠
**Strategic thinking and high-level design**
- Architecture planning and system design
- Task breakdown and workflow planning
- Risk assessment and approach validation
- **No code execution** - pure planning phase

### Action Mode ⚡
**Implementation and execution**
- Implementation and code generation
- File modifications and creation
- Command execution and testing
- Real-time problem solving
- Direct system interaction

---

## 4. Context Management

### Clear Contexts 🧹
- Fresh start capability
- Remove conversation history
- Reset agent state
- Clean slate for new tasks

### Compress Contexts 📦
- Summarize long conversations
- Retain essential information
- Optimize token usage
- Maintain continuity while reducing overhead

### Smart Context Retention
- Automatic relevance scoring
- Priority-based information keeping
- Efficient memory utilization

---

## Current Status: What Agents Excel At ✅

### 1. Rapid Prototyping
- **New feature development**
- **Proof-of-concept implementations**
- **Quick iterations and testing**

### 2. Function Implementation
- Algorithm development with provided signatures
- Interface implementations
- Data structure operations

### 3. Code Generation with Example Templates
- Similar functions/classes based on examples
- Pattern replication across codebase
- Consistent code style maintenance

### 4. Test Generation
- Unit tests for target interfaces
- Edge case coverage
- Test data generation

---

## Current Challenges: Where Agents Struggle ⚠️

### 1. Large Project Integration
- Adding features without design guidance
- Understanding complex system architecture
- Maintaining consistency across modules

### 2. Code Duplication Issues
- Generating redundant implementations
- Missing existing utility functions
- Creating parallel solutions

### 3. Pattern Inconsistency
- Not following existing system patterns (MVC, Design Patterns)
- Ignoring established conventions
- Breaking architectural principles

### 4. Library Utilization
- Not using available libraries
- Choosing alternative solutions unnecessarily
- Missing optimization opportunities

---

## Solution: Enhanced Development Process

### Developer Roles in New Process

#### 1. System Design
- **Design system modules**
  - Define clear boundaries
  - Establish communication patterns
- **Outline module interfaces**
  - Specify input/output contracts
  - Define error handling

#### 2. Quality Assurance
- **Design unit tests**
  - Test against modules/interfaces
  - Validate behavior expectations
- **Refactor for consistency**
  - Ensure pattern compliance
  - Maintain code quality

#### 3. Code Review
- **Review generated code**
  - Understand implementations
  - Validate against requirements

---

## Memory Banks: Project Intelligence

### 1. Project Brief 📋
- **Core requirements definition**
- **Primary use cases**
- **Success criteria**

### 2. System Patterns 🏗️
- **System Architecture Graph**
- **Workflow Diagrams**
- **File/Folder Structure**
- **Mermaid flowcharts** - LLMs process them excellently

### 3. Technical Context 🔧
- **Dependencies** with specific versions
- **Libraries and packages** in use
- **External service integrations**

---

## Task Management Strategy

### Task Creation & Breakdown
1. **Build tasks from PRD** or ad-hoc requests with plan mode
2. **Break large tasks** into manageable sub-tasks
3. **No upfront full task lists** - long dependencies are unreliable
4. **Outline changes clearly** - identify new vs modified components

### Task Execution Principles
- **Incremental development** approach
- **Continuous validation** against requirements
- **Pattern consistency** enforcement
- **Context-aware** implementation

### Task Tracking
- **Progress monitoring** with clear milestones
- **Dependency management** between tasks
- **Quality gates** at each step
- **Rollback capabilities** for failed attempts

---

## Tips
    1. 3-strike rule
    2. Context compress or clear for every 10 messages
    3. Describe your requirements clearly, do not use words like, the UI doesn’t work properly, instead, use something like: “the page crashes on refresh”
    4. Version control is your escape hatch, commit after each successful iteration with agent 
    5. Last resort, Burn it down. 

## MCP servers:
    1. Figma: we can have our UI design, or system design in Figma, and coding agent pull the design directly and implement it
    2. JIRA: we can pull the ticket and generate the task and to-do list from the ticket directly
    3. Context7: always pull the latest library/SDK docs from internet. 
    4. StageWise: a browser toolbar that connects your frontend UI to your code ai agents in your code editor.

## Best Coding Agent in the Market
    1. Claude Code:
        1. Build in feature to break down the user input into to-do list, which make the implementation more accurate
        2. Can use /clear to clear the context , and use /compact to compress the context
    2. Roo COde:
        1. Excellent context auto-compress feature to make the agent fast and cost efficient 
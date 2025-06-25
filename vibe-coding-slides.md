# Vibe Coding

---

# VIBE CODING BASICS

## 1. Three Types of Prompts: Global, Predefined & Ad-hoc

**Global Prompts:** Your coding tool adds these to every chat automatically
- Rules for your whole project - make sure code follows team standards
- System patterns like MVC, microservices, or other design approaches
- Team habits for naming, organizing files, and writing consistent code
- Special knowledge for your domain (banking, healthcare, shopping)

**Predefined Prompts:** Easy to load custom commands
- Instructions for different coding languages or project types
- Your own workflows to handle common tasks automatically
- Checklists to make sure code meets quality standards

**Ad-hoc Prompts:** Most commonly used context
- What you type in the chat window
- Code files from your project that AI can read
- Whole folders of code that AI can work with
- Web links to documentation or helpful resources

**Key Point:** All popular coding agents support these three types of prompts

---

## 2. Why Use Multiple LLMs: Cross-Check & Validate

### Popular Models:
- **Claude Sonnet 3.7/4.0** - Great at complex tasks and understanding how code parts work together
- **Gemini 2.5 Pro** - Good at turning visual designs into code, documentation, and fast responses
- **GPT 4.1** - Balanced LLM that handles common tasks very well

### Why Multiple LLMs?
- **Cross-check plans** - One AI creates plan, another AI reviews it
- **Cross-validate code** - One AI writes code, another checks for bugs
- **Get different opinions** - More confidence that your code is good

**Key Point:** Not much performance difference for daily tasks, but multiple LLMs help catch problems

---

## 3. Two Agent Modes: Plan First, Then Action

### Plan Mode 🧠 - Thinking and Planning Phase
- Design how your system will work before writing code
- Understand how modules connect and depend on each other
- Check for problems and see if ideas will actually work
- Estimate work time and plan realistic timelines
- **Important: No code writing** - only thinking and planning
- Talk back and forth with AI to make sure it understands everything

### Action Mode ⚡ - Building and Making Things
- Write and change code as you work together
- Manage files and organize your project
- Run commands and handle development tools
- Test and check that things work correctly

### When to Switch:
- **Plan → Action:** Always finish planning before building
- **Action → Plan:** Go back when things get too complicated

**Key Rule:** Good coding agents need both Plan Mode and Action Mode

---

## 4. Context Management: Clear vs Compress

### Clear Context
- Use when starting to work on new features
- Helpful when switching to something completely different
- Good when AI seems stuck on wrong approach
- Fresh start removes confusing old information

### Compress Context
- Keep in mind that longer context is NOT always better
- Really helpful for long coding sessions working on same thing
- Makes key points clearer, lowers cost, makes things faster
- When too much context, AI gets confused by extra information
- Helps AI focus on what really matters for current work
- Most agents support manual clearing and compressing
- **Roo Code** does automatic context compression without you asking

**Key Point:** Good context management keeps AI working well and gets better results

---

# VIBE CODING ADVANCED

---

## 5. Where AI Coding Agents Excel

1. **Building Prototypes** - Quick working demos to test ideas fast
   - Good for showing concepts to stakeholders
   - **Warning:** Code isn't organized for long-term projects

2. **Known Algorithms** - Standard computer science solutions
   - Search algorithms, sorting methods, graph traversal
   - Well-documented patterns that have been written many times

3. **Template Code** - Similar features from examples
   - Show AI one feature, it can create similar ones
   - Great for API endpoints, UI components, following existing patterns

4. **Unit Tests** - Comprehensive test coverage
   - Think of different test cases and edge cases you might forget
   - Check normal situations, errors, and unusual inputs

**Key Point:** AI works best when tasks are well-defined and follow known patterns

---

## 6. Current AI Limitations & Problems

1. **Adding Features Without Big Picture**
   - Don't understand how whole system works together
   - Build things that don't fit with existing code
   - Create conflicts that are hard to fix later

2. **Failed Consistency Across Modules**
   - Each part written in different style
   - Different error handling in similar situations
   - Makes codebase confusing and hard to maintain

3. **Generate Duplicate Code**
   - Don't recognize existing functionality already built
   - Create new functions when similar ones already exist
   - Make projects bigger and harder to maintain

4. **Introduce Unexpected Libraries**
   - Choose new libraries instead of using existing tools
   - Pick libraries that don't fit with current setup
   - Cause conflicts and make project harder to manage

**Key Point:** These problems happen because AI can't see the whole project at once

---

## 7. Developer-Led Development Flow

1. **Drive System Design** - Create simple project design document
   - Show how whole system works and what parts you need
   - Write down main modules and how they connect
   - Like making blueprint before building house

2. **Generate Tasks from Requirements** - Break big features into smaller tasks
   - Look at features you need and figure out work to be done
   - Don't try to build everything at once - take smaller bites
   - Easier for AI to understand and build each piece right

3. **Design Unit Tests for Module Interfaces**
   - Write tests that check if each module works correctly
   - Cover normal situations, errors, and edge cases
   - Make sure new features work and fit with existing code

4. **Review and Refactor Generated Code**
   - Check if AI-built code matches your design plan
   - Make sure new code uses same style as rest of project
   - Remove duplicate code and fix anything that doesn't fit

5. **Update Project Documents**
   - Keep design documents current with what you built
   - Help future development and keep documentation useful

**Key Point:** Developer leads design, AI helps with implementation

---

## 8. Memory Banks

**Project Brief 📋** - Basic Foundation
- Project requirements and success rules
- Main use cases - who uses system and how
- Success numbers and performance goals
- Team agreement and business goals

**System Patterns 🏗️** - Building Blueprint
- System architecture pictures
- Module explanation with inputs and outputs
- Data flow pictures and system connections
- File and folder structures

**Technical Context 🔧** - Building Details
- Libraries used with versions
- External dependencies and APIs
- Environment setup and deployment instructions

### Why Memory Banks?
- **Long-term memory** for your project across conversations
- **No re-explaining** - AI remembers project details automatically
- **Save time** - don't waste time explaining same things over and over

**Key Point:** Like giving your AI agent a notebook where it writes down everything important about your project, so it never forgets and always helps you in the right way

---

## 9. Task Management

### Combined Plan + Action Flow:
1. **Take requirement or PRD and project docs** Create one clear task
2. **Talk with AI to improve task plan** ask questions, add details
3. **AI builds the feature** write code, create files, and unit tests
4. **Review what was built** check quality and update project docs

### Why Short Task Lists Work Better:
- **Long task chains are unreliable** - hard to keep track of dependencies
- **Hard to keep system design clean** - code doesn't fit together well
- **Better quality** - focus on few tasks, build each one well

**Key Point:** Task management should be combined with memory banks working together

---

# VIBE CODING TOOLS

## 10. Tips

1. **3-Strike Rule** - When approach isn't working after 3 tries:
   - Switch AI models
   - Change your prompt strategy
   - Break problem down differently
   - Go back to plan mode

2. **10-Message Rule** - Every 10 messages with AI:
   - Compress or clear the context
   - Prevents context degradation
   - Keeps AI performance optimal

3. **Be Specific** - Vague descriptions = vague results
   - Bad: "UI doesn't work properly"
   - Good: "Page crashes on refresh when user not authenticated"

4. **Version Control is Your Safety Net**
   - Commit code after each successful iteration
   - Gives confidence to experiment boldly
   - Can always roll back if needed

5. **Last Resort: Start Fresh**
   - When complexity becomes unmanageable
   - Sometimes clean slate is more efficient than fixing mess

---

## 11. Popular MCP Servers

**Figma Integration** - Turn Designs into Code Automatically
- AI reads your Figma designs and understands what they should look like
- Creates working React, Vue, or Angular components that match design perfectly
- Reads design tokens and creates proper CSS code
- Updates code automatically when you change designs in Figma

**JIRA Integration** - Connect Project Management to Code Building
- AI reads ticket details from JIRA project management system
- Creates detailed task lists that match what needs to be built
- Updates ticket status automatically as you work
- Connects code commits to specific JIRA tickets

**Context7** - Always Have Latest Documentation
- Pulls latest library and SDK documentation from internet
- AI always works with most current information
- Knows about newest API specifications and features
- Gets real-time access to community best practices

**StageWise** - Connect Website to Code Editor
- Browser toolbar that connects frontend UI to your code editor
- Click any UI element to see exact code that creates it
- See code changes reflected immediately in browser
- Great for debugging UI problems

---

## 12. Top AI Coding Platforms

**Claude Code:**
- **Built-in Task Breakdown** - Automatically breaks your input into structured to-do list
- **Context Management Commands:**
  - `/clear` - completely clear context and start fresh
  - `/compact` - compress context while keeping important information
- **Best for:** Complex projects that need systematic step-by-step planning

**Roo Code:**
- **Automatic Context Compression** - Manages context without manual work
- **Cost-efficient and Fast** - Automatically optimizes performance
- **Best for:** Large codebases where context becomes unwieldy quickly

**Key Point:** Match platform capabilities to your specific needs and workflow requirements

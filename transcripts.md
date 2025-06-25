# Presentation Transcripts: Mastering AI-Powered Development

**Total Duration: 20 minutes**

## 📅 Presentation Timeline

```
0:00 - 1:00    │ Introduction
               │
1:00 - 7:00    │ VIBE CODING BASICS
1:00 - 2:30    │ ├─ Section 1: Prompts (1.5 min)
2:30 - 4:00    │ ├─ Section 2: Support Multiple LLMs (1.5 min)
4:00 - 5:30    │ ├─ Section 3: Agent Mode (1.5 min)
5:30 - 7:00    │ └─ Section 4: Context Management (1.5 min)
               │
7:00 - 16:00   │ VIBE CODING ADVANCED
7:00 - 8:30    │ ├─ Section 5: AI Strengths (1.5 min)
8:30 - 10:00   │ ├─ Section 6: AI Limitations (1.5 min)
10:00 - 11:30  │ ├─ Section 7: New Development Flow (1.5 min)
11:30 - 13:00  │ ├─ Section 8: Memory Banks (1.5 min)
13:00 - 16:00  │ └─ Section 9: Task Management (3 min)
               │
16:00 - 20:00  │ VIBE CODING TOOLS
16:00 - 17:00  │ ├─ Section 10: Tips (1 min)
17:00 - 19:00  │ ├─ Section 11: MCP Servers (2 min)
19:00 - 20:00  │ └─ Section 12: Best Coding Agents (1 min)
```

---

## Introduction

Good morning/afternoon everyone. Today we're diving deep into vibe coding. Over the next 20 minutes, we'll explore everything from the fundamentals to advanced professional techniques.

Let's begin with the foundation.

---

# VIBE CODING BASICS

## Section 1: Prompts

There are three types of prompts you can use:

### Global Prompts:
Your coding tool automatically adds these Global prompts to every chat message and uses them when creating code or documents.

- Rules for your whole project that make sure every piece of code follows your team's standards
- Making sure your code follows system patterns - like MVC, microservices, or other design approaches
- Your team's habits for naming things, organizing files, and writing code in a consistent style
- Special domain knowledge for project like banking, healthcare, or online shopping

### Predefined Prompts:
You can also make one or more pre-defined prompts. They won't be added to every chat automatically, but they should be very easy and fast to load to context. Think of them as your custom commands.

For example, you might have:
- Instruction files for different coding languages, documents, or types of projects
- Your own workflows: Create a personal process to handle common tasks automatically
- Checklists that make sure every piece of code you create meets your quality standards

### Ad-hoc Prompts:

Ad-hoc prompts are the most commonly used context when talking to your Coding Agent.
They can be different things like:
- What you type in the chat window when talking to your AI Agent
- Code files from your project that the AI can read and understand
- Whole folders of code that the AI can look through and work with
- Web links to documentation or other helpful resources online

These ad-hoc prompts let your Agent understand what you're working on right now and give you the best solution for your specific situation.

All the popular Coding Agents we can use today support these three kinds of prompts. However, most of developers are only using ad-hoc prompts. Leveraging global prompts and predefined prompts will save time and reduce inconsistent results.

---

## Section 2: Support Multiple LLMs

Let me walk you through the three most popular models that coding teams use:

**Claude Sonnet 3.7/4.0** is really good at complex architectural and coding tasks. It's great at understanding how different parts of your code work together and making smart decisions about code structure. When you're building complicated systems or fixing messy old code, Claude's strong understanding of code relationships makes it perfect for these tough jobs.

**Gemini 2.5 Pro** is good at coding and documentation work. It can look at pictures of designs and turn them into working code, or read through documentation and help you understand it. Its ability to work with different types of information like images and text, plus its fast responses, makes it great for quick prototyping and turning visual designs into code.

**GPT 4.1** is a balanced LLM that can handle common tasks very well. It's reliable for everyday coding work like fixing bugs, writing regular features, and handling routine development tasks. It gives you steady, dependable results across a wide range of programming jobs and works consistently for most standard development workflows.

There are not too many performance differences among these LLMs for daily common coding tasks. So why do we need multiple LLMs?

We need multiple LLMs to cross check plans and cross validate or review the generated code. When one AI creates a plan, you can ask another AI to review it and catch any problems. When one AI writes code, another AI can check it for bugs or better ways to do things. This gives you more confidence that your code is good and your plans will work.

You might want to have a coding agent that has a feature to quickly switch between different LLMs, or have multiple coding agents running in your code editor at the same time. This way you can easily get different opinions and check your work without switching between different tools.

---

## Section 3: Agent Mode

### Plan Mode - Thinking and Planning Phase

Plan Mode is when you want AI to think and plan things out. Use this when you're working on complicated features, designing systems, or figuring out how to fix old messy code.

In Plan Mode, your Agent works on:
- Designing how your system will work - figuring out how different parts will talk to each other before you write any code
- Understanding how parts connect and depend on each other - knowing what happens when you change one thing
- Checking for problems and seeing if your ideas will actually work - finding issues before they become big problems
- Estimating how much work things will take and planning timelines - getting realistic ideas about how long things will take

The important thing about Plan Mode is that it's only for thinking and planning - It don't write any actual code during this phase. You can talk to AI Agent back and forth to make sure Agent understand all the details and create a complete project plan before it start building anything.

### Action Mode - Building and Making Things

Action Mode is where you actually get things done. This is for building features, fixing bugs, testing your code, and putting it live.

In Action Mode, your Agent does:
- Writing and changing code - creating and updating code as you work together
- Managing files and organizing your project - making folders, organizing files, keeping your project neat
- Running commands and managing your development setup - running tests, starting servers, handling the tools you need
- Testing and checking that things work - making sure your code does what it's supposed to do

### When to Switch Between Modes

**Plan → Action:** Always finish your planning and design checking before you start building. I've seen many projects fail because developers skipped the planning part and jumped straight into writing code.

**Action → Plan:** Go back to planning mode when things get too complicated for what you're currently doing. If you find yourself making big design decisions while you're trying to build, it's time to stop and plan.

A good Coding Agent needs to support both Plan Mode and Action Mode.

---

## Section 4: Context Management:

Context management is really important for keeping your AI working well and getting good results every time.

### Clear Context

Use clear context when you're starting to work on new features. This is also helpful when you've been working on one problem for a long time and want to switch to something completely different, or when the AI seems stuck on the wrong approach.

### Compress Context

Keep in mind that longer context is not always better.

For long coding sessions and when you're working on the same thing over and over, context compression is really helpful.

Compress context will make the key points clearer and also lower the cost and make things faster. When you have too much context, your AI can get confused by all the extra information and might focus on the wrong things. By compressing context, your AI can focus on what really matters for your current work.

Most of the current coding agents support manually clearing and compressing context. However, Roo Code performs extremely well by automatically compressing the context without you having to ask. This automatic feature makes it more cost efficient and faster than other coding agents because it's always managing your context in the background, so you don't have to think about it or remember to do it yourself.


---

# VIBE CODING ADVANCED

## Section 5: Where Coding Agents Work Really Well ✅

#### 1. Building Prototypes

Coding agents are very good at building prototypes, but only if you don't care about system design and project maintenance. They can quickly create working demos and proof-of-concepts that show your ideas in action. This is perfect when you need to test an idea fast or show something to stakeholders. However, the code they generate for prototypes usually isn't organized well for long-term projects. It works for showing concepts, but you'll need to redesign it properly if you want to build a real product from it.

#### 2. Implementing Well-Known Algorithms

Coding agents are very good at implementing well-known algorithms like search algorithms, travel algorithms, sorting methods, and other standard computer science solutions. Since these algorithms are well-documented and have been written many times before, AI agents can create clean, working versions of them quickly. They understand the patterns and can implement things like binary search, graph traversal, or pathfinding algorithms without much trouble.

#### 3. Creating Similar Code with Templates

Coding agents are very good at implementing similar code and features when you give them sample code as a template. If you show them how you built one feature, they can create similar features following the same pattern. This is great for building multiple API endpoints that work the same way, creating similar UI components, or adding features that follow your existing code style. The key is giving them a good example to follow.

#### 4. Writing Unit Tests

Coding agents are good at writing unit tests. They can look at your functions and create tests that check if the code works correctly. They're especially good at thinking of different test cases and edge cases that you might forget. They can create tests that check normal situations, error situations, and unusual inputs. This saves developers time and often catches problems that human testers might miss.

The important thing to remember is that coding agents work best when the task is well-defined and follows known patterns.

---

## Section 6: Current Limitations: Where Agents Struggle ⚠️
*Duration: 2-3 minutes*

### 1. Adding New Features Without the Big Picture

Coding agents often add new features without understanding the design. They don't see how the whole system works together, so they might build something that doesn't fit well with what already exists. For example, they might create a new way to handle user login without knowing that there's already a security system in place that handles authentication differently. This creates conflicts and problems that are hard to fix later.

### 2. Failed to Maintain Consistency Across Different Modules

Coding agents fail to maintain consistency across different modules in your project. Each part of your code might be written in a different style or follow different patterns, even though they should all work together smoothly. One module might handle errors one way, while another module handles the same type of errors completely differently. This makes the codebase confusing and harder to maintain over time.

### 3. Generate Duplicate Code

Coding agents may generate duplicate code because they don't always recognize existing functionality that's already been built. They might create a new function to format dates when there's already a date formatting function somewhere else in the codebase. This happens because they can't see or understand all the existing code, especially in large projects. You end up with multiple pieces of code that do the same thing, which makes your project bigger and harder to maintain.

### 4. Introduce unexpected Libraries

Coding agents may choose unexpected libraries instead of using the tools and libraries that are already part of your project. They might suggest adding new libraries that do the similar job as what you already have, or pick libraries that don't fit well with your existing setup. This can cause conflicts and make your project harder to manage. 

---

## Section 7: New Development Flow
*Duration: 2-3 minutes*

To fix the problems we just talked about, we need to reorganize the development flow.

#### 1. Drive System Design and Build Project Design Document

The developer's first job is to drive the system design and build a simple project design document that includes modules and shows the module interfaces. This means you create a clear plan that shows how your whole system will work, what different parts you need, and how these parts will talk to each other. You write down the main modules, what each module does, and how they connect together. This document becomes the base that guides all the work that comes after it. Think of it like making a blueprint before you build a house - it shows everyone what you're trying to build and how all the pieces fit together.

#### 2. Generate Tasks Based on Feature Requirements

Next, you generate tasks based on feature requirements and project documents. If the task is too big, break it down into smaller tasks that are easier to handle. Look at what features you need to build and use your project documents to figure out what work needs to be done. When you have a big feature, don't try to build it all at once. Instead, break it into smaller pieces that are easier to work with. This makes it much easier for the AI helper to understand what you want and build each piece the right way. It's like eating a big meal - you don't try to eat everything at once, you take smaller bites.

#### 3. Design and Create Unit Tests for Module Interfaces

Design and create unit tests for the module interfaces. Write tests that check if each module works the way it's supposed to work. These tests should cover normal situations when everything works fine, error situations when things go wrong, and edge cases that are unusual but might happen. This is to make sure the new feature works and fits properly with existing code. These tests are also really helpful when we need to change the codebase later because they tell us if we broke anything.

#### 4. Review and Refactor Generated Code

After the AI Agent builds the feature, you need to review the generated code and refactor the code to make sure the new code follows the same patterns, and remove any duplicate code. Look carefully at what the AI built and check if it matches your design plan. Make sure the new code uses the same style and patterns as the rest of your project. If you find duplicate code or code that doesn't fit your patterns, fix it so everything works together smoothly. This step is really important because it keeps your whole project organized and easy to understand.

#### 5. Update Project Documents

Finally, update the project documents with new feature changes. Keep your design documents current so they show exactly what you've built. This helps future development work and makes sure your documentation stays useful for Agent to build the next feature.

---

## Section 8: Memory Banks: Persistent Project Memory
*Duration: 2-3 minutes*

### Organized Knowledge Management System

Memory banks are the long-term memory of your project, made up of three important parts:

#### Project Brief 📋 - Basic Foundation

The project brief has:
- Project requirements and success rules - what you're building and how you'll know it worked
- Main use cases - who uses your system and how they use it
- Success numbers and performance goals - ways to measure if your project is doing well
- Team agreement and business goals - making sure everyone understands why you're building this

#### System Patterns 🏗️ - Building Blueprint

System patterns write down:
- System architecture - pictures that show how your system is built
- Module explanation with what are the input and output
- Data flow pictures and system connections - how information moves through your system
- File and folder structures - how your code files are arranged and organized

#### Technical Context 🔧 - Building Details

Technical context includes:
- Libraries used with versions - what code libraries and tools your project needs to work properly
- External dependencies - outside services and APIs that your project connects to and relies on
- Environment setup - how to set up your development environment and deploy your application to make it work

### Why Memory Bank

Memory banks help your AI coding agent remember important things about your project even when you start new conversations. Without memory banks, you have to explain your project setup, coding rules, and how your system works every single time you talk to your AI agent. This wastes a lot of time and makes your AI give you answers that don't fit your project. With memory banks, your AI agent already knows your project details, so it can give you better code that follows your patterns and works well with what you already built. Think of it like giving your AI agent a notebook where it writes down everything important about your project, so it never forgets and always helps you in the right way.

---

## Section 9: Task Management:
*Duration: 3-4 minutes*

### 1. Task Management is Plan Mode and Action Mode Working Together

Task management is a combined flow that uses both plan mode and action mode together. You take your PRD (Product Requirements Document) and project documents to create tasks. Then you can talk to your AI agent to update and improve the task until it's ready to build.

The whole process starts when you take your product requirements and project design documents that tell you what you need to build and how your system should work, then you use these documents to make one clear task - just focus on the next thing you need to build. Once you have a basic task, you can talk back and forth with your AI agent to make the task better by asking questions, adding details, and making sure the task is clear and doable, which is like using plan mode to think through the task before you start building. When the task is ready and well planned out, your AI agent switches to action mode to actually build the feature by writing code, creating files, and making all the changes you need to get the work done. After the task is finished and working, you review what was built to make sure it's good quality and then update your project documents to keep everything organized and ready for the next task. This back-and-forth between planning and building makes sure each task is well thought out and fits properly with your project, creating a smooth flow that combines the best parts of both plan mode and action mode working together.

### 2. Don't Build Long Task Lists - Keep Dependencies Simple

You don't have to build a long task list at the beginning. Making a long chain of tasks that depend on each other is not reliable, just like Claude Task Master shows us. It's very hard to keep the system well designed without refactoring the codebase between tasks.

Short task lists work much better because when you have many tasks that depend on each other, it becomes very hard to keep track of what needs to happen when, and if one task changes, it can affect many other tasks and create confusion that makes everything harder to manage. Long task chains also make it hard to keep your system design clean and organized, so you end up with code that doesn't fit together well and needs lots of fixing later, which wastes time and creates more problems. When you have a long list of planned tasks, it's also much harder to change your mind or adjust when you learn new things during development, but short task lists let you be more flexible and responsive to what you discover as you build and learn about your project. Most importantly, when you focus on just a few tasks at a time, you can give each one proper attention and make sure each task is built well and tested properly before moving to the next one, which leads to much better quality code and fewer bugs. The smart approach is to plan just a few tasks ahead, finish them completely with good quality, then plan the next few tasks based on what you learned from the work you just finished, and this approach keeps your project organized, your code quality high, and your development process smooth and manageable.

---

# VIBE CODING TIPS

## Section 10: Tips
*Duration: 1-2 minutes*

Let me share some hard-earned wisdom from teams using vibe coding in production environments.

### Essential Development Guidelines

#### 1. The 3-Strike Rule

When an approach isn't working, don't keep banging your head against the wall. After three failed attempts with the same strategy, change your approach. This might mean:
- Switching AI models
- Changing your prompt strategy
- Breaking the problem down differently
- Taking a step back to plan mode

#### 2. Context Management Every 10 Messages

This is a practical rule that prevents context degradation. After every 10 messages in a conversation with your AI agent, either compress or clear the context. This maintains optimal AI performance and prevents the conversation from drifting off-topic.

#### 3. Describe Requirements Clearly

Vague descriptions lead to vague results. Instead of saying "the UI doesn't work properly," be specific: "the page crashes on refresh when the user is not authenticated." The more specific you are, the better your AI agent can help you.

#### 4. Version Control is Your Escape Hatch

Commit your code after each successful iteration with your AI agent. This gives you confidence to experiment boldly because you can always roll back. I've seen teams become much more innovative when they know they have a safety net.

#### 5. Last Resort: Burn It Down

Sometimes, complexity becomes unmanageable. When refactoring isn't enough and the codebase has become too tangled, don't be afraid to start fresh. Sometimes a clean slate is more efficient than trying to untangle a mess.

These aren't just tips - they're battle-tested strategies from teams shipping production code with AI agents.

---

## Section 11: MCP Servers
*Duration: 3-4 minutes*

MCP servers, which stands for Model Context Protocol servers, are special helper programs that make your AI coding agent much more powerful by connecting it to other tools and services that you use every day. Think of MCP servers like bridges that let your AI agent talk to and work with all the different programs and websites you use for development work.

### How MCP Servers Help You Build Better Software

#### 1. Figma Integration - Turn Designs into Code Automatically

This connection between your AI agent and Figma is really amazing for building websites and apps. When you have a Figma MCP server working with your AI agent, your agent can look at the designs you made in Figma and understand exactly what they should look like when built as real code. Your AI agent can pull the UI designs directly from your Figma files, study all the design details like colors, fonts, spacing, and layout, then create working React, Vue, or Angular components that match your design perfectly. The AI agent can also read your design tokens and style guides from Figma and turn them into proper CSS code or styled-components that follow your design system. Even better, when you make changes to your designs in Figma, the MCP server can tell your AI agent about these changes and automatically update your code to match the new design. Imagine working on a new dashboard design in Figma, and then having your AI agent build the complete React code for it, including all the responsive breakpoints that make it work on phones and tablets, plus all the accessibility features that help people with disabilities use your app.

#### 2. JIRA Integration - Connect Project Management to Code Building

JIRA integration makes managing your development projects much easier and more organized. With a JIRA MCP server, your AI agent can read ticket details directly from your JIRA project management system and bring all that information into your development environment where you write code. This means your AI agent can look at JIRA tickets and create detailed task lists and to-do items that match exactly what needs to be built according to your project plan. As you work on building features, the MCP server can automatically update the ticket status in JIRA to show your progress, so your project manager and team members always know what's been finished and what's still being worked on. The system can also connect your code commits to specific JIRA tickets, which creates a complete trail showing exactly what code changes were made for each feature or bug fix. This creates a smooth flow from project planning in JIRA all the way to delivering finished code, with everything connected and tracked properly.

#### 3. Context7 - Always Have the Latest Documentation

Context7 solves a big problem that many developers face - working with old or outdated documentation that leads to using deprecated code patterns that don't work anymore. This MCP server always pulls the latest library and SDK documentation directly from the internet, so your AI agent is always working with the most current information about how to use different programming libraries and tools. The system makes sure your AI agent knows about the newest API specifications and features, and it automatically updates when libraries release new versions with changes or improvements. Context7 also gives your AI agent real-time access to community best practices and examples from other developers, so you get code that follows current standards and works well with modern development practices. This means you never have to worry about your AI agent suggesting old ways of doing things that might not work with current versions of libraries and frameworks.

#### 4. StageWise - Connect Your Website to Your Code Editor

StageWise is especially powerful when you're building full-stack applications that have both frontend user interfaces and backend server code. This tool works as a browser toolbar that creates a direct connection between your frontend UI running in the browser and your AI coding agents in your code editor. When you're looking at your website in the browser, you can click on any UI element like a button, form, or menu, and StageWise will show you the exact code that creates that element in your editor. When you make changes to your code in the editor, you can see those changes reflected immediately in the browser without having to refresh or restart anything. This is really helpful for debugging UI problems because you can connect visual issues you see in the browser directly to the code solutions in your editor, making it much faster to find and fix problems.

All of these MCP server integrations work together to change your AI agent from being just a code writing tool into being a complete part of your entire development workflow that connects to all the other tools and services you use to build software.

---

## Section 12: Best Coding Agent in the Market
*Duration: 1-2 minutes*

### Leading Platform Comparison

#### 1. Claude Code

Claude Code stands out for several reasons:

**Built-in Task Breakdown Feature:** This is huge for complex projects. Claude Code automatically breaks down your input into a structured to-do list, making implementation more accurate and systematic. Instead of trying to tackle a large feature all at once, it creates a step-by-step plan.

**Context Management Commands:** 
- Use `/clear` to completely clear the context and start fresh
- Use `/compact` to compress the context while maintaining important information

This gives you fine-grained control over context management, which is crucial for long development sessions.

#### 2. Roo Code

Roo Code's standout feature is its **excellent context auto-compress capability**. This makes the agent both fast and cost-efficient by automatically managing context without manual intervention. It's particularly valuable for teams working on large codebases where context can quickly become unwieldy.

### Platform Selection Considerations

When choosing a platform, consider:
- **Project complexity** - More complex projects benefit from Claude Code's task breakdown
- **Team size** - Larger teams might prefer Roo Code's automatic context management
- **Budget constraints** - Context compression directly impacts costs
- **Integration requirements** - Which platform works best with your existing tools

The key is matching the platform capabilities to your specific needs and workflow requirements.

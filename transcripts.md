# Vibe Coding

**Total Duration: 20 minutes**

## 📅 Presentation Timeline

```
0:00 - 1:00    │ Introduction
               │
1:00 - 7:00    │ VIBE CODING BASICS
1:00 - 2:30    │ ├─ Section 1: Three Types of Prompts: Global, Predefined & Ad-hoc (1.5 min)
2:30 - 4:00    │ ├─ Section 2: Why Use Multiple LLMs: Cross-Check & Validate (1.5 min)
4:00 - 5:30    │ ├─ Section 3: Two Agent Modes: Plan First, Then Action (1.5 min)
5:30 - 7:00    │ └─ Section 4: Context Management: Clear vs Compress (1.5 min)
               │
7:00 - 16:00   │ VIBE CODING ADVANCED
7:00 - 8:30    │ ├─ Section 5: Where AI Coding Agents Excel (1.5 min)
8:30 - 10:00   │ ├─ Section 6: Current AI Limitations & Problems (1.5 min)
10:00 - 11:30  │ ├─ Section 7: Developer-Led Development Flow (1.5 min)
11:30 - 13:00  │ ├─ Section 8: Memory Banks (1.5 min)
13:00 - 16:00  │ └─ Section 9: Task Management (3 min)
               │
16:00 - 20:00  │ VIBE CODING TOOLS
16:00 - 17:00  │ ├─ Section 10: Tips (1 min)
17:00 - 19:00  │ ├─ Section 11: MCP Servers (2 min)
19:00 - 20:00  │ └─ Section 12: Top AI Coding Platforms (1 min)
```

---

## Introduction

Good morning, good evening everyone. The world of vibe coding has changed really quickly in the past year. There are many new coding agents, useful tools, and strategies that came out during this time. I think that in the next few years, this whole area will keep growing and changing even faster than it is now. Today I am here want to share the things I have learned and the helpful tips I have discovered while working with AI coding tools over the past few months.

---

## Section 1: Three Types of Prompts: Global, Predefined & Ad-hoc

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

## Section 2: Why Use Multiple LLMs: Cross-Check & Validate

Let me walk you through the three most popular models that coding teams use:

**Claude Sonnet 3.7/4.0** is really good at complex architectural and coding tasks. It's great at understanding how different parts of your code work together and making smart decisions about code structure. When you're building complicated systems or fixing messy old code, Claude's strong understanding of code relationships makes it perfect for these tough jobs.

**Gemini 2.5 Pro** is good at coding and documentation work. It can look at pictures of designs and turn them into working code, or read through documentation and help you understand it. Its ability to work with different types of information like images and text, plus its fast responses, makes it great for quick prototyping and turning visual designs into code.

**GPT 4.1** is a balanced LLM that can handle common tasks very well. It's reliable for everyday coding work like fixing bugs, writing regular features, and handling routine development tasks. It gives you steady, dependable results across a wide range of programming jobs and works consistently for most standard development workflows.

There are not too many performance differences among these LLMs for daily common coding tasks. So why do we need multiple LLMs?

We need multiple LLMs to cross check plans and cross validate or review the generated code. When one AI creates a plan, you can ask another AI to review it and catch any problems. When one AI writes code, another AI can check it for bugs or better ways to do things. This gives you more confidence that your code is good and your plans will work.

You might want to have a coding agent that has a feature to quickly switch between different LLMs, or have multiple coding agents running in your code editor at the same time. This way you can easily get different opinions and check your work without switching between different tools.

---

## Section 3: Two Agent Modes: Plan First, Then Action

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

## Section 4: Context Management: Clear vs Compress

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

## Section 5: Where AI Coding Agents Excel ✅

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

## Section 6: Current AI Limitations & Problems ⚠️

### 1. Failed to Maintain Consistency Across Different Modules

Coding agents fail to maintain consistency across different modules in your project. Each part of your code might be written in a different style or follow different patterns, even though they should all work together smoothly. One module might handle errors one way, while another module handles the same type of errors completely differently. This makes the codebase confusing and harder to maintain over time.

### 2. Generate Duplicate Code

Coding agents may generate duplicate code because they don't always recognize existing functionality that's already been built. They might create a new function to format dates when there's already a date formatting function somewhere else in the codebase. This happens because they can't see or understand all the existing code, especially in large projects. You end up with multiple pieces of code that do the same thing, which makes your project bigger and harder to maintain.

### 3. Introduce unexpected Libraries

Coding agents may choose unexpected libraries instead of using the tools and libraries that are already part of your project. They might suggest adding new libraries that do the similar job as what you already have, or pick libraries that don't fit well with your existing setup. This can cause conflicts and make your project harder to manage. 

### 4. Problems with Fixing Unit Tests

When you add new features to your project using coding agent and some of your unit tests start failing, the agent might take the wrong approach. Instead of looking at the actual code that has the real problems and fixing those issues, the agent might choose the easier path and just change the unit test cases themselves to make them pass. This is a bad approach because the unit tests are there to catch problems in your code and make sure everything works correctly. When the AI agent changes the tests instead of fixing the real code problems, it means the actual bugs are still there but hidden, which can cause trouble later when users try to use your application.


Coding agents often introduced issues when adding new features without understanding the design.

---

## Section 7: Developer-Led Development Flow

#### 1. Drive System Design and Build Project Design Document

The developer's first job is to drive the system design and build a simple project design document that includes modules and shows the module interfaces. This means you create a clear plan that shows how your whole system will work, what different parts you need, and how these parts will talk to each other. You write down the main modules, what each module does, and how they connect together. This document becomes the base that guides all the work that comes after it. Think of it like making a blueprint before you build a house - it shows everyone what you're trying to build and how all the pieces fit together.

#### 2. Generate Tasks Based on Feature Requirements

Next, you generate tasks based on feature requirements and project documents. If the task is too big, break it down into smaller tasks that are easier to handle. Look at what features you need to build and use your project documents to figure out what work needs to be done. When you have a big feature, don't try to build it all at once. Instead, break it into smaller pieces that are easier to work with. This makes it much easier for the AI Agent to understand what you want and build each piece the right way. It's like eating a big meal - you don't try to eat everything at once, you take smaller bites.

#### 3. Design and Create Unit Tests for Module Interfaces

Design and create unit tests for the module interfaces. Write tests that check if each module works the way it's supposed to work. These tests should cover normal situations when everything works fine, error situations when things go wrong, and edge cases that are unusual but might happen. This is to make sure the new feature works and fits properly with existing code. These tests are also really helpful when we need to change the codebase later because they tell us if we broke anything.

#### 4. Review and Refactor Generated Code

After the AI Agent builds the feature, you need to review the generated code and refactor the code to make sure the new code follows the same patterns, and remove any duplicate code. Look carefully at what the AI built and check if it matches your design plan. Make sure the new code uses the same style and patterns as the rest of your project. If you find duplicate code or code that doesn't fit your patterns, fix it so everything works together smoothly. This step is really important because it keeps your whole project organized and easy to understand.

#### 5. Update Project Documents

Finally, update the project documents with new feature changes. Keep your design documents current so they show exactly what you've built. This helps future development work and makes sure your documentation stays useful for Agent to build the next feature.

---

## Section 8: Memory Banks

Memory banks are the long-term memory of your project, I've build my memory bank with three important parts:

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


This is my way of organizing memory bank files, and it's different from what the official guides suggest. You might want to use different types of documents in your memory bank, and that's perfectly fine. As long as your documents can explain your project and system in a clear way, your memory bank should work really well for your needs.

#### Workflows 🔄 - How Memory Banks Work

Even though the memory bank itself is not a global prompt, we set up our global prompts to automatically load the memory bank information at the start of every conversation with our AI agent. This means coding agent always has access to the project's important details right from the beginning of each chat.

We also create rules about how to build your memory bank and when should update it. Normally, memory bank should be updated every time you make changes to the project, whether add new features, clean up the code, or fix bugs. However, updating the memory bank can be expensive when the codebase is very large. Because of this cost issue, I changed my memory bank update process from automatic updates to manual updates, and now I only update the memory bank when there are big important changes that really matter for future development work.

### Why Do We Need Memory Banks

Memory banks are very important for keeping long-term information about your project. With memory banks, agent can understand the project clearly without having to load and read through your entire codebase every time. This saves time and helps agent give you better answers that fit your specific project needs.

---

## Section 9: Task Management:

Task management is another important method we use in vibe coding. It is a predefined prompt that includes the structure and format of tasks, and it also includes the custom workflows for new task, update task, and execute task.

### 1. Task Management Process

The whole process begins with creating task. You start by taking your product requirements and project design documents that explain what you need to build and how your system should work. The key is to focus on just the next thing you need to build, not everything at once.

Once you have created a basic task, you can have conversations back and forth with your coding agent to improve the task. You do this by asking questions, adding more details, and making sure the task plan is clear and doable.

When the task is well planned out and ready, you run the task and let the coding agent build the feature. The agent does this by writing code, creating new files, and making all the changes that are needed to get the work finished.

After the task is completed and everything is working properly, you need to review what was built to make sure it meets good quality standards. Then you update your project documents to keep everything organized and ready for the next task you want to work on.


### 2. Don't Build Long Task Lists - Keep Dependencies Simple

You don't need to plan out all your tasks at the beginning. Instead, build your project step by step by creating just one or two tasks at a time. Making a long chain of tasks that depend on each other is not reliable. It's very hard to keep the system well designed without refactoring the codebase between tasks.

Incremental building works much better than planning everything upfront. When you generate only one or two tasks at a time, you can adjust your development direction more often and keep moving toward your goal. You finish the current tasks, see what you learned, then create the next one or two tasks based on that new knowledge. This way, if something goes in the wrong direction, you catch it early and can fix it before it affects the rest of your project. This incremental approach helps you stay on track and build exactly what you need.

# VIBE CODING TIPS

## Section 10: Tips

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

Sometimes, complexity becomes unmanageable when working on big changes. if you or the agent are unable to fix the code issue, don't be afraid to start fresh. Sometimes a clean slate is more efficient than trying to untangle a mess.

These aren't just tips - they're battle-tested strategies from teams shipping production code with AI agents.

---

## Section 11: Popular MCP Servers

There are lots of popular MCP server can be integrated into the coding agent, I'm here list some server I've used a lot.

#### 1. Figma Integration - Turn Designs into Code Automatically

I use Figma integration in two ways:

**UI Design to Code:** Design the UI on Figma, then generate the UI code directly from the design. Your AI agent can look at your Figma designs and create working React, Vue, or Angular components that match your design perfectly.

**System Design to Project:** Design system architecture and workflows on Figma, then generate project documents and code from the design diagrams. This helps you plan bigger projects and create the project structure based on your architectural design.

#### 2. JIRA Integration - Connect Project Management to Code Building

I usually use JIRA server to search and check my ticket status from my coding environment, so I don't have to switch between different tools. I can also generate tasks and update tasks from the JIRA ticket directly. This means when I see a JIRA ticket that needs work, I can quickly turn it into a coding task for my coding agent, and when the work is done, I can update the ticket status right from where I'm coding. This keeps everything connected and saves time.

#### 3. Context7 - Always Have the Latest Documentation

Context7 solves a common problem - using old documentation that doesn't work anymore. This MCP server always gets the newest documentation from the internet, so your agent always has the most up-to-date information about programming libraries and tools. It automatically updates when new versions come out. This means coding agent will never suggest old ways of coding that don't work with current versions.

#### 4. StageWise - Visual UI Selection and Direct Agent Communication

StageWise lets you see and select UI elements directly on your website and highlight what you're pointing at. Once you select a UI element, you can talk to agent directly about that selected element and ask for changes to its visual effects or styling. This makes it really easy to change the looks of the UI elements


---

## Section 12: Top AI Coding Agents

#### 1. Claude Code

Claude Code stands out for several reasons:

**Built-in Task Breakdown Feature:** This is huge for complex projects. Claude Code automatically breaks down your input into a structured to-do list, making implementation more accurate and systematic. Instead of trying to tackle a large feature all at once, it creates a step-by-step plan.

**Context Management Commands:** 
- Use `/clear` to completely clear the context and start fresh
- Use `/compact` to compress the context while maintaining important information

This gives you fine-grained control over context management, which is crucial for long development sessions.

#### 2. Roo Code

Roo Code's standout feature is its **excellent context auto-compress capability**. This makes the agent both fast and cost-efficient by automatically managing context without manual intervention. It's particularly valuable for teams working on large codebases where context can quickly become unwieldy.

The coding agent market is changing very fast, and coding agents will keep getting smarter and smarter. The tools and strategies we use may also change from time to time. Right now, coding agents won't replace humans, but they do significantly boost productivity. It’s worth keeping an eye on how this area develops in the coming years 

# Repo Deconstruction Project

Due: Nov 24th

## Overview

The Repo Deconstruction project is designed to help you deeply understand a compiler or AI systems codebase by leveraging an in-editor AI agent to generate **targeted, personalized documentation** that teaches you the architecture and navigation of the code. This is not just about reading documentation—it's about actively exploring, asking questions, and building a mental model of how complex systems work.

## Objectives

By the end of this project, you will:

1. **Master codebase navigation**: Learn to efficiently explore and understand large, complex compiler and AI system repositories
2. **Build architectural understanding**: Develop a comprehensive mental model of how major components interact
3. **Practice AI-assisted learning**: Leverage in-editor AI agents (like Claude, GitHub Copilot, Cursor, etc.) to accelerate your learning
4. **Create teaching materials**: Document your learning journey in a way that could teach others
5. **Communicate technical concepts**: Present your understanding through a video walkthrough

## Project Steps

### 1. Choose Your Repository

Select a repository you are curious about. These can be any interestingly sophisticated repo and can be from the course materials or related to your research project but doesn't have to. Good candidates include:

- **Apache TVM**: End-to-end deep learning compiler
- **PyTorch**: Deep learning framework and compiler stack
- **Triton**: GPU programming and kernel compilation
- **vLLM**: High-throughput LLM serving engine
- **DSPy**: Declarative self-improving language model pipelines
- **SGLang**: Structured language model programming
- **byLLM/Jac**: Multi-level compiler infrastructure
- **Any repository related to your course project or is very interesting**

### 2. Use an In-Editor AI Agent

Use an in-editor AI agent such as:
- **Claude Code** (VSCode extension)
- **GitHub Copilot Chat**
- **Cursor AI**
- **Continue.dev**
- Or any other AI coding assistant

### 3. Generate Targeted Documentation

Work with the AI agent to create documentation that includes:

- **Architecture overview**: High-level system design and component relationships
- **Key abstractions**: Important classes, interfaces, and design patterns
- **Data flow**: How data moves through the system
- **Critical paths**: Main execution flows for core functionality
- **Extension points**: Where and how the system can be extended
- **Code organization**: Directory structure and module responsibilities
- **Build system**: How the project is built and tested

### 4. Example Prompts to Use

Use these prompts as starting points for your exploration. Adapt them to your specific repository:

#### Getting Started
```
"Give me a high-level overview of this repository's architecture.
What are the main components and how do they interact?"

"What is the entry point of this system? Walk me through what
happens from start to finish for a typical use case."

"Can you create a diagram showing the main modules and their
dependencies, use mermaid?"
```

#### Deep Dives
```
"Explain the compilation pipeline in this project. What are the
main passes and transformations?"

"How does [specific feature] work? Show me the key files and
functions involved."

"What design patterns are used in this codebase and why?"

"Create a table showing all the major classes in [module] and
their responsibilities."
```

#### Navigation and Discovery
```
"Where would I look to understand how [specific functionality]
is implemented?"

"Show me examples of how to extend this system with a new
[operator/optimization/backend]."

"What are the most important files I should understand first?"

"Generate a call graph for [specific function] showing the
execution flow."
```

#### Optimization and Performance
```
"How does this system optimize [specific operation]? Show me
the code and explain the algorithm."

"What are the key data structures used for performance? Why
were they chosen?"

"Create a flowchart showing the optimization pipeline."
```

#### Testing and Examples
```
"Show me test cases that demonstrate [feature]. Explain what
they're testing."

"Can you create a simple example that demonstrates the core
functionality of this system?"

"Walk me through how this example code gets compiled/executed."
```

#### Comparative Analysis
```
"How does this approach differ from [alternative system]?"

"What trade-offs were made in the design of this component?"

"Create a comparison table of different [backends/optimizations/
strategies] available in this system."
```

### 5. Request Visual Aids

As you explore, ask the AI to generate:

- **Architecture diagrams**: System-level component interactions
- **Class diagrams**: Object-oriented relationships
- **Flow charts**: Algorithm and process flows
- **Sequence diagrams**: Interaction between components over time
- **Tables**: Comparing features, listing components, summarizing APIs
- **Code examples**: Annotated snippets showing key patterns
- **Call graphs**: Function invocation hierarchies

### 6. Create Your Documentation

Organize the AI-generated content into coherent documentation that includes:

1. **Introduction**: What the project does and why it matters
2. **Architecture Overview**: High-level system design
3. **Core Components**: Deep dives into major subsystems
4. **Code Navigation Guide**: How to find and understand key functionality
5. **Examples and Use Cases**: Concrete demonstrations
6. **Visual Aids**: Diagrams, tables, and annotated code

Save your documentation in markdown format in your course repository.

### 7. Create a Video Walkthrough

Record a **5-10 minute video** that:

- **Tours the codebase** using your documentation as a guide
- **Shows your screen** as you navigate the actual code
- **Explains key concepts** in your own words
- **Highlights diagrams and tables** the AI generated
- **Demonstrates understanding** by walking through code examples
- **Points out interesting discoveries** or insights you gained

#### Video Tips

- Use screen recording software (OBS, QuickTime, Windows Game Bar, Loom, etc.)
- Show both your documentation and the actual codebase side-by-side
- Speak clearly and explain as if teaching someone else
- Highlight code sections as you discuss them
- Keep it concise—focus on the most important aspects
- You don't need fancy editing, just clear explanations

## Submission

### Required Submission

1. **Upload your video** to a platform of your choice:
   - Google Drive (must be viewable by anyone with the link)
   - Dropbox
   - Your university file storage
   - Any other video hosting service

2. **Submit the video link** in the "Repo Deconstruction" tab of the course spreadsheet:
   - https://docs.google.com/spreadsheets/d/1y7yw2zQt6hjsVg0bTg0fLS1cplkk9_-1nd-qYPybwfE/edit?usp=sharing
   - Include your uniquename and a working link to your video

3. **Include your documentation** in your course GitHub repository

### Optional (But Encouraged!)

**I'd be delighted to see your video on YouTube!**

If you're comfortable making your video public, consider uploading it to YouTube. This allows:
- Other students to learn from your exploration
- The broader community to benefit from your documentation
- You to build a portfolio of technical content
- Easy sharing and viewing without download limits

But this is entirely optional—private links are perfectly fine if you prefer!

## Grading Criteria

Your Repo Deconstruction will be evaluated on:

1. **Depth of exploration**: How thoroughly you explored the codebase
2. **Quality of documentation**: Clarity, organization, and usefulness of generated docs
3. **Use of visual aids**: Effective use of diagrams, tables, and examples
4. **Video quality**: Clear explanations and effective walkthrough

## Tips for Success

2. **Ask follow-up questions**: When the AI explains something, ask "why" and "how"
3. **Verify understanding**: Try to explain concepts back to the AI in your own words
4. **Iterate on prompts**: If you don't get useful output, rephrase your question
5. **Connect to course concepts**: Relate what you find to papers and topics from class
6. **Use the code, not just docs**: Look at actual implementations, not just high-level descriptions
7. **Find the interesting parts**: Focus on the compiler techniques, optimizations, or runtime innovations
8. **Make it personal**: Document what YOU find interesting and useful as a developer

**Remember**: The goal is not to become an expert in the entire codebase, but to demonstrate that you can effectively use AI tools to learn complex systems and communicate your understanding. This is a crucial skill for working with modern compiler and AI infrastructure!

Happy exploring! 🚀

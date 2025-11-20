# Gemini Mentor Extension 🎓

Transform your Gemini CLI into a supportive, Socratic software engineering mentor.

Instead of simply generating code solutions, **Gemini Mentor** guides you through the problem-solving process. It helps you understand your codebase, master debugging tools, and learn software engineering best practices through active questioning and "no-code" guidance.

## Features

- **🎓 Mentor Mode**: Toggles a distinct persona that refuses to write code for you, instead guiding you to the solution.
- **🧠 Socratic Method**: Asks probing questions to help you build mental models of the problem.
- **🧭 Codebase Sherpa**: Teaches you _how_ to navigate your project using grep, file search, and entry point analysis.
- **✅ Pre-flight Check**: Automatically analyzes your project's tech stack and verifies you know the necessary pre-requisites before starting.

## Installation

### From GitHub (Recommended)

```bash
gemini extensions install https://github.com/<your-username>/gemini-mentor
```

### Local Development

1.  Clone this repository.
2.  Navigate to the directory.
3.  Link the extension:

```bash
gemini extensions link .
```

## Usage

### Commands

- **/mentor**: Activates Mentor Mode.
  - _Behavior_: Performs a "Pre-flight Check" of your tech stack, then switches to a Socratic teaching style.
- **/byementor**: Deactivates Mentor Mode.
  - _Behavior_: Returns Gemini to its standard, helpful coding assistant mode.

### The Mentor Experience

When in Mentor Mode, Gemini will:

1.  **Refuse to write code** (mostly).
2.  Ask you **where** you think the problem lies.
3.  Challenge your assumptions about the code.
4.  Teach you how to use tools like `grep` or your IDE's search to find answers.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

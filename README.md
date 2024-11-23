# LeetCode Helper

A Chrome extension that enhances your LeetCode experience with AI-powered assistance, hints, and solutions.

## Features

### 🤖 AI Chat Assistant

- Real-time coding assistance
- Context-aware responses based on current problem
- Markdown support with syntax highlighting
- Dark/Light theme support

### 💡 Smart Hints

- Get targeted hints based on your current code
- Compares previous attempts to provide relevant suggestions
- Fun, emoji-filled responses to keep you motivated

### ⌨️ Keyboard Shortcuts

- `Ctrl + Shift + H`: Get a hint
- `Ctrl + Shift + S`: Get the solution
- `Ctrl + Shift + ?`: Show/hide shortcuts overlay

### 🎨 UI Features

- Draggable chat button
- Responsive design
- Code syntax highlighting
- Copy code functionality
- Smooth animations and transitions
- Theme toggle (Dark/Light mode)

## Technical Stack

- **Frontend**: React, TypeScript
- **Styling**: TailwindCSS
- **AI Integration**: OpenAI GPT-4
- **Code Highlighting**: Prism React Renderer
- **Markdown**: React Markdown with remark-gfm

## Components

### Core Components

- ChatPanel: Main chat interface with AI interaction
- ChatButton: Draggable floating action button
- CodeBlock: Syntax-highlighted code display
- ThemeToggle: Dark/Light mode switcher
- ShortcutsOverlay: Keyboard shortcuts display

### Context

- ThemeContext: Global theme management

### Utils

- aiHelpers: OpenAI API integration
- keyboardShortcuts: Global keyboard shortcuts
- uiHelpers: UI utility functions

## Installation

1. Clone the repository

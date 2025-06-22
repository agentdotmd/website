# Agent Configuration

## Project Overview

Simple static website for agent.md standard - vanilla HTML, CSS, and JavaScript. No build tools or frameworks.

## Development Commands

- Open `index.html` in browser for development
- No build process required - static files served directly
- No test suite - simple static site

## Code Style

- Vanilla HTML5, CSS3, and ES6+ JavaScript
- Use semantic HTML elements
- CSS follows BEM-like naming where applicable
- JavaScript uses modern ES6+ features (arrow functions, const/let)
- Indent with 4 spaces consistently

## Architecture

- `index.html` - Main page with AGENT.md template and documentation
- `style.css` - XKCD-inspired styling with monospace fonts
- Single-page application with embedded JavaScript
- No external dependencies or build process

## Files

- `index.html` - Main webpage content and inline JavaScript
- `style.css` - All styling including responsive design
- `README.md` - Basic project description
- `LICENSE` - Project license

## Browser Compatibility

- Modern browsers supporting ES6+
- Responsive design for mobile and desktop
- No polyfills required

## Git Commands

When `/git` is included in a prompt, you will exclusively use the following Git commands (each in a separate subagent AND in order) to help you accomplish the following tasks:

- `git status -short` - To check the current state of your repository
- `git add` - To stage files for commit
- `git -no-pager diff` - To view changes between commits or working
directory and index
- `git commit` - To record changes to the repository (summarizing git status and git diff)
- `git push` - To push changes to the remote repository
- `gh pr create --fill` - Use GitHub CLI to create a pull request
# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

AgentWorkshop is a curated resource collection focused on Agentic AI and the Future of Digital Making. This is a documentation repository maintained by Anastasia Salter, containing links to demos, examples, and further reading materials related to agentic AI in education and digital humanities.

## Repository Structure

- **index.md** - Main workshop page with structured sections
- **_config.yml** - Jekyll configuration using Cayman theme
- **assets/css/style.scss** - Custom stylesheet with Terminator aesthetics and animated network effects

## Content Organization

The index.md file is organized into structured sections:

1. **About This Workshop** - Introduction and overview
2. **Demos and Examples**:
   - Educational Applications
   - Tools and Platforms
3. **Further Reading**:
   - Critical Perspectives
   - Educational Resources
   - Technical Deep Dives
4. **About the Facilitator** - Information about Anastasia Salter

When updating this repository, maintain this hierarchical structure and ensure links are current and functional.

## Jekyll Site Configuration

This repository uses Jekyll for GitHub Pages deployment:

- **Theme**: Cayman (remote theme: pages-themes/cayman@v0.2.0)
- **Custom Styling**: Terminator-inspired aesthetics with:
  - Animated network background in header
  - Red/green cyberpunk color scheme
  - Glowing text effects and terminal-style interface
  - HUD-inspired link styling
  - Responsive design for mobile devices

### Modifying Styles

To update the visual design, edit `assets/css/style.scss`. The stylesheet includes:
- CSS custom properties (variables) for colors at the top
- Modular sections for different elements
- Animation keyframes for network effects, glowing, and glitch effects
- Responsive breakpoints for mobile optimization

## Development Workflow

This is a documentation and Jekyll site repository:

- Edit index.md directly to add/update resources
- Modify assets/css/style.scss to change visual styling
- Update _config.yml for site metadata or theme changes
- No build commands needed - Jekyll builds automatically on GitHub Pages
- Test locally with `jekyll serve` if needed
- Verify all links are functional before committing
- Maintain the existing markdown formatting and section structure

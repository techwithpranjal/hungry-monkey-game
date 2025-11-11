# Hungry Monkey Game

A Flexbox learning game built with Tailwind CSS

Hungry Monkey Game is an interactive learning project inspired by Flexbox Froggy, but designed specifically for practicing Tailwind CSS Flexbox utilities.
Instead of writing raw CSS, players type Tailwind classes in a small code editor to rearrange animated characters (monkey, banana, carrot, bamboo, hare, etc.) until they match the target layout for each level.
The game provides instant visual feedback, simple animations, sound effects, hints, and small in-game documentation sections that explain how each CSS Flexbox property maps to its Tailwind equivalent.

# Demo
https://techwithpranjal.github.io/hungry-monkey-game/

# Features
Animated characters and theme-based levels
A built-in Tailwind class editor with real-time validation
Level components that gradually introduce Flexbox utilities
Correct/incorrect audio cues
Hint system and progress tracking
In-game explanations mapping CSS → Tailwind utilities
Written with React + Tailwind CSS + Framer Motion

# Flexbox Froggy
This project is inspired by the original Flexbox Froggy:
https://flexboxfroggy.com/

The goal of Hungry Monkey Game is similar, but focused entirely on learning Flexbox through Tailwind utility classes.

# Tech Stack
React
Tailwind CSS
JavaScript
Vite
Framer Motion
Custom React Hooks

# Installation
Clone the repository:
git clone https://github.com/techwithpranjal/hungry-monkey-game.git
cd hungry-monkey-game

# Install dependencies:
npm install

# Start development server:
npm run dev

# Build for production:
npm run build

# How the Game Works
Each level contains:
A target layout showing how the items should appear.
A live preview area where the player’s Tailwind classes are applied.
A code editor where the player types classes like:
flex flex-col justify-center
If the applied classes match the target layout (regardless of order), the level is marked as correct and the player moves on.

# The game covers Tailwind equivalents for properties like:
flex-direction
justify-content
align-items
flex-wrap
order
and more

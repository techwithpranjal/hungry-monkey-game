# Hungry Monkey Game 🐒🍌
*A Flexbox learning game built with Tailwind CSS*

Hungry Monkey Game is an interactive learning project inspired by **Flexbox Froggy**, but designed specifically for practicing **Flexbox through Tailwind CSS utilities**.

Instead of writing raw CSS, players type **Tailwind utility classes** in a small code editor to rearrange animated characters (monkey, banana, carrot, bamboo, hare, etc.) until they match the target layout for each level.

The game provides instant visual feedback, simple animations, sound effects, hints, and in-game documentation that explains how **CSS Flexbox properties map to Tailwind utilities**.

The goal is to build intuition, not memorization — helping players understand *why* a layout works, not just *what* to type.



## Demo
https://techwithpranjal.github.io/hungry-monkey-game/

![Hungry Monkey Game Demo](/src/assets/images/demo.png)




## Features

- Animated characters and theme-based levels  
- Built-in Tailwind class editor with real-time validation  
- Progressive level design introducing Flexbox utilities gradually  
- Correct / incorrect sound effects  
- Hint system and progress tracking  
- In-game explanations mapping **CSS → Tailwind utilities**  
- Smooth animations using Framer Motion  



## Tailwind CSS Focus

This game is entirely centered around **Tailwind CSS**, not raw CSS.

Players learn how common Flexbox properties translate into Tailwind utilities:

| CSS Property | Tailwind Utility Examples |
|-------------|---------------------------|
| display: flex | flex |
| flex-direction | flex-row, flex-col |
| justify-content | justify-start, justify-center |
| align-items | items-start, items-center |
| flex-wrap | flex-wrap, flex-nowrap |
| order | order-1, order-2 |

### Tailwind Documentation
- Flexbox: https://tailwindcss.com/docs/flex  
- Layout utilities: https://tailwindcss.com/docs/display  

These references are also surfaced inside the game to encourage documentation-driven learning.



## How the Game Works

Each level includes:
- A **target layout** showing the expected result
- A **live preview** where Tailwind classes are applied instantly
- A **code editor** where players type classes like:

```
flex flex-col justify-center items-center
```

If the layout matches the target (regardless of class order), the level is marked as complete and the player advances.



## Concepts Covered

- flex-direction
- justify-content
- align-items
- flex-wrap
- order
- Multi-axis alignment
- Visual debugging of Flexbox layouts

Difficulty increases progressively to reinforce learning without overwhelming the player.



## Inspiration

Inspired by **Flexbox Froggy**  
https://flexboxfroggy.com/

Hungry Monkey Game focuses entirely on **Tailwind CSS**, making it more relevant for modern frontend workflows.



## Tech Stack

- React
- Tailwind CSS
- JavaScript
- Vite
- Framer Motion
- Custom React Hooks



## Installation

Clone the repository:

```bash
git clone https://github.com/techwithpranjal/hungry-monkey-game.git
cd hungry-monkey-game
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

---

## Who This Is For

- Frontend developers learning Tailwind CSS  
- Students struggling with Flexbox layouts  
- Developers transitioning from CSS to Tailwind  
- Educators looking for interactive teaching tools  
- Recruiters reviewing frontend learning projects  

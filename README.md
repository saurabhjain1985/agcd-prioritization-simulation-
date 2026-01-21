# AGCD Dynamic Prioritization System

Interactive mockup demonstrating Natural Language Powered Agentic Conversation Distribution (AGCD) for Dynamics 365.

## Features

- **Dynamic Priority Scoring**: Real-time priority calculation based on customer tier and wait time
- **Starvation Prevention**: Visual alerts and balanced scoring to prevent customer starvation
- **Multiple Queue Types**: Priority-based (Q1, Q2) and FIFO (Q3) queue logic
- **Configurable Settings**: Customize time intervals, base priorities, and score increments
- **Live Statistics**: Track customer counts, wait times, and at-risk customers by tier

## Queue Logic

- **Queue 1 & 2 (Q1, Q2)**: Priority-based routing - Highest priority score served first
- **Queue 3 (Q3)**: FIFO (First In First Out) - Customers served in arrival order

## Customer Tiers

- **Diamond Tier**: Premium customers with initial priority advantage
- **Gold Tier**: High-value customers with strong priority growth
- **Yellow Tier**: Standard+ customers with competitive priority growth
- **Standard Tier**: Base tier customers with fair catch-up mechanism

## How to Use

1. Open `index.html` in your browser
2. Adjust configuration settings as needed
3. Add customers to specific queues and tiers
4. Watch the real-time prioritization simulation
5. Monitor starvation indicators and statistics

## Demo

Visit the live demo: [GitHub Pages URL will be here]

---

Built for Dynamics 365 AGCD capability demonstration

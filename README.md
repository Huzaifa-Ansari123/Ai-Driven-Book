# Teaching Physical AI & Humanoid Robotics Course

This repository contains the source for the "Teaching Physical AI & Humanoid Robotics Course" book, built with Docusaurus.

## Overview

This educational course covers the fundamentals and advanced concepts of Physical AI and Humanoid Robotics. The course is structured into 13 weekly modules, each building upon the previous to provide a comprehensive understanding of the field.

### Course Structure

The course is organized into the following weekly modules:

1. **Weeks 1-2**: Introduction to Physical AI - Foundations of Physical AI and embodied intelligence, from digital AI to robots that understand physical laws, overview of humanoid robotics landscape, and sensor systems
2. **Weeks 3-5**: ROS 2 Fundamentals - ROS 2 architecture and core concepts, nodes, topics, services, and actions
3. **Weeks 6-7**: Robot Simulation with Gazebo - Gazebo setup, URDF and SDF formats, physics & sensor simulation
4. **Weeks 8-10**: NVIDIA Isaac Platform - Isaac SDK & Isaac Sim, AI perception & manipulation, RL for robot control
5. **Weeks 11-12**: Humanoid Robot Development - Kinematics & dynamics, bipedal locomotion & balance, manipulation & grasping
6. **Week 13**: Conversational Robotics - GPT-powered conversational AI, speech recognition & NLU

## Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

## Local Development

```bash
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The GitHub Actions workflow in `.github/workflows/deploy.yml` handles the deployment process.

## Tech Stack

- **Framework**: Docusaurus v3.1.0
- **Language**: Markdown, JavaScript/TypeScript
- **Deployment**: GitHub Pages with GitHub Actions
- **Styling**: Custom CSS with Docusaurus theme

## Contributing

Feel free to open issues or submit pull requests to improve the course content.

## License

This project is licensed under the MIT License."# Ai-Driven-Book" 

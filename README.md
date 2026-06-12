# Agentic Workflows That Read the Room

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey RakeshsarmaKarra!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/issues/1)


## Agentic AI Workflows with GitHub — Microsoft Skills Fest 2026
A portfolio-style repository that documents my completion of the Microsoft Skills Fest 2026 learning path focused on Develop agentic AI systems with GitHub. This repo captures what I learned, how I plan to apply it in real software projects, and the artifacts I earned along the way.

## Overview
This repository showcases my learning journey in agentic AI workflows, with GitHub as the system of record and control plane for planning, review, evaluation, and deployment governance. The underlying course themes include plan  act  evaluate loops, pull-request-based execution, CODEOWNERS for path-based review routing, environment protections for production safety, and evidence stored in GitHub-native artifacts such as workflow runs and checks.

## Live Showcase
[View the live GitHub Pages site](https://rakeshsarmakarra.github.io/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/)

## What I learned
Agents are different from assistants because they can take action in the SDLC, such as creating branches, updating code, and opening pull requests for review.

Safe agentic workflows separate planning, execution, and evaluation so reviewers can inspect intent before merge.

GitHub works well as a system of record because it stores issues, plans, commits, pull request discussion, workflow evidence, and approval history in one place.

CODEOWNERS and required checks help route the right reviews and prevent unsafe or incomplete changes from being merged.

GitHub Environments add risk-based controls, including required reviewers for sensitive deployments such as production.

Agent execution commonly runs inside GitHub Actions workflows with permissions bounded by workflow configuration and token scope.

## How I would apply this in practice
1. PR-based AI code contribution workflow
I would design AI-assisted repositories so that agents always work on isolated branches and open pull requests instead of pushing directly to the default branch. This keeps all changes reviewable and allows required checks, CODEOWNERS, and reviewers to validate both the code and the execution plan before merge.

2. Plan  Act  Evaluate governance
For higher-risk automation, I would require the agent to publish an inspectable plan in the pull request description, run the implementation in a workflow, and attach evaluation evidence as workflow logs, checks, and artifacts. That creates traceability and reduces hidden reasoning.

3. Risk-based deployment controls
I would allow broader autonomy in low-risk environments such as development and staging, while protecting production with GitHub Environments and required human reviewers. This is a practical way to combine speed with safety.

4. Least-privilege execution
I would scope workflow permissions and tokens tightly so the agent can perform only the actions needed for the task. This reduces blast radius if a workflow or tool behaves unexpectedly.

## Application-oriented project ideas
PR Review Gate Agent: an agent that verifies every pull request contains a plan, changed-file ownership review, and evidence links before merge.

Evaluation Evidence Collector: a GitHub Action that publishes benchmark results, screenshots, logs, and summary artifacts for model or code changes.

Risk-Aware Deployment Repo: a sample repo with dev/stage/prod environments, where production deployments require human approval.

Path-Sensitive Ownership Demo: a repo using CODEOWNERS to automatically route infrastructure, data, and application changes to the right reviewers.

## Lab screenshots:
![pic1](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Intro1.jpg)
![pic2](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Intro2.jpg) 
![pic3](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Course%20Intro.jpg) 
![pic4](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Agentic%201.jpg) 
![pic5](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Agent%20Workflow1.jpg) 
![pic6](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Agent%20Workflow%202.jpg) 
![pic7](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Orchestration%20Sub%20Agents.jpg)
![pic8](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/screenshots/Dev%20team.jpg)

## Badges
![pic1](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/badges/Playlist%20complete.jpg)

![pic2](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/badges/Foundations%20of%20Agents%20AI%20in%20GitHub.jpg) 
![pic4](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/badges/Designing%20Agent%20%20Architecture%20and%20SDLC%20Integration.jpg)
![pic3](https://github.com/RakeshsarmaKarra/MicrosoftSkillsFest-Getting-Started-With-Agentic-Worksflows/blob/projectrepo/docs/badges/Tooling%2C%20MCP%2C%20and%20Agent%20Execution%20Environments.jpg)
                         


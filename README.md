Let’s say we have a slow-speed client and want to save their mobile traffic.

For that purpose we decide not to show images immediately, but rather replace them with placeholders, like this:

`<img src="placeholder.svg" width="128" height="128" data-src="real.jpg">`

So, initially all images are placeholder.svg. When the page scrolls to the position where the user can see the image – we change src to the one in data-src, and so the image loads.

Requirements:
----------------
- When the page loads, those images that are on-screen should load immediately, prior to any scrolling.
- Some images may be regular, without data-src. The code should not touch them.
- Once an image is loaded, it should not reload any more when scrolled in/out.

P.S. If you can, make a more advanced solution that would “preload” images that are one page below/after the current position.

P.P.S. Only vertical scroll is to be handled, no horizontal scrolling.

Before starting any of the tasks in this Learning Path, please READ the following rules
===============================

What do you need to start this Learning Path:
----------------
1. A GitHub account
3. A Local IDE or Editor
5. Git Environment
6. A http://toggl.com/ account and Chrome Extension
7. A Netlify account

Rules that you MUST follow:
----------------
- **Fork this repo into your own Github Account** as a **public** Repository
- **Create a Github Project** connected to the repository
- Read **carefully** the task description
- Analyze the task, and **create relative subtasks** to track any requirement and knowledge needed
- **Assign an estimate to each created subtask**
- Define a **deadline for the main task**
- **Provide a Flowchart within the project**
- Where required, involve other members of the community to support you on the development
- When working on a task, move it to the **In progress** column and start tracking it
- After each task completion, **move it to the "Done" column** and stop tracking it
- After the main task completion, share the solution (e.g. your GitHub repo) over the community

Following some useful materials for your work:
----------------

[Git and GitHub configuration and usage](https://www.loom.com/share/6b86aa3bc0aa4f2d88a315bc9d3209c4)

[Pseudo Code Methodology](https://wtmatter.com/pseudocode/)



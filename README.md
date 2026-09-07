![An illustrated study corner with a laptop, balcony plants and piano keys](assets/garden-banner.webp)

# Hi, I'm Hưng

**A student at PTIT, Vietnam, learning AI engineering through software projects.**

English · [Tiếng Việt](README.vi.md)

I build tools for my own life and work on university projects with teammates. I enjoy figuring out how a system should work, helping people get started, and improving what we build. I'm interested in internship and junior opportunities where I can keep learning and contribute to a team.

## Projects

### [microSched](https://github.com/NguyenHaiHung0510/microSched) — my everyday app

A personal web app for tasks, notes, calendars and trackers, built with FastAPI, React and PostgreSQL. I use it in daily life and improve it as I discover what works and what doesn't.

It grew from a [C++ command-line tool](https://github.com/NguyenHaiHung0510/Code_HoTro_HocTap), through a [Python/Flet desktop app](https://github.com/NguyenHaiHung0510/VC_QuanLyThoiGian), into my main project for learning about software architecture, deployment and working with AI coding agents.

### [FANG](https://github.com/PTIT-TTCS-Team-5/Fang) — exploring AI in recruitment

A university team project for matching candidates and jobs. Alongside the ranking system, an agent helps HR explore applicants for a job posting, and a separate chatbot focuses on one applicant's profile.

I developed a two-way ranking pipeline that combines semantic and keyword retrieval with scoring for skills, experience and salary. One part I especially enjoyed was tuning it with Optuna and comparing ranking quality using MRR and nDCG@10 on synthetic candidate–job data. HR can inspect the rankings directly or ask the agent to call the ranking tool and filter applicants.

I led the team, worked on architecture and integration, and wrote and presented the report. We used [miCareer-mini](https://github.com/PTIT-TTCS-Team-5/miCareer-mini), a Streamlit frontend, to develop and demonstrate the FastAPI backend. This was a course prototype, not a production recruitment service.

### [miCareer](https://github.com/NguyenHaiHung0510/miCareer) — building with a team

A university team project: an IT recruitment website with a lightweight applicant tracking system (ATS). As team lead, I worked on shared foundations such as connection pooling, wrote setup and development guides, reviewed integration, and helped teammates debug problems.

My first experience leading a web project was [microShop](https://github.com/NguyenHaiHung0510/microShop). We started without web experience; getting a Java Servlet app running on Tomcat was our first breakthrough. I later worked with a team on a DevSecOps course project using microShop as the test application.

## What I'm learning now

I'm learning from Chip Huyền's *AI Engineering* alongside coursework and projects.

I'm also learning **harness engineering** through the workflow I use to build microSched. I stay responsible for product decisions and scope while a coordinating agent can implement changes or delegate focused tasks. I use independent reviews and test evidence to challenge the results, and keep decisions and lessons in project docs and memory. The aim is a way of working I can carry with me as models and tools change.

Around microSched, I'm designing three connected projects:

- **Mimi**, an assistant throughout microSched, designed to work with my tasks, notes, trackers and documents and take actions with appropriate approval. Longer term, if miGarden works out, I'd love Mimi to help care for my flowers, from suggesting watering to carrying out an approved watering request.
- **microLink**, an MCP connection between my coding-agent workspace, currently Codex, and microSched. I'm designing it so the agent can read and update app data through specific tools, with permissions and confirmations appropriate to the action.
- **miGarden**, a way to connect my love of growing flowers with IoT: sensing conditions for individual pots and controlling watering from microSched. Hardware, unreliable connections and water make this an ambitious project with plenty that can go wrong. I want to start with a small pilot, learn from what fails, and keep working toward a system I can use and trust.

My goal this semester is to build solid first versions of these projects, then keep developing them beyond the coursework.

Another personal experiment is [ClaudeRelay](https://github.com/NguyenHaiHung0510/ClaudeRelay), a Windows launcher I built to keep using the Claude Code CLI with alternative model backends when its usual route was unavailable. It changes routing for the launched process without rewriting my normal Claude Code configuration.

## Beyond projects

I play football and piano, enjoy inline skating, and grow flowers on my balcony. I like quiet places, nature and reading when the semester leaves room for it.

I'm comfortable communicating and working in English. In high school, I was a member of my school's English debate and academic competition teams (though I never made it to the actual competitions!). At university, I'm often the main presenter for our team projects, explaining the system, walking through the demo and answering questions about our design choices. Presenting is one of the parts of team projects I feel most confident about.

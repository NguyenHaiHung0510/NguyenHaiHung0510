![An illustrated study corner with a laptop, balcony plants and piano keys](assets/garden-banner.webp)

# Hi, I'm Hưng

**A PTIT student in Vietnam. I want to become an AI engineer, so I’m learning on my own and building projects.**

English · [Tiếng Việt](README.vi.md)

I still have a lot to figure out. Using microSched every day shows me where it falls short and what I need to learn next. In university projects, I’m often both the team lead and the main presenter. I’m open to internships and junior roles where I can keep learning and contribute to a team.

## Projects

### [microSched](https://github.com/NguyenHaiHung0510/microSched) — my everyday app

[Visit the website](https://microsched.fly.dev/home?lang=en)

A personal web app for tasks, notes, calendars and trackers, built with FastAPI, React and PostgreSQL. I use it in daily life and improve it as I discover what works and what doesn't.

It grew from a [C++ command-line tool](https://github.com/NguyenHaiHung0510/Code_HoTro_HocTap), through a [Python/Flet desktop app](https://github.com/NguyenHaiHung0510/VC_QuanLyThoiGian), into my main project for learning about software architecture, deployment and working with AI coding agents.

- [Mimi](https://github.com/NguyenHaiHung0510/microSched/blob/develop/docs/mimi/README.md) is the assistant inside microSched. I used to give the same kind of task a different name every time, with typos and inconsistent capitalization. Mimi helped me standardize 68 task titles over three rounds. I reviewed the proposed changes before applying each batch.
- [miGarden](https://github.com/NguyenHaiHung0510/miGarden) lets me automate and manage balcony watering in microSched. The IoT setup for Zone A is complete. I can manage the schedule and start watering from my phone. Once the house renovation is done, I’ll run the water line along the railing to the pots.

### [FANG](https://github.com/PTIT-TTCS-Team-5/Fang) — AI for miCareer

FANG was an ambitious team project to build AI features for miCareer, our recruitment website. We wanted to help people at both ends of hiring, from finding a suitable job to taking a closer look at an application.

- **Candidates** get job recommendations ranked using their CV and profile information.
- **HR** starts with a ranking based on the job posting and applicant profiles. An agent uses tools to search and filter applicants quickly. Once a recruiter picks someone to look at more closely, a separate chatbot answers questions using that applicant’s CV and profile as context.

I built the two-way ranking pipeline, combining semantic and keyword retrieval with scores for skills, experience, and salary. I especially enjoyed tuning it with Optuna and measuring ranking quality with MRR and nDCG@10 on synthetic candidate–job data.

I led the team, worked on architecture and integration, wrote the report, and gave the main presentation. We tested and demonstrated the FastAPI backend in our course prototype, [miCareer-mini](https://github.com/PTIT-TTCS-Team-5/miCareer-mini), with a Streamlit frontend.

### [miCareer](https://github.com/NguyenHaiHung0510/miCareer) — building with a team

A university team project for an IT recruitment website with a lightweight applicant tracking system (ATS). As team lead, I worked on shared foundations such as connection pooling, wrote setup and development guides, reviewed integration, and helped teammates debug problems.

My first experience leading a web project was [microShop](https://github.com/NguyenHaiHung0510/microShop). None of us knew how to build a website at the time. I looked for a way to get started, and getting our Java Servlet app to run felt like a small miracle xD. Later, I worked with a team on a DevSecOps course project to automate security testing across the software development lifecycle, using microShop as the test app.

## What I'm learning now

I’ve been enjoying Chip Huyền’s *AI Engineering*. I’ve made it to chapter 4 and I’m trying out what I learn in my own projects.

I’m learning **harness engineering** on microSched. I set the scope first, then work through architecture options with agents. I write down my decisions and the evidence I used so I can revisit them later.

Another personal experiment is [ClaudeRelay](https://github.com/NguyenHaiHung0510/ClaudeRelay), a Windows launcher I built to keep using the Claude Code CLI with alternative model backends when its usual route was unavailable. It changes routing for the launched process without rewriting my normal Claude Code configuration.

## Beyond projects

I enjoy playing football and piano, inline skating, and growing flowers on my balcony. I like quiet places, nature, and reading when I have time away from my studies.

I’m comfortable communicating and working in English. In high school, I was on the English debate and English academic competition teams (though I never made it to an actual competition xD). Presenting is one of the things I’m most confident about on team projects. I enjoy figuring out how a system works, explaining it in a demo, and answering questions about our design choices.

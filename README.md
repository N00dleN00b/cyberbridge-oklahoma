# CyberBridge to Oklahoma 

**Free, beginner-friendly cybersecurity and AI lessons for Oklahoma students, educators and families, with global perspectives from study abroad in China.**

Created by **Bristie Rahman**, a first-generation college student and Benjamin A. Gilman International Scholar, as her **Gilman Follow-on Service Project**. The project has two goals:

1. **Increase awareness of study abroad and the Gilman Scholarship** among students who don't think it's for them.
2. **Demystify cybersecurity and AI** for Oklahoma's under-resourced communities, connecting global trends to local threats, so students see they can be **protectors, not just bystanders**.

Everything here is free to use, adapt and share, so schools, libraries, community programs and outreach teams can keep teaching it.

---

## What's here

| Part | What it is | Where it lives |
|---|---|---|
| **Beginner-friendly modules** adapted from my study abroad experience | Three core modules + a "Global Perspectives: China" lesson | [`curriculum/`](curriculum/) |
| **Ready-to-run workshops** for students, educators, families and college peers | Run-of-show guides; connect global trends to local threats (phishing aimed at school districts, hospital data breaches, scams targeting families) | [`workshops/`](workshops/) |
| **Study abroad & Gilman promotion** | A "Study Abroad Is for You" segment built into every workshop, plus a mentoring guide | [`workshops/gilman-segment.md`](workshops/gilman-segment.md), [`mentorship/`](mentorship/) |
| **Interactive game** | Phishing Spotter: safe or scam? | [`activities/phishing-spotter/`](activities/phishing-spotter/) |
| **The story behind it** | First-person blog posts about going from Oklahoma to China and back | [`mentorship/blog/`](mentorship/blog/) |

## Curriculum at a glance

| Module | Title | Ages | Time |
|---|---|---|---|
| 1 | [AI in Everyday Life](curriculum/module-1-ai-in-everyday-life/) | 11–18 | 45 min |
| 2 | [Understanding Security Controls](curriculum/module-2-understanding-security-controls/) | 11–18, adults | 50 min |
| 3 | [Pathways to Cybersecurity Careers](curriculum/module-3-pathways-to-cyber-careers/) | 13–18 | 45 min |
| Bonus | [Global Perspectives: What I Learned in China](curriculum/global-perspectives-china/) | 13+, adults | 30 min |

Each module includes a lesson plan, slides outline, hands-on activity, short quiz with answer key, and a take-home handout. Every activity has an unplugged version for sites without devices or internet.

## Workshop formats

| Format | Length | Guide |
|---|---|---|
| College peer session (study abroad + cyber/AI) | 45–60 min | [`workshop-peer-session.md`](workshops/workshop-peer-session.md) |
| School classroom | 50–60 min | [`workshop-school.md`](workshops/workshop-school.md) |
| Library / family night | 60–75 min | [`workshop-library.md`](workshops/workshop-library.md) |
| Educators & school staff | 60 min | [`workshop-educators.md`](workshops/workshop-educators.md) |

## Try Phishing Spotter

[**Phishing Spotter**](activities/phishing-spotter/index.html) is a browser game where players decide whether messages are safe or scams, including scenarios aimed at school staff, patients and families. It runs offline from one HTML file, works on Chromebooks and phones, and collects no data. Once GitHub Pages is on, it's playable online at `/activities/phishing-spotter/` on this repo's Pages site.

## Quick start for teachers, librarians and outreach teams

1. Pick a module and read its `lesson-plan.md` (about 10 minutes).
2. Print the `handout.md` for each participant.
3. Run it with the [facilitator guide](workshops/facilitator-guide.md).
4. Optional: use the anonymous [pre/post survey](impact/pre-post-survey.md) to see what's working.

No cybersecurity background needed. Questions or feedback? Open an issue.

## Repository structure

```
cyberbridge-oklahoma/
├── README.md
├── docs/
│   ├── project-plan.md            Goals, proposal crosswalk, timeline
│   └── github-setup.md            Publish this repo + turn on GitHub Pages
├── curriculum/
│   ├── module-1-ai-in-everyday-life/
│   ├── module-2-understanding-security-controls/
│   ├── module-3-pathways-to-cyber-careers/
│   └── global-perspectives-china/
├── workshops/
│   ├── facilitator-guide.md
│   ├── gilman-segment.md          "Study Abroad Is for You" (used in every workshop)
│   ├── workshop-peer-session.md
│   ├── workshop-school.md
│   ├── workshop-library.md
│   └── workshop-educators.md
├── activities/phishing-spotter/   Interactive browser game
├── mentorship/
│   ├── mentorship-guide.md
│   └── blog/                      First-person blog posts
├── outreach/email-templates.md
├── impact/                        Optional survey + session log
├── CONTRIBUTING.md
└── LICENSE
```

## About the creator

**Bristie Rahman** is a first-generation college student in cybersecurity and a Benjamin A. Gilman International Scholar. She grew up in a low-income Oklahoma household where her high school offered no cybersecurity classes, and nearly left college in her first semester before finding her footing in the field. She has worked as a Security Control Assessor at the Oklahoma Cyber Innovation Institute (OCII) and as a teaching assistant for the GenCyber bootcamp, and currently as serves as a Cyber Engineer at Northrop Grumman. Through the Gilman Scholarship she studied in China, attending Shanghai University of Sport and China University of Petroleum (Beijing), sitting in on sample AI lectures, and visiting places like the Forbidden City and the Great Wall. Read the story on the [blog](mentorship/blog/) or find her on LinkedIn.

## Acknowledgments

This is a Follow-on Service Project of the **Benjamin A. Gilman International Scholarship Program**, sponsored by the U.S. Department of State's Bureau of Educational and Cultural Affairs. Views and content are the author's own and do not represent the U.S. Department of State, the Gilman Program, or any current or former employer. Learn about the scholarship at [gilmanscholarship.org](https://www.gilmanscholarship.org).

## License

Curriculum and written content: [CC BY 4.0](LICENSE). Code (Phishing Spotter): MIT. Use it, adapt it, share it, just give credit.

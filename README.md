<!--
  ───────────────────────────────────────────────────────────────────────
  EVERYTHING VISUAL HERE IS SERVED FROM THIS REPO. Nothing upstream can
  rot, rename a folder, or pause a Vercel deployment and take you with it.

  assets/header-strip.png   saved copy of the halfrost tech collage
  assets/divider.png        saved copy of the colored rule
  assets/banner.svg         custom, text baked to outlines, no font loading
  assets/h-*.svg            section headers, same deal

  Only two external services survived the cull, both verified working:
    github-profile-summary-cards.vercel.app
    streak-stats.demolab.com
  If either ever dies, delete its line. Nothing else depends on it.
  ───────────────────────────────────────────────────────────────────────
-->

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/divider.png" width="100%">

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/header-strip.png" width="100%">

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/banner.svg" alt="Satyam Singh, backend systems and AI automation" width="100%">

<div align="center">
  <a href="https://portfolioforsatyam.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-02061C?style=flat-square&logo=vercel&logoColor=F5F1E6"></a>
  <a href="https://drive.google.com/file/d/1ibG7XC30fwEWV9OXs2ufUDx9iZIxPcv1/view"><img alt="Resume" src="https://img.shields.io/badge/Resume-02061C?style=flat-square&logo=googledrive&logoColor=F5F1E6"></a>
  <a href="mailto:businesswithsatyam9555@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-02061C?style=flat-square&logo=gmail&logoColor=F5F1E6"></a>
  <a href="https://www.linkedin.com/in/satyam8932/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-02061C?style=flat-square&logo=linkedin&logoColor=F5F1E6"></a>
  <a href="https://www.upwork.com/freelancers/~015123bd12ad914e39"><img alt="Upwork" src="https://img.shields.io/badge/Upwork-02061C?style=flat-square&logo=upwork&logoColor=F5F1E6"></a>
  <a href="https://leetcode.com/u/Satyam8932/"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-02061C?style=flat-square&logo=leetcode&logoColor=F5F1E6"></a>
  &nbsp;
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=satyam8932&label=Visitors&color=F7BD40&style=flat-square&abbreviated=true">
  <img alt="Followers" src="https://img.shields.io/github/followers/satyam8932?style=flat-square&label=Followers&labelColor=02061C&color=2289B6">
</div>

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-whoami.svg" alt="whoami" width="100%">

Full stack developer and AI automation engineer, operating out of India under the name **TechFixNexus**. I build two kinds of things: backend systems that are not allowed to fall over, and automation that quietly deletes work somebody was doing by hand at eleven at night.

Around **50 clients** so far across real estate, fintech, healthcare and ecommerce, mostly through Upwork, where I am **Top Rated with a 100% job success score**. Nobody has asked for a refund yet. I am choosing to read that as enthusiasm rather than politeness.

Before freelancing ate my calendar I was the founding and only engineer at **DripPilot**, a B2B SaaS for real estate campaign automation. Sole technical owner means I wrote the code, picked the infrastructure, lost arguments with third party APIs, and carried the pager. There was nobody else to blame, which is character building and also genuinely awful.

I also ran **GenieAI** as project admin through GSSoC, which meant reviewing pull requests from strangers on the internet. Turns out that is an entirely different skill to writing the code yourself, and a much more annoying one.

<details>
<summary><b>You are a recruiter and want the facts without the poetry</b></summary>

<br>

| | |
| :-- | :-- |
| **Looking for** | Backend, full stack, or AI engineering |
| **Open to** | Full time, contract, or contract to hire. Remote, or India based |
| **Timezone** | IST, UTC+5:30. Happily overlap US and EU hours, caffeine permitting |
| **Education** | B.Tech, Computer Science and Engineering, 2021 to 2025 |
| **Certification** | [Microsoft Certified: Azure AI Engineer Associate, AI-102](https://learn.microsoft.com/api/credentials/share/en-us/satyam8932/26A8EFD973FF83B4?sharingId=AF4BE9753542A0C0) |
| **Resume** | [Grab it here](https://drive.google.com/file/d/1ibG7XC30fwEWV9OXs2ufUDx9iZIxPcv1/view) |

My best work is in private client repositories, so this profile is the smaller and less interesting half of the story. Ask and I will screen share the real thing.

</details>

<details>
<summary><b>You want something built and need to know if I can build it</b></summary>

<br>

| | |
| :-- | :-- |
| **Typical scope** | AI automation, voice agents, LLM features, integrations, internal tools, APIs |
| **Engagement** | Fixed scope with milestones, or a weekly retainer |
| **Track record** | 50+ clients, Top Rated on Upwork, 100% job success score |
| **Verticals** | Real estate, fintech, healthcare, ecommerce |
| **Start here** | [Upwork](https://www.upwork.com/freelancers/~015123bd12ad914e39) or [email](mailto:businesswithsatyam9555@gmail.com) |

I will also tell you when your problem does not need custom software and a spreadsheet would do. That conversation is free, and it has saved clients more money than anything I have ever invoiced for.

</details>

<details>
<summary><b>You are a developer and want to know if I have opinions</b></summary>

<br>

I have several, and I will defend them for longer than anyone wants.

- Queues and retries are not a scaling concern, they are a day one concern. Anything crossing a network boundary will fail, and it will pick a Friday evening to do it.
- Idempotency keys on every write path a webhook can reach. Providers replay. They do not warn you. They do not apologise. They will happily charge your customer twice.
- An LLM feature with no eval set is a demo. Demos are delightful right up until a user finds the one prompt that makes your support bot confess to things it did not do.
- Multi tenancy belongs in the data model from the first migration. Bolting it on later is a rewrite wearing a false moustache.
- Boring infrastructure, interesting product. Postgres until Postgres genuinely taps out, which is considerably later than most architecture diagrams assume.
- The automation is not finished when it works. It is finished when it fails loudly, retries sensibly, and tells a human which record it choked on.

</details>

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-build.svg" alt="what i build" width="100%">

| Area | What that actually means | Tools I reach for |
| :-- | :-- | :-- |
| **AI automation** | Multi step workflows moving data between systems, with retries, queues, and a human in the loop wherever the stakes deserve one | n8n, Make, Zapier, custom Node workers |
| **LLM features** | Retrieval pipelines, tool calling, structured extraction, and evaluation before any of it meets a paying customer | OpenAI, Claude, Gemini |
| **Voice agents** | Phone agents that qualify, book and route calls without sounding like a fax machine having a bad day | Vapi, Retell, Bland |
| **Backend services** | REST and event driven APIs, background jobs, caching, multi tenant data models | NestJS, FastAPI, Node.js, Go, PostgreSQL, Redis |
| **Full stack products** | The dashboards and client facing apps that sit on top of all of the above | Next.js, React, TypeScript |

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-work.svg" alt="selected work" width="100%">

| Project | What it is | Stack | |
| :-- | :-- | :-- | :-- |
| **[GenieAI](https://github.com/satyam8932/genieai)** | Chat with your own PDFs. Retrieval over a vector store, real auth, a document workspace. Ran as a GSSoC project, so a good chunk of it is other people's code that I reviewed into shape. | Next.js, TypeScript, Drizzle, Postgres, Pinecone, Clerk | <img alt="stars" src="https://img.shields.io/github/stars/satyam8932/genieai?style=flat-square&labelColor=02061C&color=F7BD40"> |
| **[Sign Language Detector](https://github.com/satyam8932/Sign-Language-Detector)** | Real time hand sign recognition off a webcam feed. Computer vision, back when I thought that was the hard part. | Python, OpenCV | <img alt="stars" src="https://img.shields.io/github/stars/satyam8932/Sign-Language-Detector?style=flat-square&labelColor=02061C&color=F7BD40"> |
| **[Portfolio](https://portfolioforsatyam.vercel.app)** | My own site. Case studies, and a contact form I actually read. | Next.js | <img alt="stars" src="https://img.shields.io/github/stars/satyam8932/Portfolio-Website?style=flat-square&labelColor=02061C&color=F7BD40"> |

Client work stays private by contract. What is public here is what legal lets me show you, which is not the same thing as what I am proud of.

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-stack.svg" alt="toolchain" width="100%">

| Layer | |
| :-- | :-- |
| **Languages** | <img alt="TypeScript, JavaScript, Python, Go, C++, C" src="https://skillicons.dev/icons?i=ts,js,python,go,cpp,c" height="36"> |
| **Backend** | <img alt="NestJS, Node.js, Express, FastAPI, Django" src="https://skillicons.dev/icons?i=nest,nodejs,express,fastapi,django" height="36"> |
| **Frontend** | <img alt="React, Next.js, Redux, Tailwind, Figma" src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,figma" height="36"> |
| **Data** | <img alt="PostgreSQL, MySQL, MongoDB, Redis, Prisma, Supabase" src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,prisma,supabase" height="36"> |
| **Infrastructure** | <img alt="Docker, Linux, Nginx, AWS, Azure, Vercel" src="https://skillicons.dev/icons?i=docker,linux,nginx,aws,azure,vercel" height="36"> |
| **Automation and AI** | <img alt="n8n" src="https://img.shields.io/badge/n8n-02061C?style=flat-square&logo=n8n&logoColor=EA4B71"> <img alt="Make" src="https://img.shields.io/badge/Make-02061C?style=flat-square&logo=make&logoColor=6D00CC"> <img alt="Zapier" src="https://img.shields.io/badge/Zapier-02061C?style=flat-square&logo=zapier&logoColor=FF4F00"> <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-02061C?style=flat-square&logo=openai&logoColor=F5F1E6"> <img alt="Claude" src="https://img.shields.io/badge/Claude-02061C?style=flat-square&logo=claude&logoColor=D97757"> <img alt="Gemini" src="https://img.shields.io/badge/Gemini-02061C?style=flat-square&logo=googlegemini&logoColor=8E75F8"> <img alt="Vapi, Retell, Bland" src="https://img.shields.io/badge/Vapi%20%7C%20Retell%20%7C%20Bland-02061C?style=flat-square&labelColor=02061C&color=94AFC0"> |

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-now.svg" alt="currently" width="100%">

<div align="center">
  <img alt="What I am working on right now" src="https://readme-typing-svg.demolab.com?font=Chakra+Petch&weight=600&size=20&pause=1500&color=94AFC0&center=true&vCenter=true&width=820&height=46&lines=Building+agent+driven+automation+for+client+operations;Shipping+multi+tenant+backends+that+survive+real+traffic;Reading+about+distributed+systems+and+failing+gracefully;Grinding+DSA+so+whiteboards+stop+being+a+personality+test;Explaining+to+APIs+why+their+documentation+is+fiction">
</div>

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-receipts.svg" alt="receipts" width="100%">

<div align="center">
  <img alt="Profile summary" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=satyam8932&theme=github_dark" width="100%">
</div>

<div align="center">
  <img alt="Languages by repository" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=satyam8932&theme=github_dark" width="48%">
  <img alt="Languages by commit" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=satyam8932&theme=github_dark" width="48%">
</div>

<div align="center">
  <img alt="Contribution streak" src="https://streak-stats.demolab.com?user=satyam8932&hide_border=true&border_radius=10&background=02061C&stroke=1E2A5E&ring=F7BD40&fire=E0160A&currStreakNum=F5F1E6&sideNums=F5F1E6&currStreakLabel=F7BD40&sideLabels=94AFC0&dates=94AFC0" width="62%">
</div>

<div align="center">
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/dist/snake.svg" width="100%">
</div>

GitHub only counts the work I am allowed to push. Treat all of the above as a lower bound.

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/h-ping.svg" alt="ping me" width="100%">

| You want to | Go here |
| :-- | :-- |
| Hire me for a project | [Upwork](https://www.upwork.com/freelancers/~015123bd12ad914e39) |
| Talk about a role | [LinkedIn](https://www.linkedin.com/in/satyam8932/) or [email](mailto:businesswithsatyam9555@gmail.com) |
| See the case studies | [portfolioforsatyam.vercel.app](https://portfolioforsatyam.vercel.app) |
| Read the resume | [Google Drive](https://drive.google.com/file/d/1ibG7XC30fwEWV9OXs2ufUDx9iZIxPcv1/view) |
| Check I am not lying about the cert | [Microsoft Learn](https://learn.microsoft.com/api/credentials/share/en-us/satyam8932/26A8EFD973FF83B4?sharingId=AF4BE9753542A0C0) |

<br>

<img src="https://raw.githubusercontent.com/satyam8932/satyam8932/main/assets/divider.png" width="100%">

<div align="center">
  <sub>I build software because arguing with a computer feels more productive than arguing with people. The computer also loses more often.</sub>
</div>

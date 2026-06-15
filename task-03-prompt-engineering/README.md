# Task 03: Production-Grade Prompt Engineering Framework

## Task Objective
The objective of this task is to test and document how professional prompt structures (utilizing explicit context, roles, and constraints) improve AI code and content outputs compared to basic, lazy inputs. 

---

## Category 1: Website Content (Engineering Approach)

### Prompt 1.1: CoreTech Homepage Hero Headline

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a hero headline for a software development agency web page. |
| **Expected Output (AI Raw)** | *"We build high-quality software applications for your business needs."* (Too generic, sounds like every other company). |
| **Improved Version** | Act as a tech startup copywriter. Write a powerful hero headline and subheadline for our agency 'CoreTech'. We specialize in custom full-stack web applications for scalable startups. Make it sound modern, tech-focused, and project an ambitious brand image. |
| **Analysis (Why it works)** | Giving it a role (startup copywriter) and mentioning our specific focus (full-stack web apps for startups) forces the AI to stop giving generic corporate fluff and write something sharp. |

### Prompt 1.2: Portfolio Project Description (Alibaba Clone)

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a short text describing an Alibaba clone project we built. |
| **Expected Output (AI Raw)** | *"We built an e-commerce application inspired by Alibaba featuring search and multiple grid layouts."* (Sounds like a high school project). |
| **Improved Version** | Draft a professional portfolio project breakdown for our 'Alibaba-inspired E-Commerce UI Clone'. Structure it with three headings: 1. The Challenge (Responsive CSS layout), 2. Our Backend & Frontend Stack (PHP, SQL database integration, dynamic product galleries), and 3. Final Outcome. Keep the tone highly technical. |
| **Analysis (Why it works)** | I explicitly forced the AI to use our engineering stack keywords (PHP, SQL, CSS Grid). This changes a simple description into a proper technical case study that looks good on GitHub. |

### Prompt 1.3: CoreTech Services Page Layout

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | List our services: web development, brand identity, and custom automation tools. |
| **Expected Output (AI Raw)** | A boring list with dictionary definitions of what web development or logo design means. |
| **Improved Version** | Create a services page breakdown for our agency 'CoreTech'. For our three core services (Full-Stack Web Development, UI/UX Optimization, and Graphic Design/Branding), write a catchy benefit-driven title and 3 bullet points showing what the client gets. Keep the focus on how we help businesses grow, not just tech jargon. |
| **Analysis (Why it works)** | Instead of letting the AI write dry definitions, I told it exactly what our 3 services are and asked for "benefit-driven" bullets so it sounds appealing to a real client. |

### Prompt 1.4: About Us Section (Our Tech Background)

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write an about us page introduction for CoreTech engineering agency. |
| **Expected Output (AI Raw)** | *"We are a team of dedicated professionals who work hard to give you excellence since day one."* (Standard robotic text). |
| **Improved Version** | Write a 120-word 'About Us' intro text for CoreTech. Mention that we have a strong background in Computer Systems Engineering (microprocessors, logic design) but we specialize in building modern web apps. The tone should be young, energetic, professional, and confident. |
| **Analysis (Why it works)** | Adding our core background (Computer Systems Engineering) makes the text authentic and distinct. Setting a 120-word limit also stops the AI from writing long, useless paragraphs. |

### Prompt 1.5: Project Inquiry Form FAQ

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Generate 3 FAQs for software development clients. |
| **Expected Output (AI Raw)** | Super broad questions like "How much do you charge?" with vague answers like "It depends on the project." |
| **Improved Version** | Generate 3 professional FAQ pairs for our CoreTech project onboarding page. Address these specific doubts that clients usually ask: 1. Who owns the final source code and GitHub repository? 2. Do you help with server hosting? 3. What happens if we want to change a feature mid-project? Write clear, firm, but polite answers. |
| **Analysis (Why it works)** | I pre-selected the exact pain points (code ownership, hosting, scope changes). This ensures the AI provides valuable, realistic project management answers instead of fluff. |

---

## Category 2: Social Media Captions

### Prompt 2.1: My C++ Internship Project Post

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a LinkedIn post about finishing a C++ console project internship task. |
| **Expected Output (AI Raw)** | *"Excited to share that I completed my C++ project today! Thanks to my mentors for the support."* (Too simple, sounds like a high school student status). |
| **Improved Version** | Write a professional LinkedIn post about my new C++ console To-Do List app. Mention that I used Object-Oriented Programming (OOP) to make it. Split the text into short lines, add 3-4 hashtags at the end, and don't use too many emojis. |
| **Analysis (Why it works)** | I told the AI exactly what project I built (To-Do List) and what coding concept I used (OOP). Now the post will look like a real programming student wrote it. |

### Prompt 2.2: Instagram Carousel for UI/UX Design Tips

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write tips on typography for designers for an Instagram post. |
| **Expected Output (AI Raw)** | A long paragraph about fonts that is impossible to read on an Instagram photo. |
| **Improved Version** | Create text for a 5-slide Instagram carousel post. The topic is 'Best Typography Tips for Web Design'. For Slide 1 to 4, give a short heading and 2 simple bullet points. Slide 5 should be a Call-to-Action like 'Follow CoreTech for more design tips'. Keep text very short. |
| **Analysis (Why it works)** | I told the AI to break the text slide-by-slide. This makes it easy to copy-paste directly into Canva or Figma for designing the post. |

### Prompt 2.3: Twitter Thread about Clean Coding

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write tweets explaining why clean code matters. |
| **Expected Output (AI Raw)** | One giant message that doesn't fit the Twitter character limit. |
| **Improved Version** | Write a Twitter/X thread of exactly 3 tweets about why writing clean code is important for beginners. Number them as 1/3, 2/3, and 3/3. Keep each tweet short and under 240 characters. |
| **Analysis (Why it works)** | Specifying the number of tweets and character limit stops the AI from generating text that is too long for Twitter. |

### Prompt 2.4: My AI Internship Announcement Post

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a post stating I started my AI internship at CoreTech Innovation. |
| **Expected Output (AI Raw)** | *"Happy to report I am starting an artificial intelligence engineering internship at CoreTech!"* (A bit boring). |
| **Improved Version** | Write an announcement post for LinkedIn. I am starting my new Artificial Intelligence Engineering Internship at CoreTech Innovation. Mention that I am excited to learn Python automation and core AI concepts. Keep the tone enthusiastic and professional. |
| **Analysis (Why it works)** | Adding specific topics (Python automation, AI concepts) makes the announcement sound much more credible to tech recruiters on LinkedIn. |

### Prompt 2.5: Sharing My GitHub Repository

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a short post telling developers to check out my repository. |
| **Expected Output (AI Raw)** | *"Check out my new code repo on GitHub. It has custom full-stack solutions built using PHP and SQL databases."* (Doesn't grab attention). |
| **Improved Version** | Write a friendly post for the developer community. Tell them I built an 'Image Gallery with Metadata' project using PHP and an SQL database. Ask them to check my GitHub repository, try the code, and give feedback on my database structure. |
| **Analysis (Why it works)** | Asking for "feedback on my database structure" makes the post interactive. Other developers are more likely to click the link and help out. |

---

## Category 3: Client Emails

### Prompt 3.1: Replying to a New Client Inquiry

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Email a potential client back who wants a web platform built. |
| **Expected Output (AI Raw)** | *"Thanks for contacting us. Let us know when you want to call to talk about your custom web platform."* (Too short and not very professional). |
| **Improved Version** | Write a polite email reply to a new client who filled out our website form asking for a web application. Use placeholders like [Client Name]. Thank them for reaching out, and ask 3 simple questions about their project requirements, budget, and timeline. End with an invitation to jump on a quick call. |
| **Analysis (Why it works)** | By telling AI to ask 3 specific questions (requirements, budget, timeline), the email helps us get all the important project details before we start working. |

### Prompt 3.2: Sending Figma Designs for Review

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Tell the client the UI/UX mockups are finished in Figma. |
| **Expected Output (AI Raw)** | *"Hey, the mockups are ready on Figma. Look over them and send your review when you can."* (Sounds too casual, like talking to a friend). |
| **Improved Version** | Write a professional project update email to a client. Tell them that our CoreTech team has finished the UI/UX high-fidelity designs in Figma. Give them clear steps on how to open the Figma link and view the screens. Ask them to share their feedback within 4 days so we can stay on schedule. |
| **Analysis (Why it works)** | Setting a deadline ("within 4 days") keeps the project on track and ensures the client knows their feedback is needed quickly to avoid delays. |

### Prompt 3.3: Handling Out-of-Scope Requests (Scope Creep)

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Reject a client request to add extra features for free. |
| **Expected Output (AI Raw)** | *"We cannot add these features because they were not part of the initial payment agreement."* (Sounds very rude and harsh). |
| **Improved Version** | Act as a polite Project Manager. Write an email to a client who is asking for extra features that were not in our original agreement. First, praise their idea. Then, gently explain that this requires extra development hours. Offer them two options: add it as a paid extension now, or build it in Phase 2 after the main launch. |
| **Analysis (Why it works)** | Instead of saying a flat "No," this prompt helps us say no politely while offering helpful solutions, keeping the client relationship happy. |

### Prompt 3.4: Friendly Payment Reminder Email

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Send an invoice reminder email to a client who hasn't paid. |
| **Expected Output (AI Raw)** | *"Your invoice is overdue. Please pay it as soon as possible so we don't halt development."* (Sounds panicked and aggressive). |
| **Improved Version** | Write a gentle but firm email reminding a client that their project invoice is 5 days overdue. Keep the tone completely objective and polite. Use placeholders like [Invoice Number]. Ask them to confirm if they have received the invoice or if they need any assistance with the payment process. |
| **Analysis (Why it works)** | It removes any awkward or angry language, making it look like a standard, professional automated system reminder. |

### Prompt 3.5: Final Project Handover and Code Delivery

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Send the final project code and documentation to the client. |
| **Expected Output (AI Raw)** | *"Attached is the source file zip archive. Thanks for working with our team on this project."* (Too dry for such a huge milestone). |
| **Improved Version** | Write a comprehensive project closure email for CoreTech. Congratulate the client on their successful website launch. Provide clear details about what we are handing over (GitHub repository links, admin credentials, and documentation guide). At the end, mention that we also offer monthly maintenance services to help them long-term. |
| **Analysis (Why it works)** | It celebrates the launch, itemizes everything clearly so there's no confusion, and opens the door to upselling our monthly maintenance package. |

---

## Category 4: Business Ideas

### Prompt 4.1: Tech Business Ideas for Students

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Give me 3 software business ideas. |
| **Expected Output (AI Raw)** | Generic suggestions like "An online clothing marketplace" or "A basic food delivery app." (Too common). |
| **Improved Version** | Act as a business startup advisor. Brainstorm 3 realistic Micro-SaaS software ideas that a team of 2-3 university engineering students can build in a month. Focus on simple automated tools that solve everyday problems for local freelance graphic designers or content writers. For each idea, give a short title and monetization plan. |
| **Analysis (Why it works)** | It narrows down the scope for students (1-month timeline) and targets a specific audience (local freelancers), so the ideas are practical and achievable. |

### Prompt 4.2: Local Workflow Web App

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | What is a good business app idea for tech students? |
| **Expected Output (AI Raw)** | *"A notes sharing app or an online campus group study finder."* (Very basic). |
| **Improved Version** | Generate a business model concept for a web layout handoff tool. This tool should help student front-end developers easily convert Figma designs into basic PHP and CSS layouts. Explain the main problem it solves and why it is better than standard complex tools. |
| **Analysis (Why it works)** | This prompt focuses on a real workflow problem that engineering and design students face daily, making it a valuable project concept. |

### Prompt 4.3: Graphic Design & Web Micro-Agency Plan

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | How do I start a design web agency? |
| **Expected Output (AI Raw)** | Vague steps like "Make a portfolio website and look for clients online." |
| **Improved Version** | Provide a simple, step-by-step 4-week roadmap for two university students to launch a micro-agency that designs and builds custom portfolio websites for local professionals. Tell us what tasks to do each week to set up our workflow and reach our first 3 clients. |
| **Analysis (Why it works)** | Setting a strict 4-week timeline and a small target goal (3 clients) turns a massive business idea into a simple, practical checklist. |

---

## Category 5: Chatbot Responses

### Prompt 5.1: CoreTech Website Welcome Message

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | Write a greeting for a chatbot on an agency website. |
| **Expected Output (AI Raw)** | *"Hello! Welcome to our website. How can I help you today? Please choose an option."* (Standard and robotic). |
| **Improved Version** | Act as CoreTech's website chatbot assistant. Write a short, friendly welcoming greeting. Right after the greeting, show 3 clear bullet-point choices for visitors: 1. Request a website project quote, 2. Check out our student portfolio work, 3. General inquiry. Keep it brief and professional. |
| **Analysis (Why it works)** | It immediately gives the visitor clear options to click, routing them to the right place instead of letting them type long messages. |

### Prompt 5.2: Server Downtime / Error Response

| Layer | Content / Technical Execution |
| :--- | :--- |
| **Initial Prompt (First Try)** | What should a chatbot say when a server crashes? |
| **Expected Output (AI Raw)** | *"Error 500: The server is offline. Please refresh your browser window later."* (Cold). |
| **Improved Version** | Write a reassuring chatbot response for when our application server faces unexpected downtime. Keep the tone professional but human. Tell the user that our engineering team has been notified, triage is underway, and provide a helpful link where they can check our live system status page. |
| **Analysis (Why it works)** | It reduces client panic by assuring them that the engineering team is already working on the problem, building trust even during a crash. |

---

## Deliverables
* **Jupyter Notebook File:** `Prompt_Engineering_Lab.ipynb` (Contains raw code runs).

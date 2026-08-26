# Retrospective

To the version of me starting this in week one.

I thought the goal was to look competent. A clean portfolio. A tidy case study. A site that made me look ready before I was ready. That goal was wrong. I found out fast.

My week one proof statement said I understood a business problem before I started building. It sounded good to me. Then a real person looked at my site and told me she thought I managed a company. She based that on the charts and the case study language, not on anything about data or AI. My statement had not landed. I rewrote it. "I research the data before I build, so what I ship actually works." One person told me the truth. I listened instead of defending my first draft.

That pattern repeated. I wrote five test cases for the ABNT agent before I built anything. Two of them failed the first time I ran them for real. The agent cited a source it did not have. In another case, I asked it to email a professor for me, and it treated the missing tool as a logistics problem instead of refusing outright. I rewrote the instruction until it held the line every time.

The same bug shape showed up again on my portfolio's AI feature. It blocked a prompt injection attempt, but the error message looked like a crash instead of a refusal. I had already marked that fixed once. My girlfriend tested it with no coaching from me and found the real problem in ten seconds. That moment mattered more than anything else in this program. Someone outside my own head tested for real and found what I missed reviewing my own work.

I also learned that finished does not mean working. A perfect SEO score told me nothing about whether Google had indexed my site. It had not. A commit that looked fine broke the whole page because of one missing line of code. I stopped trusting "it should work." I started trusting "I tested it and here is what happened."

Here is what I built, in order.

- A BI dashboard for a real client, before I had any right to call myself a data analyst.
- An n8n automation with a real webhook and a real API call, the first one I wrote by hand.
- A citation checking agent that replaced an earlier no-code workflow.
- A RAG pipeline in Python, my first real work with embeddings and vector search.
- A live AI feature on my own site, with a real security bug and a real fix behind it.

Next, I want to build something with real users beyond myself. I want a feedback loop that runs on its own, not one I have to go find each time. Automation and data pipelines for a real business process feel like the right direction. That thread showed up in everything I enjoyed building this program.

Three things I will carry into whatever comes next.

- Write the test before you build the thing. My five ABNT test cases existed before I wrote the first prompt. That order is the only reason the two failures got caught instead of shipped.
- A stranger's five minutes beats your own hundred hours staring at your own work. Every real fix this program came from someone else's eyes, not mine.
- When something looks broken, find the reason before you explain it away. I checked logs. I checked the network tab. I checked search results. I did not settle for a guess until I actually knew.

I did not become someone who looks competent. I became someone who checks.

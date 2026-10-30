# STAR Story Coach

An interactive coach for behavioral interviews, built for airport operations roles.

## Modules

**Training.** Short lessons on the STAR method plus Lessons learned. Type a story in your own words and the coach turns it into Situation, Task, Action, Result and Lessons, scores each part, and marks the places where a real number would make the answer stronger. Fill in your figures and it rewrites the answer with them. It never invents numbers.

**Interview Prep.** Enter the role and paste the job posting. The coach predicts likely questions, matches each one to your best saved story, lists gaps to fill and suggests questions to ask the interviewer.

**Mock Interview.** A hiring manager asks 3 or 5 behavioral questions one at a time, probes with follow ups, then scores every answer.

**My Stories.** Your saved story bank, the habits the coach has learned from your sessions, and your score trend.

## How to run it

`index.html` is built to run as a Claude artifact. The AI coaching and the private story bank use Claude's artifact runtime (`sample`, `db` and `user` capabilities), so those features work only when the page is opened inside Claude. Opened as a plain file in a browser, the lessons display and stories save to that browser, but the coach buttons stay disabled.

## STAR at a glance

| Part | Share of answer | What to say |
| --- | --- | --- |
| Situation | about 10 to 15% | The scene in one or two sentences |
| Task | about 10% | What you personally owned |
| Action | about 60% | Your steps and why, using "I" |
| Result | about 10 to 15% | The outcome with numbers |
| Lessons | a sentence or two | What you learned and do differently now |

# Coding the Law Fall 2018

##Small Firm Security & Efficiency Q&A

#####**<u>Links</u>**:

[QnA Interview](https://dbarrgh.github.io/ctl_final/Final_page.html)

[Source Code](https://dbarrgh.github.io/ctl_final/ONGOING QNA.txt)

[Docassemble Mockup](https://dbarrgh.github.io/ctl_final/Docassemble%20Mockup.jpg)

[QnA Markup Mockup](https://dbarrgh.github.io/ctl_final/QnA%20Markup%20Mockup.jpg)

[User Feedback (spreadsheet download)](https://dbarrgh.github.io/ctl_final/Q&A User Feedback(1-4).xlsx)

# Framing

This project emerged due to anecdotal observation during my time working in Boston's small-firm civil litigation community. The concept developed in part due to "culture shock" after transitioning from Boston's software/technology industry to the aforementioned legal community. I noticed that otherwise highly intelligent, capable, informed, and diligent attorneys appeared (again, anecdotally) *behind* in two aspects. The first: information; the second: implementation. 

## The Problem

Small firms that I have interacted with seem to have little in the way of *information* regarding what risks come along with the "Information Age." Specifically, it appears many attorneys simply do not have the information to make informed decisions regarding the use of technology, whether that use relates to storing and keeping data, transmitting data, or efficiently collaborating with others using electronic documents and content. Simple adjustments in behavior can significantly reduce risk, implementing a secure file transfer tool rather than E-Mailing medical records, or encrypting PC/Mac hard drives and making sure computers and other devices have passwords and are set to lock automatically after a period of idleness. To start, a simple means of identifying and describing these risks to attorneys through a "question and answer" format should be enough to *get them thinking.* Attorney's I have spoken with indicate an interest in learning more, but do not know where to start. Attorneys are accustomed to a "question and answer" approach to information gathering, and are typically responsive to clearly spelled out risk. This tool sets out ask simple, but probative questions that a small or solo practice attorney may answer, and produce a "score" of risk as well as simple, high level suggestions, providing key terms and descriptions so attorneys may pursue solutions on their own.

## Relevant Stakeholders/Users

This poses an issue, partially in the way this QnA functions, and partially in that it is meant to apply to any small or solo practice firm. There is no specific stakeholder in the project. Firstly, any direct testing of the QnA is asking attorneys to make "admissions" regarding present data practices, and given the inherent risk-averse attitude of most attorneys, this presents a real problem. To make a viable real world tool, it is likely this QnA would need to be hosted by a trusted source where an attorney could feel comfortable providing honest answers. Broadly, the hypothetical stakeholder in this solution is any attorney that might learn something useful from using it. Narrowly and realistically, I am the only genuine stakeholder at this time. 

The relevant user, as described above, is a small or solo practice attorney. Ideally, an attorney open to making small and incremental changes to habits, behaviors, and workplace tools, and is responsive to explanations of risk and options to mitigate exposure to said risk. Anecdotally, this ideal use is not real. The target user is generally busy, overwhelmed, and lacks the time to make any considerable changes or learn how to use new solutions or technologies. This up-front investment means any options this solution offers will have a high time-investment barrier to entry, which is why the tool aims to reduce the amount of total information provided to small "snippets." Ideally, an explanation of the risks associated with the user's current practices will spur motivation.

# Research

Law firm data security and privacy practices are hot topics in the legal community, which is apparent from both our class time and eve a cursory web search. My findings reveal that there are an abundance of articles, blog posts, and "list" format articles (IE "5 Things you can Do Right Now to Reduce..") targeting attorneys and law firms. Prominent publications such as *Lawyerist.com* and Massachusetts-based legal industry blog Masslomap.org address these topics. These are the "destinations" I would like this tool to send attorneys by equipping attorneys with the right "buzzwords" to get them there. I am unsure if it is appropriate to link to these articles through my project, as the articles are the work of others. As an example, Masslomap.org has an section of its website dedicated to the topic of data security: https://masslomap.org/category/risk-management/. My research yielded endless articles, videos, webinars, and the like, however, no interactive question-and-answer tool came up in my search. This page presents itself as a "quiz" (https://www.legalcomputer.com/law-office-technology/data-security-quiz/) but is not interactive. Although I cannot say with 100% confidence (nor should I) that no tool, concept, or product like this short question and answer exists, I did not find any in my research. Below are links to online publications addressing the same theme. I do not consider these "competitors" because these publications are where I would like the user to end up. The idea is to kick-start the search for information.

https://www.nicitpartner.com/cyber-security-quiz/ - this is a quiz targeting at "businesses" in general, however, it's also a sales funnel and obviously meant for lead generation.

[This ABA article addresses the issues succinctly](https://www.americanbar.org/groups/gpsolo/publications/gpsolo_ereport/2018/january-2018/cybersecurity-small-law-firms-survey/) but it is not a competitor because it's not a Q&A.

Importantly, there appears to be an abundance of generalized "cybersecurity" quizzes aimed at businesses. These are almost universally customer "hooks" found on the pages of consulting firms, cyber security providers, etc. and are evidently for capturing new customer interest.

# Ideation and Prototyping

 ## Brainstorm and Ideate: 

The initial manifestation of this tool was larger, more ambitious, and unrealistic. The first (unwritten) concept consisted of a series of branching logic questions, each question inquiring about a specific practice or behavior. 

**Example**
How, if at all, do you save or retain passwords for online services, accounts, and software?
A) With a password manager
B) I write them down on paper (in a journal, sticky notes, etc)
C) I keep them in a spreadsheet or electronic document...

Originally the QnA markup was the tool I imagined using. After realizing the limitations of QnA, and learning about Doccassemble, I determined Docassemble was the "better" option. However, this was a flaw in my design process. By picking Docassemble, I began to try and force my concept to fit Docassemble, and fir the first time my prototype changed substantially. I decided that because Docassemble is meant to produce a document, the Q&A should result in a "Memo" regarding risk exposure based on the user's answers. This idea was quickly abandoned based on users feedback (in the form of responses to my Intro Pitch). The memo would also include a "risk" score (1-10; or perhaps Red to Green, etc) *and* suggested products and behavioral changes.

## Prototype: 

###Prototype 1: Docassemble

I drew up a mockup (labeled "Docassemble Mockup") that should show the basic idea. Efforts to implement began a week prior to thanksgiving weekend. This was a failure in the design process on my part. I failed to a consider a third option, or properly research Docassemble. The design process faltered in this phase. I stumbled with Docassemble and determined I had selected it while making a number of underlying assumptions about the tool. Firstly, I assumed Docassemble, like QnA markup, consisted of simple *Question:_______* --> *Answer:_____* branching logic. This knowledge gap, one of my own making, hamstrung the project and significantly delayed it. Regardless, the other than abandoning the "Memo" element, the goal remained to produce a "score" and suggestions.

Docassemble required more time learning and the tool and the YAML language then I had anticipated. This was an oversight on my part, and a a direct result of assumptions about Docassemble that I had no business making. After two weeks of signficant time investment, I determined that my Docassemble ambitions are not feasible given the project timeline, and as a form of triage I needed to pivot to an expert system that was more layperson friendly. My self-imposed roadblock fatally derailed my first prototype.

**Prototype 2: QnA Markup**

I returned to the drawing board with a significantly reduced timeline. Given the structural differences between Docassemlbe (a much heavier tool) and QnA markup, I had to scale back the level of detail and specificity of the questions a user would be asked. See the QnA mockup designated "QnA Markup Mockup." The design philosophy shifted, by necessity, to producing a "minimal working product." The prototype developed quickly and did not change much. A few simple changes were made through the process, listed below. For reference, the product's design goals were dramatically changes.

### Testing

Serving as my own "user" at first, I found that my question format was clumsy and made it near impossible for the Q&A to properly ask every question I wanted to ask. Secondly, my efforts to shoehorn JavaScript into the the source code as a means of creating a "score." I abandoned this less as a "user" and more as the developer. Given the rushed nature of the project at this stage, user feedback was likely inadequate and incomplete. Using Microsoft Forms, I asked various users with differing backgrounds (A UI/UX Technical Writer; an IT consultant; and a feedback from a Tech Support professional). The IT consultant has paralegal experience. See attached spreadsheet "Q&A User Feedback" for all feedback generated. The feedback indicates 4 users, however, I believe one of the users may have done the survey twice or refreshed it. I was able to implement some user feedback, but only minimal amounts due to time constraints.

# Documentation?

Given the nature of the tool, it amounts to its own "documentation." There are simple instructions at the beginning, as well as a disclaimer. Instructions at the end inform the user he/she may download or print the results.

# Sustainability

This tool is minimally functional, and falls far short of the lofty goals I set for it. As far as future development goes, I would like to do the following:

1. Refine the questions, gather more user feedback, get the tool in front of attorneys.
2. Find a location to host the Q&A other than Github, so that attorneys in the Boston area might find it and use it.
3. Possible future transition to Docassemble, however, because this will incur costs, it may not be feasible unless the tool is hosted by a site that generates some ad revenue and the tool serves to drive "hits" to the site and pays for itself.
4. Given the rapid changes in technology, this tool's best chance for sustainability is to keep all questions simple and broad, and not drill down into the detail I had planned at the start.
5. To state the obvious, this tool needs a user base or stakeholder other than myself and the nebulous "Boston legal community" that is so far unaware of the tool. Perhaps collaboration with the LIT lab could see this tool published as part of Suffolk University's publicity push in the legal technology field.


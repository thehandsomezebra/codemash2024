
... Back to [[index]] ...


[[Thinking Architecturally]]

#### Thinking Architecturally
https://codemash.org/session-details/?id=535616

##### **Presented by:** [Nathaniel Schutta](https://codemash.org/speaker-details?id=1f3fa71c-0021-4d6e-af47-0013ecbaeb33)

Time: Wednesday, Jan. 10, 1:00 PM - 5:00 PM

Rich Hickey once said programmers know the benefits of everything and the trade offs of nothing...an approach that can lead a project down a path of frustrated developers and unhappy customers. As architects though, we must consider the trade offs of every new library, language, pattern or approach and quickly make decisions often with incomplete information. How should we think about the inevitable technology choices we have to make on a project? How do we balance competing agendas? How do we keep our team happy and excited without chasing every new thing that someone finds on the inner webs?  
  
As architects it is our responsibility to effectively guide our teams on the technology journey. In this talk I will outline the importance of trade offs, how we can analyze new technologies and how we can effectively capture the inevitable architectural decisions we will make. I will also explore the value of fitness functions as a way of ensuring the decisions we make are actually reflected in the code base.

Room: Nile**Tags:** Career Development, Soft Skills, ArchitectureLevel: Intermediate

---



I attended this as a 4 hr workshop session, the following are my notes from this session, from my perspective.


---


Recording of his talk from different conference in shorter-from:
https://www.youtube.com/watch?v=HaBKwa4E-Ro

His written abstract:
https://ntschutta.io/abstracts/thinking/

---


[[MY_NOTES from Thinking Architecturally]]



MY SUMMARY:


As DevOps engineers, we are often at the forefront of designing and maintaining complex software systems. Our decisions have a profound impact on the system's performance, reliability, and maintainability. To ensure we make well-informed decisions, we must adopt a structured approach that emphasizes documentation and continuous evaluation.  There's a lot that we can learn from an architectural viewpoint, so here's some of my biggest takeaways:

**The Power of Architectural Decision Records (ADRs)**

ADRs provide a systematic way to capture the rationale behind our architectural choices. They serve as a valuable communication tool, enabling team members to understand the "why" behind our decisions, not just the "what." With ADRs, we can:

- Facilitate effective knowledge transfer, ensuring that new team members can quickly grasp the architectural landscape.
- Establish consistency in our decision-making process, promoting a shared understanding of the system's evolution.
- Create a historical record of architectural decisions, enabling us to revisit and learn from past experiences.

An example ADR could look like this:
```
- It does not need to be complicated
- ADR: Lightweight atchitecurtew decision records
- title/ID (immutable)
- sequential order. 3-ish digit number should be suficient
- This can be helpful to eliminate tribal knowledge and establish context rapidly.
- Status - proposed, accepted, deprecated, superceded
- What is the problem - do not skimp on this! Give couple paragraphs or even pages!
- Give assumptions and constraints
- What are the options - 
- list pros and cons
- Which did you choose?
- Explain why?
	- Also explain why not --- we eliminated this other reason because xyz.
- Consequences of the decision (both positive and negative)

```

Some other information about using ADRs:
- If you do not fill this out, someone else will come up with a story and it could be drama.. Show your work!
- Also, you gain credibility if you go thru this process.
- This is also being done for people who are coming after you....(CYA)
	- Please remember that you will be the person who comes after you at some point.. You will always wonder "which idiot wrote this?!" but eventually it will dawn on you that YOU were that idiot.
- Consider a "time capsule" of what did you do and why. Even a short and sweet screencast can be good.
- Prevent Monday-morning-quarterbacking for "Why did we do this?" ... *"I'm sure we had a good reason, does anyone remember what that was?" "That's not what I would have done"* <--- you will now have reasons if you fill out all of the above.
- Do periodic reviews (especially with teams that have new members) because it can bring valued info to the table.
- Store in version control! Old versions WILL stick around.  Make sure that things are documented and stored and updated.  This is not the place for wiki or jira tickets! No one looks back at those things as regularly as they should... keeping it in version control with the repo will allow ease of use, access and maintainability.
	- Also don't overcomplicate it! Does not need to be it's own app...It does not need to be a website. It does not need to be a wiki. This should be short and sweet, always able to be updated when someone commits their code.  Simply use a bunch of files with a sequential order in your repo for best results.


https://adr.github.io/



By embracing ADRs, we foster a culture of transparency and accountability, encouraging thoughtful decision-making and continuous improvement.  If you don't do them right now, you can always start today. You don't need to start with a new project to do something right.


**Leveraging Fitness Functions for Architectural Health**

Quality attributes are essential characteristics that measure the non-functional aspects of a software system, complementing the functional requirements. These attributes, often referred to as "-ilities", encompass a wide range of aspects, including (but certainly not limited to) scalability, reliability, security, usability, and maintainability. By focusing on quality attributes, software architects and engineers can create systems that are not only functional but also resilient, adaptable, and user-friendly. Defining and prioritizing quality attributes early in the software development process helps ensure that the resulting system meets the needs of end-users and stakeholders.

Fitness functions are ways to achieve these quality attributes. They are essential tools for assessing the effectiveness of our architectural decisions. They provide quantifiable metrics that measure how well the system meets its intended quality attributes, such as performance, scalability, reliability, and maintainability. By continuously monitoring fitness functions, we can:

- Identify areas where the architecture may be falling short, allowing us to take proactive steps to address potential issues.
- Track the system's progress over time, ensuring that it continues to meet our evolving requirements.
- Make data-driven decisions about architectural changes, optimizing the system's overall health and performance.

Fitness functions empower us to make informed decisions, ensuring that our architectural choices align with the system's desired outcomes and user expectations.

Together, ADRs and fitness functions form a powerful combination that enables us to create and maintain software systems that are resilient, adaptable, and responsive to changing needs. By embracing these practices, we can elevate our engineering capabilities and deliver exceptional solutions that can stand the test of time.



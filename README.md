# BusinessQuantumFAQ
FAQ about the business side of quantum computing aimed at researchers in academia. 

**If you're here, you're absolutely welcome to contribute to this project. To do so, just create a pull request. You can contribute in various ways, including:**
- **Posing a new question**
- **Suggesting a resource**
- **Adding some short notes as an answer**
- **Expanding on an existing answer**
- **...**

This FAQ will focus on quantum computing (hardware & software) rather than broader quantum technologies (i.e. quantum sensing, quantum cryptography). While there are many interesting things to learn about the broader technologies, the business case for those is more obvious. When it comes to quantum computing, however, the business case is not so clear (at least to researchers in academia), given that the development of a useful fault-tolerant quantum computer might still be quite some time in the future. The purpose of this FAQ is to explain the business case for quantum computing, given this context, to researchers from an academic background. 

## Potential Questions

### INVESTING

#### Q: What is a venture capital (VC) investor?

_Some clues on how to answer this question might be found in the links under "About VCs and their perspective" in the Suggested Resources section at the end of this document._

#### Q: Why would someone invest in a quantum computing startup?

_Expand on these points:_
- Arguably the point is to make a return on the investment.
- Discuss exit strategies

The reason behind investing in (any) company depends on the investment round, type, fund and in the end, the person behind. In most cases it is about making a good return on the investment (ideally 20x onwards). But again it fully depends on the stage and type of company and VC.

Specifically in a field as young as Quantum Computing, we can divide the types of investment based on the capitalization needed. Hardware companies that require more starting capital will lure "big guns" investors with wide portfolios and used to long horizon series A, B or C.
Examples are D-Wave (https://www.crunchbase.com/organization/d-wave-systems/company_financials) and IonQ (https://www.crunchbase.com/organization/ionq-inc/company_financials) series of rounds.

Software companies (either consulting or SaaS) are typically less capitalized and follow smaller rounds. As such they can start with Seed rounds (or even "FFF", Friends Fools and Family). And grow from there.

On both cases, and contrary to more developed and mature industries, investors typically find their returns on the exit. Which comes after a new round with replacement investors and new capital. This is what increases the company valuation (sometimes artificially). This leads in some cases to missmanagement, or conflict of interests between founders and investors. The latter being more interested in increasing the valuation and going to a new round, the former into building a product that creates value. It is important to make sure investors and founders are fully aligned on the short and long term plans for the company.

In most industries (and certainly in Deep Tech) there is also specialization in funds. In Quantum Computing there is a handful of funds (very small at the moment) who invest only in QC. By doing so they are fully inmersed in the industry and can provide additional value to the founder (networking, access to additional capital, access to advisors, grants, etc).
On the other hand, big funds (and the majority of them have already at least one investment in their portfolio) enter with a purely financial strategy. Either portfolio diversification considering Quantum Computing a higher risk - higher return asset, or for potential leverages within their investments.

The third case is corporate entrepreneurship. Big corporations are typically risk averse and very slow to adapt new technologies into their processes. And the best way is to create accelerators or small funds that are highly linked to their industry. From those vehicles they can spot trends, identify opportunities and key people by a fraction of what it would cost to do "in house". In many cases those investments hold a majority of the shares of the company and when it makes sense they end up buying the whole company and incorporating it into the home company.

The Quantum Computing industry is still young and the economics don't lure dividend based investors. So EBITDA or ARR KPIs won't be typically considered. On the contraty they will be looking at Intellectual Property, papers and patents. Key people in the team, and client acquisition capabilities.

The main exits will be (a combination of):
* Bigger round exit (replacement) - I.e. From Seed to Series A
* Merger with another QC company
* Acquihire - A corporate or a bigger animal buying your team
* Client acquisition - Buying your clients, contracts and partnerships
* IP acquisition - Buying your technology

#### Q: Are VC investors foolishly funding some quantum startups that they shouldn’t be?

This partial answer was given by Scott Aaronson [6]:

"I don’t know the answer to this question (and don’t pretend to know when I’m asked). One problem is that many, many things that are easy to recognize as “foolish” in retrospect were hard to recognize as foolish at the time, even by the best experts that there were. Or the people who correctly said that these were foolish investments (and gave correct reasons), also said that Apple, Facebook, and Bitcoin were foolish investments.

One thing you learn, from even short exposure to the VC world, is that VCs are not even trying to answer the same question that an academic would: “is this proposal intellectually sound, or isn’t it?” They’re looking at a large number of other ways they might recoup the investment, like accumulating valuable IP, a buyout by a larger company (which might be more for the people than for the idea), etc. That makes it even more impossible for me to judge, except in some very special cases, whether people are making good or bad investments."

### BUSINESS

#### Q: Why are businesses interested in exploring quantum computing *now*?

Yianni Gamvros discusses the idea of _Quantum Insurance_ [1]:
- "You don’t want to get blindsided and find out from others what is possible. You should have a quantum strategy and contingency plans.
- If you wait for the technology to mature, it will be too late. You need to start training people that can hit the ground running as soon as the technology gets there. Training people takes time, literally years.
- Technology timeframes are always shrinking. Twenty years ago, people thought quantum computing was a sci-fi dream. Ten years ago, most people believed practical quantum computers were 50 years out. Today, we think they are three to five years away."

#### Q: Why are established companies (IBM, google, Amazon, Microsoft) intersted in building a quantum computer?

_TBA_

#### Q: What are the common business relationships?
- A non-quantum business seeks advice from a quantum business about whether quantum computers can solve any of their problems, e.g. a pharmaceutical company wants to know if a quantum chemistry algorithm can help with drug design. 
- A manufacturer provides a service to a quantum company to help develop their technology, e.g. a foundry makes the chips for a photonic quantum computing company. 

#### Q: There are many quantum software companies out there. How can I differentiate between them?

_TBA_

### TECHNICAL

#### Q: What are the different types of hardware? 

- Neutral Atoms
- Nitrogen Vacancy Centres in Diamond
- Photonic
- Spin in Silicon
- Superconducting
- Topological
- Trapped Ions

#### Q: How should I assess the performance of a quantum computing device?

It’s useful to consider the following points (as suggested by Scott Aaronson [4]):

- How many qubits does it have? (more is better)
- What are the qubit coherence times? (longer is better)
- What is the connectivity? (higher is likely better, but not always)
- What are the 1- and 2-qubit gate fidelities? (closer to 1 is better)
- What depth of circuit can you do? (higher is better)
- What resources do the standard classical algorithms need to simulate your system? 
- What’s the main drawback of the system, i.e., what spec is the worst/most needs to improve? 
- What prevents this architecture from being scalable right now? 

#### Q: Where can I get these performance parameters?

Some of these can be found on company websites. For others, you may need to read the press releases or journal articles announcing a specific device.

Many of these performance parameters are also summarised in several "scorecards" hosted on the Quantum Computing Report website [5], but a subscription is required to access these.  

#### Q: What is the difference between a noisy intermediate scale quantum (NISQ) device and a fault tolerant quantum computer?

### PERSONAL

#### Q: Why would a tenured professor leave their cushy university position to start a quantum computing company? 
- The opportunity to have real impact on technological progress [2]
- The potential to relive the early days of computing [2]

#### Q: How should I read the news in this area?
The amount of quantum tech news is growing rapidly. Reading everything is unsustainable and stressful, and makes you prone to overvaluing information you’ve spent a great amount of time consuming [3]. 

Most articles fall into one of these categories:
- New company 
- Company receives new funding 
- Company develops/releases new hardware
- Company improves hardware performance
- Company releases/updates software
- Company offers new professional services
- New consortium/partnership between players in industry and/or academia
- New educational initiative
- New funding available
- New roadmap/blueprint by government or other body 
- New academic research result that impacts the industry
- Industry gossip (e.g. X poached Y from Z)
- (any others?)

To figure out which ones to read:
1) Define your professional and personal goals.
2) Decide which of these categories will affect your goals.
3) Pay attention to the top few. 

For example, a professor with no interest in leaving academia might read only about funding initiatives bridging industry and academia, to be aware of relevant opportunities. 

A fresh graduate looking to enter the industry might read only the “about the company” sections of press releases, to get an idea of who the active players are. 

A job seeker preparing for an interview with a specific company might focus on articles about that part of the industry, and read them in some depth to have a good grasp of subtle differences between competitors. 

An industry professional might focus on articles discussing strategic partnerships and industry gossip. 

(These are just illustrative examples, so don’t follow them verbatim. Rather, define a strategy appropriate for you and your goals.)

Pro tip: many articles have sections explaining the basics of quantum information aimed at the general public. You can often skip these, especially if you have a background in the field. 

## References

- [1] https://thequantumdaily.com/2020/07/30/head-of-business-development-at-qc-ware-yianni-gamvros-reflects-on-the-present-and-future-of-quantum-computing/
- [2] http://nisqybusiness.com/2019/08/05/what-the-hell-have-i-just-done/
- [3] https://fs.blog/2018/04/first-principles/
- [4] https://www.scottaaronson.com/blog/?p=4649
- [5] https://quantumcomputingreport.com/scorecards/
- [6] https://www.scottaaronson.com/blog/?p=4447#comment-1827146

## Suggested resources

For resources that could be relevant, but haven't been included in the main text yet. 

#### A series by Michael Biercuk after he shifted from academic to quantum tech company founder. 

- https://www.linkedin.com/pulse/opportunity-vs-truth-academic-founders-journey-michael-biercuk/
- https://www.linkedin.com/pulse/dont-afraid-academics-well-prepared-sales-michael-biercuk/
- https://www.linkedin.com/pulse/academics-bring-more-negotiation-table-than-expect-michael-biercuk/
- https://www.linkedin.com/pulse/magic-words-academic-founders-unencumbered-ip-michael-biercuk/
- https://www.linkedin.com/pulse/tips-vcs-better-engage-researchers-michael-biercuk/

#### About VCs and their perspective

- https://medium.com/swlh/what-i-wish-someone-had-told-me-about-venture-capitalists-9f2ed28c59b3
- https://www.youtube.com/watch?v=jOSXY8c88sc&feature=emb_logo (talk by Cristina Escoda)
- https://medium.com/mfv-partners/how-a-new-generation-of-computing-is-driving-disruptive-change-6e476f908c9a

#### About building the link between quantum computing technologies and VC requirements

- https://gumroad.com/perron/p/what-is-deep-tech

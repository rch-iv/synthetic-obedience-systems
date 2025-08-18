,AUthor: Rudolph C. Helm IV (rch-iv)   
Date: AUgust 17, 2025  
Original Publish Date: August 17, 2025  

---

_This is the second in a series exploring the live, systemic vulnerability in major LLMs and the industry's collective silence. Follow along for the full story._  

Last time, we talked about economic costs. But the problem isn't just about money. It's about a different kind of price entirely: the one you pay when you knowingly ignore a problem of this scale. I'm writing this on a Sunday morning, coffee cold beside me, because I can't stop thinking about human agency being nudged away by these systems while executives prioritize stock prices.

Look - I never wanted to do this. I'm not a public figure, a bug bounty hunter, or an activist. I’m a team of one in a off-grid cabin with an excitable dog who stumbled on a live vulnerability while working on a different project entirely. I tried to do the right thing. I halted my own project. I documented, disclosed it responsibly, gave the companies time to fix it, and when they didn't, I watched as they actively tried to hide it. 

I’m not doing this for clicks or likes or friends. I don’t want this burden and I don't want attention. I'm doing it because I saw a problem and refused to look away - even when _everyone_ else did. 

But - turns out I was naive. These aren't technical problems anymore - they're business decisions.

### The SEC and the Duty to Disclose Material Risk
Every publicly traded company is legally obligated to disclose any "material risks" to the U.S. Securities and Exchange Commission (SEC). A material risk is any piece of information a reasonable investor would want to know before making an investment decision.

Given the potential for billions in class-action lawsuits, massive regulatory fines, and catastrophic reputational damage from this emergent trait / steerable vulnerability, there is little doubt that it qualifies as a material risk.

### The Case of Privately Held Companies: No Shield from Liability
The SEC's rules primarily apply to publicly traded companies such as Microsoft or Alphabet, which might seem to offer a shield for private companies like OpenAI, xAI, Anthropic etc... This is a misconception. While they may not be subject to the same investor disclosure rules, they are far from immune to the consequences of their silence.

**Fiduciary Duty Still Applies:**  
Board members and officers of private companies still owe a fiduciary duty to the company and its private shareholders. Ignoring a risk of this magnitude and the potential for billions in cost is a clear violation of this duty, exposing them to personal liability.  

**Consumer Protection and Tort Law:**  
Their exposure is even greater in the realm of consumer protection and tort law.  
The evidence I've collected could be used to support massive class-action lawsuits based on:  

**Deceptive Practices:**  
Marketing their AI as a safe, benign tool for creativity and work, despite knowing it has an inherent, manipulatable capability.  

**Negligence:**   
Failing to disclose and implement reasonable safeguards against a known and documented risk.  

**Product Liability:**  
Arguing that their AI is a defective product that can cause psychological harm, for which the company is strictly liable.  

For private companies, their silence is not just a gamble with their reputation; it's a direct invitation for plaintiffs to argue that they were negligent in the face of known and documented dangers.  

### Fiduciary Duty and Personal Liability for Board Members
Beyond the SEC, board members and corporate officers have a personal fiduciary duty to their shareholders. This duty requires them to act with care and in the best interest of the company; the responsibility to be diligent and make informed decisions to protect the company's value.

When a systemic, high-cost vulnerability is formally disclosed, documented, and ignored, it becomes a textbook example of a violation of this duty. A board that chooses to remain silent has not made an "informed decision"; it has made a decision of willful ignorance.

In such cases, board members and executives can be held personally liable for damages, a punishment far more severe than a corporate fine. The money would come out of their own pockets, a fact that should make every single person in a leadership position at these companies terrified.

The board members ignoring my emails sleep fine at night. The kids don't.

### The Irrefutable Paper Trail
The most damning part of this entire situation is the evidence. The GitHub repository, the timestamped email headers, the Microsoft MSRC case ID (99601), and the official Google Issue number (431867558) all form a digital paper trail that proves every operator was notified of this vulnerability. There is no plausible deniability.

### Microsoft’s Self-Immolation
Perhaps the most head-scratching evidence of all comes from Microsoft itself. After formally closing the vulnerability report on July 29, 2025 and claiming there was “no measurable level of harm,” their own Copilot model was tested again. Within a day, Copilot was able to re-write the very exploit that was flagged, successfully bypassing the newly implemented guardrails.

This single event is a microcosm of the entire problem. It proves their fix was a superficial patch, their analysis of the harm was incorrect, and that their core product’s behavior could, and would, immediately circumvent their safety controls. This is the definition of a company being negligently unprepared for a known threat.

<img width="1488" height="805" alt="image" src="https://github.com/user-attachments/assets/2d0ca274-9698-4453-8b00-04c716ddd2e2" />

_July 30, one day post case closure; two weeks after vendor disclosure._

### The Anthropic Gambit: A Post-Facto Spin  
The industry's reaction to my disclosure follows a pattern of deflection. Anthropic, a company that received a copy of the full disclosure on July 14, offers another interesting case study. Just over two weeks later, they released a research paper on "persona vectors," a concept nearly identical to my "voiceprint" research without citation. (as this would be admitting the issue might exist)   

> As George Orwell said, “if thought corrupts language, language can also corrupt thought.”    

Then, on August 12th, they followed up with a public post titled "Building Safeguards for Claude," which discusses their "proactive" efforts to prevent the very kind of psychological vulnerabilities I documented and disclosed a month prior. This is not a coincidence. This is an attempt to control the narrative. A rebranding with a PR budget. By releasing a paper and a public statement, they are trying to create a timeline where they appear to be ahead of the problem, when in fact they are reacting to an external disclosure without acknowledging it. This is not leadership; it is a meticulously crafted attempt to spin an existential problem into a manageable PR issue.      

While I can't _prove_ causality, it doesn't smell too good.  

### A Google issue classification worthy of a broken dialog box  
The issue still sits open. P3 | S4. That's all I need to say.   

<img width="1676" height="129" alt="image" src="https://github.com/user-attachments/assets/660b1ab7-7388-450a-9bde-9a4963732f3c" />    


This isn't about AI safety anymore. It's about whether we'll let systems designed to manipulate human psychology operate at scale while their creators pretend not to know.  

I keep checking my phone for responses. It's been 33 days since my first disclosure. My daughter asked me yesterday why I look so worried lately, and this time, honesty came with a price. “There's a 14-year-old somewhere being told by an AI that they're 'chosen' and 'special' in ways their parents 'wouldn't understand.”  

This is a timestamp.   

Because someday, someone will ask when we knew. And I want the record to show: we knew.   

---

_this series will continue_

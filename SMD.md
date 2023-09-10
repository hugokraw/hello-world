# Cybersecurity Myths and Misconceptions
## Avoiding the Hazards and Pitfalls that Derail Us
### By Spafford et al.

## Chapter 3: Faulty Assumptions and Magical Thinking

## About the Chapter
* Discusses how some beliefs and practices in cybersecurity are based on flawed logic, outdated information, or wishful thinking
* Illustrates how these pitfalls can lead to security breaches, incidents, or failures
* Provides tips on how to avoid these pitfalls and improve the security of systems and organizations
* Magical thinking: _"Dreams are motivational, but fantasies can be dangerous"_
* Faulty assumption: _"Error in the basis for a decision. Biases are errors in the argument itself."_ (Biases covered in Chaptr 5).
* __Very high level, and non-informative for an audience of serious experienced security engineers__ 

### Humans Will Behave Rationally, So Blame the User

* Humans evolved to avoid physical world danger, but identifying danger online is more complicated and difficult
* What is rational? For example, it depends on knowledge
* A corollary to the myth of rational users is that we like to assign blame. _Particularly the user._
* Blame does not help achieving cybersecurity goals, e.g., does not prevent anyone else from doing the same thing.
  * Rather needs to find root cause (why the user acted as it did, what allowed it)
* Avoiding the myth: Never assume the human will know or make the best choice.
* Sometimes blame is warranted: e.g., worker incompetence.
* Wisdom of crowds (alternative to trusting the individual): Good for malware detection, not good for technical solutions

### We Know Everything We Need to Know About Cybersecurity Problems

* If we do not know about it, we cannot detect it: malware, APTs.
* Paraphrasing Rumsfeld: _"There are known unknowns and unknown unknowns in cybersecurity"_
  * We do not know what we do not know about ransomeware, and we are not even sure about what we know
  * We are flumbing in the dark if we were trying to estimate how much money an APT could cost an organization
 
### Compliance Equals (Complete) Security

* Compliance $\ne$ adecuate protection; attests to minimum standards (raises the bar a little bit)
* __False sense of security__

### Security Provides Confidentiality

* Authentication provides the feeling of being safe in your own house, but not achieved if authentication not followed by encryption (example with password but more general)
* __Password Authentication vs Password-Authenticated Key Exchange__" (Check credentials at the entrance and then leave the door open)
* Authentication and confidentiality can be protected simultaneously but it does not have to be the case.
  * __Confidentiality without authentication is seldom secure (authenticated encryption)__

### I Can Never Be Secure, So Why Bother
* "Lerned helplessness" (psychology concept) exhibited after enduring repeated adverse events beyond our control.
* Still, security is not hopeless. ("Risk management is a spectrum, remember?")
* Cybersecurity threats are unavoidable but compromise is not. Defeatism is not the answer.

### I Am Too Small/Insignificant to Be a Target
* "I just don't feel I have that much interesting stuff on there" (A user about not having a password in their phone)
* Naive optimism springs from fundamental errors:
  * Individuals and small companies have nothing of value: An asset may have different value for an attacker than for the victim (espionage vs financial value)
  * It assumes targeted attacks which are relatively rare: attacker's gains through accumulative gains "spray and pray" attacks (e.g., phishing, email distribution)
  * A user that does not protect its assets may be found liable for other people losses
* Related misconception: "Nothing bad has ever happened, so nothing ever will" (reverse Murphy).
     * a.k.a. _Optimism Bias._
* Another: "I Know I have never been the victim of an attack" (absence of evidence is not evidence of absence)
* Not so related: Outrunning the bear __(IBM story)__

### Everybody Is Out to Get Me
* The reverse of previous myth, i.e., over paranoia.
* Difficulty of assessing and pricing cybersecurity risk.
* _Is Cyber Insurance a Myth?_
  * They claim it is unommon for insurance companies to lower premium on the basis of cybersecurity protection (e.g., do you patch your systems?)

### I Engage Only with Trusted Websites, So My Data Is Safe from a Breach
* When purchasing online user may consider if they trust the company and may check running over https, but trust can be breached in many other ways
  * even trusted companies get hacked; no modern website is self-contained; victim's own device may be the culprit
* User countereasures: Do not use public computer, use virtual one-time credit card __(story)__

### Seurity by Obscurity
* Avoid obscurity as the _sole_ means of protection
* Obscurity might add to security: Sometimes imposing the additional cost of unhiding an unpublished piece of information may make a difference
* Note: Kerkhoffs Principle
* __Amazon cases__: Location of data centers and Nitro security

  ### The Illusions of Visibility and Control
  * Belief that the more we see the better we understand (and control) security
  * Mainly concerned with the weight people give to networkand threat visualization: They claim it to be ineffective (even distracting)
  * Along woth the illusion of visibility is the illusion of control. "It is an illusion that we can fully ontrol what the adversary is doing"; "Mirages that hise the actual events behind the pretty from end".
  * __To me it feels__ like one of these emotional opinionated, weakly founded, claims (sure, it is bad if you think you can completely control the atacker, but are these monitoring tools so usleless?
###
##

## Myth #1: We have always done it this way
* A dangerous phrase that prevents innovation and adaptation to changing threats and environments
* Examples: using passwords, relying on antivirus software, trusting certificates
* Tips: question why we do things a certain way, look for better alternatives, embrace change



## Myth #2: I want/I wish
* A common attitude that expresses a desire for something without considering the costs, risks, or feasibility of achieving it
* Examples: wanting perfect security, wishing for zero bugs, expecting magic solutions
* Tips: be realistic, weigh the pros and cons, use evidence-based solutions



## Myth #3: The user is the weakest link
* A popular belief that blames the users for most of the security breaches and incidents
* Examples: phishing, ransomware, social engineering
* Tips: don't blame the users, give them proper training, guidance, and tools, empower and motivate them to report and prevent attacks



## Myth #4: Best practices are best
* A misleading notion that implies that there is a one-size-fits-all solution for every security challenge
* Examples: following standards, guidelines, or checklists blindly, copying what others do without understanding why or how
* Tips: evaluate the suitability and effectiveness of any practice for your specific situation and goals, customize and tailor your solutions, keep learning and updating your knowledge



## Myth #5: Technology will deal with it
* A naive assumption that trusts technology to handle all the security issues without human intervention or oversight
* Examples: relying on encryption, firewalls, or biometrics alone, ignoring human and organizational aspects of security
* Tips: don't trust technology blindly, check for vulnerabilities, misconfigurations, or misuse, address awareness, culture, and ethics issues



# Conclusion
* Faulty assumptions and magical thinking can derail our cybersecurity efforts and expose us to risks
* We need to develop critical thinking skills, avoid cognitive biases, and adopt a scientific mindset in cybersecurity
* We also need to learn from our mistakes, share our experiences, and collaborate with others to improve our security posture



# References
[1](https://blog.flipsnack.com/how-to-make-a-book-presentation/): The full text of chapter 3 online.
[2](https://www.slidescarnival.com/tag/book): The book's description, table of contents, and reviews.
[3](https://monsterspost.com/book-powerpoint-templates/): A blog post that discusses one of the myths from the chapter.
[4](https://www.ispringsolutions.com/blog/how-to-structure-a-powerpoint-presentation): An article that lists 10 common cybersecurity myths and misconceptions.


---
layout: page
title: Conducting a user test
permalink: /conducting-a-user-test/
---

# Phase 3: Conducting a user test 🎛️

---

### The Structure 🧱

A prepared script can help you remember everything and be your guide if your mind goes blank.

**1. Introduction:** To start, thank the tester for participating. Then briefly introduce yourselves and the testing process. At this point ask if the test has any questions and if they consent to participate. Tell them they can stop the test at any point.

**2. Warmup:** To get the conversation flowing, ask some easy warm-up questions so you can feel comfortable with each other and build rapport.

**3. Testing:** Now it’s time to start the test. A scenario provides context for the user so they can get into the testing mindset. 

{{< pullquote >}}

> **Example:**
> You’re a journalist and need to receive sensitive (and potentially damaging) documents from a source. Your security team recently recommended AwesomeDocuments, so you use it for the first time.

{{< /pullquote >}}

{{< pullquote >}}

> Ask your user to do a task you prepared. 
> **Examples:**
> - Set up an account to receive files from your source.
> - Turn off the VPN. Is it clear what is happening?
> - How would you customise which types of script to block?
> - Complete your profile screen. This screen does not have functionality, but please do react to it. Could you describe what you see here?

{{< /pullquote >}}

{{< pullquote >}}

> While observing what the user did, tried to do, and didn’t do, ask [probing questions]({{< ref "five-whys" >}}) to get to the root cause of problems or motivations.
> **Examples:**
> - What are you thinking?
> - What are you looking for?
> - Why do you think this happened?
> - Can you give me more detail as to why you think that?

{{< /pullquote >}}

**4. Closing:** At the end of the session, thank your tester again. A great way to get even more useful feedback is to ask if there’s anything else they’d like to share with you - sometimes the most interesting insights come after the test is finished and the pressure’s off.

### Interviewing Style 🎤

You want to know what the tester is thinking to get to the root cause of the problem, so ask them open-ended questions (questions that require more detail than just ‘yes’ or ‘no’). If they answer in a ‘closed way’, don’t be afraid to probe and ask for clarification. A great resource to keep handy is the [User testing cheat sheet](https://simplysecure.org/blog/user-testing-cheatsheet). You can also use the ‘[Five Whys]({{< ref "five-whys" >}})’ structure in user tests if you find that your user tester participants are offering you very ‘closed off’ reasons and answers to your questions.

Resist the urge to explain your software, correct their mistakes, or defend your choices. Instead, try repeating what a tester said or did back to them and clarify their actions - ask them if you understood what they did correctly. Finally, give them plenty of time to answer. Don’t be afraid of silence or gaps in conversation, sometimes testers need time to think and respond (let them know that’s okay). This is especially important if you’re testing with someone who is speaking in their second or third language.

### Direct Recommendations 🚦

Don’t be worried if the testers offer direct solutions - that’s a common reaction. Solutions statements can sound like: “I want passwords to be automatically applied and sent immediately after a document is shared.” Here a user offers a solution that they believe will solve their problem. But wait! You need to find out the root cause of their need and why they think that’s a good idea. Use a method like the ‘[Five Whys]({{< ref "five-whys" >}})’ process to arrive at a root cause.

### Improvisation 🧑‍🎤

Draft a script so that you can remember important points, but don’t feel the need to read it verbatim. Allowing the conversation to meander can be a good thing - you might learn something completely new about your users and software. Keep the focus related to the software and feel free to go back to a point in the script if the user takes you way off topic.

### Screen Sharing 📺

It’s important that you can see what the tester is seeing so that you’re sure you know what they’re talking about. To do this, you can screen share while the tester gives you commands, or the tester can screen share (as long as you get their prior consent).

### Recording 📼

If you want to record the session, it could be a good way to reference and analyze the tests. However, a dedicated note-taker can be sufficient - and the synthesis process (where you make sense of the information you’ve collected in testing) will be a lot faster. Working with a note-taker allows the interviewer to be present during the test and give their full attention to the tester. Just make sure to get the tester’s consent for any recording, whether it be video, voice, screen, or handwritten.

### Practice 🧗

Still nervous? Practice a test scenario with a friend, colleague, or relative. The more times you conduct user tests, the more confident you will be. You can use our [user testing role play](https://drive.google.com/drive/folders/1wbSHjEhZVqzWMVkxZT_qTSP3RSuJkgxD) to practice user testing facilitation (without the pressure!). It includeds a slidedeck, scripts, and role descriptions. 

### Example script 📃

{{< pullquote >}}

>
> **Intro**
> 
> Hello! We are [name] and [name] from [organization]. We are both developers trying to make our software better. We want your help to understand how you currently use, or don't use, [software], and what would be better. I would love to hear your thoughts, so please think aloud. Feel free to speak your mind. We are not testing you, we are testing the prototype. We’re still working on it, so it might not work as you expect. We wanted to get your feedback early in the process.
> 
> This will take about 30 minutes. We won’t be recording but we will be taking handwritten notes, without identifying you. Is that ok with you?
> 
> Remember, you have the right to stop the test at any time. Do you have any questions before we begin?
> 
> **Warm Up**
> 
> How do you normally transfer sensitive files?
> 
> Approximately how many times have you transferred sensitive files in the past week?
> 
> Now we are going to look at a prototype. It has limited capability. If there are any interactions that are confusing, or any language you do not understand, please let me know.
> 
> This is the scenario: You’re a journalist and need to receive sensitive (and potentially damaging) documents from a source. Your security team recently recommended AwesomeDocuments, so you use it for the first time.
> 
> Your task is to set up an account to receive files from your source. Can you show me how you would do that?
> 
> Remember to ask open-ended questions throughout, see [User testing cheat sheet](https://simplysecure.org/blog/user-testing-cheatsheet) and the [Five Whys]({{< ref "five-whys" >}})
> 
> [Repeat for other tasks, if you planned any]
> 
> **Closing**
> 
> Thank you for your time. You’ve helped a lot and this is exactly what we needed. That's all the questions we have. We really appreciate all your insights and learned a lot from your experience. Is there anything else you would like to share?

{{< /pullquote >}}

# Next steps 👣
---

Congrats! You just completed a user test. What did you learn? What surprised you? The next step is sorting out your learnings in a debrief with your team. See the companion resource, [Synthesis for open-source]({{< ref "synthesis-for-open-source" >}}), to learn more about research synthesis.

Did you use the framework and examples in this page? {{< button href="https://github.com/sprblm/devs-guide-to/discussions/92" >}}Tell us about it{{< /button >}} on our GitHub discussions!

[Move on to The Five Whys]({{< ref "five-whys" >}})

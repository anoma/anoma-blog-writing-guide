# anoma-blog-writing-guide.github.io

Welcome to the _C[omprehensive guide to writing blogposts](anoma.github.io/anoma-blog-writing-guide.github.io)_ for the anoma blog. 

# Table of Contents (TOC)
* [Table of Contents (TOC)](#Table-of-contents-(TOC))  
  * [Acknowledgements and Feedback](#Acknowledgements-and-Feedback)
* [The comprehensive guide to writing blogposts](#The-comprehensive-guide-to-writing-blogposts)
    * [Introduction](#Introduction)
    * [What are blogposts?](#What-are-blogposts?) 
      * [Types of Blogposts](#Types-of-Blogposts)
      * [Difference between a blogpost and formal communication](#Difference-between-a-blogpost-and-formal-communication)
    * [Methods and techniques for writing blogposts](#Methods-and-techniques-for-writing-blogposts) 
      * [Steps to success](#Steps-to-success)
    * [Best Practices for well written blogposts](#Best-Practices-for-well-written-blogposts)
      * [Navigating the Process](#Navigating-the-Process)
    * [Publish effective blogposts](#Publish-effective-blogposts)
    * [References](#References)
    * [Future Improvements](#Future-Improvements)

## Acknowledgements and Feedback

Thank you to @graphomath for early feedback, discussion and review. Thank you to @cwgoes for discussion. 

To all please provide reveiw and or [feedback](https://research.anoma.net/t/the-comprehensive-guide-to-writing-blogposts/471). Once feedback is collected, adjustments will be made. See Future improvements below.

# The comprehensive guide to writing blogposts
Blogposts are important for communicating research ideas to different sets of target audiences. In this article, you'll learn how to write an effective blogpost and help your reader get the most out of their experience. **Blogposts help us communicate research**. They provide an opportunity to share our work in a legible yet digestible format for the community of academics, researchers, builders, engineers, hobbyists, etc. that are interested in our ideas. 

## Introduction

Our guide decomposes into three sections. In section one we ask *what are blogposts*? We answer the question, then discuss types of blogposts and some differences between blogposts and formal communication.  Next, in section two we review methods and techniques for writing an effective blogpost. We enumerate the steps to success, taking the reader from idea to published blogpost. Thereafter, in section three we discuss additional best practices for writing a blogpost, navigating the process of writing, and dealing with writer's block. 

## What are blogposts? 

According to Wikipedia, a blog is an informational website consisting of discrete, often informal diary-style text entries (posts). Posts are typically displayed in reverse chronological order so that the most recent post appears first, at the top of the web page. 

How often have you read a paper or report and forgotten about the nuances or key insights? Blogposts provide readers a "short-cut" or API to access an idea that otherwise requires more time and effort to conceptually decipher. Simply the act of writing blogposts is also beneficial to the author, as it forces them to articulate a particular concept in a clear and concise fashion. 

In the cryptocurrency industry blogposts are primarily used for breaking down technical or abstract concepts into a legible format that retains rigor but makes the content accessible for a target audience. Examples of blogposts authored by stakeholders in the cryptocurrency research community;

- [Anoma Blog](https://anoma.net/blog) 
- [Flashbots Blog](https://writings.flashbots.net)
- [Frontier Research](https://Frontier.tech)   

### Types of Blogposts

There are three common types of blogposts. Indeed, there maybe more types than what is presented below. Although, these types in particular are the most common.

- **Summary of an Anoma Research Topic (ART) report**
	- [Privacy in Tents: an overview of private solving strategies]() 
 - **Research directly related to Anoma**  
	- [Typhon's Chimera Chains](https://anoma.net/blog/chimera-chains)
	- [A brief introduction to Anoma's P2P layer](https://anoma.net/blog/anomas-p2p-layer)
	- [Zexe vs. VeriZexe vs. Taiga](https://anoma.net/blog/zexe-vs-verizexe-vs-taiga)
- **Community-oriented, relational to Anoma**
	- [Logic Programming with Differential Equations](https://anoma.net/blog/logic-programming-with-differential-equations)
	- [The 1996 Nobel Prize, the Second Price Auction, and Elixer](https://anoma.net/blog/tags/distributed-systems)
	- [Towards an intent-centric topology](https://anoma.net/blog/tags/distributed-systems) 

Blogposts should all in one form or another relate to research you do for Anoma. This means that each article requires either a short blurb in the introduction or explicit thematic references throughout the post. For the first two types the allusion to Anoma will either be in the title or a major theme of the article. For Community-oriented posts the allusion should be placed early on in the article to provide the appropriate context for  the "Anoma blog reader".  For example here is an excerpt taken from Anthony Hart's masterful article *Logic Programming with Differential Equations*;

> You may wonder how this post relates to Anoma. I mentioned this method near the end of my [survey on constraint satisfaction](https://zenodo.org/records/10019113?ref=blog.anoma.net). This is a general and heavily parallelizable method for incomplete constraint satisfaction, which Anoma is interested in for applications to distributed intent solving. In the survey, I give further pointers to related material, explain formulations of intent solving, and explain how to generalize to approximate solving domains, such as MaxCSP.

Here is another example from Tobias Heindel's excellent blogpost *The 1996 Nobel Prize, the Second Price Auction, and Elixer*;

> The second price auction—the most down to earth aspect of [Vickrey's Nobel prize](https://www.nobelprize.org/prizes/economic-sciences/1996/summary/?ref=blog.anoma.net)—is a splendid example for a protocol that one can easily implement in Elixir. If all you care about is Anoma, note the following:
>
> >1. Anoma is a protocol.
> >2. Anoma is being implemented in Elixir.
> >3. Auctions are one typical application of Anoma.
>
> So, the main topic is actually protocols. However, they are pretty complex in general. Hence we consider the second price auctions as an illustrative example and provide a hands on implementation in Elixir that you can experiment with.

### Difference between a blogpost and formal communication

Blogposts need not be formal. They can use both colloquial and formal language. Though it is acceptable to use *only* colloquial language. For example in Christopher Goes' article *Towards an intent-centric topology* he highlights both a colloquial and mathematical definition of intents. 

> Intents can be understood colloquially as _commitments to user preferences over the state space_ and mathematically as _atomic information flow constraints_.

The goal of the blogpost is to connect with your target audience first and foremost. If your target audience is academic for example, you may choose to include LaTex or code blocks to support your argument and speak to this reader. For example, here is a function written in LaTex from *Logic Programming with Differential Equations*

$$
V(x) = x^2 (x - 1)^2
$$


On the other hand, if the post is targeted at "the Ethereum research community" you may also include relevant memes and or diagrams to convey your message, for example from the *Towards an intent-centric topology*;

![image](https://github.com/anoma/anoma-blog-writing-guide.github.io/assets/116141134/bd0f7562-6e75-47db-a7f9-0f304a8a7e33)


## Methods and techniques for writing blogposts

There are several techniques for writing effective blogposts. Each author may have slightly different approaches. In general, there are common themes that all good methods or techniques share. Let's discuss the steps to success. 

### Steps to success

1. **Clearly choose a topic to write about.** 
	- This may sound trivial, but it is probably the most important part of the writing process. 
	- If you do not have a specific topic, the reader will not understand your intent.
	- Commit to writing the blogpost by assigning an issue on the promise graph with a customer and performer. 

2. **Create an outline**. This can be thought of as your table of contents (TOC), which is a list found on a page before the start of a written work, of its chapter or section titles or brief descriptions with their commencing page numbers. 
	- The outline informs how you will write about the chosen topic. 
	- If you do not have an outline, it will make the process more difficult and perhaps send you back to step 1. 

3. **Write your first draft.** There are three components to note here 
	- Take good notes. If you have notes on the topic you are writing on, you can begin. If you need to get up to speed, it starts with the note-taking process while researching the appropriate reference materials
	- Try to work section by section through your outline. The process will uncover if the outline is correct and also what additional information you'd like to discuss that perhaps you overlooked. Each section should have a start middle and end, almost like a mini-blogpost within a blogpost. For shorter summary type of blogposts there may not be enough depth for subsections
	- Read the post top to bottom. Check for cohesion, syntax, and spelling errors. Include diagrams and links to references in the draft, as it will help the reviewer of your draft provide helpful feedback.

4. **Seek peer feedback.** Once you are ready, submit a draft to your *customer* for review, as well as colleagues and other friends. 
	- Typically it is helpful to have members of your target audience both internal and external review the post prior to publication. The research forums are also a great place to seek feedback on posts while the ideas are still cooking. 
	- When seeking feedback be explicit in what you want; e.g., scrutiny over a particular section, check for logical consistency, or general feedback. It helps to be explicit! 

5. **Make changes and prepare the blogpost for publication**. 
	- Incorporate feedback from reviewers - can always ask for another check after feedback is adressed. 
	- Add any final art or diagrams. All blogposts should have cover art which is descriptive of the blog. Art can be generated with various AI assistants like DALLE 3 or Mid-Journey. 
	- Link and call out any explicit references to other work that is cited in the blogpost.
	- Reread the post again to check that the intended message is apparent. 
	
6. **Submit the draft for publication**.
	- Upload the blogpost draft to anoma.ghost.io and ask for review from the customer on the promise graph. 
	- Work with apriori on scheduling publication and distribution, including producing a [twitter thread](https://x.com/apriori0x/status/1723077194518585525)
7. **Publish blogpost.** 
	- Distribute to friends and colleagues via social channels like Telegram, Farcaster, or Twitter.
	- Publish the blog from the Anoma.ghost interface - review in preview format first to ensure that any images, LaTex, or diagrams render appropriately. 
	- Congratulate yourself on a job well done!


## Best Practices for well written blogposts

- The **title** of your post should aim to tell the reader what the blogpost is about. For example, a blogpost titled *An introduction to intents and intent-centric architectures* tells the reader exactly what the article will cover. 

- The blogpost should have an **architectural style**, a set of characteristics and features that make a structure notable or identifiable; (i) Long paragraphs, (ii) use of bullet points and or numbering, (iii) clear breaks / transitions, (iv) narration ("I", "We"), and (v) introduce - explain - conclude cadence. 

- **Repeat yourself**. In the introduction, say what you are going to talk about in the blog. In the heart of the blog, make sure to say the things you promised. In the conclusion, reference what you introduced and talked about. 

- **Know your audience**. Who is the audience going to be reading your blog? This can change for each blog that you write, so you may want to consider this before beginning. 

- **Structure your blog**. Having a well-defined outline from the start is the best way to accomplish providing a solid structure. 

- **Use visuals and examples**. Some people learn visually. Visuals can help reinforce the arguments presented in text. "A picture can tell a thousand words..."

- **Be clear and concise**. Do not waste words for the sake of it. Every sentence should be precisely the correct length. Language and terms should be chosen carefully to convey the message clearly.

- **Add Personality.** Make the writing authentic. See architectural style for ideas. 

- The **conclusion** of the blogpost needs to link back to the introduction and the sections or parts of the blog. Often readers go directly to the conclusion first. 

### Navigating the Process

- **Manage the scope of your article**. Avoid scope-creep at all costs as it will slow you down. The world cannot be explained in one blogpost, do not try. The most effective blogposts often have a specific focus with rich density of information / insights that teach the reader something they didn't know. 

- **Create an Outline**. This was mentioned in the prior section, but it bears repeating. An outline will keep your writing focused and to the point. If you find yourself deviating from the outline, then you may want to reconsider your scope. Discuss any renegotiation with your customer. 

- **Plan effectively.** It's necessary to understand how long it will take to write the post you have chosen. If it requires additional research, this should be agreed upon and estimated before making a promise to your customer. 

- **Allocate the necessary time**. If you estimate it will take 40 hrs of work until your first draft's completion, it's important that you allocate your time. If you don't and choose to work on other tasks that take precedence, you will rush and be stressed about completing your work in a compressed amount of time. 

- **Explain your writing to a friend.** Often in casual conversation, if you attempt to explain your writing to friends, you'll encounter inconsistencies in your argument and or holes in your thinking. 

- **Be humble**. Many blogposts never see the light of day. It's okay to work on a blogpost and receive critical feedback. The feedback will help you grow and get better as a writer. While writing can be a highly personal process, feedback is not - it's specific to how your writing can be improved to achieve the level it needs for publication and distribution. 
### Getting unstuck: overcoming writer's block

Unfortunately, when writing a blogpost sometimes the author "gets stuck", meaning they struggle to progress. This is also known as a mild form of Writer's block - a condition in which an author is either unable to produce new work or experiences a creative slowdown. Writer's block has various degrees of severity, from difficulty in coming up with original ideas to being unable to produce work for years. The best way to overcome this is; 

- **Write a little bit every day.** This helps you stay consistent and not get discouraged. 
- **Leverage your creativity**. When you are in a good writing flow, extend it. At times, you may find that you can accomplish a good deal with consistent focus over a four to eight-hour window.
- **Ask for help**. If you get stuck, talk to a friend or colleague who has the relevant knowledge to help. 

## Publish effective blogposts

In our guide we provided a comprehensive overview of how to write an effective blogpost. First we defined what blogposts are spending time discussing the different types of blogposts. Next we thoroughly examined the steps to success, pipelining from idea to publication. Thereafter, we discussed best practices, navigating the writing process, and how to overcome writer's block. Indeed, I hope this guide is helpful for future blogpost authors who wish to publish on the Anoma blog. 

## References

- [The Ultimate Guide to writing technical blogposts](https://dev.to/blackgirlbytes/the-ultimate-guide-to-writing-technical-blog-posts-5464)
- [How do you write technical blogs](https://www.linkedin.com/advice/1/how-do-you-write-technical-blogs-attract-retain) 
- [How to write a great technical blogpost](https://www.freecodecamp.org/news/how-to-write-a-great-technical-blog-post-414c414b67f6/) 
- [Write technical blogposts](https://sendgrid.com/en-us/blog/write-technical-blog-posts) 
- [How to write your first successful technical blogpost](https://medium.com/quark-works/tips-on-how-to-write-your-first-successful-technical-blog-4cb65e5b4ce4) 

## Future improvements

- This post does not include a decision tree, or explicit checklist, which takes the writer through the blogpost writing process.
- Examples of each step in the process.

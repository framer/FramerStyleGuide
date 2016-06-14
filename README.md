# Framer Style Guide
Use this style guide as a suggestion for your writing, but not a set of hard rules. Our goal for offering this guide is to align all writing efforts for consistency, but not uniformity. Great writing is expressive and we'd never want to limit you. Use the ideas presented here as a foundation.

This is a living document. Framer's brand will naturally evolve over time, and your writing is a major component of that. So when you write about Framer, keep in mind our core goals, audience, voice, and tone. However, do challenge us where we need to grow.

### Writing Principles
1. Write how you speak.
2. Avoid programming jargon when possible.
3. Emphasize an outcome or benefit.
4. Relate to tasks designers already do.
5. Be specific and explicit.
6. Voice and tone are more important than grammar.

### Audience
The most important part of great writing is understanding the reader. At Framer, we have the luxury of writing for designers. When you write for Framer, remember that our audience is professional, highly skilled, and exceptionally creative. However, Framer's designer audience also represents a spectrum of skills and experience levels. As the line between programming and design continues to blur, so does the definition of Framer's audience. The result is that sometimes a programmer will be using Framer and thus will be reading what you are about to write.

However, don't let this distinction distract you. With all writing for Framer, we default to a specific reader archetype: **an established designer who has limited coding ability.**

Some readers will be advanced coders or even have computer science degrees. But write about Framer as if the reader has basic understanding about programming and significant design experience. This way, the more technically challenging aspects of using Framer will be less intimidating to our core audience, and the purpose of using Framer will be abundantly clear: achieving great design.

### Challenges & Goals
The design profession is changing. Coding skill is increasingly becoming a requirement, and designers view this as a significant hurdle. They've read the articles and books about how designers should learn to code, but it's overwhelming. These are people who are already experts in one field, and who now feel they must master an expansive second profession simply to continue working.

At Framer, this is where our opportunity lies. We are in a unique position to advance the design profession and increase a designer's output, while only requiring a small investment to learn simple coding. We're a simple alternative to designing in the browser with HTML and CSS, which requires a designer to possess substantial knowledge before earning even a minimal return.

##### Challenges
1. Learning to code
  - Intimidating
  - Takes a long time to see results
  - Feels disconnected from the creative process
  - Coding interrupts creativity
2. Designs are never built with 100% accuracy
  - Developers don't understand my designs
  - Mockups don't always translate to code perfectly
3. Standard tools only work for limited aspects of design
  - Cannot explore animation in Sketch/Photoshop
  - Creating responsive design is complex
  - Unable to make certain design decisions until I can try out the interface

##### Goals
1. Explore every aspect of design
  - Visual
  - User Experience
  - Animation
  - Creative and new interfaces
2. Nail the implementation faster
  - Lose less detail when designs are translated into code
  - Communicate design ideas more clearly
3. Make functional and beautiful design that we can be proud of!

Our Values at Framer
---
Framer is a new kind of design tool: one that changes how designers can shape digital products. Our users are blurring the traditional distinction between designers and developers. Framer adds exploration and discovery to the design process where it was previously impossible.

**Interaction** - Images and words have long dictated how we communicate ideas. With them, we explain and define how products work. But they're insufficient to describe how products feel. To understand the effect of our ideas, we need to be able to interact with them.

**Creativity** - Framer offers a playground to tinker with interactivity and learn how to code. Learning to code is challenging, but its value is undeniable and obvious. Once grasped, the creative possibilities are limited only by your imagination. However, many designers see code as an obstacle to creativity. Framer turns this expectation on its head and empowers creatives to explore ideas in even greater depth.

**Evolution of Design** - The nature of design is always changing, and we see interactive prototyping as the next adaptation. Framer is pushing the profession forward by providing a way to explore more ideas, in greater depth. Designs made using Framer are more effective because the designer has control over every detail and the freedom to explore every idea. We believe this approach is the logical step for digital creativity. Our community of designers around the world and at companies like Dropbox, Google, Apple, Twitter, Facebook and at Berkeley and Carnegie Mellon support this philosophy.

**Tone** - Tone should adapt to context, such as documentation, support, marketing, etc. When writing for Framer, choose your tone to match the reader's specific situation and emotional state. See the Examples section below.

**Voice** - Always be consistent — this doesn't change across any content type. While tone is empathetic and dependent upon the reader, voice is about Framer's brand and values. Refer to the Our Values at Framer section above. Here's a list of adjectives describing Framer's voice:

**Aspirational** but not **Pretentious**  
**Ambitious** but not **Grandiose**  
**Creative** but not **Frivolous**  
**Practical** but not **Stiff**  
**Meticulous** but not **Fussy**  
**Friendly** but not **Funny**  

The Benefits of Using Framer
---
Write about the outcome that is achieved when a designer uses Framer, not just about its features. There are many other prototyping tools available, and discussing the difference in features isn't enough to help users make a decision about which to choose. So, beyond explaining features, demonstrate their value. To do this, you'll rely upon your understanding of designers, their challenges, and their goals. Here are some examples:

| Feature                      | Benefit                                                          |
| :--------------------------- | :--------------------------------------------------------------- |
| Animation                    | Explore design in greater depth                                  |
| Prototype using code         | More control over the interaction                                |
| Import from Sketch/Photoshop | Uses familiar tools, doesn't replace workflow                    |
| Uses CoffeeScript            | Only need basic coding knowledge, unlike prototyping in HTML/CSS |

Using your knowledge about Framer and our audience, your writing should address questions like these:
- As a designer, why would I want to prototype in the first place?
- Why should I choose Framer over other prototyping tools?
- If I am not comfortable writing code, can I use Framer?

Content Types & Examples
---
#### Documentation
While using programming terms is unavoidable, assume basic programming knowledge and avoid advanced concepts if possible. Documentation should explain only Framer's features, and not CoffeeScript, JavaScript, Sketch, Photoshop, etc.

Our documentation is not a programming tutorial, so don't explain programming syntax or methods unless they are unique to Framer. However, do refer the reader to programming tutorials (including our own) where appropriate and when possible. The [CoffeeScript documentation](http://coffeescript.org/#language) is a great resource to suggest.

**Incorrect** - Printing allows you to inspect variables in runtime. It works similarly to console.log, only when using print, the output is shown directly within your prototype. Note that you need to use print() in Javascript (but not in CoffeeScript). We will omit these in the rest of the docs.

**Correct** - Printing allows you to inspect variables in runtime. It works similarly to console.log, but the output is shown directly on top of your prototype in Framer Studio.

#### Marketing
All marketing content should mirror our audience's challenges and suggest ways that Framer can help them find a better solution.

**Incorrect Headline** - Invent, design and experiment with interaction

This headline is vague and disconnected from our audience's challenges. It does not explain how Framer is different from any other prototyping tool, and worse, does not even indicate that Framer is a prototyping tool.

**Correct Headline** - Prototype insightful design with simple-to-learn coding

This new headline addresses the audience's fear of coding while suggesting a benefit: more insightful design. It also presents Framer as a prototyping tool.

**Incorrect Sentence** - Connect pixels to behavior and discover exciting new ways of interaction design.

This sentence is certainly clever, but that cleverness could prevent readers from understanding what Framer does. Further, the outcome is vague: what is a "new way of interaction design"? What about it is exciting?

**Correct Sentence** - Bring your design to life. Try expressive animations and create innovative interactions.

This sentence is more specific and is something designers will get excited about. But notice it doesn't use the word "exciting". Framer is an exciting product, and simply by explaining it clearly, we can show how exciting it is. Or as the saying goes, "Show, don't tell."

#### Educational
Our training and educational content is a place to build rapport with new users. It's our chance to give back to the design community by sharing our expertise. When writing tutorials or courses for Framer, don't be sales-y. Don't try to push people to purchase. Instead, teach them. Find out what designers' challenges are and make the value of Framer obvious by showing off what it can do for them. Educate them without asking anything in return. We know that when people understand Framer, they'll see its value and purchase. However, we don't need to hide the fact that we're a for-profit company, either. Be honest and genuine while delivering great educational content.

**Incorrect** - This tutorial is about basic programming concepts with CoffeeScript (If you enjoy it, support us by purchasing our product, Framer). CoffeeScript is great for new programmers because of the easy syntax. You don't even need to use parentheses in function calls.

This asks the reader to purchase before we've even provided any value or earned their trust. It's also impersonal and uses programming jargon.

**Correct** - In this tutorial, you'll learn basic programming concepts with CoffeeScript. If you are fairly new to coding, I highly recommend that you try CoffeeScript, because you'll gain understanding of important concepts but with easy-to-write code. In fact, we think CoffeeScript is so clear that we built our interactive prototyping tool, Framer, on top of it. Read this tutorial and you'll be prototyping in no time.

This version is much more friendly and relatable. It doesn't hide the fact that the tutorial is written by someone working for Framer, but it doesn't sound like a sales pitch, either.

#### Social Media
Instead of using social media as a press release feed, use it to connect with our users on a more personal level. Social Media is very informal, and while Framer is a company, we are a team of real people and want to encourage authenticity with our users.

**Incorrect Feature Release Tweet** - We just released Framer Studio 1.10 with major editor improvements and many more devices. [http://framerjs.tumblr.com/post/110641414997/editor-and-devices](http://framerjs.tumblr.com/post/110641414997/editor-and-devices) ...

This tweet is impersonal and stuffy. Our audience doesn't care about software versioning or vague "major improvements". They want to know how Framer will help them make great designs.

**Correct Feature Release Tweet** - Now you can prototype iPhone 6+ and Apple Watch apps using Framer. We also improved the code editor to make your workflow easier. [http://framerjs.tumblr.com/post/110641414997/editor-and-devices](http://framerjs.tumblr.com/post/110641414997/editor-and-devices) ...

Instead of talking about Framer (we), the tweet talks about the user (you). Furthermore, it's specific, so the reader can decide if they're interested before clicking the link.

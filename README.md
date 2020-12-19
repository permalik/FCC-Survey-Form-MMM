# FCC-Survey-Form-MMM
Mass Music Measurement Survey-freeCodeCampChallenge

Gaining Speed

This marks my second freeCodeCamp challenge. As I mentioned in my after action report from the first FCC challenge (tribute page), it took some time to finally gain traction and fully complete that project. That was a problem with (one) unnecessary complexity of design and (two) a lack of planning (before I began to code.) It was my assumption that if I laced the project with many working parts, I would learn much, much faster; also, that by getting right to the code, I could pick up the syntax, semantics and general knack for writing (code) in less time. And wow, I was very incorrect in thinking so.

As a response to my previous poor start (with my tribute page,) this time I was better able to address some lessons which had only occurred to me when halfway through the last project. So this time, I really dialed in the importance of streamlining my initial paperwork designs, learning how to more proficiently use Figma and some of its tools, how to better approach icon design with Photoshop and vastly improve my entire workflow. This provided (not only) an easier build, but also a more efficient angle by which I was empowered to catch more lessons along the way.

In the next few paragraphs, I will detail just which specific advantages I picked up in terms of HTML5, CSS3 and JavaScript capability. In addition, I will move through some of the tactics I employed to help me finish this challenge with much more confidence than the last.


Planning Stages

When I set out to hand-write the marked goals (set down by FCC’s challenge,) I do find it tedious. The thing is, I am copying (in my own words) precisely what the challenge is demanding of me. Let me elaborate…

With every line, I am telling myself that I really do not need to do this. I mean, I can pretty easily peer over at the other browser window (when necessary) and see exactly what my marching orders are. Though albeit true, there are a couple of key differences in (one) reading from FCC and (two) writing/reading my own notes.

As I write out every expected step of my project, I can build an image immediately for how I would like my creation to take shape. This falls in line with the visual aspects and design, the color scheme, the functionality of each element and the code itself. It is a powerful method to which I will pay better respect going forward. (I already have plenty of ideas on how to implement more potent procedures — like larger drafting paper, (which will allow for a greater landscape on my pages, maybe using a tablet for notation and perhaps a few voice recordings along the way)). Now, I may be getting ahead of myself! Back to the plans..

And so writing out the objectives is terrific for lots of reasons, but moving to the drawn design itself — this may be the most crucial bit yet. Here’s the deal. When I physically drew the (expected) survey form, I may have well completed the whole project. So what does that mean?

I took so much liberty in imagining what the design should resemble. More specifically, I let my mind wander and allowed thoughts to spill out onto the legal pad before me. This (in combination with my understanding of how everything needed be expressed in code) let me structure my rough draft with such a degree that the next step made the actual coding like an exercise in copy and paste. I’ll expound…

I was drawing parts which were effectively elements of HTML. This was followed by some (more precise) markings of pseudo-code (which amounted to about all of the HTML I required to code for the whole challenge.) So, when I say the planning has proved to be useful, this would be an undestatement. This attention to planning has made it possible for me to avoid the ‘nuts and bolts’ in my code editor. Now, this advancement is massive, because the saved time and effort was a testement to why I was then able to better learn more intricate detail when coding. And now let’s get to those lessons and the code at large.


Within Earshot of Paper and Pencil

My goal is not to elaborate on the use of specific technologies, but more-so the process itself. however, I will briefly touch on Figma and Photoshop…

Using Figma helped me focus on each element and understand how they more literally fit together in the puzzle. I was able to name every piece such that it would show me what my HTML element should be in code and how each need be named. Also, I took those separate entities and grouped them such that I could postion everything exactly as I wished. My next goal with Figma will be to utilize the ‘component’ feature and truly unroll some strong functionality of the software.

Regarding Photoshop, I made a logo for my survey and spun it into a favicon with relative ease. In an attempt to create animations and advertisements for my affiliate site, I have better come to understand Photoshop’s effectiveness. Thereby, building my icon was fairly straightforward. I simply pieced it together with a couple of layers and exported the PNG. I still want to be able to employ SVGs for this application; but until now, I haven’t perfected the craft. I will leave that for the coming FCC challenge. Onward!


Coding the Beast

The first topic to address here is quite obvious for me… SUITE TESTING.

When I began coding this project, I wrote my HTML boilerplate and immediately tied in the FCC testing script so I could begin verifying my code at every turn. I’ll elaborate…

I ran into a few issues with debugging throughout my last project; those were problems which resulted in code errors piling up on me simultaneously. And, while an error (for which you don’t know the remedy) is frustrating…several of those errors (all at once) becomes infuriating. Luckily, I ran into a great solution. Unit testing.

By instantiating the FCC test suite before I began coding the bulk of my project, I was then gifted the opportunity of verifying each of the sixteen goal posts.

In more detail, nearly no problems snuck up on me while coding the breadth of this project because I was adamant on addressing them in real time (as they appeared). What a true life-saver...


Input Text (element, attribute)

I found it repetitive and annoying at first, when the 10th goal of this challenge asked me to give both the input and label elements their own respective and corresponding ids. This was because I (very simply) did not understand the request. Along with that, I definitely didn’t understand why it was being asked (to begin with.) 

That said, I now realize that the goal was to identify the label for the text field, in addition to the field itself. In understanding this distinction, I have now been able to find value in this very feature.

By giving ids to both my labels and input texts, I was then able to style each distinctly and find them with more ease (while peering though my HTML.) Now here’s real solid tip which I will not soon forget.


Don’t Pick More Than One Option!

So, I was writing the code for my radio buttons and what happened next is certainly a rookie mistake. When I navigated to my browser (in order to test the options,) I found that EVERY one of my buttons was clickable. And this, for obvious reasons, is not ideal.

This solution was super easy. All I needed to do was unify (or make each value the same for) the input-radio buttons. After I placed cloned values for each radio button, only one option could then be chosen. Success!

Nitpick the Name and Ids

This is something which should possibly be glossed over. But, when working with various input fields, I was asked to employ many names and ids for each.

While I’m not entirely certain (even now) whether there is a standard for which comes first, I have come to realize that name attributes should possibly supercede id attributes.

Using Visual Studio Code, it seems to like placing names before ids. And in a real life estimation, using name over id seems to be old-fashioned, but admirable.

More seriously, I understand in code, name will be less subjective (while more actionable) and ids will more far more particular and prone to alteration.


Dropdown

I was in a position to use dropdown boxes twice in this project. The problem I came across was that my options continued to begin with the default option as selectable. While I learned the solution quickly and with ease, I believe it should be recorded as vital.

When inserting a placeholder option in a dropdown box, in order to keep it from being a clickable entity, you have to style it as such.

I called the id of the option in my CSS sheet and set its display as none. That easy.


Pseudo Class and Element Selectors

Very little of my experience with this challenge dealt with pseudo class or pseudo element selectors. But, I will cover (in short) what I did learn (with these topics in mind.)

Using a pseudo element selector is the best (or maybe only) way to call an attribute from an HTML element and style with CSS.

This is how I was able to change the appearance of my placeholder text in each input-text.

I know pseudo class selectors are the way to alter elements (in a certain state) like ‘hover’ or ‘before’, but I haven’t used them enough to expand this monologue. That said, I’ll press on…


Attribute Selectors

In confluence with my previous words, I may have provided a misnomer to exactly what was being modified with pseudo-elements. But, I digress (and hopefully you see what I mean).

Using attribute selectors is quite different from other selectors, because you will be placing true brackets in as your selector which house your attribute, followed by an equal sign and a set of quotations (housing your value.)

Looks like this [attribute=“value”]. And that’s that!


Media Queries

While I employed media queries for this project, I have yet to fully grasp exactly how to use them (in reference to appropriation and context.) Therefore, I will not go into detail; but, only mention that I used them to alter my CTA button across pixel-widths. Also, I realized that setting a new media query works better when starting with the immediate values from your last screen size.


A Bit of JavaScript

The big task I pushed for in this project was this: change the client-side font family for a text area as the user types. And by big, I mean, it took me about as long as the rest of the whole challenge to learn this functionality with JavaScript. That said, I now understand much better how JS semantics are employed. And, that’s pretty priceless…

For this goal, I inserted a script with an event listener. First, I started with DOMContentLoaded, which allows for firing without the images or styling need be loaded.

The next bit lets my document be called by its (element) id.

Then, it states that my id will be triggered by any input (via an eventListener) and will force my later instantiated function.

The function declared will let the charCode number equal a string which will be console.log(ed) out as my target.value (of Nunito, sans-serif) with proper style.fontFamily.


Conclusion

Attempting to wrap this project up in a nice bow is difficult, as I have onboarded a great deal of information (from one simple survey page.) After completing this task, I am left with a split-brain. While I have learned so much from something, seemingly straightforward, now I am thrilled to make it to the next project and take on those new expectations.

I suppose my takeaway is that I should fine-tune my HTML and CSS understanding and seriously crack open all that is JavaScript. All which, can wait until tomorrow. Cheers!

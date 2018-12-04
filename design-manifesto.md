---
type: page
title: Design manifesto
---

TLDR; designers need to be constantly mindful of five things:
* ethics (testing and implications of their technology)
* accessibility and equability 
* *we are not the end user*
* tech won’t always fix the problem 
* 

If you’re still reading, I’ve got a story for you. It’s about how I’m apparently incapable of following directions. 

### The first piece of advice I got going into college was “don’t major in sociology.” 
I have since majored in sociology, and am awfully close to a double in philosophy. The ‘hard skills’ section of my resume lists three computer science courses, three economics classes, introductory statistics, and a whole lot of skilled trades abilities. I'm really hoping that Steve Jobs was [right](https://www.washingtonpost.com/news/innovations/wp/2018/06/12/why-liberal-arts-and-the-humanities-are-as-important-as-engineering/?utm_term=.53e0ff2597bd) when he said 
> it's technology married with liberal arts, married with the humanities, that yields us the result that makes our heart sing...

I’ve never thought of myself as designer before. Pre-college, I was a machinist and welder. So craftsman, sure. But a designer? That seemed like a job for people with artistic ability. Turns out, design isn’t just about making pretty infographics or app interfaces. It’s about creating functional and intuitive products that actually improve users lives. It’s about understanding the end user, as well as the potential consequences of implementing a design.  And this is where my humanities degree is useful. 
Part of sociology is ethnography, "the scientific description of the customs of individual peoples and cultures."<sup>1</sup> In other words, become part of a community in order to analyze them, then probably write up a book or article. If that makes you feel icky, then great, we're in the same boat. But when ethnographic principles meet design, a whole world of possibilities open up.

My Human Computer Interaction course (one of those three aforementioned CS classes) involved a group project with [Chris](https://cla1.github.io/) and [Kenneth](https://kennethan12.github.io/).  By combining our three individual proposals we came up with [heART](https://londonmeanswild.github.io/museum-experience/), a mobile application designed to * “make data useful”* for curators. We developed this project alongside UX design/research readings as a way to make the concepts tangible. What I didn’t expect, however, is just how useful my humanities classes would prove to be in navigating, and complicating, the questions we were about to face. 

Our project began with wanting to make database information [more three-dimensional](https://londonmeanswild.github.io/museum-experience/2018/09/28/initial-proj-proposal/). By the end of our semester, we ended up [creating an application](https://youtu.be/wmY6SomfXZg) that would visualize visitor feedback and connect curators with visitors who want to ask questions. 

> Museum databases are flat and one-dimensional. There is no way to quantify the things people feel while looking at, or experiencing, art. This flatness makes it difficult to connect people with artwork based on hard-to-articulate themes (such as feelings)... We have decided to try and use the responses people have to artwork in order to add depth to museum data files. We want to show the “texture and personality” of a collection, and the way exhibits make people feel. 

### Design presupposes ethical considerations.
By that, I don't mean [calculating utility](https://plato.stanford.edu/entries/utilitarianism-history/#IdeUti) or determining the proper [categorical imperatives to determine duty](https://plato.stanford.edu/entries/kant-moral/). I mean... when my group and I sat down to design and application for museum curators, we had an obligation to provide curators with the best product possible, to be transparent about their role in [testing](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/), and to be honest about our project goals. When we performed [contextual inquiries with students and curators](https://londonmeanswild.github.io/museum-experience/2018/10/05/contextual-inquiry-review/), we needed to be upfront about our motivations and understand the value of their time, as well as the responsibility we had to understand their needs and wants rather than looking for ways to cement our pre-existing opinions.  

More importantly, however, we had - and have - a responsibility to people who visit museums, not just curators. For example, each piece in the WCMA database is assigned a category by a curator. There are no ways to search with cross-category variables. Photographs by African artists can be in “Africa” or “photographs,” or even categorized by the photographer’s nationality. Each of these queries will produce a different result.<sup>2</sup> Since the artwork in WCMA's database reflects categorization bias, how could we intervene? How would our data representations help curators create more equitable, responsible, and accesssible exhibits? 

We didn't have solid answers for this. We still don't. Or at least, I don't. But what I do know is that having conversations is the only place to start finding solutions. 

When [starting the contextual inquiry process](https://londonmeanswild.github.io/museum-experience/groundwork/research/2018/10/04/CI-writeups/), we realized that we didn't understand our users, or rtheir issues. Curators weren't concerned with emotional responses, since emotions are subjective. What the curators were interested in, however, was communication. 

> ...one of her [U1] goals was to find pieces that invoke intriguing ideas and unexpected discussion points.

> most of the feedback he [U2] receives is positive, which made him worry that people who are confused or frustrated aren’t expressing this information to him. He even said he wished he could get visitor questions directly sent to his phone so he could answer them (given he had the time), that way it might eliminate some frustration... He said would like to know which galleries people liked the most, that way he could incorporate that feedback in his choices.

In our design process, we decided to emphasize communication and transparency between visitors and curators, since curators expressed a desire to communicate with and understand visitors. I believe that respectful and open communication is the first step to addressing bias, repairing damaged systems, and understanding the very real impact our actions - and interpretations - can have.<sup>3</sup> 

### Users have to be able to access and use products.

It sounds simple. It really does. But it's not nearly as simple as I (and my group) expected. What seemed efficient, logical, and natural to us ended up being useless - at best - to our users. And our website? 
We designed our site around the logo colors, which were picked with little to no fanfare. It's a good thing we're not being graded on web design, because it is quite inaccessible. I still don't think we have added alt text, our text colors are unreadable to anyone with color-blindness, and the organization of headers and text is a nightmare for anyone with reading disabilities. 

Our website aside, [understanding the different way users interacted with our prototype](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/) showed us just how many assumptions we had been making about the ways users navigated our app. And many testers didn't know what to do with our visualiation mock-ups. I was mortified. The last six years of my life have been motivated by the desire to make post-military resources accessible to LGBTQ veterans. If information isn't accessible, it might as well not exist. I've spent time working on accessibility and equitability in tech, and yet had discarded all of that in favor of a design that made sense to me. I still wish we had taken this as an opportunity to do a deep dive on data representation. Our entire project easily could have focused on the way people access and understand information. I regret not speaking up for that approach, because I think that understanding how people interact with data could have made me a better designer, writer, and communicator. 

### We are not users.

Not only did I have to recenter accessibility as a priority, I also had to constantly remember that *I am not the end user.* I had to recenter my focus on the user, whether that was through refering to interviews and contextual inquiries, or bringing specific questions to usability reviews. This process was both new and familiar: in UX, having a user be involved at every stage of the design process is called participatory design. Previously, I had encountered this idea when writing an [ethnography on female queerness in Kuwait, last spring](https://londonmeanswild.github.io/research/2018/03/16/Kuwait.html). For the social scientists in the room, participatory design is similar to  Patricia Hill-Collins' Black Feminist Thought.<sup>4</sup>

In UX,  which means having a user be involved at every step of the design process. Our participants were co-researchers and co-designers, not simply testers. The timeframe we were working in proved to create some limitations, however. The design process put parameters around the decisions my team and I made. Once we realized what we were testing for, or the questions to ask, it was time to iterate again. At every step we were pushing forward a half-polished product, guided by feedback that may or may not have been the best to follow. Our contextual inquires were guided by the best questions we knew to ask -- and those evolved with each encounter. Because our time and knowledge was limited, we often found ourselves looking back and saying "man, we should have asked **this one thing** differently, it could have changed everything." And because we had not established long-standing relationships with curators, the curators didn't know us well enough to understand what we were trying to say, nor did we know them well enough to always understand them. We found that thinking out loud was an important tool in continually centering the user experience, needs, and wants. 

I consider this ability to look back and identify opportunities for change to be an extremely valuable takeaway. 

### Sometimes the best solution is low-tech

One of the barriers to our application is that it is a new mobile platform. 




1. [Google Definitions, "ethnography".](https://www.google.com/search?q=ethnography&oq=ethnog&aqs=chrome.0.69i59j69i60l5.897j1j7&sourceid=chrome&ie=UTF-8)
2. [Usability Tester 2, though this particular quote is not in our final write-up](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/)
3. For a conversation of the ethics around representation and classification, feel free to send me an email. Or, until 12/21/2018, swing by WCMA's [The Field is the World](https://wcma.williams.edu/the-field-is-the-world-williams-hawai%CA%BBi-and-material-histories-in-the-making/) exhibit. 
4.  In understanding the experiences of our users, I needed to remember that concrete experiences create meaning for individuals and communities;  it's important to maintain dialogue between co-researchers in order to constantly assess the accuracy of our representations, interpretations, and iterations; community member engagement is key to ensuring each iteration is done with the end user (our co-researcher), in mind; knower adequacy depended on my team's collective perspectives and experiences, as well as our understanding of our privilege as designers. 

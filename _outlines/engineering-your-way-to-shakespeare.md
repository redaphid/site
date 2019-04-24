Or, how you can't do that.

# Look at how successful long-form blogs organize articles beforehand.
* Ask for feedback. Disclaimer that you're not authoritative. Helps me, maybe others.

* Start with a "sting" - why does it matter?
  * This blog is ugly. Good.
    * Brief sting re: blog epic.
  * I like writing - why don't I do it?
  * Clearly, some of this is my tumultuous personality, which I'm trying to correct. But I've seen this cycle repeat in **many** developer friends of mine, so it must be a real thing.
  
  * As an engineer, my "engineering brain muscles" are much more developed.
    * This is likely true for other professions as well - we software devs like to think we're special.
    * Comfortable headspace, with much less fear.    
    * Making something creative is scary, so we avoid it by turning things into engineering problems.
      * It makes us vulnerable in an area that we're not too familiar with.
  * Hopefully this post can be helpful for other engineering-types trying to engineer themselves to Shakespeare.
    * It'll help me, at least. I value creativity very intensely, and constantly have a million ideas unrelated to my field.
  * It's Good For Your Brain (tm) to do things it's not used to.

* Outline of "The Cycle"
  * Grand idea. Ideas are great!
  * Making lists of features, getting everybody excited.
  * Head full of how to make a tool/framework/engineering effort that will make the creative effort easier. 
    * Informed by UNIX tool philosophy
    * Code generators, etc. Ideal tools would make this so much better!
  * Start "researching" other tools that have the features you imagined. But of course they're not good enough!
    * Odds are, the project doesn't need anything close to this!
    * Shades of developer goldplating.
  * Start actually developing the tool
    * Pretend you're just going to make a little thing at first. It won't be **that** much of a distraction.
  * Solve the difficult engineering problems of the new, pure-engineering goal.
    * Since the tool is really only for me, I lose interest or burn out after the hard problems are solved.
  * Burn out, never return to the original creative project.

* Examples
  * Blog
  * Regex
  * Music
    * Ableton
      * Generating instruments instead of songs.
    * Overtone.
  * Space Game
    * Maybe put at the end as an addendum!
    * Make own product
    * AR/VR interest and potential job opportunities.
    * Real physics became an engineering goal.
    * Engineering issues:
      * Porting to ECS vs. closing the loop.
      * "Maneuvers" - Flies to Destination.
    * These engineering goals burnt me out. After successfully solving them, abandoned project.    
    * Once past this hurdle 
  * Writing.
  * Private Blog
  * others....
  
* Use blog as example
  * I made an ugly blog, on purpose. Here's why.
    * It doesn't do nearly everything I wanted it to do.
      * But guess what - it exists.
    * Rendering all the posts on one page may be a problem - but **fuck** it.
  * Talked about doing it for months
  * Thought about it while traveling, keeping the ideas in my head, memorizing them over and over.
  * I have a lot of stories my friends tell me I need to write down.
    * Instead, I spend a lot of time and energy rehearsing, memorizing, making sure I don't forget them.
    * Even then, I eventually forget them for the most part, except the ones I tell a lot
    * Or are emotionally impactful.
  * When I finally forced myself to do it, it devolved into an engineering problem.
  * Ended up, instead, inventing your own blog system - in your head.
    * Fixating on features and memorizing them, rather than the task at hand.
    * Start talking about features, or writing them down.
  * Start researching tools with features like the ones I dreamed up.
  * Rationale: Lawyer's wife stealing his family blog, locking him out, distraught.
  * Wanted to make a solution for this that was loss-resistant
    * No vendor lock-in
    * Readable even without any software
      * Markdown w/YAML metadata
      * Came up with own solution for this before discovering Front Matter.
    * Easily backed up (by default), with version control.
    * Freely hostable.
    * The entire blog initiative devolved into this
      * CircleCI committing back to github, React, etc etc.
      * Once that engineering obstacle was overcome, I stopped without writing a single post.
      * (screenshot of the "old blog", e.g. React hello world).
      * Still was avoiding starting the blog months later - but I like writing!
  * Still think this is a good idea, but the blog project devolved into this.
  * Very practical developer friend (who also suffers from this syndrome) tells me about Jekyll.
    * Pretty much exactly the blogging system I came up with in my head.
    * I spent maybe 10 minutes trying to understand it, without rationalizing that it wouldn't work for me.
    * Halfheartedly tried to set it up on Github
      * It's very easy to set up. I just didn't want to. I **wanted** to make my own thing.
      * Wouldn't do this at all if contracted to do this.
  
  * So, what did I do instead?
    * Focus on Lean Startup-esque principles of delivering.
    * Almost content-free first post.      
    * Moved my totally non-functional blog project to a different repo.
      * May use it as an example to go from CircleCI->Github pages.
    * Actually used Jekyll
    * Setup Linux Subsystem for Windows.
    * Installed ruby, debugged lack of compilation support
    * Got Jekyll running locally.
    * Figured out how to smash all posts into one big file
    * Insisted on using only markdown, transcribed examples.
    * Intentionally make the blog as feature-free as possible
      * Write down the features not implementing in a disorganized thought dump to avoid "idea loss anxiety"
    * Use Jekyll. Actually read the docs. Hello world.
    * Still an engineering project - so arguably procrastinating.
      * But, I mean, it's Jekyll. It satisfies what I was worried about re: plaintext articles, backups, etc.
      * But it made it fun, it was contained, and I learned a lot!
      * Plus, way less time. And look at this - results!
      * Jekyll is so extensible, these imaginary features I'd never implement probably exist in some form or another.
        * But **don't** try to enable them!
    * So basically Lean Startup-y way of doing things.
      * We know this, as developers. But it slips mine and other's mind when in non-engineering enterprises.    
      * Or, more precisely, we rationalize that we're making a mvp of the tool, and so are following Agile principles - just on the wrong thing!
  
  * Conclusion
    * restate muscle thing, thesis.
      * Creative enterprises are fun, but make you more vulnerable.
    * Forcing myself out of that state by introspection made the blog happen!    
    * There's nothing wrong with making tools to do things!
      * But only if that is the stated goal.
    * Record the features - a lot of this was due to an underlying motivation to make the tool, and a concern that I'd forget about all of the ideas I had while being a customer for my imaginary product.
    * Will it continue to work? This blog continuing will be the test.
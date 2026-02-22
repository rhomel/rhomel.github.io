# Surrendering to the march of LLM vibes

As expected, the latest generation of LLM releases continues to improve. I've
now experienced enough to wave the white flag for "traditional" software
development practices.

Rather than turn this into another sob-post, I'll try to first point out what's
different now and why I feel slightly less bothered despite nearly 2 decades of
pre-LLM software engineering experience.

## A Static Site Generator vibed in an afternoon

First this blog is just a bunch of Markdown files on a file system. Instead of
taking the time to read up on how to use existing [static site
generators](https://gohugo.io/getting-started/) I can instead just explain how
I want my ideal static site generator to work to an LLM and have it build one
tailored exactly to my needs.

This was part experiment and part real-work. I always wanted a generator that
was simple to me. While I knew I could write the code myself, I never did.
Probably because I created my own mental blocks that if I didn't do a good
enough job with the code, it would result in:

- an embarrassing show of my actual best software engineering skill
- an unmaintainable mess I would rarely want to return to
- an over-investment in code that most of the world probably will never care about

That's just a round-about way of saying my _pride_ got in the way.

Instead I took the opportunity to try using the [Codex
App](https://openai.com/index/introducing-the-codex-app/) to make this a
reality. There wasn't any particular reason other than wanting to free myself
from the traditional mold of coding tools.

Claude Code did more or less what I imagined a text-based vibe coding tool
should have done almost a year ago. And it works fairly well. Codex CLI is a
similar experience and works nicely if you already have an OpenAI subscription.
But those tools kind of lean too heavy on integrating nicely with existing dev
workflows. If I'm going to try this stuff, let me have a glimpse of what the
future feels like. I have a subscription, so Codex app it was.

And the experience was part future, and part not future. One "future" feeling
part was being one more abstraction away from the code; the code editor is not
part of the experience, instructing what should be built was along with
reviewing the code. That's a small step in the future, but not quite there yet.
What definitely not future (or even present IMO) is the fact that I have to
still sit in front of my computer to give it instructions. With all of the
raving about [OpenClaw aka ClawdBot](https://www.reddit.com/r/clawdbot/)
enabling interactions via WhatsApp I did feel a bit annoyed about the Codex App
experience.

But all of that is for another time. The point I want to make is by letting go
of my specialist pride, and diving into the clearly vibe-leaning tools, I made
a static site generator idea that sat rent-free in my head for longer than I
feel comfortable a reality.

Sure the code is awkward and weird for anyone used to "traditions." But after
this experience _everyone_ should be trying these tools to understand what
changed.

For example way way back in undergrad university we had to take the standard
algorithms and runtime class. The classic sorting algorithms ate a majority of
the time but I liked my professor for two reasons:

1. He clearly made the underhanded joke that for grading "we should imagine
   we're being chased by a hungry lion; we shouldn't try to outrun the lion,
   but instead not be the slowest person in the group."
2. The work on sorting algorithms as for the most part focused on _comparisons_
   being slow. What if _comparisons_ are nearly free and instead memory swaps
   are slow?

Both of those perspectives opened up my mind as a student a bit. We need to
again adopt that mindset and understand what generated code via LLMs changed:

- You don't want to be left-behind to be eaten by the lion, so you must do
  something differently.
- LLMs make generating and modifying code cheap. Our ability to think of what
  should be built is now the bottleneck.

## Code Quality or Quantity?

I blame my dad for my obsession with quality. He used to be able to open the
hood on a new car and from his experience repairing them make a snarky comment
about how crappy it was designed. Or open the wall of a house and either be
disgusted or enamoured with the quality of hidden craftsmanship. But even to
him speed and efficiency was obvious. No matter how ugly the job was he took it
as a challenge to see how quickly he could fix it.

Our industry is no different. It's well known that those who don't deliver get
their lunch eaten. Management doesn't care about tech debt until they feel the
embarrassment themselves. That nicely craft code base is a pipe dream unless
you're in the position of Linus Torvalds.

I feel like the drive to be "agile" is a symptom of this. Agile processes value
movement over nicely crafted designs. The bespoke and beautiful implementation
is always a few iterations away.

So the good news, that's all dead! You don't have to play by those rules
anymore. But now? If your non-techy friend can manage to vibe a solution with
OpenClaw in a weekend then you better be ready to accept that eventually your
company's management is going to demand no less fairly soon.

On the bright side that refactor or bug fix you put off is just a few prompts
away. The LLMs don't complain so you might as well see if you're lucky and get
a few fixes.

And you don't even have to _see_ the code anymore. Ask the LLM what is going on
and just confirm if it is true or not. Saw a large swathe of code that looks
and feels wrong? Ask the LLM to examine it and propose ways to improve. Hell
even have the LLMs try several ideas and pick the one you like.

If you're still not convinced then go to your local furniture stores. Even for
the mid-range priced furniture see how many people are there. Then flip over
that table or couch and try to find the number of corners that were cut. Now go
to IKEA and see how many people are happy just to have a cheap colorful table
made from cardboard. Either way corners were cut. People will pay for what they
need and can afford.

Only if you're willing to find the local woodworker will you find something
built with care and attention to detail. But even they will use whatever tools
or processes for efficiency. Rarely to people hand-plane entire boards anymore
when the machine does it far more efficiently.

Don't get me wrong, I would love to have hand-crafted artwork and pottery if I
was filthy rich. But the reality is most have no choice but to settle for the
mass-produced products because they have no choice.

On the other hand you can still go for the specialist route. But that's like
trying to be a hit artist among millions. It definitely isn't the right play if
you need to pay your bills.

## The Good Parts

I'll admit, I'm definitely struggling to see the positives because all of the
negatives are very obvious:

- Traditional software engineering will be less valued as the ability to
  execute quickly becomes the priority.
- The AI players are eating all computing infrastructure making even personal
  computing more expensive.
- No one but incumbents can compete with data centers and fabs. All resources
  are quickly diverting there.
- Slop is nearly free.

But we do have something big changes in technology:

- Automated personal assistants are becoming reality
- Filling a dumb HTML form for the millionth time should go away
- The latest frontend framework don't matter anymore because people prefer
  natural language and the LLM generates code anyway
- ChatGPT can probably do tech support for your parents
- One day you won't have to "do" your taxes yourself
- The generators of slop are also the filters of slop
 
It's definitely hard to see that last point as a positive. Let me explain. Your
smart coworker says they'll write a nice email for you with all the details.
They put a few lines in their slop generator and send it off. You get this
giant email that will obviously take too much time and is suspiciously feels
generated. So you hit the slop filter button and pull out their original
prompt. People will catch on and start valuing the people that don't waste time
and get shit done. Social pressure will overcome anything when people begin to
realize they're being excluded.

In other words whatever the machine can do will become average because it
becomes common. What people can do (for each other) remains interesting because
most humans still value social language.

Does that mean software engineers (or any other desk job) will have work in the
future? Probably not. But there will definitely be no shortage of hair
dressers and nurses.

+++
date = '2026-04-24'
draft = false
title = 'My thoughts on AI'
description = 'I have opinions. Let me push them down your throat.'

[cover]
image = 'images/ai-slop-web.webp'
alt = 'A tired cook ladling from a bucket labelled Generative AI'
relative = false
+++

So, most stuff on AI tends to fall into one of two extremes nowadays. You've got your AI tech bro hypetrain people talking on YouTube about how their next OpenClaw clone or Claude Code workflow is making them a gazillion dollars a day, whilst promoting their $500 USD a month skool.com "course", and you've got people with a hatred of AI with the intense burning fury of a thousand suns because ChatGPT stole their job, fucked their mother and ran over their dog too. AI is evil, so fuck you for ever admitting you ever asked Gemini or Claude for their opinion on something, because that instantly makes you just like Hitler.

So let's do some good old-fashioned fencesitting centrist bullshit and see where this really lands, shall we?

## AI didn't fuck my mother

So, spoiler alert, I actually use AI a fair bit. I'm a Claude subscriber, but I'm one of those weirdos who's not really a traditional developer per se. I'm just a run of the mill sysadmin, looking mostly after Windows and Azure based infrastructure for **[INSERT COMPANY NAME HERE]** whilst also serving as a jack of all trades. I predominantly use it for writing PowerShell scripts, with the occasional bash or zsh script for Linux and Mac devices as well (and I'll get into my OMG KILLER WORKFLOW A GAZILLION DOLLARS AN HOUR SUBSCRIBE TO MY SKOOL DOT COM ACADEMY Claude skill for that another day), and for faffing about with my homelab, such as documenting all the weird Proxmox VM's and docker containers I've spun up, and what things are on what machine, plus how everything's all tied together. We have Copilot at work, but it's mostly useless for what I use AI for, so at best it's for writing boring monotone e-mails to people I don't like and don't have the inclination to properly write for.

In reality, Claude's great for the PowerShell stuff, and for tasks regarding my homelab. It doesn't generate art, it doesn't take anyone's job away, and I mostly use it as a force multiplier for the skills I already have, while also using it to learn more about the stuff and skills required for things I don't know so much about. Regarding the PowerShell scripting, it's easy enough to follow the logic (which helps when you already know how to code in PowerShell), and I often go through multiple revisions and testing before it gets deployed out.

Diving a bit deeper into how I use it for my homelab, I personally instruct Claude to push back on my ideas, critique my plans, and remind me not to over-engineer shit. If I think about investigating something, the first question is always "Why are you doing this? What are you getting out of it? What do you hope to achieve with it?" and that's a great way to keep yourself grounded and really think about things before you start writing a docker compose file.

Ultimately, that's where I think AI shines. Using it as a productive tool to help you do your job better. It's very interesting technology, and it is definitely a fundamental shift when it comes to tech, but it's neither Skynet nor Tech Bro Utopia. It's just a tool.

## But it did fuck that guy's mother

So, everything's awesome and smelling of roses, right? Not quite. I think it's best used as a force multiplier for someone with their hands on the wheel that knows how to do what they ask the AI to do, so it can help them do their job better. But we live in the real world, and if you've been around since the early 80s like I have, you know exactly what direction this world is taking, and the greedy fuckers at the top look at AI and think "I don't have to pay wages anymore!" because of course they fucking do. I mean, if robots replace everyone, who's going to have the money to buy their stupid shit? Well, long term thinking's not exactly a trait with these fucking ghouls.

Generating code with AI is one thing - I'm open source minded myself, and I usually license everything I put out there under the MIT license or some form of Creative Commons license. But generating artwork or music with AI is a touchy thing, and it doesn't make me feel great. When I see the telltale signs of generated AI like.. oh.. the shit at the start of this page for instance, it doesn't inspire me with much confidence of the quality of whatever I'm about to look at.

...and then there's the slop. Hang around Reddit long enough, and you'll see countless droves of personal dashboards, usage monitors, memory systems, and dashboards with memory systems for all of your usage monitors, but at least these people are honest about what Claude or Codex generated for them with the inevitable follow up post a week later on all of the security flaws hidden in X app that someone created. Stick around things like the Mac apps subreddit, and it's a slop buffet with far less honest people, but all the telltale signs nonetheless.

On the one hand, AI democratises coding, but on the other hand, AI also democratises coding. YouTube's full of grifters who will tell you how they used Claude Code to one shot an app that made them a gazillion dollars in a week (as long as you sign up for their $800 USD a month Skool dot com academy that is) and the result is people with no coding background will take that as inspiration to create the sloppiest slop that ever slopped.

The last thing is the whole AI agent fad, which I admit is a cool idea but it's also one of the riskiest. OpenClaw's a fantastic self hosted prompt injection machine, which happily plugs into every system you have and all facets of your life, so who wouldn't want to give all the keys to their kingdom to something that'll happily be willing to be socially engineered into handing all of that over to some North Korean script kiddy with numbers in their name?

## Okay, enough whiplash. Should I learn about AI?

Okay, so we've got how I personally use it, and also how a lot of people abuse it. Should you learn more about it for your job in the IT industry?

**Yes.** You should learn it for the same reason Novell sysadmins should have learned Active Directory, and for the same reasons Windows AD sysadmins should have learned AzureAD/Entra ID and M365. It's the next step in technology, and if you don't keep up, you're going to be left behind.

Are we in an AI bubble akin to the dot com bubble of the late 90s and early 2000s? Of course we fucking are. Does that mean that AI is already a dead man walking? No, and for the same reason we still have internet connections in our homes and places of business, and why we walk around glued to devices that are always online. The underlying technology actually has a use, unlike crypto and "the metaverse" horseshit before it. It's full of hype, and I have strong doubts that AGI is even possible (or more likely, tech bros will run out of money before they can buy enough GPUs to actually build it). I don't think the gazillion parameter models will continue to produce anything of worth, and I think the real future of AI is going to be in smaller, more efficient models for the same reason that ARM based Mac laptops spank their Intel counterparts silly.

But regardless of which direction AI goes, it's too useful to die off just because of yet another impending financial collapse, and after the dust settles, it'll still stick around, and you'll still be expected to have some modicum of understanding of how it works if you want to remain gainfully employed in the future (at least when it comes to tech orientated fields, and likely quite a few other fields as well). I still believe the real benefit is using it as a force multiplier instead of a replacement for genuine skill, but sadly it looks like we're all going to have to learn this lesson the hard way and eat shit for a while yet.

You don't have to embrace the slop, and you don't have to be yet another purity testing dickhead that loudly judges everyone else. You don't have to like AI, but you should have a basic understanding of how it works and where it can best be applied, and if you can find novel ways for it to help you do day to day stuff without outsourcing your thinking to it, then by all means, use it. There's lots of genuinely cool things you can make use of it with, especially when it comes to tech and homelabbing. Documentation's a great example - you can slap Claude with a bunch of local MCP servers that can access your internal homelab stuff like Proxmox, Unraid, your *Arr stack, and let it go explore and document everything into Notion or Outline for you (or whatever else you like using for documentation). Tell it to ask you what stuff is, if it's not clear by the name. That's just one example.

Things are likely to get worse before they get better, but when the dust settles, you'll still want to know how to use what comes out of it. Don't fall for the hype, but don't let baseless ideology keep you back.
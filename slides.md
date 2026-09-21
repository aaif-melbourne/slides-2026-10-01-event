---
theme: apple-basic
title: Agentic AI Melbourne — September 2026
info: |
  MC slides for Agentic AI Melbourne, 2 September 2026.
  Licensed under Creative Commons Attribution 4.0 International.
author: Ryan Djurovich
colorSchema: light
exportFilename: agentic-ai-melbourne-september-2026
transition: slide-left
mdc: true
---

<div class="hero hero-with-image">
  <div class="eyebrow">Agentic AI Melbourne · September 2026</div>
  <h1 style="padding-top: 4rem">G'Day</h1>
  <div class="hero-meta">
    <span>2 September 2026</span>
    <span>Vivanti Consulting · Docklands</span>
  </div>
</div>

<div class="hero-art">
  <img src="/agentic-ai-melbourne-hero.png" alt="AI agents building together beside Melbourne's Docklands" />
</div>

<!--
G'day everyone, and welcome to Agentic AI Melbourne.

I'm Ryan Djurovich, one of the AAIF community event organisers here in Melbourne, and I'll be your MC tonight.

Thank you for making the time to be here.

Before we get into the talks, I want to give a little context about this community, why we've brought this room together, and how we hope tonight will work.

First, I just want to call out that our aim for this event is progress over perfection. This is a new community and, and we're hoping to learn from tonight. 

So if you have feedback after tonight, please let us know. And of course, we'll be asking for it!
-->

---

# What is the AAIF?

<p class="text-md !leading-[1.4] pt-2">The Agentic AI Foundation is the Linux Foundation’s neutral home for open standards and projects that power AI agents.</p>

<div class="foundation-map">
  <div class="foundation-root logo-node">
    <img src="/logos/linux-foundation.svg" alt="The Linux Foundation" />
  </div>
  <div class="foundation-branches">
    <div class="foundation-lane cloud-native-lane">
      <div class="foundation-label">Cloud native ecosystem</div>
      <div class="logo-node foundation-node">
        <img src="/logos/cncf.svg" alt="Cloud Native Computing Foundation" />
      </div>
      <div class="map-arrow">↓</div>
      <div class="ecosystem-projects">
        <div class="logo-node project-node">
          <img src="/logos/kubernetes.svg" alt="Kubernetes" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/cilium.svg" alt="Cilium" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/flux.svg" alt="Flux CD" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/fluent-bit.svg" alt="Fluent Bit" />
        </div>
      </div>
    </div>
    <div class="foundation-lane agentic-lane">
      <div class="foundation-label">Agentic AI ecosystem</div>
      <div class="logo-node foundation-node">
        <img src="/logos/aaif.svg" alt="Agentic AI Foundation" />
      </div>
      <div class="map-arrow">↓</div>
      <div class="ecosystem-projects">
        <div class="logo-node project-node mcp-node">
          <img src="/logos/mcp.svg" alt="Model Context Protocol" />
        </div>
        <div class="logo-node project-node agents-node">
          <img src="/logos/agents-md.png" alt="AGENTS.md" />
          <strong>AGENTS.md</strong>
        </div>
        <div class="logo-node project-node named-project-node">
          <img src="/logos/goose.png" alt="goose" />
          <strong>goose</strong>
        </div>
        <div class="logo-node project-node named-project-node">
          <img src="/logos/agentgateway.png" alt="agentgateway" />
          <strong>agentgateway</strong>
        </div>
      </div>
    </div>
  </div>
</div>

<!--
You've probably seen the AAIF name everywhere around this event, and because it's relatively new, there's a chance you might not have heard of it before or don't know anythign about it.

The AAIF is the Agentic AI Foundation. It is a non-profit, vendor-neutral foundation under the Linux Foundation.

This diagram shows the relationship relative to a more well known sibling, the CNCF. The Linux Foundation provides the umbrella and neutral governance. The CNCF is home to projects including Kubernetes, Cilium, Flux, and Fluent Bit. In a similar way, the AAIF is home to MCP, AGENTS.md, goose, and agentgateway.

For those not familiar, the CNCF became a neutral home for important cloud-native projects and helped an ecosystem form around Kubernetes. It's my understand that the AAIF aims to play a similar role for agentic AI: stewarding shared standards and open source infrastructure so the ecosystem can develop in the open.
-->

---

# Who is in the room?

<div class="audience-grid">
  <div class="audience-card">
    <div class="audience-number">01</div>
    <strong>Engineers</strong>
    <p>Software experience, demonstrated use of AI agents, and a habit of building things.</p>
  </div>
  <div class="audience-card accent-card">
    <div class="audience-number">02</div>
    <strong>Builders</strong>
    <p>Different background, exceptional use of AI agents, and something real to show for it.</p>
  </div>
</div>

<p class="text-center pt-4 !leading-10">
Our goal for tonight:<br /><strong>Bring people together who are building with AI agents.</strong>
</p>

<!--
As you all know, this event required registration which needed approval.

Every registration was hand reviewed, because this event is deliberately for engineers and builders.

Roughly, our entry requirements were one of two things.

First: engineers — people with a history of work as a developer or software engineer, who also demonstrate that they're using AI agents and building things.

Or second: builders — people who might not have that traditional work history, but who demonstrate exceptional use of AI agents to build something.

The common thread is merit. We want people in this room primarily because of what they're building, learning, and contributing — not their title, their employer, or the size of their following.
-->

---

# What do expect of you?

<div class="expectation-grid">
  <div class="expectation-card kindness-card">
    <div class="expectation-heading"><span>01</span><strong>Kindness</strong></div>
    <div class="expectation-actions">
      <div><strong>Introduce yourself</strong><span>Start with hello.</span></div>
      <div><strong>Be friendly</strong><span>Assume good intent.</span></div>
      <div><strong>Welcome others</strong><span>Make room in the conversation.</span></div>
    </div>
  </div>
  <div class="expectation-card curiosity-card">
    <div class="expectation-heading"><span>02</span><strong>Curiosity</strong></div>
    <div class="expectation-actions">
      <div><strong>Ask questions</strong><span>Explore ideas together.</span></div>
      <div><strong>Share</strong><span>Offer what you know.</span></div>
      <div><strong>Learn</strong><span>Stay open to new answers.</span></div>
    </div>
  </div>
</div>

<!--
Now, there are two things we'd like to see from everyone here tonight: kindness and curiosity.

Kindness means introducing yourself to somebody you don't know, being friendly, and actively welcoming other people into the conversation.

Curiosity means asking questions in good faith, sharing what you know, and being ready to learn from the experience around you.

There is a huge range of experience in this room, and the field itself is moving incredibly quickly. None of us have all the answers.

So please learn generously and share generously. The conversations before, between, and after the talks are as important as what happens on stage.
-->

---

# Say hi to our event team

<div class="organiser-grid">
  <div class="organiser">
    <img src="/organisers/chris-rickard.png" alt="Chris Rickard" />
    <div class="organiser-details">
      <strong>Chris Rickard</strong>
      <a href="https://www.linkedin.com/in/chrickard/" target="_blank"><carbon-logo-linkedin />@chrickard</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/gajan-kugamoorthy.png" alt="Gajan Kugamoorthy" />
    <div class="organiser-details">
      <strong>Gajan Kugamoorthy</strong>
      <a href="https://www.linkedin.com/in/kgajananan/" target="_blank"><carbon-logo-linkedin />@kgajananan</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/iman-yusuf.png" alt="Iman Yusuf" />
    <div class="organiser-details">
      <strong>Iman Yusuf</strong>
      <a href="https://www.linkedin.com/in/imanyusuf/" target="_blank"><carbon-logo-linkedin />@imanyusuf</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/phil-nash.png" alt="Phil Nash" />
    <div class="organiser-details">
      <strong>Phil Nash</strong>
      <a href="https://www.linkedin.com/in/philnash/" target="_blank"><carbon-logo-linkedin />@philnash</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/prem-pillai.png" alt="Prem Pillai" />
    <div class="organiser-details">
      <strong>Prem Pillai</strong>
      <a href="https://www.linkedin.com/in/cloud-on-prem/" target="_blank"><carbon-logo-linkedin />@cloud-on-prem</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/rob-kenefeck.png" alt="Rob Kenefeck" />
    <div class="organiser-details">
      <strong>Rob Kenefeck</strong>
      <a href="https://www.linkedin.com/in/robkenefeck/" target="_blank"><carbon-logo-linkedin />@robkenefeck</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/ryan-djurovich.jpg" alt="Ryan Djurovich" />
    <div class="organiser-details">
      <strong>Ryan Djurovich</strong>
      <a href="https://www.linkedin.com/in/ryandjurovich/" target="_blank"><carbon-logo-linkedin />@ryandjurovich</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/dr-sam.png" alt="Dr Sam Donegan" />
    <div class="organiser-details">
      <strong>Dr Sam Donegan</strong>
      <a href="https://www.linkedin.com/in/samueldonegan/" target="_blank"><carbon-logo-linkedin />@samueldonegan</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/yann-vigara.png" alt="Yann Vigara" />
    <div class="organiser-details">
      <strong>Yann Vigara</strong>
      <a href="https://www.linkedin.com/in/yvigara/" target="_blank"><carbon-logo-linkedin />@yvigara</a>
    </div>
  </div>
</div>

<!--
A quick introduction to the people who've signed up to be community organisers for this event.

They are Chris Rickard, Gajan Kugamoorthy, Iman Yusuf, Phil Nash, Prem Pillai, Rob Kenefeck, Ryan Djurovich, Dr Sam Donegan, and Yann Vigara.

Events like this take a surprising amount of work behind the scenes. Please say hello to us, and please tell us what would make the next one better.
-->

---

# Thank you, Vivanti

<div class="sponsor-stage">
  <img src="/sponsors/vivanti.png" alt="Vivanti" />
  <p>Our venue host and event sponsor</p>
</div>

<div class="handoff">Gajan — tell us about Vivanti.</div>

<!--
Tonight would not be possible without Vivanti Consulting.

They've generously provided this venue, are covering the food an drinks, and supported us in bringing the community together.

Rather than have me speak for them, I'd like to invite Gajan to take one minute to tell us a little about Vivanti and why they're supporting the event.

[HAND TO GAJAN — APPROXIMATELY ONE MINUTE]

Thank you, Gajan — and thank you again to everyone at Vivanti for having us.

One ask for everyone: please be respectful of this venue and clean up after yourselves before you leave.
-->

---

# Tonight's line-up

<div class="agenda">
  <div class="agenda-item featured">
    <img class="agenda-speaker" src="/speakers/dan-harper.png" alt="Dan Harper" />
    <span class="agenda-kind">Main Talk</span><strong>Hosting LLMs in production and failing to scale to 10 users</strong><span>Dan Harper · CTO, AskYourTeam</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/speakers/thiago-shimada-ramos.png" alt="Thiago Shimada Ramos" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>Shifting Down: Agentic Security at Infra Level</strong><span>Thiago Shimada Ramos · Founder, EnclaveAI Studio</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/organisers/phil-nash.png" alt="Phil Nash" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>What you might not know about Stateless MCP</strong><span>Phil Nash · Developer Experience Engineer, Resend</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/speakers/james-bannan.png" alt="James Bannan" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>From Ideation to Presentation with Markdown, Slidev, & Agents</strong><span>James Bannan · Principal Consultant, Microsoft</span>
  </div>
</div>

<div class="timeline"><span>Doors 5:30</span><i></i><span>Talks from 6:00</span><i></i><span>Social 8:00–8:30</span></div>

<!--
Here's our line-up for tonight.

The format we're looking at running with these events is to have one main talk, followed by three lightning talks.

Dan will share the very honest story of hosting LLMs in production and failing to scale to ten users.

Then Thiago will shift agentic security down to the infrastructure level.

Phil will cover what you might not know about stateless MCP.

And James will show a workflow from ideation to presentation using Markdown, Slidev, and agents.

The goal is to finish here between 8 and 8:30, then head to our after-event community social.
-->

---
class: blank-slide
---

<!--
INTENTIONAL SECTION BREAK.

Leave this slide displayed during the talk programme if a neutral screen is needed.

The following slides are the outro section.
-->

---

# Thank you to our speakers

<div class="speaker-thanks">
  <div><strong>Dan Harper</strong><span>AskYourTeam</span></div>
  <div><strong>Thiago Shimada Ramos</strong><span>EnclaveAI Studio</span></div>
  <div><strong>Phil Nash</strong><span>Resend</span></div>
  <div><strong>James Bannan</strong><span>Microsoft</span></div>
</div>

<div class="applause">One more round of applause.</div>

<!--
What a fantastic set of talks.

Please join me in thanking Dan, Thiago, Phil, and James — for the preparation, the candour, and the ideas they shared with us tonight.

Speaking takes work. Sharing unfinished lessons and real failures takes courage. The quality of this community depends on people being willing to do both.

Let's give all four speakers one more round of applause.
-->

---

# How did we do?

<div class="qr-layout">
  <div>
    <div class="statement">Help us make the next event better.</div>
    <p>Just 5 short questions.<br />It should take one minute.</p>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLScvHpNuDkmmrnTYqIHZ_-wUaWOmE3xNDmZ45ZN-hGyj7DJs_w/viewform?usp=dialog">Open the feedback form →</a>
  </div>
  <ProjectQr value="https://docs.google.com/forms/d/e/1FAIpQLScvHpNuDkmmrnTYqIHZ_-wUaWOmE3xNDmZ45ZN-hGyj7DJs_w/viewform?usp=dialog" :size="260" />
</div>

<!--
Before we wrap up, we'd really value your feedback on tonight's event.

It's just five short questions and should take one minute. Please scan the QR code and let us know what worked and what we could make better next time.
-->

---

# What are you building?

<div class="qr-layout">
  <div>
    <div class="statement">Speak at our next event.</div>
    <p>Practical lessons. Honest failures.<br />Things that other builders can use.</p>
    <a href="https://forms.gle/yeyvhsizE1f6oqAX8">forms.gle/yeyvhsizE1f6oqAX8</a>
  </div>
  <ProjectQr value="https://forms.gle/yeyvhsizE1f6oqAX8" :size="260" />
</div>

<!--
With that said, we're a new event and we're looking to build our list of potential speakers.

If you're building something interesting, learning something the hard way, or have a practical technique others can use, we'd love to hear from you.

You do not need a polished keynote. In fact, practical lessons and honest failures are exactly what we want. And with what James has just shown you, hopefully you'll be able to whip-up some slides, should you need them, in just a few minutes!

So please scan the QR code to submit to our call for papers. If you're unsure whether an idea is ready, come and talk to us tonight.
-->

---

# Next month

<div class="qr-layout">
  <div>
    <div class="statement">Registrations are now open.</div>
    <p style="font-size: 1.2em;">Thursday 1st October 2026</p>
    <a style="font-size: 1.1em;" href="https://luma.com/ioxvp4zf">luma.com/ioxvp4zf</a>
    <p style="font-size: 1em;">Follow the Melbourne community Luma page<br />to be notified of all future events.</p>
    <a style="font-size: 1em;" href="https://aimelb.org">aimelb.org</a>
  </div>
  <ProjectQr value="https://luma.com/ioxvp4zf" :size="260" />
</div>

<!--
Registrations are now open for next month's event: Agentic AI Melbourne in October.

Talks and the CBD venue will be announced soon.

Scan this QR code to open the event page and request to join.

Capacity is limited and registrations are reviewed, so apply early and tell us what you're building.

Also just to clarify on those RSVPs, when you tell us what you're building, if you can link to your projects, it's going to go a long way with the review of your registration.

You can also follow the Melbourne community Luma page at aimelb.org to be notified of all future events.
-->

---

# Thank you to our sponsor

<div class="sponsor-stage outro-sponsor">
  <img src="/sponsors/vivanti.png" alt="Vivanti" />
  <p>Space to meet. Support to learn. A home for tonight.</p>
</div>

<!--
Before we wrap up, one more thank you to Vivanti Consulting.

Thank you for opening your space to us, for supporting the event, and for making a room like this possible.

Please help us leave the venue as we found it, and take a moment to thank the Vivanti team if you see them tonight.
-->

---

# Keep the conversation going

<div class="social-callout">
  <div class="time-block"><strong>8:00–8:30</strong></div>
  <div class="social-copy">After-event<br /><span>community social</span></div>
</div>

<!--
[ANNOUNCE THE CONFIRMED SOCIAL VENUE AND DIRECTIONS VERBALLY]
-->

---
class: aaif-banner-slide
---

<img class="aaif-banner-content" src="./aaif-banner.svg" alt="Agentic AI Foundation Community Event" />

<a class="aaif-qr" href="https://aimelb.org" aria-label="Visit aimelb.org">
  <ProjectQr value="https://aimelb.org" :size="96" foreground="#fff" background="transparent" />
</a>

<!--
Leave this final banner on screen as people depart.
-->

---
hide:
  - navigation
description: April 21-22, San Francisco -- Best practices and tools for building LLM-powered apps
embed_image: https://staging.fullstackdeeplearning.com/llm-bootcamp/opengraph.png
---

<style>
  .admonition.abstract p, .admonition.abstract ul {
    font-size: large;
  }
  [dir=ltr] .md-typeset .admonition.abstract .admonition-title {
    padding-left: 0.6rem;
    text-align: center;
  }
  .admonition.abstract .admonition-title::before {
    display: none;
  }
  .md-typeset .admonition.abstract>:last-child {
    margin-bottom: 1.25rem;
  }

  .md-typeset table:not([class]) {
    font-size: inherit;
    line-height: inherit;
  }
  .md-typeset table:not([class]) td {
    vertical-align: top;
  }
  .md-typeset table:not([class]) th {
    white-space: nowrap;
    min-width: 5rem;
  }

  .newsletter-signup {
    display: flex;
    align-items: center;
  }

  .newsletter-signup input[type="email"] {
    width: 100%;
    padding: 0.5rem;
    border-radius: 0.25rem;
    border-width: 1px;

    border-style: solid;
    color: black;
  }

  .newsletter-signup #mc_embed_signup_scroll {
    display: flex;
    flex-wrap: wrap;
    gap: .5rem;
  }

  .newsletter-signup .mc-field-group {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .logo--image {
  border-radius: 50%;
  border: 4px solid #4350af;
}
</style>

# LLM Bootcamp

<div class="admonition abstract">
  <p class="admonition-title">🚀 Announcing Full Stack Deep Learning LLM Bootcamp 🚀</p>
  <div class="grid-2 items-center">
    <ul>
      <li>In person in San Francisco on <strong>April 21-22</strong></li>
      <li>Learn <strong>best practices and tools</strong> for building LLM-powered apps</li>
      <li><strong>Network</strong> with a couple hundred other builders</li>
      <li>Get <strong>cloud credits</strong> from OpenAI and other <a href="#sponsors">sponsors</a></li>
    </ul>
    <div class="flex items-center justify-center">
      <img alt="Venn diagram showing that FSDL is at the intersection of a course, a hackathon, and a conference." src="/images/fsdl-2023-overview.png" width="480px">
    </div>
  </div>
  <div class="flex justify-center mt-8 mb-2">
    <a href="#register" class="md-button">Sold Out</a>
  </div>
</div>

## Why

We are at the cusp of a technology unlock of a magnitude not seen since the early days of the Internet.
Rapid AI progress is fulfilling the old promise of Language User Interfaces (*LUI*s), which will revolutionize software just as GUIs did in the 90s.

The way AI-powered apps are built is rapidly changing:

- Before LLMs, an idea would bottleneck on training models from scratch, and then it'd bottleneck again on scalable deployment.
- Now an MVP based on pretrained, promptable LLM models and APIs can be configured and serving users in an hour.

An entirely new ecosystem of techniques, tools, and tool vendors is forming around LLMs and LUIs. Even ML veterans are scrambling to orient themselves to what is now possible and figure out the most productive techniques and tools.

Engineers are asking themselves:

- Are there any good open-source LLMs?
- What is my moat if I rely on OpenAI APIs?
- Is *Prompt Engineering* some kind of sick joke?
- How can I gather and use feedback from users?
- Should I be able to code a Transformer from scratch?
- How exactly am I supposed to test these damn things?

## What

We have put together a two-day program based on emerging best practices in the LLM community and the latest research results to help you answer these questions and make the transition to building.

**Our goal is to get you 100% ready to build and deploy LLM applications and 100% caught up with the state-of-the-art.**

!!! question "What do I need to know already?"
    We aim to get anyone with experience programming in Python ready to start building applications that use LLMs.

    Experience with at least one of machine learning, frontend, or backend will be very helpful.

    And if none of the questions above resonate, this probably isn't for you.

### Schedule

<table>
  <thead>
    <tr>
      <th></th>
      <th>Friday (April 21)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9 am</td>
      <td>Registration &amp; Breakfast</td>
    </tr>
    <tr>
      <td>10 am</td>
      <td>
        <strong>🚀 Launch an LLM App in 1 Hour</strong>
        <ul>
        <li> We'll go from idea to user-ready website in one hour
        </ul>
      </td>
    </tr>
    <tr>
      <td>11 am</td>
      <td>
        <strong>🗿 LLM Foundations</strong>
        <br />
      <ul>
        <li>Learn the core concepts behind transformer architectures, self-supervised learning, and text generation
        <li>Develop clear intuitions for model internals based on the latest work in "reverse engineering" LLMs
      </ul>
      </td>
    </tr>
    <tr>
      <td>12 pm</td>
      <td>Lunch and networking</td>
    </tr>
    <tr>
      <td>1 pm</td>
      <td>
        <strong>✨ Learn to Spell: Prompt Engineering and Other Magic</strong>
        <ul>
          <li>Prompt techniques for language modeling, instruction, and agent simulation
          <li>Arcana and curiosities from the world of prompt wizardry
          <li>Heuristics for where LLMs can and cannot be effective
        </ul>
      </td>
    </tr>
    <tr>
      <td>2 pm</td>
      <td>
        <strong>🔨 Augmented Language Models</strong>
        <ul>
          <li>Moving beyond pure language modeling with tools and retrieval
          <li>Choosing between vector stores/indices (e.g. FAISS, Milvus, Pinecone, Weaviate, Vespa) for long-term memory
        </ul>
      </td>
    </tr>
    <tr>
      <td>3 pm</td>
      <td>Coffee and networking</td>
    </tr>
    <tr>
      <td>345 pm</td>
      <td>
        👷‍♂️ <strong>askFSDL Walkthrough</strong>
          <ul>
          <li> Detailed breakdown of a well-documented sample project demonstrating use of LLM APIs and frameworks, traditional and vector databases, and user feedback ingestion
          </ul>
      </td>
    </tr>
    <tr>
      <td>430 pm</td>
      <td>
        🎤 Invited Talk from<br/>
        <strong>Richard Socher</strong>: CEO and co-founder of You.com
      </td>
    </tr>
    <tr>
      <td>515 pm</td>
      <td>
        🎤 Invited Talk from<br/>
        <strong>Peter Welinder</strong>: VP of Product at OpenAI
      </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th></th>
      <th>Saturday (April 22)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9 am</td>
      <td>Breakfast</td>
    </tr>
    <tr>
      <td>10 am</td>
      <td>
        <strong>🌳 Demo Garden</strong>
        <ul>
          <li>Present your cool project
          <li>Review other cool projects
        </ul>
      </td>
    </tr>
    <tr>
      <td>11 am</td>
      <td>
        <strong>🤷 UX for LUIs</strong>
        <ul>
          <li>Emerging UX patterns in language user interfaces
          <li>Principles of successful design, applied to AI-powered apps
          <li>Case studies on the best AI-powered apps today
        </ul>
      </td>
    </tr>
    <tr>
      <td>12 pm</td>
      <td>Lunch and networking</td>
    </tr>
    <tr>
      <td>1 pm</td>
      <td>
        <strong>🏎️ LLMOps: Deployment and Learning in Production</strong>
        <ul>
          <li>How vendors like OpenAI, Anthropic, and Cohere compare with each other and with open-weights options like T5, Pythia, and LLaMA
          <li>How to manage prompts and programs, monitor models, trace chains, and record feedback
          <li>Methods for learning from users, like RLHF, and from chains of LLMs, like Constitutional AI
        </ul>
      </td>
    </tr>
    <tr>
      <td>2 pm</td>
      <td>
        <strong>🔮 What's Next?</strong>
        <ul>
          <li> What are the limits of scale, large and small?
          <li> Has multimodality unlocked general purpose robotics?
          <li> Is AGI already here?
          <li> Can we make it safe?
        </ul>
      </td>
    </tr>
    <tr>
      <td>3 pm</td>
      <td>Coffee and networking</td>
    </tr>
    <tr>
    <td>4 pm</td>
      <td>
        🎤 Invited Talk from<br />
        <strong>Harrison Chase</strong>: Creator of LangChain
      </td>
    </tr>
    <tr>
      <td>4:45 pm</td>
      <td>
      🎤 Invited Talk from<br />
      <strong>Reza Shabani</strong>: Training LLMs at repl.it</td>
    </tr>
    <tr>
      <td>5:30 pm</td>
      <td>Discussion Panel: <strong>Building a Defensible Business</strong></td>
    </tr>
  </tbody>
</table>

## Who

We are <a href="https://fullstackdeeplearning.com">Full Stack Deep Learning</a>.
We're a team of UC Berkeley PhD alumni with years of industry experience who are passionate about teaching people how to make deep neural networks work in the real world.

Since 2018, we have taught in-person bootcamps, online multi-week cohorts, and official semester-long courses at top universities.

As former academics, we always make sure that all of our materials become accessible for free, right here on [this website](../course/2022).

<div class="grid-3">
  <img alt="Group photo of the attendees of FSDL March 2019 bootcamp" src="/images/group-march2019.jpg" width="480px">
  <img alt="Group photo of the attendees of FSDL August 2018 bootcamp" src="/images/group-august2018.jpg" width="480px">
  <img alt="Group photo of the attendees of FSDL November 2019 bootcamp" src="/images/group-november2019.jpg" width="480px">
</div>

### Instructor Team

<div class="grid-2">
  <div class="person">
    <img src="/images/charles.png" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Charles Frye">
    <div><strong>Charles Frye</strong> educates people in AI. He has worked on AI/ML tooling with Weights & Biases and Gantry since getting a PhD in Theoretical Neuroscience at UC Berkeley.</div>
  </div>
  <div class="person">
    <img src="/images/sergey.png" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Sergey Karayev">
    <div>
    <strong>Sergey Karayev</strong> builds AI-powered products as Co-founder of Volition. He co-founded Gradescope after getting a PhD in AI at UC Berkeley.
    </div>
  </div>
  <div class="person">
    <img src="/images/josh.png" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Josh Tobin">
    <div>
    <strong>Josh Tobin</strong> builds tooling for AI products as Co-founder and CEO of Gantry. He worked as a Research Scientist at OpenAI and received a PhD in AI at UC Berkeley.
    </div>
  </div>
</div>

### Invited Talks

<div class="grid-2">
  <div class="person">
    <img src="/images/speaker-peter-welinder.jpg" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Peter Welinder">
    <div><strong>Peter Welinder</strong> is VP of Product and Partnerships at OpenAI.</div>
  </div>
  <div class="person">
    <img src="/images/speaker-harrison-chase.jpg" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Harrison Chase">
    <div><strong>Harrison Chase</strong> is the creator of LangChain.</div>
  </div>
  <div class="person">
    <img src="/images/speaker-richard-socher.jpg" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Richard Socher">
    <div><strong>Richard Socher</strong> is the co-founder and CEO of you.com.</div>
  </div>
  <div class="person">
    <img src="/images/speaker-reza-shabani.jpg" class="person--image" height="160px" width="160px" loading="lazy" alt="Photo of Reza Shabani">
    <div><strong>Reza Shabani</strong> trains LLMs at repl.it.</div>
  </div>
</div>

## When and Where

The event will be **in-person** and run **all day** on **Friday, April 21, 2023** and **Saturday, April 22, 2023** at the [South San Francisco Conference Center](https://ssfconf.com/).

## Register

<div class="tiers">
  <div class="tier">
    <div class="tier--header">Regular</div>
    <div class="tier--price">
      <div>$950</div>
    </div>
    <div>
      <p style="height: 3rem;">
      </p>
      <a href="https://fsdl.me/2023-llmbc-reg" style="width: 100%" class="md-button">Sold Out</a>
    </div>
  </div>
  <div class="tier">
    <div class="tier--header">Academic</div>
    <div class="tier--price">
      <div>$450</div>
    </div>
    <div>
      <p style="height: 3rem;">
        If you are a <strong>current</strong> full-time student or post-doc, enjoy this lower price.
      </p>
      <a href="https://fsdl.me/2023-llmbc-academic" style="width: 100%" class="md-button md-button--secondary"> Sold Out </a>
    </div>
  </div>
</div>

Need to expense the registration costs?
Check out our [quick guide to reimbursement](./expense),
including an LLM-generated email template for getting manager approval.

If you have any questions about the bootcamp, contact
[`admin @ fullstackdeeplearning.com`](mailto:admin@fullstackdeeplearning.com).
We cannot honor requests for additional discounts.

<div class="admonition info">
  <p class="admonition-title">Missed your chance to buy a ticket?</p>
  <p>Join over 25K subscribers and we'll notify you when we eventually put the materials online.</p>

  <!-- Begin Mailchimp Signup Form -->
  <div id="mc_embed_signup" class="newsletter-signup">
    <form action="https://fullstackdeeplearning.us18.list-manage.com/subscribe/post?u=68cabce2e74766ca3d2c089d6&amp;id=79e6eb0052&amp;f_id=00b517e7f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_self">
      <div id="mc_embed_signup_scroll">
        <div class="mc-field-group">
          <label for="mce-EMAIL">Email Address</label>
          <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" required>
          <span id="mce-EMAIL-HELPERTEXT" class="helper_text"></span>
        </div>
        <div id="mce-responses" class="clear">
          <div class="response" id="mce-error-response" style="display:none"></div>
          <div class="response" id="mce-success-response" style="display:none"></div>
        </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_68cabce2e74766ca3d2c089d6_79e6eb0052" tabindex="-1" value=""></div>
        <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="md-button md-button--secondary"></div>
      </div>
    </form>
  </div>
<!--End mc_embed_signup-->

<p>
While you're at it, follow us on
<a href="https://twitter.com/full_stack_dl" target="_blank" rel="noopener">
    <span class="twemoji twitter" style="color: #1DA1F2">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
            <path
                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z">
            </path>
        </svg>
    </span>
    <strong>Twitter</strong>
</a> and <a href="https://www.youtube.com/c/FullStackDeepLearning?sub_confirmation=1" target="_blank" rel="noopener">
    <span class="twemoji youtube" style="color: #FF0000;">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
            <path
                d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z">
            </path>
        </svg>
    </span>
    <strong>YouTube</strong>
</a>!
</p>
</div>

## Sponsors

We're grateful to a number of sponsors who are helping us make this event happen.

### Compute Credit Sponsors

<div style="display:grid;grid-template-columns: 30% 30% 30%; row-gap: 2rem; column-gap:3%;">
  <div class="logo" markdown>
    <a href="https://openai.com"><img src="/images/logo-openai.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of OpenAI"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://modal.com"><img src="/images/logo-modal.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Modal"></a>
    </div>
  <div class="logo" markdown>
    <a href="https://replicate.com"><img src="/images/logo-replicate.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Replicate"></a>
    </div>
  <div class="logo" markdown>
    <a href="https://banana.dev"><img src="/images/logo-banana.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of banana.dev"></a>
    </div>
  <div class="logo" markdown>
    <a href="https://lambdalabs.com/cloud"><img src="/images/logo-lambdalabs.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of LambdaLabs"></a>
    </div>
  <div class="logo" markdown>
    <a href="https://repl.it"><img src="/images/logo-replit.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Replit"></a>
    </div>
</div>

We're partnering with compute vendors to offer free cloud credits to all attendees, including $1000 in credits for serverless model hosting on [Replicate](https://replicate.com), $500 in credits for data-centric compute infrastructure on [Modal](https://modal.com), $50 in credits to query LLMs via the [OpenAI API](https://openai.com/api/),  $50 in credits for running serverless GPU jobs on [banana.dev](https://banana.dev), $50 in credits to run servers in the [LambdaLabs GPU Cloud](https://lambdalabs.com/cloud), and 1000 cycles on [repl.it](https://repl.it).

### Direct Sponsors

<div style="display:grid;grid-template-columns: 30% 30% 30%; row-gap: 2rem; column-gap:3%;">
  <div class="logo" markdown>
    <a href="https://openai.com"><img src="/images/logo-openai.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of OpenAI"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://wandb.com"><img src="/images/logo-wandb.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Weights & Biases"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://aws.amazon.com"><img src="/images/logo-aws.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Amazon Web Services"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://bloombergbeta.com"><img src="/images/logo-bloomberg.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Bloomberg Beta"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://gantry.io"><img src="/images/logo-gantry.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Gantry"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://volition.co"><img src="/images/logo-volition.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Volition"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://anyscale.com"><img src="/images/logo-anyscale.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Anyscale"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://twelvelabs.io"><img src="/images/logo-twelvelabs.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Twelve Labs"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://pinecone.io"><img src="/images/logo-pinecone.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Pinecone"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://you.com"><img src="/images/logo-you.com.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of you.com"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://banana.dev"><img src="/images/logo-banana.jpg" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Banana"></a>
  </div>
  <div class="logo" markdown>
    <a href="https://distyl.ai"><img src="/images/logo-distyl.png" class="logo--image" height="160px" width="160px" loading="lazy" alt="Logo of Distyl AI"></a>
  </div>
</div>

We are deeply grateful to all of the sponsors who helped us make this event more affordable for attendees.

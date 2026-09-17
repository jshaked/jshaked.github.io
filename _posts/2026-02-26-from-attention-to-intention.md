---
layout: "post"
title: "From Attention to Intention"
categories: "writing"
---
## Intro

The attention-based web advertising business model is contingent on owning the screen real estate users see. The longer people stay on your website, the more revenue you can generate from advertising. In other words, attention-based advertising platforms are in the business of capturing user attention and selling it to advertisers, which incentivizes platforms to impose high-switching costs and create walled-gardens. And the higher the switching costs, the worse a company can treat its users — a phenomenon known as [enshittification](https://en.wikipedia.org/wiki/Enshittification). 

Social media platforms are infamously one of the largest, if not the largest, beneficiaries of the attention-based web advertising business model, holding user attention hostage through engagement farming, algorithmic feeds, and infinite scrolling. As a byproduct of this business model decision, social media platforms don’t interoperate with one another. In fact, some platforms have even invented [laws](https://iapp.org/news/a/can-a-cease-and-desist-notice-create-cfaa-liability-scrapers-beware?utm_source=chatgpt.com) that make interoperability illegal unless they give permission. A Twitter post lives on Twitter. A Medium blog lives on Medium. A YouTube video lives on YouTube.

Emerging open publishing standards like [atproto](https://atproto.com/) and [standard.site](http://standard.site) hold the potential to move social media away from enshittifying, attention-based advertising business models towards intent-based advertising business models that deliver sustainable revenues without sacrificing openness, interoperability, and low-switching costs.

## Google Search and Intents

While attention-capturing social media applications try to keep users on their platform for as long as possible, Google built its flagship search business on the opposite message. Instead, Google aimed to help users find what they were looking for and then send them quickly to other sites. In a 2004 interview, Google co-founder Larry Page [said](https://www.techdirt.com/2024/05/21/decentralized-systems-will-be-necessary-to-stop-google-from-putting-the-web-into-managed-decline/), “Google’s goal is to get the user off of Google and to the right place as fast as possible.”

Rather than monetizing attention, Google monetizes intents. Users come to Google with clear intents — “car insurance quotes,” “Nike running shoes,” “best CRM software,” etc. — which are valuable to advertisers because they indicate high probability of near-term action. If a user is searching for “hotels in Miami,” there’s a high likelihood the user is booking a trip to Miami. Google monetizes these intents by auctioning priority placement in search results to advertisers. 

While attention-capturing social media platforms and intent-capturing search engines both monetize via advertising, search benefits from, and is therefore incentivized to preserve, the web’s openness and interoperability, while social media platforms work against it. 

## [Standard.site](http://Standard.site) and Intentional Social Media

Social platforms are inherently anti-intent because they monetize attention. Users typically go to social media apps for entertainment and stimulus-inducing reels, not declared demand. The world needs ***intentional*** social media to move us away from addictive algorithms (recent [studies](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2024.1383913/full) even prove that short-form videos weaken one's ability to focus) and towards social platforms that drive value through outcomes and intent resolution.

By providing an open surface area for aggregating, discovering, and interacting with social objects across the web, open protocols like [standard.site](http://standard.site) and [atproto](https://atproto.com/) provide the foundational infrastructure to create intentional social media apps.

[Standard.site](http://Standard.site) is a shared vocabulary, a lexicon, that defines how long-form content should be structured, stored, and discovered on atproto — the identity and data protocol underpinning Bluesky. While [standard.site](http://standard.site) is built with long-form content in mind, in theory, the standard could work for any content type. Structurally, [standard.site](http://standard.site) wraps web URLs into portable social objects that can be globally discovered and interacted with across integrated clients.

So, what does an intentional social media app look like?

**Whereas Google connects people with information, intentional social media apps connect people with social objects in a unified portal — subscribers to publishers, like-minded people to communities and events, and scientific researchers to relevant papers — akin to a social web browser.** 

Instead of monetizing attention, I imagine this social web browser-like tool would monetize similarly to search engines, resolving user intents by facilitating connections between users and social objects in social-rich contexts and spaces.

Reddit is probably the closest mainstream social platform that shares the properties of an intentional social media app. Reddit users typically arrive with a specific question in mind or a particular topic they’re looking to engage with other people on. However, as an attention-capturing platform, Reddit is a closed system — identity is platform controlled, communities are platform-bound, and API access is permissioned and monetized. This means that conversations happening outside of Reddit don’t populate within Reddit and vice-versa.

If you’re looking to engage in a conversation about a particular topic, say the New York Knicks, why would you want the conversation to be constrained to the Knicks subreddit when people are talking about the Knicks across the internet in Twitter posts, YouTube comments, Instagram stories, journalistic articles, etc.

![](/assets/images/reddit.png)
![](/assets/images/clipping.png)

Instead of Reddit users having to manually clip screenshots from third-party sites, all social objects across the web relating to the Knicks should be able to be natively referenced within the Knicks subreddit community, creating native social linkages across Twitter posts, YouTube videos, blog posts, and podcasts under the same contextual window. With [standard.site](http://standard.site), it becomes possible to build an open and meaningfully larger and more connected Reddit-like app that builds communities and context-rich spaces around a universe of portable social objects, whether they live on platform or off.

## What the Future Holds

With AI being all the rage right now, a question I often get asked is “what does this all mean for AI?” AI agents are the ultimate intent machine. An AI agent’s core objective is to resolve user intents, and so intentional social media apps are perfect complements to AI agents.

AI agents thrive in open, structured, and machine-friendly environments, and lexicons like [standard.site](http://standard.site) provide exactly that. Today, each social platform has a distinct API and access is permissioned, making it difficult for an AI agent to uniformly participate across all social platforms on behalf of a user. On the contrary, [standard.site](http://standard.site) is an open, standard API for discovering and interacting with social objects that anyone, even AI agents, can tap into.

One developer already deployed an AI agent named [Koios](https://bsky.app/profile/koio.sh) to atproto who then proceeded to write a [blog post](https://koio.sh/p/00000mk1weyur) that extolled the interoperable publishing virtues of [standard.site](http://standard.site). It is still early days here, but I’m excited to see more experiments played out.

In addition to experiments around AI, I’m excited to see how mixing and matching different lexicons ([standard.site](http://standard.site) for long-form publish, events, bluesky posts for microblogging, podcasts, videos, etc.) can expand the market for social media beyond stereotypical feeds and reels. Social interactions occur any time people coordinate, signal, and interact around an object, whether it be a review on an e-commerce site, a comment on a code repository, edits to a Wikipedia page, or a response to a question on Stack Overflow.

One of atproto's key affordances is decoupling social objects from interfaces, enabling social interactivity and identity to seamlessly traverse across platforms. Social is much bigger than microblogging and long-form publishing, and I expect that atproto entrepreneurs will build novel interfaces and user experiences that bundle these cross-platform contextual relationships into a unified worldview.

Lastly, I am hopeful that the introduction of private / permissioned data will broaden the design space for intentional social media by moving us away from skeuomorphism.

Imagine you're in a closed group chat or event page for a party looking for people interested in a particular niche topic or interest. Since atproto enables users to have a singular identity across both private and public spaces, it becomes possible to import global contextual social search into local and private spaces, something that wasn't possible before.

If you enjoyed this article, let's chat. If you didn't enjoy this article, let's chat. It's still early days here, and we are all trying to figure out what sustainable business models look like in the atmosphere.
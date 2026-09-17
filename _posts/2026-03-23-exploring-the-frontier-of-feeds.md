---
layout: "post"
title: "Exploring the Frontier of Feeds"
categories: "writing"
---
## The Original Sin

One of the original sins of social media was forcing all users onto a one-size-fits-all “For You” feed. The social media algorithm is the invisible gatekeeper of digital information distribution, deciding what content is seen, by whom, and at what scale. And since the algorithm is the mechanism by which user attention is captured, it is also the layer that captures the most economic value and unilaterally determines how that value is allocated.

Today, we live in a world of ***platform-controlled algorithms***, where the algorithm is built by, and serves the interests of, the platform it lives on. While the algorithm also serves regulators, advertisers, content creators, and end users, it does so increasingly poorly as their interests diverge from the platform's. The end result is that the algorithm defaults to prioritizing the platform's interests above all else, despite the fact that these third-party stakeholders create the value that the algorithm captures.

The problem with platform-controlled algorithms is twofold:

1. **Distribution**: Publishers have no control over how their content reaches their audience, and users have no control over what content they see. Distribution is determined by the platform-controlled algorithm, which optimizes curation based on the platform’s internal KPIs (i.e. screen time, engagement, etc.) that are often misaligned with the interests of publishers, users, advertisers, and regulators. 
2. **Monetization**: Value capture is concentrated in big tech algorithms (Google and Meta own roughly two-thirds of the digital advertising market) and these companies have little to no incentive to share value with other constituents that provide value to the feed.

The world doesn’t have to be this way. Pioneering companies like [Bluesky](https://bsky.social/about), a microblogging platform built on [ATproto](https://atproto.com/), an open protocol for building social applications, and [Graze Social](https://www.graze.social/), a developer infrastructure company that enables anyone to build their own content-rich feed, are trailblazing an alternative path forward for ***user-controlled algorithms*** that:

- Give publishers control over how their content reaches their audience
- Empower users with fine-grained control over what content they see
- Redistribute attention, and thus economic value, across a long tail of user-controlled algorithms
- Enable new business models that explore how value can be more fairly distributed across users, publishers, and platforms

Rather than forcing users onto a one-size-fits-all algorithm, Bluesky outsources “the algorithm” to an open marketplace of third-party feeds, most of which are hosted by Graze, enabling users to subscribe to many feeds concurrently. 

## Redistribution of Attention and Wealth

As mentioned, platform-controlled algorithms adjudicate curation based on a platform’s internal KPIs, such as engagement and screen time. This explains why you typically see content on your “for you page” that sucks you in, like culture war content, excessively partisan takes, or clips of violence and disorder. As opposed to platform-controlled algorithms that serve the platform’s interests, user-controlled and defined algorithms unlock a new design space for feeds, shifting curation from platform-imposed objectives to user-defined ones such as high-signal content, news consumption, education, geographic proximity, and / or sentiment.

To give you a sense of what is possible when feed curation is opened up to third-party developers, here are some of the managed feeds I subscribe to on Bluesky:

- [The News feed](https://bsky.app/profile/did:plc:kkf4naxqmweop7dv4l2iqqf5/feed/verified-news) (by @[aendra.com](http://aendra.com)): feed that contains headlines from verified news organisations in reverse-chronological order.
- [For You feed](https://bsky.app/profile/did:plc:3guzzweuqraryl3rdkimjamk/feed/for-you) (by @[spacecowboy17.bsky.social](http://spacecowboy17.bsky.social)): a personalized, algorithmic feed based on your likes that finds people who liked the same posts as you, and shows you what else they've liked recently.
- [Leaflet Reader feed](https://bsky.app/profile/did:plc:btxrwcaeyodrap5mnjw2fvmz/feed/subscribedPublications) (by @[leaflet.pub](http://leaflet.pub)): a feed that surfaces all posts from publications I have subscribed to on Leaflet, a long-form blogging platform built on ATproto (this blog post is hosted on Leaflet!).
- [BookSky feed](https://bsky.app/profile/did:plc:geoqe3qls5mwezckxxsewys2/feed/aaabrbjcg4hmk) (by @[clarabelle.xyz](http://clarabelle.xyz)): a feed for book reviews and recommendations.
- [AtmosphereConf feed](https://bsky.app/profile/atmosphereconf.org/feed/atmosphereconf) (by@[atmosphereconf.org](http://atmosphereconf.org)): feed that only includes users that are attending the [ATmosphere Conference](https://atmosphereconf.org/?ref=atprotocol.dev), the ATproto developer conference.
- For a full list of feeds, see [here](https://www.graze.social/marketplace). 

As custom feeds gain adoption, attention will no longer be funneled through a handful of platform-controlled algorithms, but instead fragmented across a long tail of independently defined feeds. This stands in stark contrast to today’s status quo, where a small number of dominant algorithms, owned by companies like Google, Meta, ByteDance, and X, capture and monetize the majority of global user attention.

If attention refracts across thousands, or even millions, of feeds, the economic value tied to that user attention should follow. Meta’s algorithm alone generated ~$196B in 2025 (source: Meta’s FY25 10-K). Imagine a world where that value is distributed across 1M algorithms each earning $196K, or 100K algorithms each earning $1.96M. The shift to user-controlled algorithms wouldn’t just change how feeds are curated, it would represent a reallocation of economic power, **marking one of the largest redistributions of wealth in modern history**. That feels like a cause worth fighting for.

In this new paradigm, independent feed creators become the primary allocators of value in the attention economy. Today, while users and publishers create value on social networks, it is the platform-controlled algorithms that capture the overwhelming majority of that value. These platforms have little incentive to meaningfully share revenue downstream, and as a result, earning meaningful income as a creator is exceptionally difficult unless you operate at [massive scale](https://www.businessinsider.com/creator-income-inequality-grows-top-earners-paydays-rise-2026-1?utm_source=chatgpt.com).

While some platforms do have creator monetization programs, the requirements for qualifying for these programs are gated behind highly prohibitive thresholds. For example, X’s creator monetization program requires creators to have at least 2,000 premium followers and 5 million impressions over three months. YouTube’s partner program requires 1,000 subscribers and either 4,000 watch hours over the past year or 10 million Shorts views over the past three months.

In practice, this means monetization is reserved for a narrow slice of “800-pound gorillas,” leaving the long tail of creators largely uncompensated. Additionally, because these platforms do not delegate actual ownership of digital accounts to users, there is a chilling effect. Many people do not invest time and resources in these systems precisely because they know the rules could change at any moment.

## The Envelope of Value

As attention fragments across many feeds, feed creators will be forced to compete not just on curation quality, but on how they allocate the economic value they generate. This opens the door to entirely new business models where the “envelope of value” created by feed-based advertising revenue is distributed across a four-sided marketplace of participants who make the feed valuable:

1. **Platforms**: provide distribution and interfaces for interacting with feeds (e.g. Bluesky)
2. **Users**: supply attention / eyeballs
3. **Publishers**: create content that attracts attention
4. **Feed creators**: curate content and manage feeds

This value chain mirrors Visa’s interchange fee model, where a single transaction generates a pool of value that is allocated across multiple stakeholders (issuing bank, merchant acquirer, card network) based on their role in facilitating that transaction. Just as different card products carry different interchange rates, and therefore different incentive structures, feeds could experiment with different revenue-sharing configurations to attract higher-quality content, more engaged users, or better distribution.

At the extreme, imagine a feed that passes through all of its advertising revenue to users and publishers, aligning incentives across participants rather than extracting value from them. In such a model, both users and publishers are directly incentivized to grow and improve the feed, creating positive-sum dynamics that are largely absent from today’s platforms.

More broadly, the unbundling of the algorithm from the platform dramatically expands the design space for how value is created and distributed in the attention economy. Instead of a single, fixed monetization model imposed by a platform, we move to a world of programmable value flows, where each feed can define its own economic logic, unlocking entirely new behaviors, incentives, and forms of economic coordination and organization.

## The Future of Platforms

One of the core affordances of ATproto is that it grants users [ownership of their digital accounts](https://anirudh.fi/identity) by decoupling data and identity from application presentation. As a result, feeds built on top of ATproto data become **portable social objects** **that you can bring with you, explore, and discover across platforms.**

This shift has profound implications for power dynamics on the social web and changes the very definition of what it means to be a social media platform. If users can take their feeds from one platform to another, switching costs decrease and user agency increases. Platforms can no longer rely on locking users into proprietary algorithms to retain attention; they must compete on experience, brand, trust, distribution, and value-add. 

Today, a social media platform’s first-party algorithm IS the product. Tomorrow, in a world of portable feeds, platforms become demand aggregators and distribution layers for third-party feeds, helping users discover, navigate, and make sense of relationships across them. In this model, platforms act less like curators and more like routers, aggregating user demand and directing it toward third-party algorithms, much like Google Search routes intent to third-party websites or Coinbase routes demand to USDC, a portable digital dollar issued by Circle. 

## Open Questions

While the future of the open social web is becoming clearer everyday, it is still early. I would be the first one to admit that many details remain uncertain. In the spirit of intellectual honesty (I don’t have all the answers) and engaging further discussion on these topics, I propose the following list of open questions that I would love to hear people’s’ opinions on.

- What does the market structure for feeds look like in the long run? Will there be one feed to rule them all? Will there be thousands of feeds? Millions?
- Who will capture the most value in the feed value chain? Will it be feed creators or platforms?
- What is the right UI to traverse multiple feeds? The current Bluesky UI feels clunky where I have to scroll through each of my subscribed feeds one-by-one.
- How would you handle mass payouts to users if feed creators wanted to pass through advertising revenue to them? I have seen [some](https://weijiekoh.github.io/bsky_handle_to_eth_address/) [experimentation](https://piss.beauty/post/atproto-payment-identities) around embedding crypto wallets within PDSs.
- What’s the best way to render multi-lexicon feeds? 
- How do we represent feed content that does not live on ATproto? 


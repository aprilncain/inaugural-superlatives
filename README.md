# Language at Full Volume: Superlatives in U.S. Inaugurals

<i> Data: 60 U.S. Presidential Inaugural Addresses (1789–2025), sourced from the U.S. Government Publishing Office. Texts available via C-SPAN Inaugural Address Corpus compiled by Kathleen Ahrens (2021).</i>

There's nothing more emphatic than a superlative. A superlative adjective marks something as occupying the upper or lower extreme in a comparison, becoming shortcuts to certainty, authority, and emotional intensity; an unsurprising reason they appear so frequently in political speeches. As Adrian Beard notes in The Language of Politics (Routledge, 2000), "Political parties like to stress the importance of their views, so not surprisingly a superlative form appears at once."

Research into political discourse has shown that heightened linguistic intensity — including hyperbole and superlatives — can correlate with detachment from reality, incitements to violence, and even real-world unrest (Los Angeles Times, 2024). In recent years, the United States has seen rising civil tension and widening socioeconomic divides, exacerbated by Donald Trump's fierce public rhetoric. His campaign slogan, Make America Great Again, is itself anchored in a superlative, implying both an existing decline and a promised restoration for the USA.

My research question asks whether the type and frequency of superlatives in inaugural speeches reflect wider political and social sentiment. To examine this, I used the full corpus of 60 U.S. Presidential Inaugural Addresses (1789–2025), sourced from the public domain texts of the U.S. Government Publishing Office (C-SPAN, 2021). Using Python's NLTK library, I tokenised the speeches, extracted superlatives through POS-tagging, and analysed their use through concordances and visualisations.

Exploratory Analysis

My initial exploration showed that a small cluster of superlatives — best, greatest, and highest — dominates the corpus. These appear far more frequently than any others, with no strong correlations between overall usage, political party, or year. More revealing is the evolution in how presidents employ these forms over time.

Monroe (1817) and Van Buren (1837) rely heavily on dimensional superlatives such as slightest, remotest, and firmest — terms rooted in measurement and degree, reflecting a nation focused on boundaries and stability. Coolidge (1925), a Republican, marks a transition, mixing dimensional and evaluative forms — best, greatest, wisest — suggesting growing economic confidence. Clinton (1993) uses predominantly evaluative superlatives centred on capability and power — strongest, mightiest, deepest. This trajectory culminates with Trump, whose addresses rely almost exclusively on high-impact evaluative terms, framing superlatives as emotional assertions of supremacy rather than contextual descriptors. In his 2017 inaugural, Trump described America as having been run by "a small group in our nation's capital" who had reaped "the rewards" while the people bore "the costs" — a framing built on implied decline. By 2025, the register had intensified further, with phrases such as the greatest nation and the greatest economy deployed not as aspiration but as assertion.

The Rhetorical Power of "The"
Another clear pattern is the persistent use of the definite article in phrases like the best or the greatest. This small grammatical choice shifts a superlative from personal judgement to fixed certainty, transforming a subjective opinion into an authoritative claim. When paired with evaluative forms, it creates an impression of absolute truth and positions the speaker as the final arbiter of national identity or purpose. In an inaugural address, this reinforces a narrative of unshakeable confidence and ideological clarity.

The Greatest
Across eras, the evolution of the greatest is striking. Early presidents used the phrase in moral and civic contexts — the greatest good, the greatest trial. After World War II, it begins to precede measurable outcomes such as progress, achievements, and advances, reflecting America's growing focus on global competition.
By the late twentieth century, the phrase becomes a direct claim of national supremacy. Reagan and Trump use the greatest to assert dominance — the greatest military, the greatest nation — marking a shift from moral aspiration to unambiguous superiority.

Limitations
This analysis has several limitations worth acknowledging. Superlatives are not the only linguistic marker of intensity in political speech — hyperbole, repetition, and modal verbs all contribute to rhetorical force and are not captured here. The analysis also relies on the accuracy of NLTK's POS-tagger, which may have missed some superlative forms or misclassified others. Finally, inaugural addresses represent only one type of political speech, delivered in a highly formal context with specific rhetorical conventions. Findings may not generalise to campaign speeches, debates, or other political communication formats.

Conclusion
Overall, the shifting use of superlatives across presidential history reflects changing priorities in how leaders assert authority and define national identity. What begins as moral guidance becomes a language of progress, and ultimately a tool for proclaiming supremacy. Trump's rhetoric across both inaugurals illustrates how rapidly this pattern can intensify — and how superlatives, once grounded in civic aspiration, can become instruments of political assertion.

References
Beard, Adrian. The Language of Politics. London: Routledge, 2000.
C-SPAN. C-SPAN Inaugural Address Corpus: US Presidential Inaugural Addresses 1789–2021. Compiled by Kathleen Ahrens, 2021.
Pyatkin, Valentina, Bonnie Webber, Ido Dagan, and Reut Tsarfaty. "Superlatives in Context: Modeling the Implicit Semantics of Superlatives." arXiv preprint, 2024. https://arxiv.org/abs/2405.20967.
"Trump Speech Rhetoric: Superlatives." Los Angeles Times, September 19, 2024. https://www.latimes.com/opinion/story/2024-09-19/trump-speech-rhetoric-superlatives.
"Why Superlatives Are the Absolute Worst (Unless You're Donald Trump)." The Guardian, April 15, 2016. https://www.theguardian.com/media/mind-your-language/2016/apr/15/why-superlatives-are-the-absolute-worst-unless-youre-donald-trump.
"How Trump Uses Superlatives." Esquire, accessed March 2026. https://www.esquire.com/news-politics/a15335203/trump-superlatives/.

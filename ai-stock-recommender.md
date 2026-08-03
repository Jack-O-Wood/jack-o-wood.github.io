---
layout: page
title: AI Stock Recommender
description: An AI app for personalized stock recommendations
image: assets/images/ai-stock-recommender.png
nav-menu: false
show_tile: false
---

<div id="main" class="alt">
<section id="one">
<div class="inner">

<header class="major">
<h1>AI Stock Recommender</h1>
</header>

<span class="image main"><img src="assets/images/ai-stock-recommender.png" alt="AI Stock Recommender" /></span>

<h2>Project Overview</h2>

<p>An AI-powered financial analytics app that generates personalized stock recommendations. It synthesizes fundamental analysis, historical pricing trends, and news-sentiment analysis, then weighs the result against user-defined preferences such as industry, market cap, and risk tolerance. The project was built as a technical demonstration of applied NLP and LLM synthesis, and is not financial advice.</p>

<div class="row">
<div class="6u 12u$(small)">
<h3>Tools Used</h3>
<ul>
<li>Python</li>
<li>Gemini API</li>
<li>Pandas</li>
<li>NLP</li>
</ul>
</div>
<div class="6u$ 12u$(small)">
<h3>Techniques</h3>
<ul>
<li>News-sentiment analysis</li>
<li>Fundamental analysis</li>
<li>Price-trend analysis</li>
<li>Preference-based ranking</li>
<li>LLM synthesis</li>
</ul>
</div>
</div>

<hr class="major" />

<h2>How It Works</h2>

<p>A user sets their preferences, including target industry, market-cap range, and risk tolerance. The app pulls the relevant fundamentals, historical price history, and recent news for candidate stocks, runs sentiment analysis over the news coverage, and uses the Gemini API to synthesize those signals into a recommendation matched to the user's stated profile. The goal is to combine quantitative fundamentals with qualitative news signal in a single, personalized read.</p>

<hr class="major" />

<h2>Results</h2>

<!-- Add detail here when ready: example recommendation output, the universe of
     stocks covered, and any evaluation of recommendation quality.
     Optionally add an app screenshot:
<span class="image main"><img src="assets/images/ai-stock-app.png" alt="Stock recommender app" /></span>
-->

<p>The app demonstrates an end-to-end flow from user preferences and raw market data through sentiment scoring to a synthesized, explainable recommendation.</p>

<hr class="major" />

<ul class="actions">
<li><a href="https://huggingface.co/spaces/Jack-O-Wood/AI-Stock-Recommender" class="button special">Try the App</a></li>
<!-- Add the repo link when ready:
<li><a href="GITHUB_REPO_URL" class="button">View on GitHub</a></li>
-->
<li><a href="projects.html" class="button">Back to Projects</a></li>
</ul>

</div>
</section>
</div>

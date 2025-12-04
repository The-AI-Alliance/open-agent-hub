---
layout: single
title: Get Involved!
permalink: /contributing/
hidden: false
header:
  overlay_color: "#FEFEFE"
  overlay_image: /assets/images/marketplace1.png
excerpt: >
  How to Get Involved.<br/>
nav_order: 100
has_children: false
---

{% comment %}
Keep the following anchor in case you change the section "Join..." text. 
The link may be used as a "default" in various places.
{% endcomment %}
<a name="join-this-project"></a>

{% if site.newsletter %}[Sign up for our newsletter]({{ site.newsletter.url }}){:target="newsletter" .btn .btn--primary}{% endif %} {% if site.community %}[Join our community]({{ site.community.url }}){:target="community" .btn .btn--primary}{% endif %}

# How to Contribute to the Open Agent Hub

We welcome your contributions! Each [hub project]({{site.baseurl}}/) has information about getting involved, such as contributing pull requests.

For general information about contributing to AI Alliance projects, visit the [`community`](https://github.com/The-AI-Alliance/community/){:target="community"} repo, specifically the [`CONTRIBUTING`](https://github.com/The-AI-Alliance/community/blob/main/CONTRIBUTING.md){:target="community"} page for general information about contributing. 

See also the full list of projects [here](https://the-ai-alliance.github.io/){:target="aia-github"} to find others that might interest you.

## Contributing to the Open Agent Hub Website

The sources for this website are in the [`docs`](https://github.com/The-AI-Alliance/open-agent-hub/tree/main/docs){:target="repo-docs"} directory in the [website repo](https://github.com/The-AI-Alliance/open-agent-hub/tree/main){:target="repo"}. 

This documentation is built with [GitHub Pages](https://pages.github.com/){:target="github-pages"}, which uses [Jekyll](https://github.com/jekyll/jekyll){:target="gh-jekyll"} to serve the website. We use the [Minimal Mistakes]({{ site.theme_url }}){:target="mm"} Jekyll theme. See the repo file [`GITHUB_PAGES.md`](https://github.com/The-AI-Alliance/open-agent-hub/tree/main/GITHUB_PAGES.md){:target="_blank"} for more information.

Notice that every page on this website has an _Edit this page on GitHub_ link to the corresponding location for the page in the GitHub repo, making it easy to view a page, then go straight to the source, make edits, and submit a [pull request](https://github.com/The-AI-Alliance/open-agent-hub/pulls){:target="prs"}! This is the best way to help us fix typos and make other small improvements.

You can also post [discussion topics](https://github.com/The-AI-Alliance/open-agent-hub/discussions){:target="discussions"} and [issues](https://github.com/The-AI-Alliance/open-agent-hub/issues){:target="issues"}. See also the [project board](https://github.com/orgs/The-AI-Alliance/projects/41){:target="dashboard"}.

Finally, you can send your suggestions via [email](mailto:contact@thealliance.ai?subject=Questions about the Open Agent Hub).


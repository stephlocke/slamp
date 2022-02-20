# SLAMP ⚡

SLAMP is an [AMP](https://amp.dev) based [Hugo](https://gohugo.io) theme that leverages the [Google AMP CSS Framework](https://www.ampcssframework.com/) to make a minimalist [bootstrap](https://getbootstrap.com) style site.

## AMP

AMP is a limited subset of functionality intended to deliver superlight pages quickly and cosnistently. The use of AMP can lead to enahcned SEO and better engagement via social media.

Make sure to use only [AMP based components](https://amp.dev/documentation/components/) for stuff like images!

-[ ] Add AMP component partials and shortcodes

You can configure which AMP JS components and templates are available in your config file.

-[ ] Document config better

## Functionality

Key areas of functionality coded into this theme include:

1. The generation of a full JSON index of the site used for search systems like Azure Cognitive Search
2. Dynamic homepage based on config values of sections to include. Sections to be included can either be based on active or latest published date attributes. Only include sections in the active options if you're using a boolean `active` parameter in the content
3. Extended SCSS and asset pipelines. Use the custom.scss file as an example to giving yourself compelte control over the style (but remember it's AMP - there's a CSS size limit!)
4. Purposefully cookie-less! Intended to be used with privacy friendly logging solutions like Netlify Analytics so the site loads quicker and you track less

-[ ] Implement search page and field
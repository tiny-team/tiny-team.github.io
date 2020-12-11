+++
title="Hello Zola"
date=2020-12-12
+++

This blog is built with [Zola](https://getzola.org) static generator, a classless CSS framework [awsm.css](https://github.com/igoradamenko/awsm.css) and Github Actions.

### Zola

Zola is a recent static generator written in Rust language. It generates pages fast, has a number of out of the box features for developers, like RSS, SASS compilation, syntax highlighting, search, taxonomies and more. Suffice it to say, it is a fairly full featured static generator.

### awsm.css

Zola has support for themes and has a decent documentation to get you started. Recently I learned about the existence of classless CSS frameworks which are a perfect fit for static blogs, especially developer blogs. Of all, I found awsm.css to be most compatible to my needs. 

I just dropped in the `unpkg` reference in the base layout file with a few lines for the mobile-first design approach. That is it. Took me 2 minutes to do this. No need to get into git submodules, configure and tweak the theme etc.

I like it so much that I am contemplating using it on my personal blog.

### Github Actions

Github Actions is a CI/CD offering by github. I have been meaning to try Github Actions out for a while and this blog seemed like the best scenario to do so. Basically the idea is to build a blog using Github Actions. In the near past, I have used Travis CI to do this, but given the recent news about Travis CI's support for OSS projects ending soon, I thought it to be another reason to jump into Actions.

I used the [recommended](https://www.getzola.org/documentation/deployment/github-pages/#github-actions) deploy action to get me started. It took me a while to get it up and running, but seemed like a good learning activity and fun overall.
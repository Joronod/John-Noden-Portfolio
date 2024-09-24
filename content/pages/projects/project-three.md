---
type: ProjectLayout
title: NC News
colors: colors-a
date: '2024-07-01'
client: Northcoders
description: >-
  NC News is a web application built using React.js that allows users to browse
  articles, read and comment on them, and interact with the community through
  voting on articles and comments. It leverages the NC News API to fetch and
  display data dynamically.
featuredImage:
  type: ImageBlock
  url: /images/Screenshot 2024-09-24 121631.png
  altText: Project Home Page
  caption: NC News is a Full Stack application built using React.JS.
media:
  type: ImageBlock
  url: /images/Screenshot 2024-09-24 121631.png
  altText: Project image
  caption: ''
bottomSections:
  - type: MediaGallerySection
    title: NC News Features
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/Screenshot 2024-09-24 122821.png
        altText: A look at "view all articles"
        caption: View all articles
        elementId: ''
      - type: ImageBlock
        url: /images/Screenshot 2024-09-24 122856.png
        altText: 'A look at an individual article, as well as the comments section'
        caption: An individual article and its comments
        elementId: ''
    colors: colors-c
    spacing: 16
    columns: 2
    aspectRatio: '1:1'
    showCaption: false
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
---
In the Header, as well as a link to the Homepage, users can access the Log In section, where selecting one of the users will update the Global Context, and allow for additional functionality throughout the website, such as posting comments and Upvoting or Downvoting articles.

The homepage of the article is designed to provide three random articles in the Featured Articles section. It also generates the Topics of the articles, so users can select one to view all article that have this topic.


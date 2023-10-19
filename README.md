# Docusaurus Template

## Steps necessary post deployment

## Github Requirements

### Enable Discussions

1. Enable discussions on the repository, leverage the default options.

### Enable giscus for comments blog and docs

1. Update **src/theme/DocItem/Content/index.js** and **src/theme/BlogPostPage/index.js**

Including the following
    - id=
    - repo=
    - repoId=
    - category=
    - category Id=

## Netlify Requirements

### Disable pretty URLs

### Algolia Search

#### Configure Search

1. Submit details @ [Docsearch](https://docsearch.algolia.com/apply/)
2. Update docusaurus.config.js with details

Including the following
    - appId
    - apiKey
    - indexName
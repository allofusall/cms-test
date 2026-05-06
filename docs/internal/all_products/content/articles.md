---
title: Articles
description: All about creating content in long-form, standalone articles.
tags: "[Articles, Stuff]"
applies_to: "[business,enterprise]"
author: Joel Bradley
admin_required: true
no_pdf: false
status: published
layout: xml_freshdesk.liquid
---
## Overview

Articles are a stand-alone content type meant for sharing long-form knowledge that doesn't fit well in the Q&A format. Articles show up in search results, and share many other features with questions. You can upvote articles, comment on them, add them to a Collection, and more. 

> Articles are available on Stack Internal Enterprise and Business (not Basic or Free). [Find your plan](https://support.stackenterprise.co/support/solutions/articles/22000294292).

<div id='hi'>To view or manage articles, click **Articles** in the left-hand menu.</div>

## The articles page

The articles page shows a list of articles on your site. You can filter and sort the results by the following:

- Name
- Author
- All articles, your articles, or articles you can edit
- Sort by newest or recently edited

You can use the `is:article` operator in the Search box to restrict a search to articles only. For example: the search "python is:article" will return articles (not questions or answers) that contain the word "python".

## View an article

When you click on an article to view it, Stack Overflow Internal displays helpful information and statistics about the article. This includes the date the author wrote it, when it was last edited, how many times users have viewed the article, and the approximate time it will take to read.

![Article overview](/public/images/internal/all_products/content/articles.md/articles-04.png)

```javascript
if (something >= nothing)
    alert('Yep')
```

## Permissions

Admins and moderators have access to Ingestion features by default. Regular users can also access Ingestion features if their reputation exceeds the admin-set threshold.


| Permissions | Site role |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Admin | - Enable/disable Ingestion - Enable/disable and configure connectors - Manually upload files for Ingestion - Upload files to API endpoint for ingestion - Delete uploaded files and resulting content - Set end user reputation threshold - Review, edit, delete, and publish AI-generated content |
| Moderator | - Upload files to API endpoint for ingestion - Manually upload files for Ingestion - Review, edit, delete, and publish AI-generated ontent |
| End user (by reputation threshold) | - Upload files to API endpoint for ingestion - Manually upload files for Ingestion - Review, edit, delete, and publish AI-generated content |



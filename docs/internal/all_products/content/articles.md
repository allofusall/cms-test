---
title: Articles
description: All about creating content in long-form, standalone articles.
tags: "[Articles]"
applies_to: "[business,enterprise]"
author: Joel Bradley
admin_required: false
no_pdf: false
status: published
layout: xml_freshdesk.liquid
---
## Overview

Articles are a stand-alone content type meant for sharing long-form knowledge that doesn't fit well in the Q&A format. Articles show up in search results, and share many other features with questions. You can upvote articles, comment on them, add them to a Collection, and more.

Articles are available on Stack Internal Enterprise and Business (not Basic or Free). [Find your plan](https://support.stackenterprise.co/support/solutions/articles/22000294292).



To view or manage articles, click **Articles** in the left-hand menu.

## The articles page

The articles page shows a list of articles on your site. You can filter and sort the results by the following:

- Name
- Author
- All articles, your articles, or articles you can edit
- Sort by newest or recently edited

## Search for articles

In addition to the main articles page, users can find articles through regular keyword searches. Searching by tags also includes articles along with questions and answers. Finally, tag summary pages show articles along with questions and answers.

You can use the `is:article` operator in the Search box to restrict a search to articles only. For example: the search "python is:article" will return articles (not questions or answers) that contain the word "python".

You can search for articles by type, by including the type as if it were a tag. For example: the search "python is:article [how-to-guide]" will return articles that contain the word "python" and are of the how-to-guide article type. You can use square brackets to search for these four article types:

- [knowledge-article]
- [how-to-guide]
- [announcement]
- [policy]

## View an article

When you click on an article to view it, Stack Overflow Internal displays helpful information and statistics about the article. This includes the date the author wrote it, when it was last edited, how many times users have viewed the article, and the approximate time it will take to read.

![](/public/images/internal/all_products/content/articles.md/articles-01.png)

The article view also shows the tags associated with the article and the avatar of the author. If the article's author is a subject matter expert in any of the associated tags, you'll see "Article authored by a subject matter expert in [tag]" above the article title. When you see this line, you'll know the article was written by a user recognized for their knowledge of the topic.

### Article edit timeline

Certain users can make changes to articles, and Stack Overflow Internal tracks and records these changes over time. To see edits made to an article, click its **timeline** button.

![](images/articles/articles-02-2.png)

The article Timeline page shows the date of each edit, who performed it, and a comment describing the edit. Click **Show vote summaries** to show user voting history along with the article edits; click **Hide vote summaries** to hide voting history.

![](images/articles/articles-03.png)

To see the actual edits performed, expand any edit row by clicking its **gray triangle** button. The detailed edit view shows deleted text with red highlights, and added text with green highlights.

![](images/articles/articles-04.png)

## Create an article

To create an article, click **Articles** in the left-hand menu. Click **Create a new Article** to go to the article creation page. When editing, articles have the same auto-save feature as Q&A posts.

Give your article an informative title, and pick from one of the four article types. Article types give your team members a general idea of the type of content within the article:

- Knowledge Article
- Announcement
- How-To Guide
- Policy

Pick at least one content tag to classify your article. You can add up to four tags.

Add the main content of the article. Try copy-pasting existing documents you have on other platforms right into the editor to save time and automatically convert them into the Markdown format. You can also upload images, use lists, add code snippets, and much more. If you link to questions on your team within the article, those questions will also be listed on the sidebar to the right of your article’s content.

### Article permissions

By default, anyone will be able to edit your article. To change editing permissions, click **Permission settings**.

![](images/articles/articles-05.png)

From the Permissions settings menu that appears, click an option to grant editing permissions to only yourself, yourself and selected users or groups, or all users. Click **Update settings** to save your selection.

### Publish an article

When you’re done editing, click **Publish article** (Stack Internal Business) or **Post article** (Stack Internal Enterprise) to publish your article.



Stack Internal Business users can also save a new article as a draft (which is not immediately published). See the [Article drafts](#article-drafts-(stack-internal-enterprise-and-business-only)) section below.



## Link to sections within articles

In addition to linking to the beginning of an article with its base URL, you can also link directly to headings inside an article. Stack Overflow Internal automatically generates links for article headings (HTML levels H1-H6). You can see these anchor links next to each article heading.

![](images/articles/articles-06.png)

Click any heading to load its link into your browser's address bar. You can then copy and save the resulting URL (with heading link) to link directly to that heading in the article.

## Add an article to a collection

While viewing an article, you can add it to a Collection by clicking the **three dots** button in the upper-right corner. Select **Add to a collection**. You can also add one or more articles to a Collection from inside the Collection itself.

## Give feedback on an article

Once your article is published, other users can provide feedback to the author and editor(s) of the article. This allows users to highlight its usefulness, similar to upvoting on questions.

To mark an article as useful, click the **upvote** button. To provide feedback to the author of the article, click the **pencil and note** (feedback) button.

![](images/articles/articles-07.png)

Clicking the feedback button will show the "Provide feedback" box.

![](images/articles/articles-08.png)

Select the type of feedback you're providing from the following options:

- Out of date
- Incorrect
- Needing more detail or context

Use the text box to add additional details about your feedback.

Click **Submit feedback** to save your feedback. Stack Overflow Internal will then notify the author so they can address the feedback.

Feedback is only visible to the author and editor(s) of the article. If they click on the feedback notification, or edit the article, they’ll see the feedback in the right sidebar. Clicking any checkmark resolves that feedback item.

Article authors receive reputation points for upvotes on articles, just like for Q&A posts.

## Article drafts (Stack Internal Enterprise and Business only)

In addition to publishing a new article immediately, you can also save it as a draft. This allows you (and collaborators, if desired) to write and edit your article before you publish it for all users to read.

To save a new article as a draft, click **Save as draft**.

![](images/articles/articles-09.png)

Draft articles show a "Draft" icon, both in the articles list and on the article edit page.

![](images/articles/articles-10.png)



Only the author and those with editing permissions can see draft articles in the articles list.



You can filter the articles list to show only your drafts by selecting **Your drafts** in the **Permissions** select menu. This view will also show draft articles that other authors have given you permission to edit.

![](images/articles/articles-11.png)

You can continue to revise a draft article by clicking **Edit article**, making your edits, and clicking **Update draft**.

![](images/articles/articles-12.png)

To change permissions while editing a draft article, click **Permission settings**. The Permission settings pop-up menu will appear.

![](images/articles/articles-13.png)

You can choose to grant editing permission to the article's owner only, or the owner plus additional users and/or user groups. If you want to allow additional editors, choose the second option to reveal the **Search by name** box. You can then search for and select users and user groups by name.

When you add editors to a draft article, Stack Overflow Internal will alert them with a message in their "For you" inbox. That message will include a link to the draft article.

There's no limit to how many times you can edit a draft article. Each time someone updates a draft article, Stack Overflow Internal generates a "For you" alert for the author and all editors.

When you're ready to publish your draft article, click **Publish article** on the article edit page. Once you publish an article, you can't take it back to draft status or unpublish it. You can continue to edit it as a published article, or delete it with the **trash can** button. You can also delete a draft article, before publishing, with the **trash can** button.

## Delete an article

You can delete an article you've written to make it permanently inaccessible from the site. To delete an article, view the article then click **Edit**. Click **Delete**, and confirm that you wish to delete the article.



Stack Internal Enterprise users can recover the contents of a deleted article if they know its ID. See the [Recover content from a deleted article](#recover-content-from-a-deleted-article-(stack-internal-enterprise-only)) section below.



## Recover content from a deleted article (Stack Internal Enterprise only)

When you delete an article, Stack Internal Enterprise permanently makes that article inaccessible—but it doesn't remove it from the database. You can still access the deleted article's revision history, which allows you to see its content. You can then copy and paste the article's content to a new article.

To see an article's revision history, you need the article's ID. If you didn't save the article ID before deletion, it may exist in your browser's history. If you can't find it in your browser history, see if someone in your company has recently accessed the article and can provide you the URL.

Once you have the article ID, you can access the revisions page of the article by putting the article ID into this URL: https://[your_site]/posts/[article_ID]/revisions. The article's revision page will appear. It lists all versions of the article, starting with the most-recent (highest-numbered) version.

If your article has no revisions, copy all the content from the top of the page (version 1). Paste the content into a new article, and format as needed.

If your article has multiple versions, click Side-by-side to show the latest version (and no inline changes) on the right side of the screen. Select and copy the content from the desired version, which is usually the latest version at the top of the page. Paste the content into a new article, and format as needed.

## Retrieve articles with the API (Stack Internal Enterprise only)

Stack Internal Enterprise users can use the Stack Overflow Internal API `/articles` endpoint to retrieve articles on their site. For more information on the API, check out our [API v3 for Stack Internal Enterprise](https://support.stackenterprise.co/support/solutions/articles/22000294545) article.
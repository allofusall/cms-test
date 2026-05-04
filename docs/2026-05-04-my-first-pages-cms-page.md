---
title: Ingestion File Upload User Guide
description: How to upload files to your site's Ingestion tool.
tags: "[Content, Ingestion]"
applies_to: enterprise
author: Loren Alldrin
admin_required: true
no_pdf: true
status: published
layout: xml_freshdesk.liquid
---
## Overview

Stack Internal's content ingestion feature leverages the power of AI to quickly turn your internal documents into high-quality content on your Stack Internal site. This allows you to take static knowledge scattered across your organization and make it dynamic, accessible content your users can easily locate and integrate into their workflows.

This is the user guide for the ingestion of "ad hoc" uploaded files. For a concise overview of the full Ingestion process, read the [Ingestion Quickstart Guide](https://support.stackenterprise.co/support/solutions/articles/22000294808).

## The Ingestion dashboard

To access your site's Ingestion controls, click **Ingestion** in the left-hand menu under the "MANAGE" heading.

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-01.png)

The Ingestion dashboard appears, showing the current status and recent history of Ingestion jobs.

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-02.png)

## File ingestion

To add a new file for ingestion, click **Upload files** in the upper-right corner of the Ingestion dashboard.

Drag one or more files into the "File Ingestion" box, or click **choose your files** to browse for files. You can upload a file in any of the supported file types.

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-03.png)

Stack Internal file Ingestion supports the following file types.


| File type | File extension |
| --------------------------------- | ------------------------------- |
| Microsoft Word document | .docx |
| Microsoft Excel spreadsheet | .xlsx |
| Microsoft Powerpoint presentation | .pptx |
| PDF document | .pdf |
| Image file | .jpeg, .jpg, .png, .heif, .tiff |
| Web page | .html |
| Markdown or plain text file | .md |


On successful upload, you'll see a green confirmation message at the top of the page. Click **View status** to see the status of your upload. You can also click **Done** at the bottom of the page to view the Ingestion job list.

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-04.png)

You should see your new file listed on the Ingestion dashboard with a status of "Queued" or "Processing".

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-05.png)

When the ingestion process is complete, you'll see your document's status listed as "Completed". You'll also see the number of Q&A pairs the Ingestion process created from your uploaded content.

![](images/ingestion_file_upload_user_guide/ingestion_file_upload_user_guide-06.png)

The newly-created Q&A pairs are in draft status, ready for review and publishing. You can click the file name in the "Source" column to go to the Ingestion review tasks page. To learn about the content review process, read the [Ingestion Review User Guide](https://support.stackenterprise.co/support/solutions/articles/22000294807).



Until a user reviews and publishes new Q&A pairs, they will be visible only to content reviewers.


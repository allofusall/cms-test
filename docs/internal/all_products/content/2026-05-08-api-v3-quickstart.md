---
title: API v3 Quickstart
description: Get up to speed quickly with the Stack Overflow Internal API v3.
tags: "[API,Quickstart]"
applies_to: "[basic,business,enterprise]"
author: Jamie Lowery
admin_required: false
no_pdf: false
status: draft
layout: xml_freshdesk.liquid
---
Stack Overflow's API v3 opens up your Stack Internal site to external integrations, allowing you to access your data, change content on your site, build reports, and much more.

You can access API v3 at ++https://[your_site].stackenterprise.co/api/v3++ (replace [your_site] with your site's subdomain). There you'll find a complete list of all API endpoints. This URL is also the base URL for all API v3 calls.

In this quickstart, you'll use the free Postman online tool to access API v3 and retrieve data.

## Register an API application

Start by creating and registering a new API application on your Stack Overflow site. This generates a unique API key and grants that key access to the API.

***NOTE:** Stack Overflow assigns ownership of the API application to the user who created it. The resulting API key will be able to access only the data the user would see while using the site.*

To register a new API application:

1. Log into your Stack Internal Enterprise site.
2. Click on your avatar (profile picture) in the top navigation bar.
3. Click **Settings**.
4. Click **API applications** under the "APPS & INTEGRATIONS" heading.



5. Enter a name for your API application in the **Application name** field.
6. Leave **Domain** blank.
7. Click **Register API application**.



8. Copy the **Key** value. This is your API access key. Copy it for use later.



## Use Postman to access the API

1. Go to ++[https://www.postman.com](https://www.postman.com)++ and sign in. If you don't already have an account and workspace, sign up and create them.
2. Add a new request.
3. Ensure that the request type is **GET.**
4. To get question data from your Enterprise instance, enter this endpoint URL: ++https://[your_site].stackenterprise.co/api/v3/questions++.



5. On the "Authorization" tab for your new request, set **Auth Type** to **Bearer Token**.



6. Paste your new Stack Internal API key into the **Token** field.



7. Optional: click **Save** if you want to return to this request in the future.
8. Click **Send** to make the request.

  


You should see a list of questions from your Stack Overflow site.



## Swagger UI API documentation

Your Enterprise site has interactive API documentation using Swagger UI. This documentation gives you information on all the API v3 endpoints, and also lets you make test calls to each endpoint. You can access your site's Swagger UI API interface at ++https://[your_site].stackenterprise.co/api/v3++ (replace [your_site] with your site's subdomain).

  
For more information on API v3 and the Swagger UI interactive documentation, read the ++[Stack Overflow Internal API v3](https://support.stackenterprise.co/support/solutions/articles/22000294545)++ article.
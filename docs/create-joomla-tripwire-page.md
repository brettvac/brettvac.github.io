---
layout: articles
title: How To Create A Tripwire Funnel In Joomla!
description: Here's a quick way to create a tripwire sales funnel inside Joomla! CMS
---
# How To Create A Tripwire Funnel In Joomla!

If you're new to sales funnels, all you need to know is that they are a series of pages to quickly take a person through the AIDA framework.

In other words, it's a way to turn a prospect into a paying customer.

One of the fastest ways that you can do this is through a tripwire funnel, and here's how you can set one up on your Joomla! Site.

## What Is A Tripwire Funnel?

A tripwire funnel, also known as an [ATM accelerator funnel by Miles Beckler](https://www.milesbeckler.com/pages/atm-funnel/), is a page that contains a small ask, which is immediately followed by a product pitch when the user consents to the first ask.

![An example of a sales page from a funnel](/brettvac.github.io/assets/Sales-page-example.png)

In other words, the first page requests something simple, usually an e-mail address, and if the user successfully inputs the information, the user is immediately hit with a paid offer, in the form of a sales page.

You may think that tripwire funnels usually require fancy funnel software, but you can set one up on your Joomla! site relatively quickly.

## How To Set Up A Tripwire Funnel On Joomla

All you need to do to set up a tripwire funnel on Joomla is create a landing page, publish a module to collect the e-mail address, and publish your tripwire offer. 

Let's look at those steps in detail.

### Create A Landing Page

First, you'll want to create a landing page, to send traffic to and collect e-mail addresses. 

You can create a simple article in Joomla, and a menu item that points to the article.

Go to Content \> Articles, and create a new article. 

This is where you'll put the sales copy for your opt-in page. 

You can also add a product image mockup as a main article image, to enhance your landing page and increase conversions.

![Create a Joomla article](/brettvac.github.io/assets/Joomla-article-creation.png)

Then, go to Menus \> Main Menu (or whatever menu you like) and create a menu item that points directly to the article.

If you followed these steps correctly, you should end up with a landing page that will convert like crazy and that looks somewhat like the
example below.

### Create A Sales Page

Next, you'll need to create a sales page that outlines your (paid) offer. 

This is a super straightforward step, as you just need to repeat the previous steps to create a sales page and a menu item.

You'll need to keep note of the name of your menu item for the next step.

### Create A Capture Mechanism

To actually collect the e-mail addresses and send your unwitting user to your \$19.99 offer, you'll need some sort of mechanism to capture the e-mails, and redirect them to your sales page.

Luckily, with Joomla!, this is a piece of cake with the [Sign Up Chimp Module](https://naftee.com/signupchimp.html).

Install the latest version of the [Sign Up Chimp Module](https://naftee.com/signupchimp.html) by going to Extensions: Install

![Install the Sign Up Chimp Module](/brettvac.github.io/assets/Sign-up-chimp-installation.png)

Next, you'll want to go to Content \> Modules and select Sign Up Chimp.

This is where you'll enter your credentials from MailChimp, optionally add tags to your subscribed contacts, and, crucially, set a redirect after successful subscription.

![Configure the Sign Up Chimp Module](/brettvac.github.io/assets/Sign-up-chimp-configuration.png)

### Publish Your Tripwire

Then, you'll need to publish this module to your opt-in page at a module position which is below your article text, such as main-bottom or whatever your template calls it.

And that's it! Start sending traffic to your opt-in page, collect e-mails, and sell millons\$\$\$ worth of product.

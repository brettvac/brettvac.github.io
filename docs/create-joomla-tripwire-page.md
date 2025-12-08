---
layout: articles
title: How To Create A Tripwire Sales Funnel Landing Page In Joomla!
description: Here's a quick way to create a landing page as part of a tripwire sales funnel inside Joomla! CMS
---
If you're new to sales funnels, all you need to know is that they are a series of pages to quickly take a person through the AIDA framework.

In other words, a sales funnel offers a way to turn a prospect (a random person interested in your stuff) into a paying customer.

One of the fastest ways that you can convert a prospect to a customer is through a tripwire sales funnel. Here's how you can set this mechanism up on your Joomla! website.

## What Is A Tripwire Sales Funnel?

A tripwire sales funnel, also known as an <a href="https://www.milesbeckler.com/pages/atm-funnel/" target="_blank" rel="noopener">ATM accelerator funnel by Miles Beckler</a>, consists of a landing page that contains a small ask, or pitch, in exchange for some information (usually an e-mail address). The tripwire means the landing page is immediately followed by a product pitch when the user consents to the first ask.

### Example Landing Page
Here's what a landing page, or the first step in a tripwire sales funnel, might look like. 

![An example of a sales page from a funnel](/brettvac.github.io/assets/Sales-page-example.png)

In other words, the first page of a tripwire sales funnel requests something simple, usually an e-mail address, and if the user successfully inputs the information, the user is immediately hit with a paid offer, in the form of a sales page.

You may think that tripwire funnels usually require fancy funnel software, but you can set one up on your Joomla! site relatively quickly.

## How To Set Up A Tripwire Funnel On Joomla

All you need to do to set up a tripwire funnel on Joomla is create a landing page, publish a module to collect the e-mail address, and publish your tripwire offer. Here are the steps in order:

1. Create a landing page which can be an article or something you created with a page builder.
2. Publish a second page, which is a sales page containing your tripwire offer.
3. Publish a module on the first landing page to collect the e-mail address and redirect to your tripwire offer upon successful submission.

Let's look at those steps in detail.

### Step 1. Create A Landing Page

First, you'll want to create a landing page, to send traffic to and collect e-mail addresses. You can create a simple article in Joomla, and a menu item that points to the article.

Go to Content \> Articles, and create a new article. This is where you'll put the sales copy for your opt-in page. 

You can also add a product image mockup as a main article image, to enhance your landing page and increase conversions.

![Create a Joomla article](/brettvac.github.io/assets/Joomla-article-creation.png)

Then, go to Menus \> Main Menu (or whatever menu you like) and create a menu item that points directly to the article.

If you followed these steps correctly, you should end up with a landing page that will convert like crazy and that looks somewhat like the
example below.

### Step 2. Create A Sales Page For Your Tripwire Offer

Next, you'll need to create a sales page that outlines your (paid) offer. 

This is a super straightforward step, as you just need to repeat the previous steps to create a sales page and a menu item.

You'll need to keep note of the name of your menu item for the next step.

### Create A Capture Mechanism

To actually collect the e-mail addresses and send your unwitting user to your \$19.99 offer, you'll need some sort of mechanism to capture the e-mails, and redirect them to your sales page.

Luckily, with Joomla!, this is a piece of cake with the <a href="https://github.com/brettvac/Signupchimp" target="_blank">Sign Up Chimp Module</a>.

#### Using The Sign Up Chimp Module

The Sign Up Chimp module is a custom module that publishes a form to collect e-mail addresses and first names on your page, and send that information to MailChimp. The real power behind this module, however, is the redirection mechanism, which allows you to create a tripwire sales funnel.

Install the latest version of the Sign Up Chimp Module on your Joomla! site by going to Extensions: Install and using this URL: [https://github.com/brettvac/signupchimp/releases/latest/download/mod_signupchimp.zip](https://github.com/brettvac/signupchimp/releases/latest/download/mod_signupchimp.zip).

![Install the Sign Up Chimp Module](/brettvac.github.io/assets/Sign-up-chimp-installation.png)

Next, you'll want to go to Content \> Modules and select Sign Up Chimp. This is where you'll enter your credentials from MailChimp, optionally add tags to your subscribed contacts, and, crucially, set a redirect after successful subscription.

![Configure the Sign Up Chimp Module](/brettvac.github.io/assets/Sign-up-chimp-configuration.png)

You'll want to set the redirect to your sales page offer, of course, not <a href="https://naftee.com/list-of-phobias.html">a silly page containing a list of phobias</a>.

### Publish Your Tripwire

Then, you'll need to publish this module to your opt-in page at a module position which is below your article text, such as main-bottom or whatever your template calls it.

And that's it! Start sending traffic to your opt-in page, collect e-mails, and sell millons\$\$\$ worth of product.

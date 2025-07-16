---
layout: default
description: An extension that displays a MailChimp signup form on your Joomla! website which submits with AJAX
---

# Sign Up Chimp
![Sign Up Chimp Logo](Sign-Up-Chimp.jpg)

Are you are interested in building a list and marketing your products? The first step is to capture e-mails from your website traffic, and you can do that using this module.
 
This is your first step to turning a sedentary website visitor into a raving Chimp who will lap up your grand slam offers.

## What Is Sign Up Chimp?
Sign Up Chimp is a Joomla extension that provides a seamless integration with MailChimp. 

After installing Sign Up Chimp, you will be able to display a highly customizable sign up form on your website to capture a user's e-mail address and first name, which will be added to your MailChimp account after successful submission. You also have the option to redirect the user, perhaps to a tripwire offer, after the form submits.

You will not find a more elegant and easy-to-use MailChimp Joomla! extension on the Web.

## How To Use Sign Up Chimp
1. Install the module via the Joomla! Extensions Manager. You can install via URL by using this URL:  [https://github.com/brettvac/signupchimp/releases/download/1.2/mod_signupchimp.zip](https://github.com/brettvac/signupchimp/releases/download/1.2/mod_signupchimp.zip)  
2. Navigate to Extensions > Modules and find "Sign Up Chimp".
3. Configure the module settings, including MailChimp API key and list ID. If you want to display a tripwire offer, set the menu item and the delay before redirect.
4. Publish the module in your desired position. Users can now enter their email and first name to subscribe directly from your website.

## Features
- **AJAX Signup** Uses an AJAX-powered form to send subscription data to MailChimp without reloading the page. 
- **Custom CSS Classes** Stylize your form to your heart's content by adding classes to the form elements
- **Error Handling** Displays success or failure messages dynamically.
- **Redirect Option**: Option to redirect users to a tripwire page after successful signup.

## Requirements
This plugin works with Joomla! versions greater than 4.4 and requires PHP 8.1 or later.
You will need a MailChimp account and an API key. [Read about API keys here](https://mailchimp.com/help/about-api-keys/)

## FAQ
**Q:Can I use this plugin with Mailerlite?**  
**A:** No, it's for MailChimp. I might vibe-code a Mailerlite version at some point.

**Q: Why didn't you use Camel casing in your code (i.e. SignupChimp)**  
**A:** Because Camel casing won't work with Joomla's com_ajax component. Because it dynamically creates the name of the ajax function that you're calling based on the module name, com_ajax fails to find your helper file if you use camel casing. It took me days to figure that out.

**Q: This plugin is awesome! Can I send a donation?**  
**A:** Sure! Send your cryptonation to the following wallets:

`BTC 1PXWZJcBfehqgV25zWdVDS6RF2yVMxFkZD`

`Eth 0xC9b695D4712645Ba178B4316154621B284e2783D`

**Q: Got any more awesome Joomla! plugins?**  
**A:** Find them [right here](https://naftee.com)

## Credits
- **MailChimp API v3 wrapper** by [Drew McLellan](https://github.com/drewm) (MIT License)

---
layout: default
description: A Joomla! module to display the path for a specified TF Learn course. 
---

# TF Learnpath Module for Joomla

![TF Learnpath logo](/brettvac.github.io/assets/Tf-Learnpath.jpg)

The **TF Learnpath** module (`mod_tflearnpath`) is a Joomla module designed to display lessons for courses in the **TF Learn** component (`com_tflearn`). 

When you install and configure **TF Learnpath**, it provides a visual representation of course modules and lessons, with support for multiple layouts (block, accordion, or tabs) and access restrictions. Perfect for e-learning websites, this module helps users navigate their learning journey with ease.

## Features

- **Learning Path Display:** Shows course modules and lessons in a clean, organized format.
- **Multiple Layout Options:** Choose between block, accordion, or tabs layouts to match your site’s design.
- **Access Control:** Integrates with `com_tflearn` to check user access, displaying restricted lessons with lock icons.
- **Customizable Styling:** Add custom CSS classes for the module title and icons for completed/incomplete lessons.

## Requirements

- **Joomla Version:** Joomla 4.x or 5.x (for the most recent version of TF Learn)
- **TF Learn Component:** You should have already installed [TF Learn](https://joomlafry.com/joomla-extensions/learn-joomla-extension) and added some courses, modules and lessons.
- **TF Library:** Requires the [Tech Fry Library](https://labs.joomlafry.com/downloads/techfry.zip) to work.
- **PHP Version:** PHP 7.4 or higher.

## Installation

1. **Download or install the Module with this URL**
   - Install via Joomla’s Extension Manager (`Extensions > Manage > Install`) the latest release [from this link](https://github.com/brettvac/TFLearnpath/releases/download/1.0/tflearnpath.zip).
   - The module will check for the TechFry Library during installation and prompt you if it’s missing.

2. **Enable the Module:**
   - Go to `Extensions > Modules`.
   - Search for "TF Learnpath" and click to edit.
   - Set the status to "Published" and assign it to the desired position and menu items.

## Module Parameters

- **Course ID (`course_id`):** Specify the ID of the `com_tflearn` course to display (e.g., `2`).
- **Layout (`path_layout`):** Choose the display style:
  - `block`: Simple stacked layout.
  - `accordion`: Collapsible sections (defaults to all closed).
  - `tabs`: Tabbed navigation.
- **Lesson Order (`lessons_order_col`, `lessons_order_dirn`):** Sort lessons by a field (e.g., `ordering`, `title`) in ascending (`ASC`) or descending (`DESC`) order.
- **Module Title Class (`module_title_class`):** Add a CSS class for the course title (e.g., `text-center`).
- **Icons (`path_incomplete_icon`, `path_complete_icon`, `path_lock_icon`):** Customize Font Awesome icons for lesson states (e.g., `fa-regular fa-square` for incomplete).

### Example Setup

1. Create a course in `com_tflearn` with modules and lessons.
2. In the module settings:
   - Set `Course ID` to your course’s ID.
   - Choose `accordion` layout.
   - Assign the module to a position (e.g., `sidebar-right`) and a menu item.
3. Save and view the frontend—your learning path will display with collapsible sections.

## Features

- **Frontend Display:** The module shows the course title, followed by sections (modules) and their lessons. Lessons are linked to their respective pages in `com_tflearn` if accessible.
- **Access Restrictions:** If a user isn’t enrolled, restricted lessons show a lock icon and message.
- **Customization:** Add custom CSS to style the `.tflearn-path` container, icons, or layout elements.

## Contributions
[TF Learn](https://joomlafry.com/joomla-extensions/learn-joomla-extension) (the best LMS for Joomla!)

## FAQ

**Q: Can I use Podia instead?**  
**A:** I guess so! I've never used that platform.  

**Q:  Can I use TF Learn(path) with Joomla! 3?**
**A:** No, TF Learn only works with Joomla! versions 4 and later. 

**Q: This plugin is awesome! Can I send a donation?**  
**A:** Sure! Send your cryptonation to the following wallets:

`BTC 1PXWZJcBfehqgV25zWdVDS6RF2yVMxFkZD`

`Eth 0xC9b695D4712645Ba178B4316154621B284e2783D`

**Q: Got any more awesome Joomla! plugins?**  
**A:** Find them [right here](https://naftee.com)

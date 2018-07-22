# Categories Vs. Tags

## Description

This lesson explains the differences between categories and tags for WordPress posts and how they can be used to  organize your information. You will learn how to use tags as keywords to help organize and search your posts.

## Objectives

After completing this lesson, participants will be able to:

*   Define "taxonomy" and describe how WordPress implements them.
*   Identify the difference between categories and tags.
*   Create categories and tags.
*   Apply categories and tags to posts.
*   Manage descriptions and slugs for categories and tags.
*   Utilize widgets for category and tag lists.

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [x] Users
* [ ] Designers
* [ ] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [x] Beginner
* [ ] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [x] Demonstration
* [ ] Discussion
* [x] Exercises
* [ ] Feedback
* [x] Lecture (Presentation)
* [ ] Show & Tell
* [ ] Tutorial

## Time Estimate (Duration)

How long will it take to teach this lesson (in minutes)?

20 minutes

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:

*   How to operate [the WordPress dashboard](https://make.wordpress.org/training/handbook/user-lessons/overview-of-the-dashboard/)
*   The difference between [Pages and Posts](https://make.wordpress.org/training/handbook/user-lessons/pages-vs-posts/)
*   Editing Posts
*   Managing [settings](https://make.wordpress.org/training/handbook/user-lessons/settings/)
*   [Adding widgets to the sidebar](https://make.wordpress.org/training/handbook/user-lessons/managing-widgets/)

## Readiness Questions

*   Are you able to log in to WordPress as an administrator?
*   Are you familiar with using the WordPress dashboard?
*   Can you differentiate Pages and Posts?
*   Can you create and edit Posts?
*   Can you add a widget to the sidebar?

## Materials Needed

*   [Twenty Sixteen Theme](https://wordpress.org/themes/twentysixteen/)
*   [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) for sample content, if needed
* [Slides](https://rawgit.com/wptrainingteam/categories-versus-tags/dev/slides/index.html) (included in this repo)

## Notes for the Instructor

*   If students are weak on screening questions, brief explanations may help.
*   Be sure that students have a variety of posts with which to work.
*   If students are using a fresh WordPress installation, they should import the Theme Unit Test Data for sample content.
*   Students should activate the Twenty Sixteen theme in order to follow the lesson, or they should be comfortable using their own theme during the lesson.
*   Students should have **Settings > Permalinks > Common Settings** set to the "Post name" option, to make it easy to view URLs in this lesson. _Note: the Category base and Tag base settings are an advanced topic._

## Have You Thought About...?

* Challenge 1
* Challenge 2

> What could present challenges to delivering this lesson? Is there anything that can be done in advance to prepare for those challenges?
>
> _For example:_
>
> *  What if there’s no internet available?
> *  What if there’s no projector available?
> *  What if a participant doesn’t has a WordPress site to work with?
> *  What if there aren’t enough computers for everyone?
> *  What if no one has the prerequisite skills? What if there are different opinions about the topic?

## Lesson Overview

* First do this
* Then move on to this
* Finish with this

> The plan for the lesson. Outline form works well.
>
> _For example:_
>
> * Talk about what a theme is
> * Demonstrate how to install and activate a theme
> * Practice exercises to have participants find and install a theme on their own site

## Exercises

**Category Hierarchy**

Create a three-level hierarchy of categories with about six items, something like this set of a categories for food:

*   Fruits
    *   Apples
        *   Granny Smith
        *   Red Delicious
    *   Bananas
    *   Strawberries
*   Vegetables
    *   Yams
    *   Potatoes
        *   Yukon Gold
        *   Idaho Russet
    *   Onions
    *   Carrots

Be sure to give your categories descriptions, and assign one or more posts to each. View your categories and the posts in them, and test that you can navigate and access the categories and posts. If you discover problems or issues, review and revise your work.

**Tag Cloud**

Create at least six tags that will be used for a tag cloud. Update ten posts using two or more tags per post, varying the usage of the tags from a low to high frequency. View the tag cloud in the sidebar on the front end of your website.

*   Do your tags stand out?
*   Are some tags displayed larger than others?
*   Can you apply a tag to more posts, so that it's the biggest in the cloud?

## Assessment

**What are categories?**

1.  A method for page and post navigation
2.  A form of taxonomy for grouping posts
3.  A default list of post types including news, services, and blog
4.  A requirement for menus in web design

**Answer:** 2. A form of taxonomy for grouping posts

**What is the best option for associating multiple keywords with posts?**

1.  Links
2.  Categories
3.  Tags
4.  Excerpt

**Answer:** 3. Tags

**Tags can be used on WordPress Pages.**

1. True
2. False

**Answer:** 2. False

**What is a slug for a category or tag?**

1.  The storage area for it's posts
2.  An instant application button
3.  An alternative spelling to redirect typos
4.  The portion of the URL representing its name

**Answer:** 4. The portion of the URL representing its name

**What does a tag cloud provide?**

1.  A list with the most frequently used tags displayed larger
2.  A popup window to show all possible tags
3.  An integration for tags stored in the cloud
4.  Grayed out text on obsolete tags

**Answer:** 1\. A list with the most frequently used tags displayed larger

**What is the main difference between categories and tags?**

1. Tags have a hierarchy, while categories do not
2. Categories have a hierarchy, while tags do not
3. Tags can be grouped, while categories can not
4. Categories can be grouped, while tags can not

**Answer:** 2. Categories have a hierarchy, while tags do not

## Additional Resources

*  [Categories](https://en.support.wordpress.com/posts/categories/) @ support.wordpress.com
*  [Tags](https://en.support.wordpress.com/posts/tags/) @ support.wordpress.com

## Example Lesson

### Introduction

WordPress has two built-in taxonomies for managing content: categories and tags. A "taxonomy" is a system to define and classify items. By default, WordPress Posts are arranged in chronological order reflecting their timely nature. But Posts can also be organized using categories and tags.

>![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/flag.png) Pages do not use categories and tags as they are organized in parent-child hierarchies.

#### Categories

Categories offer a way to sort and group posts into different sections. They tend to be pre-defined and broad ranging. A category is a descriptive word or phrase used as a text label for a group of posts. Categories may have subcategories, which allows for creating a hierarchy of category terms. WordPress considers posts in subcategories to also be members of their parent categories, so subcategories are more specific terms within a parent category.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-info.png) A post may have more than one category applied, but it's best to restrict posts to a single category. Multiple categories for single posts tends to clutter the organization of content and may confuse readers. Tags are a better means of providing additional groupings and relationships between posts.

#### Tags

Tags are similar to categories, but they are used in a more free-form manner for applying all kinds of keywords to posts. Posts tend to have multiple tags for cross referencing, and they can be used in an ad hoc way without causing confusion. Unlike categories, tags do not have any hierarchy.

### Using Categories

Go to **Dashboard > Posts** and open any Post or create a new one. In the right-hand column of meta boxes, scroll down to the "Categories" meta box. To bring this meta box up to a higher position on the screen so that it is easier to view, you can click the upward pointing triangles (▲) next to "Publish" and "Format" to collapse these meta boxes**,** as shown in the screenshot below. Or you can drag-and-drop the meta boxes to organize them any way you prefer.

![Collapse/Open Meta Box Arrow](/images/metabox-collapse.png)

By default all posts are placed in "Uncategorized", but that is not a useful classification, consider renaming it to a default category that works for your situation. Uncheck the "Uncategorized" selection, and check a different one. (If you do not see additional categories, click the "Add New Category" link to create one.) To save your work, go to the "Publish" meta box and click "Update" (or "Publish" if it hasn't been published yet).

The post now has a category stored in the metadata for the post. While themes vary in how they display post metadata, WordPress automatically provides a URL that links to a list of posts within that category (aka an archive page). Go to **Dashboard > Posts** to view the lists of posts. Notice that post you worked with now has the category listed in the "Categories" column.

![Post list with categories](/images/post-list-categories.png)

Click on the "Quick Edit" link for a post. This opens a meta box that shows only the metadata without the content of the post, so the categories selection for a post can be quickly edited.

![Post Quick Edit](/images/quick-edit.png)

#### Managing Categories

Go to **Dashboard > Posts > Categories** to view the list of categories, manage existing categories, and add new categories.

![Categories List](/images/categories-list.png)

There are five properties for categories that you see on the "Categories" page:

*   **Name**: The category name as it appears on the front end of the website
*   **Slug**: The URL-friendly version of the category name usually composed of lowercase letters, numbers, and hyphens
*   **Parent**: A category may optionally have a parent category, so that it is a child of the parent in a hierarchy
*   **Description**: Optional short descriptive phrase or sentence to describe the type of content in the category
*   **Count**: The number of posts in that category

Name, slug, description, and count are properties that are viewable in the list of categories.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) If you do not see the list of categories, use the "**Screen Options"** feature to display the columns that display these properties. 

When the "Categories" page is first opened, the top-level parent categories are displayed in alphabetical order, with child categories nested beneath their parents. You can click on the "Name" column heading to sort all the categories into a flat list with the child categories in the general alphabetical sort. Clicking the "Name" column again will reverse the order into a descending sort. You can click on the other column headings to sort the list in ascending or descending order for those properties. When you hover the mouse over a category name in the list, a menu appears underneath with four options:

*   **Edit**: Opens a full editing screen for the category
*   **Quick Edit**: Opens an in-context editing screen for just the category name and slug
*   **Delete**: Deletes the category
*   **View**: Opens the category archive page on the front end of the website

![Categories list](/images/categories-list.png)

You will add a new category along with a subcategory that uses it as a parent. On the left side on the Categories page, there is a blank form to add a new category. To add a new category, do not enter anything for the "Slug" and leave "Parent" set to "none." Fill in the following fields:

*   **Name**: Animals
*   **Description**: Both domestic pets and wild beasts.

Click the "Add New Category" button at the bottom of the form. "Animals" is added to the categories list, and you can see that WordPress automatically created the slug "animals." While it's possible to edit a slug that is different from the name, it can cause problems, so it's best to accept the WordPress default.

Return to the post you were working on, use the "Quick Edit" feature, and change the "Categories" setting by removing the check for the current category and checking "Animals." Return to the "Categories" page, and use the "View" option that appears when hovering over the category name to view the Animals category. You'll see the category archive page containing posts for that category. Notice the web address in your browser for the category on the front end of the web site:

`http://yourdomain.com/category/animals/`

The Twenty Sixteen theme displays Animals as the page title using the category name, and it also displays the description as the subtitle, although themes may or may not display the description field of the category.

![Category Page in the Twenty Sixteen theme](/images/twenty-sixteen-category-page.png)

##### Subcategories

Now add two new subcategories for the Animals category. To create a subcategory, set the "Parent" field for the child category as follows:

*   **Name**: Domestic Cats
*   **Parent**: Animals
*   **Description**: We'll have some LOL Cats in this blog.


*   **Name**: Felines
*   **Parent**: Animals
*   **Description**: The entire Felidaebiological classification of wild and domestic cats.


*   **Name**: Big Cats
*   **Parent**: Animals
*   **Description**: We love photos of both big cats in the wild and in zoos.

Notice that the order in which you enter new categories doesn't affect the order of items in the categories list, as they are placed in a logical sort order that can be adjusted. When you click on "Name" column heading, the subcategories move down into flat alphabetical order and do not appear under their parent category. Then, if you click on "Categories" in the main "Dashboard" menu, the subcategories appear under their parents in a alphabetical order.

![Categories list with subcategories](/images/categories-list-ordered.png)

To create the slug names, WordPress replaced the spaces with dashes. Dashes are used for URL-friendly labels, since spaces require extra handling for web addresses and may cause problems. WordPress permalinks can be both human-readable and search engine friendly, and dashes are a convenient delimiter between words for both users and web crawlers used by search engines. It's best not to change them.

#### Editing Categories

Categories can be edited using either the "Edit" or "Quick Edit" options, but "Quick Edit" only allows for modification of the name and slug, so use the full "Edit" option to adjust the hierarchy of categories you created by changing the parent setting. Change both Big Cats and Domestic Cats to have Felines as their parent category.

![Editing a Category](/images/editing-a-category.png)

After clicking "Edit" for a category, use the dropdown list for the "Parent" field to change the setting, then click "Update" at the bottom of the form. Click the "Back to Categories" link at the top of the form to continue. After you have updated both subcategories. you should see a three-level hierarchy for the Animals category.

![Categories and subcategories in a hierarchy](/images/subcategories-in-a-hierarchy.png)

Click on "View" for the Big Cats category in the "Categories" list. You'll see that the URL in the web address for the category archive strings together the parent category and subcategories as directories for a logical construction:

`http://yourdomain.com/category/animals/felines/big-cats/`

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png) When you apply a subcategory, you do not need to also apply the parent category. WordPress automatically includes any subcategory posts with the parent category, which makes sense, since in our example a big cat is a feline and a feline is an animal.

### Using Tags

Tags are managed in a similar manner to categories, except that tags do not have a parent property, so they cannot be organized in a hierarchy. Remember that posts can and should have multiple tags, as applicable, and they can be more specific than categories.

Go to **Dashboard > Posts** and open a post to edit. In the right-hand column, scroll down to view the "Tags" meta box, which is below the "Categories" meta box. At first, you will only see an empty input box with an "Add" button for the "Tags" meta box, unlike the "Categories" meta box which displays a list of checkboxes.

![Tags Metabox](/images/tags-metabox.png)

There are a few ways to add a tag to a post. You can add a new tag, select an existing tag from autolookup, or choose from the most used tags.

#### Create a New Tag

You can type a unique new tag name into the input box and click the "Add" button and you'll create a new tag that is applied to the post.

#### Use Autolookup

Begin typing in the input box and WordPress will apply an autolookup feature to drop down a list of existing tags starting with or including those letters. Using autolookup can help reduce duplicate tags that happen due to typos or using both singular and plural versions of words or from capitalized versions of words.

![Post Tags Autolookup List](/images/tags-autolookup.png)

#### Choose From the Most Used Tags

Click on the "Choose from the most used tags" link in order to see the tag list in a **tag cloud** format. The most frequently used tags will be displayed larger than less used ones.

![Post Tags Most Used Tags](/images/tags-tag-cloud.png)

Regardless of the method you used to select the tags for your post, you'll see them listed in the "Tags" meta box. To remove a tag from the post, click the circled "X" icon next to it.

![Post With Selected Tags](/images/selected-tags.png)

Be sure to click the "Update" button to save the tags you've associated with this post. Then click "View Post" to review the results on the front end of the website.

![Post With Tags](/images/post-with-tags.png)

You'll see that in this case WordPress displays the tags as clickable links, but keep in mind that the placement and treatment of tag links depends upon theme formatting.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-danger.png) While it's easy to quickly apply existing tags along with new tags to a post, be careful when typing tag names in the comma delimited list. It's easy for typos or variations of existing tag names to be created. You may decide to use tag variations like "kitten" and "kitty" to increase findability for your posts, but creating too many tags and over-tagging posts can decrease the usability of the tags on your website.

#### Managing Tags

Tags can also be created and managed on the "Tags" admin page. Go to **Dashboard** > **Posts > Tags** to access the "Tags" page. You'll see that it has the same layout as the "Categories" page.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) If you don't see all the columns for the name, description, slug, and count properties in the list of tags, use "Screen Options" to display them.

You create tags on the "Tags" page the same way as for categories. Descriptions are optional for tags, and themes may or may not display the description as a subtitle for the tag archive.

Create three new tags with descriptions _(names and descriptions are separated by a dash in this list):_

*   lolcat — Funny cat memes
*   cuddly — Friendly cats
*   kitten — Baby cats

Go to the "Posts" page and practice adding these new tags along with the Animals category and subcategories to a number of posts. If you use the "Quick Edit" function, it allows for entering tags directly and through autolookup but it does not support a tag cloud list.

### Viewing Posts by Categories and Tags

Both categories and tags provide a convenient means of navigating posts on both the front end and back end of the website. The "Posts" page has a list of posts that has columns for "Categories" and "Tags" metadata.

You can filter the posts list by a category or tag in several ways:

*   Click a category name in the "Categories" column for a post.
*   Click a tag in the "Tags" column of a post.
*   Click "All categories" dropdown list above the post list, select a category, and click the "Filter" button.

![Posts list with filters for categories and tags](/images/post-list-filters.png)

On the front end of a website, the theme determines how to format Posts. They may or may not display the category and tags for a post and they may appear at the top or bottom of the post content.

#### Widgets for Categories and Tags

WordPress provides default widgets for displaying category and tag lists in sidebars.

Open **Dashboard > Appearance > Widgets** to see the widgets and sidebars available for your website. If necessary, click the downward pointing triangle (▼) next to "Sidebar" to open this panel for managing widgets. Drag and drop the "Categories" widget from under "Available Widgets" over to the "Sidebar" region. Do the same for the "Tag Cloud" widget.

![Adding widgets for Categories and Tag cloud](/images/widgets-sidebar.png)

Titles are optional for widgets, as WordPress uses the name of the widget unless a title is specified. There are several checkboxes for the "Categories" widget, so that you can adjust how to display the list. The "Taxonomy" select list for the Tag Cloud widget allows you to switch from showing tags to showing either categories or link categories in a cloud format. You can use the "Tag Cloud" widget multiple times in a sidebar for those variations, but be sure to add custom titles for each.

### Converting Categories to Tags (or Vice Versa)

Categories and tags are not interchangeable, and while you could use the same name for a category as for a tag in the a website, that could be confusing. So, what can you do if you decide that a category should be a tag or that a tag would be better as a category? WordPress does not provide a standard method for changing a category into a tag or vice-versa. However, there is a plugin available that provides that function when needed: [**Categories to Tags Converter**](https://wordpress.org/plugins/wpcat2tag-importer/).

### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the Exercises and Assessment outlined above.

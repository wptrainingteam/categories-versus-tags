# Categories Vs. Tags

## Description

This lesson plan covers the differences between categories and tags and how to apply them to posts in WordPress. You will learn how to group posts into categories and subcategories according to topic areas. You'll also learn how to use tags to label posts with keywords. You'll understand how WordPress organizes posts using categories and tags, providing a means of taxonomy.

## Objectives

*   Define taxonomy and describe how WordPress implements them.
*   Create categories and tags.
*   <span style="line-height: 1.5">Apply categories and tags to posts.</span>
*   <span style="line-height: 1.5">Manage descriptions and slugs for categories and tags.</span>
*   Utilize widgets for category and tag lists.

## Prerequisite Skills

*   Understanding of how to operate [the dashboard](https://make.wordpress.org/training/handbook/user-lessons/overview-of-the-dashboard/)
*   Ability to differentiate [pages and posts](https://make.wordpress.org/training/handbook/user-lessons/pages-vs-posts/)
*   Ability to edit posts
*   Basic knowledge of how to manage [settings](https://make.wordpress.org/training/handbook/user-lessons/settings/)
*   Ability to [add widgets to sidebar areas](https://make.wordpress.org/training/handbook/user-lessons/managing-widgets/)

## Assets

*   [Twenty Sixteen Theme](https://wordpress.org/themes/twentysixteen/)
*   [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) for sample content, if needed

## Screening Questions

*   Are you able to log in to WordPress as an administrator?
*   Are you familiar with using the WordPress dashboard?
*   Can you differentiate pages and posts?
*   Can you create and edit posts?

## Teacher Notes

*   **Time Estimate:** 20 minutes
*   If students are weak on screening questions, brief explanations may help.
*   Be sure that students have a variety of posts with which to work.
*   If students are using a fresh WordPress installation, they should import the Theme Unit Test Data for sample content.
*   Students should activate the Twenty Sixteen theme in order to follow the lesson, or they should be comfortable using their own theme during the lesson.
*   Students should have **Settings > Permalinks > Common Settings** set to the "Post name" option, to make it easy to view URLs in this lesson. _Note: the Category base and Tag base settings are an advanced topic._

## Hands-on Walkthrough

### Introduction

WordPress has built-in taxonomies for managing content. A _**taxonomy**_ is a mechanism for grouping items by their characteristics through the use of terms. By default, posts are arranged in chronological order reflecting their timely nature. Posts can also be organized using categories and tags as a means of taxonomy. Pages cannot use categories and tags; instead, they are organized in parent-child hierarchies. 

Categories offer a way to sort and group posts into different sections. They tend to be pre-defined and broad ranging. A category is a descriptive word or phrase used as a text label for a group of posts. Categories may have subcategories, which allows for creating a hierarchy of category terms. WordPress considers posts in subcategories to also be members of their parent categories, so subcategories are more specific terms within a parent category. 

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-info.png) A post may have more than one category applied, but it's best to restrict posts to a single category. Multiple categories for single posts tends to clutter the organization of content and may confuse readers. Tags are a better means of providing additional groupings and relationships between posts.

Tags are similar to categories, but they are used in a more free-form manner for applying all kinds of keywords to posts. Posts tend to have multiple tags for cross referencing, and they can be used in an ad hoc way without causing confusion. Unlike categories, tags do not have any hierarchy.

### Using Categories

Go to **Dashboard > Posts** and open "Hello world!" to edit. In the right-hand column of meta boxes, scroll down to the "Categories" meta box. To bring this meta box up to a higher position on the screen so that it is easier to view, you can click the upward pointing triangles (▲) next to "Publish" and "Format" to collapse these meta boxes**,** as shown in the screenshot below. 

[![Edit Post for Categories](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig1-1024x411.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig1.png) 

By default all posts are placed in "Uncategorized", but that is not a useful classification. Uncheck the "Uncategorized" selection, and check "arrangement." (If you do not see "arrangement," select any category available or click the "Add New Category" link to create one.) To save your work, go to the "Publish" metabox and click "Update." To to this you will need to expand the metabox if you have collapsed it by clicking the downward pointing triangle (▼). Click the "View Post" link in the admin bar to see how the category was applied. 

[![Post with a category applied](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig2-1024x320.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig2.png)

The "Hello world!" post now has a category link in the metadata for the post that includes the author and date published along with the category. While themes vary in how they display post metadata, WordPress automatically provides a URL that links to a list of posts within that category. Go to **Dashboard > Posts** to view the lists of posts. Notice that "Hello world!" has the "arrangement" category listed in the "Categories" column. Also, notice that the "Scheduled" and "Draft" posts that are not yet published simply have an "Unpublished" label in the "Categories" column because no categories are applied to posts until they are published. 

[![Post list with categories](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig3-1024x344.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig3.png) 

Click on "Quick Edit" for the "Hello world!" post. This opens a view that shows only the metadata without the content of the post, so the categories selection for a post can be quickly edited. 

[![CategoriesVsTags-Fig4](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig4-1024x294.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig4.png)

#### Managing Categories

Go to **Dashboard > Posts > Categories** to view the list of categories, manage existing categories, and add new categories. There are five properties for categories that you see on the "Categories" page:

*   **Name**: The category name as it appears on the front end of the website
*   **Slug**: The URL-friendly version of the category name usually composed of lowercase letters, numbers, and hyphens
*   **Parent**: A category may optionally have a parent category, so that it is a child of the parent in a hierarchy
*   **Description**: Optional short descriptive phrase or sentence to describe the type of content in the category
*   **Count**: The number of posts in that category

Name, slug, description, and count are properties that are viewable in the list of categories. If you do not see them, use the "**Screen Options"** feature to display the columns that display these properties. When the "Categories" page is first opened, the top-level parent categories are displayed in alphabetical order, with child categories nested beneath their parents. You can click on the "Name" column heading to sort all the categories into a flat list with the child categories in the general alphabetical sort. Clicking the "Name" column again will reverse the order into a descending sort. You can click on the other column headings to sort the list in ascending or descending order for those properties. When you hover the mouse over a category name in the list, a menu appears with four options:

*   **Edit**: Opens a full editing screen for the category
*   **Quick Edit**: Opens an in-context editing screen for just the category name and slug
*   **Delete**: Deletes the category
*   **View**: Opens the category archive page on the front end of the website

[![Categories page](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig5b-1024x434.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig5b.png) 

You will add a new category along with a subcategory that uses it as a parent. On the left side on the Categories page, there is a blank form to add a new category. To add a new category, do not enter anything for the "Slug" and leave "Parent" set to "none." Fill in the following fields:

*   **Name**: Animals
*   **Description**: Both domestic pets and wild beasts.

Click the "Add New Category" button at the bottom of the form. "Animals" is added to the categories list, and you can see that WordPress automatically created the slug "animals." While it's possible to edit a slug that is different from the name, that might cause confusion, so it's best to accept the WordPress entry. However, if there is a need to shorten the spelling or clarify the wording of a category, then you may choose to edit the slug for that reason. 

Return to the "Hello world!" post, use the "Quick Edit" feature again, and change the "Categories" setting by removing the check for "arrangement" and checking "Animals." Return to the "Categories" page, and use the "View" option that appears when hovering over the category name to view the Animals category. You'll see the category archive page containing posts for that category. Notice the web address in your browser for the category on the front end of the web site: 

`http://yourdomain.com/category/animals/` 

The Twenty Sixteen theme displays Animals as the page title using the category name, and it also displays the description as the subtitle, although themes may or may not display the description field of the category.

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

Notice that the order in which you enter new categories doesn't affect the order of items in the categories list, as they are placed in a logical sort order that can be adjusted. When you click on "Name" column heading, the subcategories move down into flat alphabetical order and do not appear under their parent category. Then, if you click on "Categories" in the main "Dashboard" menu, the subcategories appear under their parents in a logical order. 

To create the slug names, WordPress replaced the spaces with dashes. Dashes are used for URL-friendly labels, since spaces require extra handling for web addresses and may cause problems. WordPress permalinks can be both human-readable and search engine friendly, and dashes are a convenient delimiter between words for both users and web crawlers used by search engines.

##### Editing Categories

Categories can be edited using either the "Edit" or "Quick Edit" options, but "Quick Edit" only allows for modification of the name and slug, so use the full "Edit" option to adjust the hierarchy of categories you created by changing the parent setting. Change both Big Cats and Domestic Cats to have Felines as their parent category. 

[![Editing a Category](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig6-1024x369.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig6.png) 

After clicking "Edit" for a category, use the dropdown list for the "Parent" field to change the setting, then click "Update" at the bottom of the form. Click the "Back to Categories" link at the top of the form to continue. After you have updated both subcategories. you should see a three-level hierarchy for the Animals category. 

[![Categories and subcategories in a hierarchy](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig7-1024x278.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig7.png) 

Click on "View" for the Big Cats category in the "Categories" list. You'll see that the URL in the web address for the category archive strings together the parent category and subcategories as directories for a logical construction: 

`http://yourdomain.com/category/animals/felines/big-cats/` 

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png) When you apply a subcategory, you do not need to also apply the parent category. WordPress automatically includes any subcategory posts with the parent category, which makes sense, since in our example a big cat is a feline and a feline is an animal.

### Using Tags

Tags are managed in a similar manner to categories, except that tags do not have a parent property, so they cannot be organized in a hierarchy. Remember that posts can and should have multiple tags, as applicable, and they are more specific than categories. 

Go to **Dashboard > Posts** and open "Hello world!" to edit. In the right-hand column, scroll down to view the "Tags" meta box, which is below the "Categories" metabox. At first, you will only see an empty input box with an "Add" button for the "Tags" megtabox, unlike the "Categories" metabox which displays a list of checkboxes. Click on the "Choose from the most used tags" link in order to see a list in a **tag cloud** format, with the most frequently used tags displayed larger than less used ones. 

[![Post Tags metabox](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig8.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig8.png) 

Before selecting from the list, type the letters "co" into the input box and WordPress will apply an autolookup feature to drop down a list of tags starting with or including those letters. 

[![Post Tags autolookup list](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig9.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig9.png) 

You can select a tag from an autolookup list from the letters you have typed, as well as selecting tags from the most used cloud. If you type a unique new tag name into the input box and click the "Add" button, you'll create a new tag on the fly that is applied to the post. Try selecting tags using both the autolookup and tag cloud techniques. Then, type "new tag" in the input box and click the "Add" button. 

[![Post with applied tags](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig10.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig10.png) 

You'll see a set of tags that you have selected in the "Tags" meta box. To remove a tag from the post, click the circled "X" icon next to it. 

Be sure to click the "Update" button to save the tags you've associated with this post. Then click "View Post" to review the results on the front end of the website. You'll see that in this case WordPress displays the tags as clickable links below the category, but keep in mind that the placement and treatment of tag links depends upon theme formatting. 

[![CategoriesVsTags-Fig11](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig11-1024x340.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig11.png) 

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-danger.png) While it's easy to quickly apply existing tags along with new tags to a post, be careful when typing tag names in the comma delimited list. It's easy for typos or variations of existing tag names to be created. You may decide to use tag variations like "kitten" and "kitty" to increase findability for your posts, but creating too many tags and over-tagging posts can decrease the usability of the tags on your website.

#### Managing Tags

On top of creating tags on the fly, they can also be created and managed on the "Tag"s page. Go to **Dashboard** > **Posts > Tags** on the to access the "Tags" page. You'll see that it has the same layout as the "Categories" page, with the addition of a "Popular Tags" block with a tag cloud. If you don't see all the columns for the name, description, slug, and count properties in the list of tags, use "Screen Options" to display them. 

You create tags on the "Tags" page in the same way as for categories. Descriptions are optional for tags, and themes may or may not display the description as a subtitle for the tag archive. 

Create three new tags with descriptions _(names and descriptions are separated by a dash in this list):_

*   lolcat — Funny cat memes
*   kitten — Little cats
*   kitty — Baby cats

Go to the "Posts" page and practice adding these new tags along with the Animals category and subcategories to a number of posts. Use the "Edit" function rather than "Quick Edit" since this format only allows for typing tags and does not support autolookup or a tag cloud list.

### Viewing Posts by Categories and Tags

Both categories and tags provide a convenient means of navigating posts on both the front end and back end of the website. Go to the "Posts" page and see how the list of posts has columns for "Categories" and "Tags" metadata. If you do not see the columns, use "Screen Options" to display them. You can filter the posts list by a category or tag in several ways:

*   Select a category link for a post in the "Categories" column.
*   Select a tag link for a post in the "Tags" column.
*   Click "All categories", select a category, and click the "Filter" button.
*   To remove the category or tag filter, click the "All" link.

[![Posts list with filters for categories and tags](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig12-1024x239.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig12.png)

#### Widgets for Categories and Tags

On the front end of a website, the theme determines how to format posts, so that they may or may not display the category and tags for a post, and they may appear at the top or bottom of the post layout. WordPress provides default widgets for displaying category and tag lists in sidebars. 

Open **Dashboard > Appearance > Widgets** to see the widgets and sidebars available for your website. If necessary, click the downward pointing triangle (▼) next to "Sidebar" to open this panel for managing widgets. Drag and drop the "Categories" widget from under "Available Widgets" over to the "Sidebar" region. Do the same for the "Tag Cloud" widget. 

Titles are optional for widgets, as WordPress uses the name of the widget unless a specific title is specified. There are several checkboxes for the "Categories" widget, so that you can adjust how to display the list. The "Taxonomy" select list for the Tag Cloud widget allows you to switch from showing tags to showing either categories or link categories in a cloud format. You can use the "Tag Cloud" widget multiple times in a sidebar for those variations, but be sure to add custom titles for each. 

[![Adding widgets for Categories and Tag cloud](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig13-1024x674.png)](https://make.wordpress.org/training/files/2014/11/CategoriesVsTags-Fig13.png)

### Converting Categories to Tags

Categories and tags are not interchangeable, and while you could use the same name for a category as for a tag in the a website, that could be confusing. So, what can you do if you decide that a category should be a tag or that a tag would be better as a category? WordPress does not provide a standard method for changing a category into a tag or vice-versa. However, there is a standard plugin that provides those features when needed: 

**Categories to Tags Converter** 

_Convert existing categories to tags or tags to categories, selectively._ 

`https://wordpress.org/plugins/wpcat2tag-importer/`

## Exercises

**Category Hierarchy** Create a three-level hierarchy of categories with about six items, something like this set of a state, region, and cities:

*   Minnesota
    *   North Shore
        *   Duluth
    *   Twin Cities
        *   Minneapolis
        *   St. Paul

Be sure to give your categories descriptions, and assign one or more posts to each. View your categories and the posts in them, and test that you can navigate and access the categories and posts. If you discover problems or issues, review and revise your work. **Tag Cloud** Create about six tags that will be used for a tag cloud. Update ten posts using two or more tags per post, varying the usage of the tags from a low to high frequency. View the tag cloud in the sidebar on the front end of your website.

*   Do your tags stand out?
*   Are some tags displayed larger than others?
*   Can you apply a tag to more posts, so that it's the biggest in the cloud?

## Quiz

**What are categories?**

1.  A method for page and post navigation
2.  A form of taxonomy for grouping posts in sections
3.  A default list of post types including news, services, and blog
4.  A requirement for menus in web design

**Answer:** 2\. A form of taxonomy for grouping posts in sections **What is the best option for associating multiple keywords with posts?**

1.  Links
2.  Categories
3.  Tags
4.  CSS

**Answer:** 3. Tags **What is a slug for a category or tag?**

1.  The storage area for it's posts
2.  An instant application button
3.  An alternative spelling to redirect typos
4.  The portion of the URL representing its name

**Answer:** 4.The portion of the URL representing its name **What does a tag cloud provide?**

1.  A list with the most frequently used tags displayed larger
2.  A popup window to show all possible tags
3.  An integration for tags stored in the cloud
4.  Grayed out text on obsolete tags

**Answer:** 1\. A list with the most frequently used tags displayed larger

## Additional resources

1.  [Categories](https://en.support.wordpress.com/posts/categories/) @ support.wordpress.com
2.  [Tags](https://en.support.wordpress.com/posts/tags/) @ support.wordpress.com

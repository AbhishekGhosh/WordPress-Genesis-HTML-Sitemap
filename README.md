# WordPress Genesis HTML Sitemap

WordPress Genesis Custom PHP-HTML archive template with responsive CSS columns for using as sitemap. [Live demo of sitemap in action](https://thecustomizewindows.com/sitemap/). It is plain HTML link, no Javascript, no CSS. All CSS are inline.

![WordPress Genesis HTML Sitemap] (https://github.com/AbhishekGhosh/WordPress-Genesis-HTML-Sitemap/raw/master/shot-2.png "WordPress Genesis HTML Sitemap")

+ Moved odd stuffs of default StudioPress Genesis archive pages towards bottom like Author-named archive.
+ Added RSS Feed
+ Added responsive CSS columns for monthly archives and pages
+ Added horizontal lines

## How To Use?

Place [page_archive.php](https://github.com/AbhishekGhosh/WordPress-Genesis-HTML-Sitemap/blob/master/page_archive.php) `wp-content/themes/your-theme-in-use`. Create a Page named `archive` or `sitemap`, choose `Sitemap` as template from WordPress Editor's `Page Attributes` > `Template` > [Dropdown] > `Sitemap`. 

![Select Template] (https://github.com/AbhishekGhosh/WordPress-Genesis-HTML-Sitemap/raw/master/shot-1.png "Select Template")

Save and publish the Page. Thats it.

## Only 100 Last Posts and Link to Archives and Pages? No Paginated List of All Posts?

It is dangerous work for websites with over 5000 posts to add such. Everytime you publish a post, the stuff will run SQL to list all freshly. It is not practical to scroll a list of 5000 URLs. In fact, category, tags do that work. In short - we are offering a lollilop to the Google bots. We are forcing Google bots to crawl the monthly archives. 

## How To Edit it?

You can edit to add PHP, HTML. Add some text with `<p> </p>` after this part :

    function genesis_page_archive_content() { ?>
    <?php echo genesis_html5() ? '<article>' : '<div>'; ?>

## I saw that you have a search form in the deno of sitemap on your website?

You can add StudioPress Genesis snippet to add search. We actually used Google Custom Search.

## There is a link at bottom towards your website?

It is for a false hope if 1-2 peoples ever keep it to say thanks. 

## Is there any support?

Nope. But you can open issues if you find bugs.


![The Customize Windows](https://thecustomizewindows.com/favicon.ico "The Customize Windows") 
Developed by [The Customize Windows](https://thecustomizewindows.com). 

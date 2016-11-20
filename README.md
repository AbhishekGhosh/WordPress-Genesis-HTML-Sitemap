# WordPress Genesis HTML Sitemap

WordPress Genesis Custom PHP-HTML archive template with responsive CSS columns for using as sitemap. [Live demo of sitemap in action](https://thecustomizewindows.com/sitemap/). It is plain HTML link, no Javascript, no CSS. All CSS are inline.

+ Moved odd stuffs of default StudioPress Genesis archive pages towards bottom like Author-named archive.
+ Added RSS Feed
+ Added responsive CSS columns for monthly archives and pages
+ Added horizontal lines

## How To Use?

Place in [page_archive.php](https://github.com/AbhishekGhosh/WordPress-Genesis-HTML-Sitemap/blob/master/page_archive.php) `wp-content/themes/your-theme-in-use`. Create a Page named `archive` or `sitemap`, choose `Sitemap` as template from WordPress Editor's `Page Attributes` > `Template` > [Dropdown] > `Sitemap`. Save and publish the Page. Thats it.

## How To Edit it?

I do not know. Your file, you'll edit. Add some text with `<p> </p>` after this part :

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

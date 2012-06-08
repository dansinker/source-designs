source-designs
==============

These are some basic design sketches for templating the Source project for OpenNews. 

All the CSS points to app.css and is shared across flat files.

I'm hosting mirrors of these on S3 for easy peeping. 

NOTE THAT INTERLINKING BETWEEN THESE EXAMPLES SUCKS ASS. Use your back button to not go crazy.

Generic List View: http://opennews-source.s3-website-us-east-1.amazonaws.com/generic_list_view.html
* note that this is viewing a top-level topic "projects" if we're in the home view, that wouldn't display
* also note that the categories are linkable (in this case only 'how-to') and they lead to...

Category List View: http://opennews-source.s3-website-us-east-1.amazonaws.com/category_list_view.html
* This ads a second level to the top-level topic listing, the category and filters to only see that category
* Note that the top-level topic listing (in this case "projects") is now linkable to move up the stack.

Article View: http://opennews-source.s3-website-us-east-1.amazonaws.com/article_view.html
* This shows a code-heavy article
* Note that this view introduces the Syntax Highlighter jquery plugin, and is only used in this view (and probably could use some tweaking)

Article No Code: http://opennews-source.s3-website-us-east-1.amazonaws.com/article_nocode.html
* Just an example of a much simpler article display.

Code View: http://opennews-source.s3-website-us-east-1.amazonaws.com/code_view.html
* the basic view into a code index entry
* note I added a little description field as well.

People List View: http://opennews-source.s3-website-us-east-1.amazonaws.com/people_list_view.html
* This probably also works for the formatting of the code list view
* (and, frankly, still probably needs more tweaking)

People Detail View: http://opennews-source.s3-website-us-east-1.amazonaws.com/people_detail_view.html
* This one's pretty solid
* Though note that the example page I was working from didn't actually have a code list, so go with what you had formatted previously for that.
* But do we want a little bio under the name? Maybe. If we do, would maybe be good on the list view too.

Article Blank: http://opennews-source.s3-website-us-east-1.amazonaws.com/article_blank.html
* This is exactly what it says on the box
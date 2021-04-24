# Making interactive tables 🧮

*Exploring different options for publishing interactive tables pulling data from a Google Sheets document.*

## Static tables

One simple option is to copy and paste the table contents into a HTML table generator to make something more nicely laid out (as well as linking to the source Google Sheets document).

This is one option: <https://russellgoldenberg.github.io/responsive-table-generator/>

- Pro: Nicely laid out.
- Con: No interactivity. Have to update data manually.

Also FooTable: https://fooplugins.github.io/FooTable/index.html

- Pro: Nicely laid out and interactive.
- Con: Have to update data manually.

## Interactive tables

Embedding Google Sheet directly.
- Pro: Easy!
- Con: May appear in an iFrame and not always work as intended.

Sheetsee seems to be one of the most widely mentioned options for making an interactive table from a Google Sheets document:
<http://jlord.us/sheetsee.js/demos/demo-table.html>
- Pro: Interactive embedding with sorting and filtering.
- Con: May need a bit of fiddling and testing to set up.

Flourish table - <https://app.flourish.studio/@flourish/table>
- Pro: It can be queried and filtered
- Con: It has to be manually updated based on spreadsheet changes (rather than pulling data directly from Google Sheet)

## Other interactive layouts

Publishing as a stack of "cards" (Flourish) - <https://flourish.studio/2019/10/17/cards-template/>
- Pro: Looks nice. You can add images. Some faceted browsing (so you can choose which to select).
- Con: It has to be manually updated; 

Interactive filtering and sorting: <https://isotope.metafizzy.co/>
- Pro: It looks really nice. Lots of ways of customising this.
- Con: It takes more time intensive to customise. 

## Tables for books/publications

There are some options specifically for making tables/displays of publications.

GoodReads has embeddable widgets: <https://help.goodreads.com/s/article/How-do-I-add-a-widget-to-my-blog-1553870933491>

Kerko creates an interactive bibliography from a Zotero library/group: 
<https://demo.kerko.whiskyechobravo.com/bibliography/>
<https://github.com/whiskyechobravo/kerko>

## Projects which are now unsupported

* tabletop.js - <https://github.com/jsoma/tabletop> - no longer works due to changes on Google side
* <http://inn.github.io/responsive-tables/> - seems not to work
* <http://listify.okfnlabs.org/> - infinite wait

## To do

* Continue looking at other libraries on GitHub: https://github.com/search?p=1&q=google+sheets&type=Repositories

Abstract class to change all links within a piece of HTML code.

Also comes with abstract tool class HTML::LinkChanger::URLFilter for creating your own filters.

Also contains pre-packaged HTML::LinkChanger::Absolutizer class for making all relative links within a document to be absolute which is useful for processing RSS feeds because RSS standards are not very strict about relative URL handling and software might misinterpret them.
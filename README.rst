Uploadr.py
==========

Uploadr.py is a simple Python script for uploading your photos to Flickr. Unlike
many GUI applications out there, it lends itself to automation; and because it's
free and open source, you can just change it if you don't like it.

I have tweaked quite a few features from the original source, so some features might not work similar to the ones in the original source. The source is fairly clear, but if you would like to pay to get documentation and tips on how best to use this script, or just buy me a coffee to appreciate a work, you can do so here : http://go.ankitdaf.com/uploadr

Authentication
--------------

To use this application, you need to obtain your own Flickr API key and secret
key. You can apply for keys `on the Flickr website
<http://www.flickr.com/services/api/keys/apply/>`_.

When you have got those keys, you need to set environment variables so that they
can be used by this application. For example, if you use Bash, add the following
lines to your ``$HOME/.bash_profile``::

    export FLICKR_UPLOADR_PY_API_KEY=0123456789abcdef0123456789abcdef
    export FLICKR_UPLOADR_PY_SECRET=0123456789abcdef


License
-------

Uploadr.py consists of code by Cameron Mallory, Martin Kleppmann, Aaron Swartz and
others. See ``COPYRIGHT`` for details.

#### [Batcache](https://wordpress.org/plugins/batcache/)

* <!-- .element: class="fragment" --> Great for sites without logged-in users
* <!-- .element: class="fragment" --> Caches pages for 5min by default
* <!-- .element: class="fragment" --> Automatically flush on post publish

Note:

* Plugin used on WordPress.com
* Full-page cache for logged-out users
    - Could also be handled via Varnish or nginx reverse proxy caching
* Make sure to install the "optional" plugin
    - Automatically clear on post changes

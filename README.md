* Very basic example of using MongoDB GridFS as a file store *

This example uses `mongoid` and `carrierwave`.

TODO:

At some file size (50mb+) the app is able to store files but not retrive them due to the following:
  assertion 10128 too much data for sort() with no index.  add an index or specify a smaller limit
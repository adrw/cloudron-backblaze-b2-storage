# Backblaze B2 Client

A thicker client for Backblaze B2 that includes `fs` to handle uploads and extensible error handling for easier integration with other platforms.

See the examples directory for integration samples. The directory includes an example implementation of Cloudron storage interface to support Backblaze B2.

## Plan

- [x] Copy over Cloudron storage interface
- [ ] Use [yakovkhalinsky/backblaze-b2](https://github.com/yakovkhalinsky/backblaze-b2) client to implement B2 interface (with inspiration from other users of the library)
  - [gnalck/ghost-storage-b2](https://github.com/gnalck/ghost-storage-b2/blob/master/index.js)
  - [UbuntuOpenStore/openstore-api](https://github.com/UbuntuOpenStore/openstore-api/blob/919c8c3c29e5f8a4764f2aa9514f43d6bacc3462/src/utils/upload.js)
- [x] Publish on NPM

## Resources

- [Cloudron Forum Post](https://forum.cloudron.io/topic/1886/is-it-possible-to-implement-custom-backup-providers/8)
- [Cloudron storage interface](https://git.cloudron.io/cloudron/box/blob/master/src/storage/interface.js)
- [Cloudron s3 storage implementation](https://git.cloudron.io/cloudron/box/blob/master/src/storage/s3.js)
- [Recommended Backblaze B2 node client](https://github.com/yakovkhalinsky/backblaze-b2)

# Release

To release new version of Kuma follow the steps:

1. Create a CHANGELOG.md.
2. Create PR to [kuma.io website repository](https://github.com/Kong/kuma-website) making sure that all new features
   are documented.
3. Create a new git tag.
4. Push git tag. This will trigger the release job on CI.
5. Make sure that new binaries are available in [Bintray](https://bintray.com/kong/kuma).
6. Download the new Kuma version and double check that it works with demo app.
7. Merge PR to website repository.
8. Announce new version on Kuma Slack #news channel.

## Major releases
For major releases make sure that you also:

1. Create a blog post on Kong's blog.
2. Send newsletter about new release.
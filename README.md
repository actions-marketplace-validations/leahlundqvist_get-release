# GitHub Action - Get a Releases

This is a fork meant specifically to be used for the vlang/v repo as part of its build pipeline. Please use the [original action](https://github.com/bruceadams/get-release) instead.

### Inputs
- `tag_name`: The tag_name to query

### Outputs
- `id`: The release ID
- `html_url`: The URL users can navigate to in order to view the release. For example `https://github.com/octocat/Hello-World/releases/v1.0.0`
- `upload_url`: The URL for uploading assets to the release, which could be used by GitHub Actions for additional uses, for example the [`@actions/upload-release-asset`](https://www.github.com/actions/upload-release-asset) GitHub Action
- `tag_name`: The git tag associated with the release. For example: `v1.1.0`

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Hyper's website

You found the source code backing Hyper's website hosted at https://tableau.github.io/hyper-db 🙂

If you want to read our documentation or any other content from our webpage, I highly recommend you do so on https://tableau.github.io/hyper-db instead of browsing the source code here.
If, however, you want to contribute to our documentation, e.g. by documenting new use cases, fixing typos, writing a blog post, then you found exactly the right spot.
Contributions are very welcome, you don't need to be a Salesforce employee.
Just open a pull request on this Github repository.
For larger contributions, however, you might want to create a [Github issue](https://github.com/tableau/hyper-db/issues) first, to discuss your idea.

## Building

Hyper's website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

After installing [yarn](https://yarnpkg.com/), run

```
$ yarn
```

from the `website` subfolder within this repository.

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Creating a Pull Request

To get your changes merged, create a Pull Request.
Github Actions are configured to automatically test for changes.
For simple typo or wording fixes, you don't need a peer review - feel free to just go ahead and merge.
For actual new content, we encourage to get at least one peer review.

Documentation changes which apply right away to the already available Hyper version should be merged directly to `main`.
If your documentation only applies to the upcoming Hyper version, merge your changes into the `upcoming` branch instead.

### Deployment

As soon as your pull request to https://github.com/tableau/hyper-db is merged to `main`, the new web page will be deployed automatically within a couple of minutes.

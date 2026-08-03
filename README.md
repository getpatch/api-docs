# Anagram API Docs

Public documentation for the Anagram API: [api-docs.goanagram.com](https://api-docs.goanagram.com).

## Development

Requires Node.js 22. Newer versions are not currently supported by Mintlify.

```bash
brew install node@22
export PATH="$(brew --prefix node@22)/bin:$PATH"
```

Install the [Mintlify CLI](https://www.mintlify.com/docs/cli/install):

```bash
npm install -g mint@latest
```

From the repository root, start the local preview:

```bash
mint dev
```

Validate changes before publishing:

```bash
mint validate
```

## Publishing

Changes are deployed to production automatically after they are merged into the `master` branch. Follow the team's standard Git flow: create a feature branch and open a PR.

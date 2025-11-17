# OpenAGI Lux Documentation

This is the official documentation for OpenAGI Lux, built with Mintlify. OpenAGI Lux is an advanced AI automation platform that enables intelligent interaction with computer interfaces.

This documentation includes:

- Core concepts (Actions, Steps, Actors, Agents)
- Python SDK reference and guides
- Installation and setup instructions
- API reference
- Examples and tutorials

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are automatically deployed to production after pushing to the main branch. The documentation is hosted and managed through Mintlify's platform.

## Contributing

When contributing to the documentation:

1. Make sure all code examples are tested and working
2. Follow the existing structure and formatting conventions
3. Update relevant sections when adding new features
4. Test your changes locally before committing

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [OpenAGI Platform](https://agiopen.org)
- [Mintlify documentation](https://mintlify.com/docs)
- [Support](mailto:support@agiopen.org)

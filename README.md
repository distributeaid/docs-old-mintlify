# Distribute Aid Docs

We'll be figuring out the overall structure as we go along for a bit, so for now we can just do a brain dump and then see what organization paradigm grows from that. I did make folders for DistroForce, How to DA (like how we use GitHub, for instance), the needs assessment, and the website, but otherwise don't worry about organization. So go ahead and dump those brains!

Here's a [Markdown guide](https://www.markdownguide.org/), in case Markdown is new for you. Feel free to ping me with questions!

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`

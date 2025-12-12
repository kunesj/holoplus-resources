# Holoplus Resources

Collection of different tools and resources that can be useful when working with Holoplus API.

- [Holoplus Mocked API](./holoplus_mocked_api) - Fake version of the API for development and testing
- [Holoplus API Docs](https://kunesj.github.io/holoplus-resources) - Built from [Holoplus Mocked API](./holoplus_mocked_api) (**Incomplete**)
- [Holoplus Tools](./holoplus_tools) - Useful tools for getting/refreshing tokens


## Development

### Pre-commit

Install prek:

```bash
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/j178/prek/releases/download/v0.2.3/prek-installer.sh | sh
prek self update
```

Install hooks:

```bash
prek install
prek install-hooks
```

To manually run it on all files:

```bash
prek run --all-files
```

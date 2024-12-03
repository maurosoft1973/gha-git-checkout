# Git Checkout

Checks-out your repository under `$GITHUB_WORKSPACE`, so your workflow can access it. Leverages the official [checkout action](https://github.com/actions/checkout) pre-configured specifically for the majority. 

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: maurosoft1973/git-checkout@v1
```

### Inputs

```yaml
with:
  # The branch, tag or SHA to checkout. Default is the head of the default branch in the repository.
  ref:
  # Upload the repo as-is for debug purposes. Default is to not upload.
  uploadCheckout:
```

### Outputs

This action has no outputs.

## Examples

### Fetch entire repository


```yaml
steps:
  - name: Checkout
    uses: maurosoft1973/git-checkout@v1
```

## Contributing to Git Checkout

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

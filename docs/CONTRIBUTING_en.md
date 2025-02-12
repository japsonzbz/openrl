## Contributing to OpenRL

Welcome to contribute to the development of OpenRL. We appreciate your contribution!

- If you want to contribute new features, please create a new [issue](https://github.com/OpenRL-Lab/openrl/issues/new/choose) first 
to discuss the implementation details of this feature. If the feature is approved by everyone, you can start implementing the code.
- You can also check for unimplemented features and existing bugs in [Issues](https://github.com/OpenRL-Lab/openrl/issues), 
reply in the corresponding issue that you want to solve it, and then start implementing the code.

After completing your code implementation, you need to pull the latest `main` branch and merge it.
After resolving any merge conflicts,
you can submit your code for merging into OpenRL's main branch through [Pull Request](https://github.com/OpenRL-Lab/openrl/pulls).

Before submitting a Pull Request, you need to complete [Code Testing and Code Formatting](#code-testing-and-code-formatting).

Then, your Pull Request needs to pass automated testing on GitHub.

Finally, at least one maintainer's review and approval are required before being merged into the main branch.

## Code Testing and Code Formatting

Before submitting a Pull Request, make sure that your code passes unit tests and conforms with OpenRL's coding style.

Firstly, ensure that unit tests pass by executing `make unittest`.

Next, format your code by running `make format`.

Lastly, run `make commit-checks` to check if your code complies with OpenRL's coding style.

> Tip: OpenRL uses [black](https://github.com/psf/black) coding style. 
You can install black plugins in your editor as shown in the [official website](https://black.readthedocs.io/en/stable/integrations/editors.html)
to help automatically format codes.
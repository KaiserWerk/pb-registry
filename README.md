# Project Bootstrap Public Test Repository

This is a public repository from the 'Project Bootstrap' for testing purposes.
Feel free to use it for testing out the features.
The short name for this project as well as its binary name is `pb`.

See the tool repository at [https://github.com/KaiserWerk/project-bootstrap](https://github.com/KaiserWerk/project-bootstrap).

Use it freely for testing and experimentation.
In order to do that, just set it up as a source in your `~/.pb/pb-config.yaml` global configuration file like this: 

```yaml
sources:
  - https://github.com/KaiserWerk/pb-registry
```

Sources must be valid repository URLs or paths (remotes) which can be used by `git` commands, like `git clone`.

In case you don't have a `~/.pb/pb-config.yaml` file yet, you can create it by executing `pb create-config` from any directory.

After setting up the configuration, you can start using the `pb` tool with the sources you have defined. See the tool's README for more info.
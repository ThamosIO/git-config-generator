# Setup

You need `direnv` installed, then do `direnv allow`.

Use `make setup` to generate the values file (`values.config`).

Then, fill out all necessary variables. You can find examples for each var.

# Use

Once the `values.config` file is filled out, use:

```
git-config
```

If you don't want to use the `values.config` file, you can execute the script in interactive mode using:

```
git-config -i
```

You will be prompted for the necessary variables.

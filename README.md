# vue-cli-plugin-platformsh

Platform.sh plugin for `@vue/cli` 3.0.

This plugin will generate the Platform.sh configuration files for your Vue.js project using [Vue CLI](https://cli.vuejs.org/).

## Install

First you need to install `@vue/cli` globally (follow the instructions [here](https://cli.vuejs.org/)).

If you start a new project, create the project with Vue CLI:

```bash
vue create my-vue-project
```

Add the Platform.sh plugin:

```bash
cd my-vue-project
vue add platformsh
```

## Fetch Platform.sh environment variables

The plugin will automatically extract the Platform.sh environment variables.

To fetch those, you simply need to import the following package:

```bash
import platformshVar from 'platformsh_variables'
```
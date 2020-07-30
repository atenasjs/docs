---
id: getting-started
title: Getting Started
hide_title: true
---

# Welcome to Atenas

The atenas is a one deno framework for building server-side applications.

It will help create server-side applications quickly, while maintaining a code style.

## Installation

### Prerequisites

First of all, you will need the deno installed, stay tuned to the version, the recommended one is ^v1.2.0

#### Deno
Please read the [Getting Started](https://deno.land/manual/getting_started/installation) of deno to install

#### Git
Please download the git by [this site](https://git-scm.com/downloads)

Atenas has a [Atenas CLI](https://github.com/atenasjs/cli) to help create, manage and run atenas applications, at the moment we are only using the [Atenas CLI](https://github.com/atenasjs/cli)  to manage Atenas, however, soon documentation will be available if you do not want to use it.

### Install the Atenas CLI

Run in terminal:

```
deno run --allow-run https://git.io/atenas
```

## Creating a new project

To create a new workspace and initial starter app:

```
atenas new my-atenas-project
```

## Run the application

The Atenas CLI does everything it needs to serve an athens project quickly without additional settings and / or additional files;

1. Navigate to the workspace folder, such as my-atenas-project
2. Run the following command:

```
cd my-atenas-project
atenas start
```

Ready!
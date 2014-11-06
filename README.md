Phing Behat
===========

## Overview

A library Behat targets for Phing.

## Installation

This project can be checked out with Composer.

```
require: "previousnext/phing-behat": "*"
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/previousnext/phing-behat/build.xml" optional="true" />
```

We also provide some template files that should be added to the root
of our project. These files are:

* behat.yml
* behat.local.yml

## Usage

To get a list of tasks.

```
phing -l
```

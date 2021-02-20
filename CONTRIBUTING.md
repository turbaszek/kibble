<!--
 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing,
 software distributed under the License is distributed on an
 "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
 KIND, either express or implied.  See the License for the
 specific language governing permissions and limitations
 under the License.
 -->

# Contributing to Apache Kibble

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of contents**

- [Community](#community)
- [Development installation](#development-installation)
- [Code Quality](#code-quality)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Community

The main development and design discussion happens on our mailing lists.
We have a list specifically for development, and one for future user questions and feedback.

To join in the discussion on the design and roadmap, you can send email to [dev@kibble.apache.org](mailto:dev@kibble.apache.org).<br/>
You can subscribe to the list by sending an email to [dev-subscribe@kibble.apache.org](mailto:dev-subscribe@kibble.apache.org).<br/>
You can also browse the archives online at [lists.apache.org](https://lists.apache.org/list.html?dev@kibble.apache.org).

We also have:

- IRC channel, #kibble on [Freenode](https://webchat.freenode.net/?channels=#kibble)
- Slack channel, #kibble on [ASF slack](https://s.apache.org/slack-invite)

## Development installation

You should be able to install Apache Kibble by simply doing:

```
pip install -e ."[devel]"
```

## Code Quality

Apache Kibble project is using [pre-commits](https://pre-commit.com) to ensure the quality of the code.
We encourage you to use pre-commits, but it's not required in order to contribute. Every change is checked
on CI and if it does not pass the tests it cannot be accepted. If you want to check locally then
you should install Python3.6 or newer together and run:

```bash
pip install pre-commit
# or
brew install pre-commit
```

For more installation options visit the [pre-commits](https://pre-commit.com).
To turn on pre-commit checks for commit operations in git, run:

```bash
pre-commit install
```

To run all checks on your staged files, run:

```bash
pre-commit run
```

To run all checks on all files, run:

```bash
pre-commit run --all-files
```

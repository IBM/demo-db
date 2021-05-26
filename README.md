# demo-db

## Introduction

This repo is used for the case study and hands-on tutorial [Build an OpenShift certifiable image from a complex application with Cloud-Native Toolkit and OpenShift pipeline](linkTBD).
For the case study, we started with the JanusGraph database open source repos:

* https://github.com/JanusGraph/janusgraph
* https://github.com/JanusGraph/janusgraph-docker

**Instead of forking the JanusGraph repos** and potentially generating noise and distractions for the JanusGraph community (e.g., accidental PRs and abnormal spikes in forks), we are providing repos that are a snapshot of those repos. This will allow you to walk through this case study using our copies and your own fork where you can create tags and releases. Our repos:

* https://github.com/IBM/demo-db
* https://github.com/IBM/demo-db-docker

This repo (demo-db) is intended to be forked by developers as they go through the tutorial. The pipelines they run will then create release tags in their own fork. They can also use their own repo access to create webhooks for triggers.

This repo is intended for the tutorial only and not as a maintained fork of the database.

## Branches

We are using `main` as the default branch, but most likely main will only contain this README.md and a LICENSE.

The branches included in this snapshot from JanusGraph are `master`, `v0.5`, and other versioned branches which were mirrored from the original. The only branch currently in use by the tutorial is `v0.5`, but it is significant that *other* branches exist to demonstrate the possibility for branches and tags.

## Tags

This snapshot includes tags that were mirrored from the original repo. The current tag style looks like `v0.5.3`. That format proved significant for the tutorial. In addition, the fact that tags on branched code will follow semantic versioning as expected is important.

## JanusGraph License

The original repo is licensed under the [Apache License, Version 2](https://github.com/JanusGraph/janusgraph/blob/master/LICENSE.txt).

Considering this is mostly a snapshot of the original. That license still applies.

## IBM License

Fortunately, we also like the Apache License, Version 2 with the following note:

This code pattern is licensed under the Apache License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/) and the [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache License FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)


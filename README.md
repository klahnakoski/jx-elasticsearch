# `jx_elasticsearch`

|Branch      |Status   |
|------------|---------|
|master      | [![Build Status](https://travis-ci.org/klahnakoski/jx-elasticsearch.svg?branch=master)](https://travis-ci.org/klahnakoski/jx-elasticsearch) |
|dev         | [![Build Status](https://travis-ci.org/klahnakoski/jx-elasticsearch.svg?branch=dev)](https://travis-ci.org/klahnakoski/jx-elasticsearch)    |


This library implements [JSON Query Expressions](https://github.com/klahnakoski/JSONQueryExpressionTests) atop an Elasticsearch.


## Contribution

New, or old, versions of Elasticsearch should be added by copying the `es52` subdirectory, and altering the implementation to deal with the differences.

There are two directories in the [ActiveData git history](https://github.com/mozilla/ActiveData/commits/dev) that may help for old versions.

1. `es09` for Elasticsearch version 0.9.x (with MVEL scripting)
2. `es14` is for any version 1.x variant of Elasticsearch (with Groovy scripting)

Both of these directories are too old to be used directly, but they do have code templates for their respective scripting language, and they do have other hints about how to construct queries with the limitations of the older versions.


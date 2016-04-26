# Experimental Platform: elasticsearch

Elasticsearch is a search server based on Lucene. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents.

This is a component of the experimental platform. To read more about it please go here:

[https://github.com/experimental-platform/experimental-platform](https://github.com/experimental-platform/experimental-platform)

## Usage

    # build
    docker build -t "platform-elasticsearch:development" .
    # run
    docker run "platform-elasticsearch:development"
    # test
    ./test-image

## Branch: Development

[![Build Status](https://travis-ci.org/experimental-platform/platform-elasticsearch.svg?branch=development)](https://travis-ci.org/experimental-platform/platform-elasticsearch)

All development branches stem from and (re-)integrate here.

## Branch: Master

[![Build Status](https://travis-ci.org/experimental-platform/platform-elasticsearch.svg?branch=master)](https://travis-ci.org/experimental-platform/platform-elasticsearch)

This is the base for α-channel releases.

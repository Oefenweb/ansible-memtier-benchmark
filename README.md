## memtier-benchmark

[![Build Status](https://travis-ci.org/Oefenweb/ansible-memtier-benchmark.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-memtier-benchmark) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-memtier--benchmark-blue.svg)](https://galaxy.ansible.com/tersmitten/memtier-benchmark)

Set up [memtier_benchmark](https://github.com/RedisLabs/memtier_benchmark) (A High-Throughput Benchmarking Tool for Redis & Memcached) in Debian-like systems.

#### Requirements

* `git-core` (will be installed)
* `build-essential` (will be installed)
* `autoconf` (will be installed)
* `automake` (will be installed)
* `libpcre3-dev` (will be installed)
* `libevent-dev` (will be installed)
* `pkg-config` (will be installed)
* `zlib1g-dev` (will be installed)

#### Variables

* `memtier_benchmark_version` [default: `1.2.9`]: What version of memtier-benchmark to check out (set up). This can be the full 40-character SHA-1 hash, the literal string HEAD, a branch name, or a tag name

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - memtier-benchmark
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-memtier-benchmark/issues)!

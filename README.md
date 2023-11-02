## memtier-benchmark

[![CI](https://github.com/Oefenweb/ansible-megacli/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-megacli/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-memtier--benchmark-blue.svg)](https://galaxy.ansible.com/Oefenweb/memtier_benchmark)

Set up [memtier_benchmark](https://github.com/RedisLabs/memtier_benchmark) (A High-Throughput Benchmarking Tool for Redis & Memcached) in Debian-like systems.

#### Requirements

* `autoconf` (will be installed)
* `automake` (will be installed)
* `build-essential` (will be installed)
* `git` (will be installed)
* `libevent-dev` (will be installed)
* `libpcre3-dev` (will be installed)
* `libssl-dev` (will be installed)
* `pkg-config` (will be installed)
* `zlib1g-dev` (will be installed)

#### Variables

* `memtier_benchmark_version` [default: `1.2.16`]: What version of memtier-benchmark to check out (set up). This can be the full 40-character SHA-1 hash, the literal string HEAD, a branch name, or a tag name

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.memtier-benchmark
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-memtier-benchmark/issues)!

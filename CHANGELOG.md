# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- Adds proper exception handling in failing tests (test_ipv4_nok, test_urls_not_ok).

### Modified
- Changes Pytricia dependency for netaddr (support for Windows), netaddr.IPSet is used instead of Pytricia tree.
- Replaces all uses of socket.inet_pton function for the ipaddress function alternative (support for Windows).

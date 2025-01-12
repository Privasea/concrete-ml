---
name: Release
about: Issue template to prepare a release step by step.
title: "Release vX.Y.Z (or vX.Y.Z-rcW)"
---

Have a look to our [Notion page](https://www.notion.so/zamaai/Releasing-847659988e0042928cc8a89daa787527) and follow the principles. If things are unclear, get some help and then update the Notion file.

- [ ] Version management
- [ ] Preparing the right commit: prepare the commit you want to release, either directly on main or in a `release/X.Y.x` branch
- [ ] Main part of the release: releasing in the internal repository
- [ ] Management of `release/X.Y.x` branch (if needed)
- [ ] Fix links in docs: remove `-internal` links, and check it works fine with `make check_links_after_release`
- [ ] If needed: open-source everything in the public repository
- [ ] If needed: prepare an official release

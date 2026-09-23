# What this revival changed

`fabacab/awesome-cybersecurity-blueteam` has not taken a pull request since
July 2024. This fork runs the gate from
<https://github.com/olitreadwell/awesome-list-template>.

## Entries

- `AutoMacTC` pointed at `CrowdStrike/automactc`, which is 404. The organisation
  still has a `Forensics` repository, but it holds code from blog posts and has
  not moved since 2019, so the entry is gone rather than repointed.
- Two entries had trailing whitespace, and `Stratus Red Team` was missing its
  closing period.

## Links that stay on http

`gauntlt.org` and `netsniff-ng.org` answer on http and not on https, so those
two entries stay where they are and `awesome.toml` records why.

## The licence moved to a file

The readme ended with a `## License` section holding the same CC BY 4.0 link the
intro already carries. The linter forbids a licence section, so the section is
gone and `LICENSE` holds the CC BY 4.0 legal code.

## Cross-references lost their links

Five body lines read "See also [Some Section](#some-section)". Every one of
those anchors is already in the Contents list at the top of the readme, and two
links to one heading is a duplicate link to the linter. The sentences keep the
section names and lost the link markup. Nothing else about them changed.

## Left alone

Every description. Nothing here was written by a model.

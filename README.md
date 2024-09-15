# DIF Open Group Repo Template

## About
Use this repository template for DIF User Groups and Special Interest Groups, collectively referred to as Open Groups (OGs). It does the following:
- Contains the group's common files (such as license and contributing instructions) in the `main` branch
- Hosts the group's landing page in the `gh-pages` branch

## Prerequisites
- DIF Steering Committee has approved the group's charter
- Group Chair / Proposer has filled out this form

See [Create DIF Group documentation](https://github.com/decentralized-identity/org/blob/master/Org%20documents/processes/create_group.md) for more context.

## Template Instructions
- Create your new repo from this template ("Use this template")
- `main` branch changes:
    - Add the approved group charter, in markdown format, as `charter.md` (use the Docs to Markdown extension)
    - Add chair github handles in the [CODEOWNERS](./CODEOWNERS) file.
    - Update links in AGENDA.md and [set up hackmd integration](https://hackmd.io/s/link-with-github)
    - Update this README.md (see example content below)
- `gh-pages` branch:
    - Find/replace "template-for-OGs" with group repo name
    - Add group images into `docs/images/`. This includes photos of chairs and the group images.
    - Update index.html with relevant group and chair information
- Configure github repo, for example  (TODO: this section needs review and clarification)
    - Update all of the links in AGENDA.md and [set up hackmd integration](https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github)
    - Check repo tags
    - Check gh-pages (double-check that Settings > Pages is configured correctly)
    - Give chairs github `maintainer` permissions

After committing these changes, you should see the group landing page at identity.foundation/[repo name]

## Example README.md content
Welcome! We'd love to collaborate with you.

[Other basic group information]

- [Charter](charter.md)
- Schedule
    - Meeting times: [list meeting times]
    - [DIF shared calendar](https://calendar.google.com/calendar/u/0/embed?src=decentralized.identity@gmail.com)
- Meeting archive: [link to past meetings]
- [Link to group communication channel (Discord, etc)]

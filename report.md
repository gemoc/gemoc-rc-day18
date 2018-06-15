# Report on the 1st annual meeting of the Eclipse Research Consortium GEMOC

*Meeting date: 12/06/2018*

*Notes from Erwan and Didier*

## Contribution process

- Requirements for a PR:
  - Should not break the tests (exceptions can be made, eg. due to dependencies inter-projects)
  - If relevant, should include an update to the **documentation**:
    - Developer documentation if changes were made to the API
    - User documentation if changes were made to the UI
  - Should be *testable*, ie. provide some programmatic API to execute the core logic, and should include **tests** relying on this programmatic API
  - Optionally, UI tests with SWTbot
- Idea: see whether we can use Github to enforce a template in the description text box of a PR

## Release cycle

We will distinguish *annual* releases from *intermediate* releases.

TODO: document this new release cycle somewhere.

### Annual release

An **annual release** happens exactly one time per year (obviously) with the following calendar:
- *May*: a discussion on the next release starts
- *June*: features and the API are frozen, release candidates are built and tested
- *July*: the official release is published

### Intermediate release

If an **intermediate release** is required by someone in addition to the annual release (to make some new features public for a demo, to be able to benefit for recent API changes, etc.), he/she triggers a discussion on the *gemoc-dev* mailing list with:
- An "if-possible" release date
- A list of issues/PR from Github that would if possible have to be solved/merged for this release


## Communication

- Among the developers:
  - Try to use the [Mattermost instance provided by Eclipse](http://mattermost.eclipse.org/)
  - Mailing list (gemoc-dev)
- With users:
  - Website (see below), although it will probably remain rather static due to a lack of maintainers
  - Twitter, for new releases?
  - Mailing list? (need to create one)
  - Try to use the [Mattermost instance provided by Eclipse](http://mattermost.eclipse.org/) (need a new room)

## Website

- The official website of the GEMOC Studio will remain http://gemoc.org/studio
- The Eclipse URL http://eclipse.org/gemoc will redirect to http://gemoc.org/studio
- Make the page http://gemoc.org/studio more self-sufficient, if required (eg. move content of the main page to the studio page?)
- The official artwork must be used on the whole http://gemoc.org website

## Distribution

- The GEMOC Studio will always contain a fixed set of official features (framework, java engine, concurrent engine, etc.)
- In the future, some additional *official* plugins might not be installed in the studio by default, and could be installed through the discovery
- Instead of using the discovery, third-party plugins (eg. xMOF) could maybe rely on the Marketplace with a "GEMOC" tag?

## Other TODOs

- Continue moving issues to the new bug tracker

## Notes for next annual meeting

- Use a shared pad (hackmd, etherpad, google docs, etc.) to write a report altogether in live
- Plan more time for technical discussions?

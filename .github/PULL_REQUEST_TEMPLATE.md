### Context / Why are we making a change?
- _Clearly described the motivation or the issue this change addresses._
- _BE GENEROUS to your reviewer and your future self!_

### Description / What has been changed?
- _Detail the specific changes made in this pull request, including what was altered, added, or removed._
- _BE GENEROUS to your reviewer and your future self!_

### Testing / What has been done to verify?
- _Explain how the changes have been tested or the testing approach taken._
- _Provide instructions on how to test the change._
- _Include reliance on any automated tests._
- _BE GENEROUS to your reviewer and your future self!_

### Links / Are there any related issues, pull requests or documents?
- https://seccltech.atlassian.net/browse/SECCL-XXXXX
- https://github.com/SecclTech/example-repo/pull/YYY
- _Supply links to any related, relevant documentation that supports the changes or is affected by them_
- _BE GENEROUS to your reviewer and your future self!_

### Other / What else might be useful to know?
- _Provide any additional context or information about the changes made and their implementation._
- _BE GENEROUS to your reviewer and your future self!_

### Checks to be considered:
If any of these don't apply to your situation, please write N/A (not applicable) next to them and tick them.
- [ ] Descriptive pull request title
- [ ] Completed all the questions above
- [ ] Performed a *self-review* of the code
- [ ] Additional *automated test* coverage
  - [ ] Unit tests
  - [ ] Integration tests
  - [ ] System tests (if appropriate)
  - [ ] Manual testing (e.g. using Postman) has been completed
- [ ] *3 green runs of [system-tests](https://github.com/SecclTech/system-tests)* in dev environment
- [ ] *Planned deployment*
  - See [Deployment and Publishing documentation](https://github.com/SecclTech/workflows/blob/main/docs/README.md#deployment-and-publishing) for guidance on the steps of the deployment process
  - Package version bumped
  - Breaking changes being rolled out to all impacted repos
    - Link those PRs within this PR description if possible
- [ ] Considered *architecture*
  - [ADR](https://seccltech.atlassian.net/wiki/spaces/EN/pages/3580788837/Architectural+Design+Records) raised and approved where required
  - [Seccl Architecture](https://app.mural.co/t/secclsipp0609/m/secclsipp0609/1684748358632/0f1a5c38302fe4e032279d9c502c7e47187ad0ff?sender=u2bda92941015f4707d213946) followed
- [ ] Considered *security*
  - OWASP [Design](https://cheatsheetseries.owasp.org/cheatsheets/Secure_Product_Design_Cheat_Sheet.html)
  - [Top 10](https://cheatsheetseries.owasp.org/IndexTopTen.html)
- [ ] Considered *performance & scalability*
  - Load testing
  - Worst performance
- [ ] Considered *resilience*
  - How will we spot if it goes wrong?
  - How will we recover if it goes wrong?
  - Described upgrades (or lack thereof) into `UPGRADING.md`
- [ ] *Repository maintenance*
  - Any updates to `README.md`
  - Captured changes into `CHANGELOG.md`
- [ ] Confluence documentation written or updated where appropriate

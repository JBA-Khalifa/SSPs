# Setheum Standards Proposals (SSPs)


A Setheum Standards Proposal (SSP) describes standards for the Setheum ecosystem. The Setheum Standards Proposal GitHub is a community-based initiative.  
SSP process is not supposed to be a substitute for Setheum Governance process and is meant to focus only on commonly agreed usage patterns rather than protocol adjustments. 

---

- [:clipboard: Process](#clipboard-process)
- [:pencil: Contributing](#pencil-contributing)
- [:bulb: Help](#bulb-help)

## :clipboard: Process  

Below is the workflow of a successful SSP:
```
1. Draft -> 2. Call for Feedback -> 3. Accepted -> 4. Integrated
```
1. **Draft:** A valid draft, which is merged into into the [draft subfolder](./SSPs/drafts) and actively improved together with the community. 
2. **Call for Feedback:** The SSP will be shared on different channels for additional feedback for at least 2 weeks. The result of this step is either an acceptance of the standard (->Accepted) or the rejection (->Draft). 
3. **Accepted:** Any further changes are unlikely, and developers can start integrating the SSP. Once an SSP is accepted, a reference implementation needs to be created and the SSP will be merged into the accepted subfolder.    
4. **Integrated:** The SSP is actively used and a reference implementation exists and the SSP will be merged into the integrated subfolder.

In order to be **merged or accepted** for the different stages, reviewers need to approve a PR. Reviewers should be known experts in the topic covered by the SSP. 

## :pencil: Contributing

Before you start writing a formal SSP, you should discuss an idea in the SSPs community channels (see the [SSPs on Riot/Element](https://riot.im/app/#/room/#ssps:matrix.org)). An SSP should provide the motivation as well as a technical specification for the feature. 

1. Fork this repository.
2. In the newly created fork, create a copy of the template.
3. Fill out the [template](./SSPs/ssp-template.md) with the details of your SSP. If your SSP requires images, the images should be integrated in a subdirectory of the src folder, which has your SSP number as the name.
4. Once you have completed the application, click on "create new pull request".
5. Rename the file with "ssp-number_of_your_pr.md".
6. Update the pull request. 

## :bulb: Help

* [SSP Channel on Riot/Element](https://riot.im/app/#/room/#ssps:matrix.org)

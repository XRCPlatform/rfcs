# RFCs

 * Authors: @baff5b
 * Start: 31 Jan. 2021
 * Status: PROPOSAL


# Summary

The RFC process is intended to discuss technical or governance issues in such a way that we can develop a consensus around the xRhodium and FreeMarket.one projects.

# Motivation

Most issues and features can be addressed through various means, with those involved in the project. But very large changes, whether in team organization, handling large changes and cross-cutting considerations like a hard fork, etc. needs to be planned out and agreed upon. The RFC process should be simple and should be an aid for all in the user community to participate in.

The RFC process should also be simple at this stage in team development.

## Is your idea worth an RFC?

 * A large breaking change that affects the use of the software and that requires coordination over multiple teams
 * A new feature or functional relationship that requires significant resources.
 * Removing large features, ending sub-projects or anything that can change the overall perception of the project as a result of removing things.
 
## Making an RFC

An RFC should be considered a structured plan to accomplish some large change. It is intended to be a place where ideas are formally collected with the intent that it should be well-considered and indicate to everyone something that will be worked on. As such, there should be high value put into the document: what will have to change and why and what is the benefits of the change, with enough research to demonstrate it is a valid change.

Getting an RFC approved is a process of consensus-building and its approval from the community indicates that a consensus has been reached around in the community.

### Steps to creating an RFC

 1. For the repository: https://www.gitlab.com/bitcoinrh/RFCS.git
 2. Copy the template file: (000-template.md). Increment the filename number and give it a proper filename and title.
 3. Is there something that needs to be added that can't be included in the RFC text? Add it to the `assets/` directory.
 4. Create a merge request as a way to start the conversation about the RFC.
 5. As commenters discuss, the author should maintain any changes needed and also describe why the change was made.
 6. Someone other than author should include an expiration on when discussion should stop, stored in the header of the RFC. It is recommended to keep it long enough to allow enough people to get involved in the discussion, but short enough to not let it linger too long. 
 7. The "Final Commenting Period" should lead to a vote : ACCEPT, DENY or POSTPONE. Even if the RFC is denied, it should be merged anyway if there was enough commentary on it. Someone other 
 8. New RFCs should supercede any old one in whatever state the RFC was left in. It's good to leave the decision of an RFC intact for future reference.
 
# References
 
 * Inspiration from: (https://github.com/mimblewimble/grin-rfcs/blob/master/text/0001-rfc-process.md) 

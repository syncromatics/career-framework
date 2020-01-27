# Common

## Typical sprint work

We follow two-week sprints with a daily standup. Within the sprint, you will also take part in grooming meetings with any squads you are part of. Sprints end and the next starts on the same day, so once every two weeks we have a sprint retrospective and planning meeting.

### Sprint planning

When starting a sprint, the software engineering team and the product team meet to discuss which stories and bugs will be worked on in the sprint. Because the product team prioritizes the backlog ahead of time, this is a time to review the planned work and evaluate whether the work is appropriate and actionable within the sprint. Most of the stories in the backlog are already groomed at this point, but some may require grooming in order to be included in the sprint. The software engineering team identifies among itself who will work on each story in the sprint, and the team gets started.

### Standup

For those present in the Downtown Los Angeles office, the entire engineering and product teams gather in the engineering nook and share a brief synopsis of what they're working on today and any blockers to that work. The meeting is intended to remain short (under 10 minutes) and keep everyone generally informed on the progress of the sprint. (People working remotely participate via Slack.)

Often a person's report within standup requires further conversation. These conversations happen after standup with only the interested people involved.

### Grooming

"Grooming" is the act of reviewing a story or bug to evaulate the work needing to be done and to ensure that all necessary aspects of the work are considered. The work is estimated on a scale using the Fibonacci sequence that is roughly calibrated along these points:

| Points | Description                                                  |
| ------ | ------------------------------------------------------------ |
| 1      | Tiny                                                         |
| 2      | Small and well-defined; roughly a day's worth of work        |
| 3      | Medium                                                       |
| 5      | Large; roughly a week's worth of work                        |
| 8      | Very large and multifaceted; could be most of a sprint's worth of work |
| 13     | Too big; probably needs to be split into smaller stories     |

We follow a written set of guidelines when grooming stories to help ensure all aspects of engineering work is considered for each story.

Most grooming happens within a squad that is focused on a particular feature or set of problems. The squad may include other people as subject matter experts as they see fit.

### Sprint retrospective

At the end of a sprint, the software engineering team and the product team meet to discuss two topics pertaining to the sprint: 

- What did we do well?
- What should we have done better?

Everyone is invited to share. We often call out team and individual achievements like "we completed every goal for this sprint" and "Kevin and Dave handled the investigation of the recurring bug and found a solution to eliminate it." In order to maintain an open and honest retrospective, we work to guard against blame when it comes to answering "What should we have done better?" The conversation is centered around the problems that were encountered and the actions we can take to resolve or avoid those problems. Most retrospectives end with a couple of action items identified for specific people to take. The retrospective notes are recorded in our wiki for anyone to review.

### Code review

We maintain a general standard of requiring two other software engineers to review and approve all code changes. This process is done through pull requests, and typically involves reading through and evaluating the code. Every software engineer is expected to submit pull requests for their work and to review their peers' pull requests as needed. Feedback is focused on the code and the problem being solved. We ask questions and learn from pull requests.

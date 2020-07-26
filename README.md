# Diversity and Inclusion Badging for Events

## Table of contents

- [Overview of the application process](#overview-of-the-application-process)
- [Applying for a Badge](#applying-for-a-badge)
- [Badge Table](#badge-table)

## Overview of the Application process

The CHAOSS Badging Application process when an applicant opens a Pull Request adding to the entries to the [Badge Table](#badge-table). While creating the Pull Request, the associated Pull Request template has a set of questions which need to be answered by the Applicant, and this is the information that is used for reviews. When the Pull Request is created, a Moderator/Maintainer assigns two or more reviewers to the Pull Request. For each reviewer, a Checklist is generated as a Pull Reuest comment. This Checklist contains a list of things a reviewer looks for in an Application. A checklist is divided in four sections:
- Initial Checks - These consist of things absolutely required in an Application.
- Reviewer Checks - This is the part where the reviewer tell about their prior association with the Applicant or their organisation, if any.
- Metric Based Checks - This is the part on which the Badge which is assigned depends. The above two sections have to filled out completely by the reviewer in order for these to be considered.
- Reviewer Recommendation - This is the final section where the Reviewer needs to recommend the Badge the Application should be assigned according to the checklist.

While the Application process goes on, the reviewer gives their feedback - along with filling the checklist - to the Applicant on the parts of the application that can be improved. Once the final recommendations are made by all reviewers, the moderator steps into the process to assign the final badge. This badge is added as another commit in the same Pull Request by the Moderator/Maintainer. When the PR is merged the process is complete.

## Applying for a Badge

In order to Apply for a Badge, make sure the Event you are applying with meets these [Requirements](./submission/requirements.md).

Applying for a Badge is a three step process:
1. Add Event details to the [Badge Table](#badge-table)
2. Propose changes by `Creating a Pull Request` for the `master` branch of this repository
3. Check the box marked as `Allow edits by maintainers` and fill out the PR template

When the Pull Request is created, a moderator will shortly assign reviewers. As an Applicant, you will be required to integrate feedeback from reviewers into your Application and data, and if necessary, provide more information about the processes followed in collecting demographic data.


## Badge Table

Date        | Event name                                       | Badge              |Application PR link     |
------------|--------------------------------------------------|--------------------|------------------------|
Feb-01-2020 | Mock Event #1 (nowhere)                          | ![Pending]         |<!--To be added later-->|
Feb-16-2020 | Mock Event #2 (nowhere)
<!-- SAMPLE ROW

Mmm-dd-yyyy | Event name (venue)                               |                    |                        |

THINGS TO KEEP IN MIND:

- Your event needs to be a valid Markdown table row
  - It must be on the line indicated by 
  - It must all be on a single line
  - It must use ` | ` to separate the columns
  - It must be terminated with a single line break
- Your event needs to use the following format
  1. Date: `Mmm-dd-yyyy`
  2. Event: `‹distinct name› (‹city or venue›)`
  3. Badge: must be left blank initially. During the application PR, a badge will be suggested according to the review information.
     That suggestion must be applied in order to get a valid badge in the Markdown table
  4. Application PR link: must be added during the final commit when the final badge suggestion is applied

-->

## Badge levels

Two statuses exist for the Diversity and Inclusion Event Badging:

| Level        | Badge        |  Requirements Met
|--------------|--------------|-------------------------------------
| Pending      | ![Pending]   |  Review ongoing/required deliverables not met
| Passing      | ![Passing]   |  Required deliverables met


Click here to [Apply for an Event Badge][APPLY].


[Pending]: https://img.shields.io/badge/D%26I-Pending-red?style=flat-square&labelColor=583586&logo=data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI1MCAyNTAiPgo8cGF0aCBmaWxsPSIjMUM5QkQ2IiBkPSJNOTcuMSw0OS4zYzE4LTYuNywzNy44LTYuOCw1NS45LTAuMmwxNy41LTMwLjJjLTI5LTEyLjMtNjEuOC0xMi4yLTkwLjgsMC4zTDk3LjEsNDkuM3oiLz4KPHBhdGggZmlsbD0iIzZBQzdCOSIgZD0iTTE5NC42LDMyLjhMMTc3LjIsNjNjMTQuOCwxMi4zLDI0LjcsMjkuNSwyNy45LDQ4LjVoMzQuOUMyMzYuMiw4MC4yLDIxOS45LDUxLjcsMTk0LjYsMzIuOHoiLz4KPHBhdGggZmlsbD0iI0JGOUNDOSIgZD0iTTIwNC45LDEzOS40Yy03LjksNDMuOS00OS45LDczLTkzLjgsNjUuMWMtMTMuOC0yLjUtMjYuOC04LjYtMzcuNS0xNy42bC0yNi44LDIyLjQKCWM0Ni42LDQzLjQsMTE5LjUsNDAuOSwxNjIuOS01LjdjMTYuNS0xNy43LDI3LTQwLjIsMzAuMS02NC4ySDIwNC45eiIvPgo8cGF0aCBmaWxsPSIjRDYxRDVGIiBkPSJNNTUuNiwxNjUuNkMzNS45LDEzMS44LDQzLjMsODguOCw3My4xLDYzLjVMNTUuNywzMy4yQzcuNSw2OS44LTQuMiwxMzcuNCwyOC44LDE4OEw1NS42LDE2NS42eiIvPgo8L3N2Zz4K

[Gold]: https://img.shields.io/badge/D%26I-GOLD-yellow?style=flat-square&labelColor=583586&logo=data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI1MCAyNTAiPgo8cGF0aCBmaWxsPSIjMUM5QkQ2IiBkPSJNOTcuMSw0OS4zYzE4LTYuNywzNy44LTYuOCw1NS45LTAuMmwxNy41LTMwLjJjLTI5LTEyLjMtNjEuOC0xMi4yLTkwLjgsMC4zTDk3LjEsNDkuM3oiLz4KPHBhdGggZmlsbD0iIzZBQzdCOSIgZD0iTTE5NC42LDMyLjhMMTc3LjIsNjNjMTQuOCwxMi4zLDI0LjcsMjkuNSwyNy45LDQ4LjVoMzQuOUMyMzYuMiw4MC4yLDIxOS45LDUxLjcsMTk0LjYsMzIuOHoiLz4KPHBhdGggZmlsbD0iI0JGOUNDOSIgZD0iTTIwNC45LDEzOS40Yy03LjksNDMuOS00OS45LDczLTkzLjgsNjUuMWMtMTMuOC0yLjUtMjYuOC04LjYtMzcuNS0xNy42bC0yNi44LDIyLjQKCWM0Ni42LDQzLjQsMTE5LjUsNDAuOSwxNjIuOS01LjdjMTYuNS0xNy43LDI3LTQwLjIsMzAuMS02NC4ySDIwNC45eiIvPgo8cGF0aCBmaWxsPSIjRDYxRDVGIiBkPSJNNTUuNiwxNjUuNkMzNS45LDEzMS44LDQzLjMsODguOCw3My4xLDYzLjVMNTUuNywzMy4yQzcuNSw2OS44LTQuMiwxMzcuNCwyOC44LDE4OEw1NS42LDE2NS42eiIvPgo8L3N2Zz4K

[Passing]: https://img.shields.io/badge/D%26I-Passing-passing?style=flat-square&labelColor=583586&logo=data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI1MCAyNTAiPgo8cGF0aCBmaWxsPSIjMUM5QkQ2IiBkPSJNOTcuMSw0OS4zYzE4LTYuNywzNy44LTYuOCw1NS45LTAuMmwxNy41LTMwLjJjLTI5LTEyLjMtNjEuOC0xMi4yLTkwLjgsMC4zTDk3LjEsNDkuM3oiLz4KPHBhdGggZmlsbD0iIzZBQzdCOSIgZD0iTTE5NC42LDMyLjhMMTc3LjIsNjNjMTQuOCwxMi4zLDI0LjcsMjkuNSwyNy45LDQ4LjVoMzQuOUMyMzYuMiw4MC4yLDIxOS45LDUxLjcsMTk0LjYsMzIuOHoiLz4KPHBhdGggZmlsbD0iI0JGOUNDOSIgZD0iTTIwNC45LDEzOS40Yy03LjksNDMuOS00OS45LDczLTkzLjgsNjUuMWMtMTMuOC0yLjUtMjYuOC04LjYtMzcuNS0xNy42bC0yNi44LDIyLjQKCWM0Ni42LDQzLjQsMTE5LjUsNDAuOSwxNjIuOS01LjdjMTYuNS0xNy43LDI3LTQwLjIsMzAuMS02NC4ySDIwNC45eiIvPgo8cGF0aCBmaWxsPSIjRDYxRDVGIiBkPSJNNTUuNiwxNjUuNkMzNS45LDEzMS44LDQzLjMsODguOCw3My4xLDYzLjVMNTUuNywzMy4yQzcuNSw2OS44LTQuMiwxMzcuNCwyOC44LDE4OEw1NS42LDE2NS42eiIvPgo8L3N2Zz4K

[README]: https://github.com/badging/diversity-and-inclusion/blob/master/README.md#applying-for-badges

[APPLY]: https://github.com/badging/event-diversity-and-inclusion/edit/master/README.md

[Event Submission Guidelines]: ./submission/guidelines.md

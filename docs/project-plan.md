# Project Plan

Required deliverable, written in Chapter 11 and updated as things change.
Keep it to this one page.

In Chapter 11, copy your team's `[Team plan]` issue (in `practice-pr`) into
this file:

| `[Team plan]` issue | This file |
|---|---|
| Topic | 1. The tool - One sentence |
| Track | 1. The tool - Track |
| Input / Process / Output | 2. Scope |
| Libraries (whitelist only) | 3. Open source we plan to use |
| Roles | 4. Team and roles |

## 1. The tool

- **Name**: Student Assignment Deadline Tracker
- **One sentence**: A tool that reads student assignment records and displays upcoming and overdue assignments to help university students manage their deadlines.
- **Category**: management
- **Track**: A only
  - A = required for every team: a small tool built with whitelist libraries (fill the two blanks)
  - B = challenge, optional: Track A plus one extension of your own tool

## 2. Scope - input, one processing step, output

| | Our project |
|---|---|
| **Input** | A CSV file containing subjects, assignments, deadlines and completion status. |
| **Processing step** | Filter incomplete assignments that are overdue or due within seven days. |
| **Output** | A formatted terminal table showing assignments that need attention. |

**Definition of done**: one run command, one input, one output result.
Anything beyond that is track B, not the baseline.

## 3. Open source we plan to use

| Library | Why we need it | On the whitelist? |
|---|---|---|
| pandas | Read and filter assignment data from a CSV file. | yes |
| rich | Display assignment results in a formatted terminal table. | yes |
| python-dateutil | Parse assignment deadlines and compare dates. | yes |

One row for each library. For example: `| pandas | reads servers.csv | yes |`

Libraries not covered in class have a recipe card - read it before you add one.

## 4. Team and roles

Write GitHub usernames (for example @gildong-hong). In a team of two or three,
one person can take two roles. Roles can rotate later. If roles change, update
this table.

| Role | Who |
|---|---|
| PM | @rupeshsherpa |
| Developer | @rupeshsherpa |
| Documentation | @Bipinnep12 |
| Reviewer | @gireepuzan-pro |

## 5. Schedule

| Chapter | What we finish |
|---|---|
| 11 | Repository set up, plan written, 3 issues opened, first feature branch |
| 12 | Core feature works end to end (the two blanks are filled) |
| 13 | Peer review, error handling, documentation complete, tests pass |
| Final submission | Final tag, "My contribution" written, peer evaluation done |

## 6. Risks

| What could go wrong | What we will do about it |
|---|---|
| Our input file has missing or invalid assignment deadlines. | Validate the required columns and deadline values before processing. |

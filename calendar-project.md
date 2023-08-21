# Calendar function implementation

**Customer:** Sketch Basketball Web users

**Project name:** Calendar

**Project goal:** Implement Calendar page on Web application that can filter basketball matches by league/league_category/season/team/player. The current implementation only allows users to see 10 matches per page, and with limited functionalities.

## Objectives:

- User is able to see Calendar view from `schedule` tab
- User is able to see matches/schedules for his/her team
- User can filter the match schedules by clicking and selecting filters
- ref: https://www.nba.com/celtics/schedule

## Constraints:

- Expected timeline is 4 sprints each sprints made out of 2 weeks interval
- There can be a change of scope depending on business requirements
- Implementation should be on top of the existing tech stack.

## Project Scope - Deliverables

- Schedules tab
- Calendar view
- Filtering function

## Implementation details

- There are two types of matches (scheduled / completed), we should be able to tell the difference between the two.
- There are each match is related with a season. And all seasons are related with a league - e.g.) Division-1 league (season 1, season 2) , season 1 (match 1, match 2)
- Each team have a logo and a name as well as a team page that needs to be linked to.
- System design, please refer to [docs](README.md#aws-architecture-)

## Closing Checklist

- [ ] All Deliverables Checked and Tested for Quality Requirements
- [ ] Get Customer/Management/Stakeholder Sign-Off
- [ ] Document Project (_Problems, Lessons Learned, Etc._)
- [ ] Declare Project Completed

### References

1. https://www.nba.com/celtics/schedule
2. Google calendar (https://calendar.google.com/)

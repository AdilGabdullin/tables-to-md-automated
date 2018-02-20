# Metric descriptions for Workplace Analytics
## Person metrics
| Metric                                | Description                                                                                                                                                                                                                                                                                                 | Query type |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| After hours collaboration             | Number of hours spent in meetings and sending email outside of working hours.                                                                                                                                                                                                                               | Person     |
| Collaboration hours                   | Number of hours the person spent in meetings and email with at least one other person.                                                                                                                                                                                                                      | Person     |
| Collaboration hours external          | Number of hours the person spent in meetings and on email with at least one person outside the company (as defined by the participant’s email domains).                                                                                                                                                   | Person     |
| Conflicting meeting hours             | Number of meeting hours where the person had overlapping meetings in their calendar. The count includes the entire duration of all overlapping meetings, not just the amount of time that overlaps. (This number includes all non-declined meetings).                                                       | Person     |
| Email hours                           | Number of hours the person spent sending and reading email.                                                                                                                                                                                                                                                 | Person     |
| Emails sent                           | Number of emails the person sent.                                                                                                                                                                                                                                                                           | Person     |
| External network size                 | Number of people external to the company with whom the person had at least two meaningful interactions (a meeting or email between five or fewer people) within the last 28 days (or if reported by month, within the last month).                                                                          | Person     |
| Generated workload email hours        | Number of email hours the person created for internal recipients by sending emails.                                                                                                                                                                                                                         | Person     |
| Generated workload email recipients   | Number of internal recipients on all emails sent by the person. (Counts each recipient once for each email received.)                                                                                                                                                                                       | Person     |
| Generated workload meeting attendees  | Number of internal attendees of meetings organized by the person. (Counts each attendee once for each meeting.)                                                                                                                                                                                             | Person     |
| Generated workload meeting hours      | Number of meeting hours the person created for internal attendees by organizing meetings.                                                                                                                                                                                                                   | Person     |
| Generated workload meetings organized | Number of internal meetings organized by the person.                                                                                                                                                                                                                                                        | Person     |
| Internal network size                 | Number of people within the company with whom the person had at least two meaningful interactions (a meeting or email between five or fewer people) within the last 28 days (or if reported by month, within the last month).                                                                               | Person     |
| Low-quality meeting hours             | Number of meeting hours where the person multitasked, had a conflicting meeting (any non-declined meeting that overlaps), or is redundant (at least three distinct levels from their organization attended).                                                                                                | Person     |
| Manager coaching hours 1:1            | The number of hours that a manager spends in one-on-one meetings with their direct reports.                                                                                                                                                                                                                 | Person     |
| Meeting hours                         | Number of hours the person spent in meetings with at least one other person.                                                                                                                                                                                                                                | Person     |
| Meeting hours with manager            | Number of meeting hours involving at least the person and their manager.                                                                                                                                                                                                                                    | Person     |
| Meeting hours with manager 1:1        | Number of meeting hours involving only the person and their manager.                                                                                                                                                                                                                                        | Person     |
| Meetings hours with skip level        | Number of meeting hours where the manager of the person's manager is an attendee.                                                                                                                                                                                                                           | Person     |
| Meetings                              | Number of meetings the person attended.                                                                                                                                                                                                                                                                     | Person     |
| Meetings with manager                 | Number of meetings where attendees include at least the person and their manager.                                                                                                                                                                                                                           | Person     |
| Meetings with manager 1:1             | Number of meetings involving only the person and their manager.                                                                                                                                                                                                                                             | Person     |
| Meetings with skip level              | Number of meetings where the manager of the person's manager is an attendee.                                                                                                                                                                                                                                | Person     |
| Multitasking meeting hours            | Number of meeting hours where the person sent:                                                                                                                                                                                                                                                              | Person     |
|                                       |  * Two emails or more per meeting hour                                                                                                                                                                                                                                                                      |            |
|                                       |  * Two emails or more per meeting for meetings less than an hour                                                                                                                                                                                                                                            |            |
| Networking outside department         | Number of departments outside their own that the person had connections with, within the last 28 days (or if reported by month, within the last month).                                                                                                                                                     | Person     |
| Open 1 hr blocks                     | Number of one-hour blocks in the person’s calendar during the work day where there are no meetings.                                                                                                                                                                                                       | Person     |
| Open 2 hr blocks                      | Number of two-hour blocks in the person’s calendar without meetings during the work day.                                                                                                                                                                                                                  | Person     |
| Redundant meeting hours               | Number of meeting hours where at least three distinct levels in the person's organization attended.                                                                                                                                                                                                         | Person     |
| Time in meetings during after hours   | Number of hours the person spent in meetings outside of working hours.                                                                                                                                                                                                                                      | Person     |
| Time in meetings during working hours | Number of hours the person spent in meetings during working hours.                                                                                                                                                                                                                                          | Person    |
| Time spent in mails after hours       | Number of hours the person spent sending email outside of working hours.                                                                                                                                                                                                                                    | Person     |
| Time spent in mails working hours     | Number of hours the person spent sending email during working hours.                                                                                                                                                                                                                                        | Person     |
| Total emails sent during meeting      | [[placeholder – definition lorem ip sum}}                                                                                                                                                                                                                                                                 | Person     |
| Total focus hours                     | The total number of hours made up of two-hour or greater blocks of time where the person had no meetings.                                                                                                                                                                                                   | Person     |
| Working hours collaboration           | Number of hours the person spent in meetings and sending email during working hours.                                                                                                                                                                                                                        | Person     |
| Workweek Span                         | Time between the person's first email or meeting and the last email or meeting in a day. (Counted Monday – Friday, with a minimum of 4 hours and a maximum of 16 hours per day.) If reported for the week, the metric is a sum for the week. If reported for the month, the metric is the weekly average. | Person     |

## Meeting metrics
| Metric                             | Description                                                                                                                                    | Query type |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Attendee meeting hours             | Sum of the total adjusted meeting hours for all attendees.                                                                                     | Meeting    |
| Attendees                          | Number of people who attended the meeting.                                                                                                     | Meeting    |
| Attendees multitasking             | Number of attendees that sent emails during the meeting.                                                                                       | Meeting    |
|                                    | * In meetings of one hour or less, two or more emails.                                                                                         |            |
|                                    | * In meetings longer than one hour, two emails per hour. (Example: Sending four emails during a two-hour meeting would count as multitasking.) |            |
| Attendees with conflicting meeting | Number of attendees with meetings that overlap with the meeting (includes all non-declined meetings).                                          | Meeting    |
| Emails sent during meeting         | Number of emails the person sent during all meetings.                                                                                          | Meeting    |
| Invitees                           | Number of people invited to the meeting.                                                                                                       | Meeting    |
| Total emails sent during meeting   | Number of emails sent during the meeting by all attendees.                                                                                     | Meetings   |

## Group metrics
| Metric                              | Description                                                                          | Query type |
| ----------------------------------- | ------------------------------------------------------------------------------------ | ---------- |
| Email hours allocated               | Number of email hours between the user-defined groups.                               | Group      |
| Meeting hours allocated             | Number of meeting hours between the user-defined groups.                             | Group      |
| Meetings attended together          | Number of distinct meetings with at least one attendee from each user-defined group. | Group      |
| Total attendees                     | Total number of attendees in all meetings from each user-defined group.              | Group      |
| Total collaboration hours allocated | Total number of collaboration hours between the user-defined groups.                 | Group      |
| Total invitees                      | Total number of invitees in all meetings from each user-defined group.               | Group      |

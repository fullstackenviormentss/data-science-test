# Data science task

This page has details of the task we'd like you to complete for the data science job offering.

By the time you're reading this, you would have already received a data set from us. It's actual appointment and patient data (sanitized) from Cliniko.

## What to do

We've tried to keep this task as similar to working here as possible. With that in mind, we think you'll know better than us what can be achieved with this. So there's no specific "thing" we want you to find or do. We want you to explore it as you would if working here.

We'd like you to analyse it and give us some insights. The insights should be useful and actionable in some way.

Ideally, the insights would help our customers improve their business. Even better if we could alter Cliniko to implement/make use of these in some automated way.

## Timeframe

It would be great if you could have this done within a week. If that's not doable for you, let us know early.

Also, we don't know how long this should take you, but we're not looking to reward the person that spends the most time on it. We believe in working smarter not harder.

## Tips

In case it's helpful, here's some other tips for you:

- You can ask questions. This isn't a "bonus points if they ask questions" thing, just we'll answer what we can if you need us. Like we would when working together.

- You can request more information/data, but we'd rather you didn't. If you really need more, let us know, but there'd need to be a compelling reason for it.

## Summary

We want to see what it's like to work with you, and the sort of quality of work you'd produce. This is a chance for both sides to see how that is.

We will be making a decision based on these tests, so do give it your best.

Thanks for giving this a go, we can't wait to see what you come up with.

## Is this test ok?

So we haven't hired a Data scientist before, so this is our first time making a test for one. If this test sucks, and it's not going to let you showcase your skills, let us know. We'll try to sort something out.

# About the data

Some important facts about the data:

- We've taken data from 166 accounts in Cliniko.

- The accounts we've selected have been using Cliniko for numerous years.

- There are two files, one has the last 12 months of appointments (795,165 records) for these accounts. The other is the patients (65,534 records) from those appointments.

- It is just a dump of our appointments and patients table in the database for these accounts (but identifiable information removed). It is missing a decent amount of information, particularly in the patients one, for privacy.

## Field descriptions

Some fields are obvious, some less so. Here's descriptions for the latter:

### Appointments data

| Field | Description |
| --- | --- |
| Account ID | Each Cliniko customer has one account |
| Business ID | An account could have multiple locations/businesses |
| SMS reminder sent | A reminder SMS message was sent shortly before the appointment occurred |
| Email reminder sent | A reminder email was sent shortly before the appointment occurred |
| Confirmation email sent at | A confirmation email/calendar file was sent when the appointment was booked |
| Patient arrived | True means they arrived, false does not mean they didn't |
| Patient did not arrive | True means they didn't show up, false does not mean they did |

### Patients data

| Field | Description |
| --- | --- |
| Reminder type | This is for reminders that go out just before the appointment is due to occur |





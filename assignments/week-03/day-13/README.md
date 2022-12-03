# Monitoring & Bug Reporting

## Prerequisites
Before starting this part of the assignment we need to make sure we have the following up and running:
- [ ] A working Connect4 Game client application
- [ ] A working Connect4 Game server application

There are a lot of ways to monitor your applications. Developer and infrastructure specialists use a lot of tools to monitor different parts of a system. There are e.g. specialized solutions to search and display logs, tracing solutions to monitor communications between different applications, metrics gathering, bug reporting, dashboard visiualization tools, alerting and more.

Today we want to add bug reporting to our application. It's very helpful to be notified when an error occurs in your application, get the line of code, time, context, etc. to be able to debug and solve the issue as fast as possible.

We are going to use Sentry. Sentry is:
> Self-hosted and cloud-based error monitoring that helps software teams discover, triage, and prioritize errors in real-time.

## Objectives
- [ ] Add Sentry to your client application
- [ ] Add Sentry to your server application

## Add Sentry

1. Start by creating an [account](https://sentry.io/signup/).
2. Select the NextJS platform.
3. Follow the setup guide.

When your application has sent an error to Sentry, exit the onboarding screen and add a second platform. Now we select Flask and create a project for our backend in our organization.

Note: We need to add the following to our `requirements.txt`:

`sentry-sdk[flask]==1.11.1`


Continue with the Sentry setup tasks displayed in the sidebar.
Finish the following tasks, following the guide Sentry provides.

- [ ] Create a project
- [ ] Send your first event
- [ ] Invite team members
- [ ] Add a second platform
- [ ] Monitor Performance
- [ ] Set up release tracking
- [ ] Configure alerting rules

## Handin

Make sure you invite a TA to your organization on Sentry.

`kristinnth@ru.is`

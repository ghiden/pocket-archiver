# Pocket Archiver

1. Archive unread articles that are older than 2 weeks.

    - also attach a tag such as 'unread' or 'movedbyarchiver'

2. Send an email to the user with the list of archived articles. And the list should contain the following:

    - title
    - a link to move it back to list again

3. Run this every day at some fixed time

## Organization

- Archiver: cron task

- De-archiver: web api

## TODO

- Pick a language

    - JS
        - Maybe run two lambdas: one cron and the other web

    - Goland
        - nano instance elastic beanstalk?

    - Clojure
        - nano instance elastic beanstalk?

Probably JS is the cheapest option.

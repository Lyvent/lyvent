# Lyvent

Living the moment, Sharing the moment.

A free and open source social platform where you can share your daily stories
with other people, living, connecting, and sharing the moment.

Explore and be inspired with what people are doing in these uncertain times.
Everyday there are new fresh stories from people about their day's progress.
Old stories automatically get deleted after a certain time.

## Overview
* A social platform.
* Share stories with everyone publicly.
* Attach other social platforms to your profile.
* Profile is part of your story.
* Top stories of the day (Highest upvotes/ratings).
* All accounts must be confirmed to write a story.

* Leveling system:
  - More stories.
  - Ability to add more pictures.
  - Attach videos.
  - Unlockable through premium.

* Anonymous sharing (mode):
  - Display only profile picture and username.

* Moderation tools:
  - Story deleting.
  - Story hiding/review.

* User Safety (Addition to Moderation tools):
  - Account reporting.
  - Account blocking.
  - Account temp muting.
  - Report/Hide stories from users.

## Stack

I'm using the following since I am most familiar with these,
eventually they might be refactored/replaced to make it scale.

* Flask (API)
* PSQL

* AWS S3 Bucket
* Mailgun
* Auth0
* Stripe API

* Frontend:
  - Vue.js + Vuesax 4 (TypeScript)
  - Flutter

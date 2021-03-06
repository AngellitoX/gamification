# Gamification by ReFlar

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ReFlar/gamification/blob/master/LICENSE) [![Latest Stable Version](https://img.shields.io/packagist/v/reflar/gamification.svg)](https://github.com/ReFlar/gamification)

A [Flarum](http://flarum.org) extension that adds upvotes, downvotes, and ranks to your Flarum Community!

Upvote and downvote posts anonymously, and reward active users with ranks, and sort posts by hotness.

### Usage

- Just click upvote or downvote
- Posts can be sorted by "Hotness"

### Installation

Install it with composer:

```bash
composer require reflar/gamification
```

Then login and enable the extension.

You can optionally convert your likes into upvotes, as well as calculate the hotness of all previous discussions.

### Developer Guide

You have 2 events to listen for "PostWasUpvoted" as well as "PostWasDownvoted" which both contain the post, post's user, and the upvoter/downvoter.

### To Do

- Add ranking page
- Add notifications
- Requests?

### Issues

- [Open an issue on Github](https://github.com/ReFlar/gamification/issues) 

### Links

- [on github](https://github.com/ReFlar/gamification)
- [on packagist](https://packagist.org/packages/ReFlar/gamification)

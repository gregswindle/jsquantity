# @archetypes/quantity

> Represents an amount of something measured according to some standard of measurement.

[![build status](https://secure.travis-ci.org/commonality/@archetypes/quantity.png)](http://travis-ci.org/commonality/@archetypes/quantity)

## Overview

_Figure 1: **@archetypes/quantity** module class diagram._

![@archetypes/quantity class diagram][class-diagram-overview]

## Installation

This module is installed via npm:

``` bash
$ npm install @archetypes/quantity
```

## Usage

``` js
const quantity = require('@archetypes/quantity')
```

[class-diagram-overview]: docs/media/archetypes-quantity-overview.png "@archetypes/quantity module class diagram"

<!-- ⛔️ OCTICON LINK REFERENCES(Begin) ⛔️  -->

[octicon-alert]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/alert.svg
[octicon-archive]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/archive.svg
[octicon-arrow-both]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-both.svg
[octicon-arrow-down]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-down.svg
[octicon-arrow-left]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-left.svg
[octicon-arrow-right]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-right.svg
[octicon-arrow-small-down]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-small-down.svg
[octicon-arrow-small-left]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-small-left.svg
[octicon-arrow-small-right]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-small-right.svg
[octicon-arrow-small-up]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-small-up.svg
[octicon-arrow-up]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/arrow-up.svg
[octicon-beaker]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/beaker.svg
[octicon-bell]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/bell.svg
[octicon-bold]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/bold.svg
[octicon-book]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/book.svg
[octicon-bookmark]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/bookmark.svg
[octicon-briefcase]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/briefcase.svg
[octicon-broadcast]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/broadcast.svg
[octicon-browser]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/browser.svg
[octicon-bug]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/bug.svg
[octicon-calendar]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/calendar.svg
[octicon-check]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/check.svg
[octicon-checklist]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/checklist.svg
[octicon-chevron-down]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/chevron-down.svg
[octicon-chevron-left]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/chevron-left.svg
[octicon-chevron-right]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/chevron-right.svg
[octicon-chevron-up]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/chevron-up.svg
[octicon-circle-slash]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/circle-slash.svg
[octicon-circuit-board]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/circuit-board.svg
[octicon-clippy]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/clippy.svg
[octicon-clock]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/clock.svg
[octicon-cloud-download]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/cloud-download.svg
[octicon-cloud-upload]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/cloud-upload.svg
[octicon-code]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/code.svg
[octicon-comment-discussion]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/comment-discussion.svg
[octicon-comment]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/comment.svg
[octicon-credit-card]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/credit-card.svg
[octicon-dash]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/dash.svg
[octicon-dashboard]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/dashboard.svg
[octicon-database]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/database.svg
[octicon-dependent]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/dependent.svg
[octicon-desktop-download]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/desktop-download.svg
[octicon-device-camera]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/device-camera.svg
[octicon-device-camera-video]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/device-camera-video.svg
[octicon-device-desktop]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/device-desktop.svg
[octicon-device-mobile]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/device-mobile.svg
[octicon-diff-added]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff-added.svg
[octicon-diff]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff.svg
[octicon-diff-ignored]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff-ignored.svg
[octicon-diff-modified]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff-modified.svg
[octicon-diff-removed]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff-removed.svg
[octicon-diff-renamed]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/diff-renamed.svg
[octicon-ellipsis]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/ellipsis.svg
[octicon-eye-closed]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/eye-closed.svg
[octicon-eye]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/eye.svg
[octicon-file-binary]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-binary.svg
[octicon-file-code]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-code.svg
[octicon-file-directory]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-directory.svg
[octicon-file]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file.svg
[octicon-file-media]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-media.svg
[octicon-file-pdf]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-pdf.svg
[octicon-file-submodule]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-submodule.svg
[octicon-file-symlink-directory]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-symlink-directory.svg
[octicon-file-symlink-file]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-symlink-file.svg
[octicon-file-zip]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/file-zip.svg
[octicon-flame]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/flame.svg
[octicon-fold-down]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/fold-down.svg
[octicon-fold]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/fold.svg
[octicon-fold-up]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/fold-up.svg
[octicon-gear]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/gear.svg
[octicon-gift]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/gift.svg
[octicon-gist]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/gist.svg
[octicon-gist-secret]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/gist-secret.svg
[octicon-git-branch]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/git-branch.svg
[octicon-git-commit]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/git-commit.svg
[octicon-git-compare]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/git-compare.svg
[octicon-git-merge]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/git-merge.svg
[octicon-git-pull-request]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/git-pull-request.svg
[octicon-github-action]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/github-action.svg
[octicon-globe]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/globe.svg
[octicon-grabber]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/grabber.svg
[octicon-graph]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/graph.svg
[octicon-heart]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/heart.svg
[octicon-history]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/history.svg
[octicon-home]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/home.svg
[octicon-horizontal-rule]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/horizontal-rule.svg
[octicon-hubot]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/hubot.svg
[octicon-inbox]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/inbox.svg
[octicon-info]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/info.svg
[octicon-issue-closed]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/issue-closed.svg
[octicon-issue-opened]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/issue-opened.svg
[octicon-issue-reopened]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/issue-reopened.svg
[octicon-italic]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/italic.svg
[octicon-jersey]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/jersey.svg
[octicon-kebab-horizontal]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/kebab-horizontal.svg
[octicon-kebab-vertical]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/kebab-vertical.svg
[octicon-key]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/key.svg
[octicon-keyboard]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/keyboard.svg
[octicon-law]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/law.svg
[octicon-light-bulb]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/light-bulb.svg
[octicon-link-external]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/link-external.svg
[octicon-link]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/link.svg
[octicon-list-ordered]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/list-ordered.svg
[octicon-list-unordered]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/list-unordered.svg
[octicon-location]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/location.svg
[octicon-lock]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/lock.svg
[octicon-logo-gist]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/logo-gist.svg
[octicon-logo-github]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/logo-github.svg
[octicon-mail]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mail.svg
[octicon-mail-read]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mail-read.svg
[octicon-mark-github]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mark-github.svg
[octicon-markdown]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/markdown.svg
[octicon-megaphone]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/megaphone.svg
[octicon-mention]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mention.svg
[octicon-milestone]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/milestone.svg
[octicon-mirror]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mirror.svg
[octicon-mortar-board]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mortar-board.svg
[octicon-mute]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/mute.svg
[octicon-no-newline]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/no-newline.svg
[octicon-note]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/note.svg
[octicon-octoface]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/octoface.svg
[octicon-organization]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/organization.svg
[octicon-package]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/package.svg
[octicon-paintcan]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/paintcan.svg
[octicon-pencil]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/pencil.svg
[octicon-person]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/person.svg
[octicon-pin]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/pin.svg
[octicon-play]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/play.svg
[octicon-plug]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/plug.svg
[octicon-plus]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/plus.svg
[octicon-plus-small]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/plus-small.svg
[octicon-primitive-dot]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/primitive-dot.svg
[octicon-primitive-dot-stroke]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/primitive-dot-stroke.svg
[octicon-primitive-square]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/primitive-square.svg
[octicon-project]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/project.svg
[octicon-pulse]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/pulse.svg
[octicon-question]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/question.svg
[octicon-quote]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/quote.svg
[octicon-radio-tower]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/radio-tower.svg
[octicon-reply]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/reply.svg
[octicon-repo-clone]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-clone.svg
[octicon-repo-force-push]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-force-push.svg
[octicon-repo-forked]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-forked.svg
[octicon-repo]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo.svg
[octicon-repo-pull]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-pull.svg
[octicon-repo-push]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-push.svg
[octicon-repo-template]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-template.svg
[octicon-repo-template-private]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/repo-template-private.svg
[octicon-report]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/report.svg
[octicon-request-changes]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/request-changes.svg
[octicon-rocket]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/rocket.svg
[octicon-rss]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/rss.svg
[octicon-ruby]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/ruby.svg
[octicon-saved]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/saved.svg
[octicon-screen-full]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/screen-full.svg
[octicon-screen-normal]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/screen-normal.svg
[octicon-search]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/search.svg
[octicon-server]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/server.svg
[octicon-settings]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/settings.svg
[octicon-shield-check]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/shield-check.svg
[octicon-shield]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/shield.svg
[octicon-shield-lock]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/shield-lock.svg
[octicon-shield-x]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/shield-x.svg
[octicon-sign-in]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/sign-in.svg
[octicon-sign-out]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/sign-out.svg
[octicon-skip]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/skip.svg
[octicon-smiley]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/smiley.svg
[octicon-squirrel]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/squirrel.svg
[octicon-star]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/star.svg
[octicon-stop]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/stop.svg
[octicon-sync]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/sync.svg
[octicon-tag]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/tag.svg
[octicon-tasklist]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/tasklist.svg
[octicon-telescope]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/telescope.svg
[octicon-terminal]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/terminal.svg
[octicon-text-size]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/text-size.svg
[octicon-three-bars]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/three-bars.svg
[octicon-thumbsdown]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/thumbsdown.svg
[octicon-thumbsup]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/thumbsup.svg
[octicon-tools]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/tools.svg
[octicon-trashcan]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/trashcan.svg
[octicon-triangle-down]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/triangle-down.svg
[octicon-triangle-left]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/triangle-left.svg
[octicon-triangle-right]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/triangle-right.svg
[octicon-triangle-up]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/triangle-up.svg
[octicon-unfold]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/unfold.svg
[octicon-unmute]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/unmute.svg
[octicon-unsaved]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/unsaved.svg
[octicon-unverified]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/unverified.svg
[octicon-verified]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/verified.svg
[octicon-versions]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/versions.svg
[octicon-watch]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/watch.svg
[octicon-x]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/x.svg
[octicon-zap]: https://cdnjs.cloudflare.com/ajax/libs/octicons/8.5.0/svg/zap.svg

<!-- ⛔️ OCTICON LINK REFERENCES(End) ⛔️  -->

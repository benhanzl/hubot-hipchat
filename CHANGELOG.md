# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and
this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- `message.user` returns an object from the brain.
  - Changed by [Andrew Widdersheim](https://github.com/awiddersheim) in Pull Request [#277](https://github.com/hipchat/hubot-hipchat/pull/277).
- `user.room` always returns a JID.
  - Changed by [Andrew Widdersheim](https://github.com/awiddersheim) in Pull Request [#277](https://github.com/hipchat/hubot-hipchat/pull/277).

### Removed
- `reply_to` from `envelope.user` and `message.user`.
  - Removed by [Andrew Widdersheim](https://github.com/awiddersheim) in Pull Request [#277](https://github.com/hipchat/hubot-hipchat/pull/277).

### Fixed
- `message.room` updates when room names are changed.
  - Fixed by [178inaba](https://github.com/178inaba) in Pull Request [#280](https://github.com/hipchat/hubot-hipchat/pull/280).
- Hubot joins newly created rooms.
  - Fixed by [178inaba](https://github.com/178inaba) in Pull Request [#280](https://github.com/hipchat/hubot-hipchat/pull/280).
- `messageRoom` works.
  - Fixed by [178inaba](https://github.com/178inaba) in Pull Request [#280](https://github.com/hipchat/hubot-hipchat/pull/280).

### Security
- Updated `node-xmpp-client` to 3.2.0.
  - Updated by [Sam](https://github.com/samcday) in Pull Request [#272](https://github.com/hipchat/hubot-hipchat/pull/272).

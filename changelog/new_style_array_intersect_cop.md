* [#11224](https://github.com/rubocop/rubocop/pull/11224): Add new cop `Style/ArrayIntersect` which replaces `(receiver & argument).any?` with `receiver.intersect?(argument)`, method `Array#intersect?` was added in ruby 3.1. ([@KirIgor][])
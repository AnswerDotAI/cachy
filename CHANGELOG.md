# Release notes

<!-- do not remove -->

## 0.0.12

### New Features

- Refactor send logic into shared helpers, add file locking, and auto-locate cache file in enable_cachy ([#25](https://github.com/AnswerDotAI/cachy/issues/25))


## 0.0.11

### New Features

- Add chatgpt.com ([#23](https://github.com/AnswerDotAI/cachy/issues/23))


## 0.0.10

### New Features

- Add more domains ([#22](https://github.com/AnswerDotAI/cachy/issues/22))


## 0.0.9

### New Features

- Sort json payload for determinstic key ([#21](https://github.com/AnswerDotAI/cachy/pull/21)), thanks to [@KeremTurgutlu](https://github.com/KeremTurgutlu)


## 0.0.8

- Handle binary


## 0.0.7

### New Features

- Add debug logging to cache hits/misses and make `enable_cachy` idempotent ([#17](https://github.com/AnswerDotAI/cachy/issues/17))

### Bugs Squashed

- Rename package from cachy to pycachy to align with PyPI ([#16](https://github.com/AnswerDotAI/cachy/pull/16)), thanks to [@RensDimmendaal](https://github.com/RensDimmendaal)


## 0.0.6

### New Features

- Support allowlisted headers ([#11](https://github.com/AnswerDotAI/cachy/issues/11))


## 0.0.5

### New Features

- add multipart request support ([#10](https://github.com/AnswerDotAI/cachy/pull/10)), thanks to [@KeremTurgutlu](https://github.com/KeremTurgutlu), [@comhar](https://github.com/comhar)
- include full url in cache key ([#7](https://github.com/AnswerDotAI/cachy/pull/7)), thanks to [@decherd](https://github.com/decherd)
 
*Note: [#7](https://github.com/AnswerDotAI/cachy/pull/7) is a breaking change. If your project relies on cachy, delete your `cachy.jsonl`, run your notebooks and commit the new `cachy.jsonl`.*

## 0.0.4

### New Features

- add `disable_cachy` ([#4](https://github.com/AnswerDotAI/cachy/issues/4))


## 0.0.3

### New Features

- update docs


## 0.0.2

### New Features

- use host instead of full url when creating cache key ([#2](https://github.com/AnswerDotAI/cachy/pull/2)), thanks to [@comhar](https://github.com/comhar)


## 0.0.1

- Initial release

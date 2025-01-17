# Common
![circleci](https://circleci.com/gh/prometheus/common/tree/main.svg?style=shield)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftriclambert%2Fcommon.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftriclambert%2Fcommon?ref=badge_shield)

This repository contains Go libraries that are shared across Prometheus
components and libraries. They are considered internal to Prometheus, without
any stability guarantees for external usage.

* **config**: Common configuration structures
* **expfmt**: Decoding and encoding for the exposition format
* **model**: Shared data structures
* **promlog**: A logging wrapper around [go-kit/log](https://github.com/go-kit/kit/tree/master/log)
* **route**: A routing wrapper around [httprouter](https://github.com/julienschmidt/httprouter) using `context.Context`
* **server**: Common servers
* **version**: Version information and metrics

## Deprecated
* **log**: A logging wrapper around [logrus](https://github.com/sirupsen/logrus)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftriclambert%2Fcommon.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftriclambert%2Fcommon?ref=badge_large)
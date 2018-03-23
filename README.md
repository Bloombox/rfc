# OpenCannabis  [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg?longCache=true&style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)

_OpenCannabis_ is a multilateral industrial effort to create an interoperable technical data specification tailored for
the **worldwide legal cannabis market**.

As legal markets to buy, sell, cultivate and manufacture cannabis products come online, a need is emerging for a
universal way of connecting data systems and components that work with cannabis or cannabis-related data.

#### Why write a spec?
Currently, the state of the art in cannabis technology is one of two options: Massive, sweeping ecosystems of
proprietary code (that frequently break), and isolated, SaaS-style startups that provide great tools but without the
ecosystem around them for maximal value.

Some business operators opt for the big players, and feel the pain when they go down. Others spread that pain out over
many smaller providers but both are still unhappy. What's the answer to fixing these problems?

An open specification, for cannabis data. For your menu, your transactions, your customers, and so on - so that when one
provider isn't enough, or it's time to switch, or you want to write your own code - your data and your business aren't
locked away.

#### On the shoulders of giants

The OpenCannabis Specification and related materials are written with modern, cutting-edge tools. The project structure
is inspired by [Unprotocols RFC](https://github.com/unprotocols/rfc), which is a repository for universal, cross-project
protocols used in software development, ranging from workflow to technical.

The specification is codified in a series of documents - referred to as the "*Specification*," or "*Spec*," and a
software implementation, referred to as the "*Protocol*," which is written in
[Protocol Buffers](https://developers.google.com/protocol-buffers/), a language from Google. Other specifications
written in industrial circumstances have seen success with this exact model (see:
[OpenRTB](https://openrtb.github.io/OpenRTB/)).

### Authors and backers

OpenCannabis was conceived at [Bloombox](https://bloombox.io), but it's open and free to the world (under the GNU GPLv3
license). Early adopters and collaborators include [Caliva](https://caliva.menu) and
[Abatin Sacramento](https://abatinsacramento.com).

If you'd like to adopt the spec, or list yourself as a backer, file a pull request and we'll get you added!


| Contributor       | Website                                             | Category                                |
|-------------------|-----------------------------------------------------|:----------------------------------------|
| Bloombox          | [bloombox.io](https://bloombox.io)                  | Software Provider                       |
| Caliva            | [caliva.menu](https://caliva.menu)                  | Cultivator, Retailer, Manufacturer, Lab |
| Abatin Sacramento | [abatinsacramento.com](http://abatinsacramento.com) | Retailer                                |

![Spec Adopters](https://storage.googleapis.com/ocs-media/backers-v1.png)


### Contributing

You can start contributing by sending a pull request to [OpenCannabis/RFC](https://github.com/OpenCannabis/RFC) on
GitHub.

### Guidelines

* Specifications **MUST** be created and modified by pull requests according to [RFC 1/C4](1/README.md)
* Specifications **MUST** follow the lifecycle defined in [RFC 2/COSS](2/README.md)
* Specifications **MUST** use a share-alike compatible license.
* Specifications **SHOULD** use GPL v3 or a later version of the license
* Specifications **SHOULD** use [RFC 2119](http://tools.ietf.org/html/rfc2119) key words.
* Specifications **MUST** be considered immutable, except for cosmetic changes, after exiting *Draft* status.

## Table of Contents

1. [1/C4](./1/README.md) - Collective Code Construction Contract
1. [2/COSS](./2/README.md) - Consensus-Oriented Specification System
1. [3/OCS](./3/README.md) - OpenCannabis Specification

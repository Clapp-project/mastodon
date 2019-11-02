![Mastodon](https://i.imgur.com/NhZc40l.png)
========

[![GitHub release](https://img.shields.io/github/release/tootsuite/mastodon.svg)][releases]
[![Build Status](https://img.shields.io/circleci/project/github/tootsuite/mastodon.svg)][circleci]
[![Code Climate](https://img.shields.io/codeclimate/maintainability/tootsuite/mastodon.svg)][code_climate]
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/mastodon/localized.svg)][crowdin]
[![Docker Pulls](https://img.shields.io/docker/pulls/tootsuite/mastodon.svg)][docker]

[releases]: https://github.com/tootsuite/mastodon/releases
[circleci]: https://circleci.com/gh/tootsuite/mastodon
[code_climate]: https://codeclimate.com/github/tootsuite/mastodon
[crowdin]: https://crowdin.com/project/mastodon
[docker]: https://hub.docker.com/r/tootsuite/mastodon/
これは日本語訳です（できる範囲の）※機械翻訳と自分でわかる範囲です　意訳しているので、本家のレポジトリを参照してください
マストドンはActivityPubを利用した**無料のオープンソースソーシャルネットワークサーバーです。**
友達をフォローして新しい友達を見つけましょう！ リンク、写真、文章、ビデオなど、必要なものをすべて公開できます。
全てのマストドンサーバーは”連合”を利用した相互運用が可能です。
つまり、あるサーバーのユーザーは、ほかのサーバーのユーザーとシームレスに通信することができるのです！
ActivityPubを利用しているほかのソフトウェアとも通信できます。

**もっと知りたい**方はこちらの動画をご覧ください。

[![Screenshot](https://blog.joinmastodon.org/2018/06/why-activitypub-is-the-future/ezgif-2-60f1b00403.gif)][youtube_demo]

[youtube_demo]: https://www.youtube.com/watch?v=IPSbNdBmWKE

## ナビゲーション

- [マストドン公式ホームページ🐘](https://joinmastodon.org)
- [Patreonで寄付する][patreon]
- [スポンサー](https://joinmastodon.org/sponsors)
- [ブログ](https://blog.joinmastodon.org)
- [ドキュメント](https://docs.joinmastodon.org)
- [マストドンサーバー一覧 ](https://joinmastodon.org/#getting-started)
- [マストドンアプリ一覧](https://joinmastodon.org/apps)

[patreon]: https://www.patreon.com/mastodon

## 特徴

<img src="https://docs.joinmastodon.org/elephant.svg" align="right" width="30%" />

**互換性のあるプラットフォームと完全に相互運用可能**

マストドンは互換性のあるプラットフォームと完全に相互運用可能です。[Learn more](https://blog.joinmastodon.org/2018/06/why-activitypub-is-the-future/)

**リアルタイムタイムライン**

WebSocketsを利用したタイムラインでフォローしているユーザーのトゥートを見ることができます。

**メディアアタッチメント**

Upload and view images and WebM/MP4 videos attached to the updates. Videos with no audio track are treated like GIFs; normal videos are looped - like vines!

**Safety and moderation tools**

Private posts, locked accounts, phrase filtering, muting, blocking and all sorts of other features, along with a reporting and moderation system. [Learn more](https://blog.joinmastodon.org/2018/07/cage-the-mastodon/)

**OAuth2 and a straightforward REST API**

Mastodon acts as an OAuth2 provider so 3rd party apps can use the REST and Streaming APIs, resulting in a rich app ecosystem with a lot of choices!

## Deployment

**Tech stack:**

- **Ruby on Rails** powers the REST API and other web pages
- **React.js** and Redux are used for the dynamic parts of the interface
- **Node.js** powers the streaming API

**Requirements:**

- **PostgreSQL** 9.5+
- **Redis**
- **Ruby** 2.4+
- **Node.js** 8+

The repository includes deployment configurations for **Docker and docker-compose**, but also a few specific platforms like **Heroku**, **Scalingo**, and **Nanobox**. The [**stand-alone** installation guide](https://docs.joinmastodon.org/administration/installation/) is available in the documentation.

A **Vagrant** configuration is included for development purposes.

## Contributing

Mastodon is **free, open-source software** licensed under **AGPLv3**.

You can open issues for bugs you've found or features you think are missing. You can also submit pull requests to this repository, or submit translations using Weblate. To get started, take a look at [CONTRIBUTING.md](CONTRIBUTING.md). If your contributions are accepted into Mastodon, you can request to be paid through [our OpenCollective](https://opencollective.com/mastodon).

**IRC channel**: #mastodon on irc.freenode.net

## License

Copyright (C) 2016-2019 Eugen Rochko & other Mastodon contributors (see [AUTHORS.md](AUTHORS.md))

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.

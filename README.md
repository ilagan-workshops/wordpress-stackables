# wordpress-stackables

This is a (small) collection of different variants of Wordpress stacks
via Docker + Docker Compose, meant for use with demos.

## Usage

For each stack in [`stacks/`](./stacks/), a `docker-compose.yml` file defines
how that specific variant is architected.
You can use this directly with `docker compose`.

```sh
cd stacks/standard
docker compose up -d
```

<hr/>

[Website][website] &middot; [@techlifemusic][techlifemusic]

[website]: https://richardneililagan.com
[techlifemusic]: https://mastodon.social/@techlifemusic

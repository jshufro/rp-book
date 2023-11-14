# rp-book

rp-book is a community-maintained index of Rocket Pool sites and tools that are useful.
It is deployed by default to [book.sprocketpool.net](https://book.sprocketpool.net)

# Contributing

rp-book uses [mdbook](https://github.com/rust-lang/mdBook) to render html from markdown.
For your convenience, a `docker-compose.yml` file is provided.
Run `docker compose up` to build the mdbook binary and start a container with host-mapped port 3000.
You will be able to access the rendered content at [localhost:3000](http://localhost:3000)

## Adding content

Try to find an existing category for your content.
Add one if none exists.

Copy the existing formatting.
Images should be 900x450.

Order should be alphabetical.

## Spellcheck

Your pull request will automatically be spellchecked.
You may need to add words to `wordlist.txt` if they are not in the dictionary.

`wordlist.txt` must be kept in alphabetical order.

## Deploying

Once your pull request is merged it will be automatically deployed in one or two minutes.

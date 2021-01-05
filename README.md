# Stripe REPL

I use stripe a lot and I like having Node REPL ready with support of top level await and ability to use stripe in REPL session, this repo does that.

## How to enable top level await

Here is the official link: https://nodejs.org/api/repl.html#repl_await_keyword, it is supported on Node 10 or greater. The following methods can be used

- Supply `--experimental-repl-await` to option as node command
- Adding `export NODE_OPTIONS="--experimental-repl-await"` to your .bashrc/.zshrc (Parmanent)
- Running node as `NODE_OPTIONS="--experimental-repl-await" node index.js`


## How to use
- Clone it
- Copy `.env.example` to `.env` and add `STRIPE_SECRET_KEY`
- Run `npm install` and then `node .`

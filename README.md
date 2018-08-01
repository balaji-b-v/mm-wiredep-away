# mm-wiredep-away
Small changes on top of wiredep-away Library


> Wire ~~Bower~~ *[Yarn][yarn]* dependencies to your source code.
with customizations on top of base wiredep-away library

## Getting Started
 
**Read [this][post] blog post from @sheerun**

Install the module with [**Yarn**][yarn]:

```bash
yarn add mm-wiredep-away
# If you still having the other one
yarn remove mm-wiredep-away
```

Replace every `wiredep` import with `mm-wiredep-away`.

## Inspiration

This package was created to help developers move away from bower :)

## Recomendations

You should use this package to help you with the migration to [Yarn][yarn], then 
you'll need to start using a advanced build like (Webpack, Rollup, Browserify, etc...), to
to import your dependencies directly from `node_modules`.

## Configuration
To see functionallity check this fork base.

## Contributing
File or grab and issue first, then clone this repo and help me out!

 [post]: https://bower.io/blog/2017/how-to-migrate-away-from-bower/
 [yarn]: https://yarnpkg.com
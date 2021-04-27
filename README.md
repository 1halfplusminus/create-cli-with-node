# Create Cli with node JS

[SOURCE](https://www.twilio.com/blog/how-to-build-a-cli-with-node-js)

## Why create CLIs with Node.js

One of the reasons why Node.js got so popular is the rich package ecosystem with over 900,000 packages in the [`npm` registry](https://npmjs.com). By writing your CLIs in Node.js you can tap into this ecosystem including it's big amount of CLI-focused packages. Among others:

- [`inquirer`](http://npm.im/inquirer), [`enquirer`](http://npm.im/enquirer) or `[prompts](https://npm.im/prompts)` for complex input prompts
- [`email-prompt`](http://npm.im/email-prompt) for convenient email input prompts
- [`chalk`](http://npm.im/chalk) or `[kleur](https://npm.im/kleur)` for colored output
- [`ora`](http://npm.im/ora) for beautiful spinners
- [`boxen`](http://npm.im/boxen) for drawing boxes around your output
- [`stmux`](http://npm.im/stmux) for a `tmux` like UI
- [`listr`](http://npm.im/listr) for progress lists
- [`ink`](http://npm.im/ink) to build CLIs with React
- [`meow`](http://npm.im/meow) or [`arg`](http://npm.im/arg) for basic argument parsing
- [commander](http://npm.im/commander) and [`yargs`](https://www.npmjs.com/package/yargs) for complex argument parsing and subcommand support
- [`oclif`](https://oclif.io/) a framework for building extensible CLIs by Heroku (`[gluegun](https://infinitered.github.io/gluegun/#/)` as an alternative)

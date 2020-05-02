# runnerty-quick-start

**Clone and run for a quick way to see Runnerty in action.**

A basic Runnerty planification needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies. Extra plugins goes here (**triggers, notifiers and executors**).
- `config.json` - Configuration file for Runnerty's plugins also global values are set here.
- `plan.json` - The processes planification and dependencies are specified here.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com), [Node.js 10.20.1](https://nodejs.org/en/download/) or higher and [Runnerty 2.6.0](https://github.com/runnerty/runnerty) installed on your computer.

From your command line:

```bash
# Install runnerty
npm i -g runnerty

# You can check the correct instalation with the command  
runnerty --version
```

Note: It's possible that you have to use super user permissions. More: [fix npm permisions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

```bash
# Clone this repository
git clone https://github.com/runnerty/runnerty-quick-start

# Go into the repository
cd runnerty-quick-start

# Install dependencies
npm install

# Run the example
runnerty
```

## Resources for Learning Runnerty

- [docs.runnerty.io](http://docs.runnerty.io) - all of Runnerty's documentation

## License

[MIT License](LICENSE)

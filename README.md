# Baksia

https://baksia.digdir.no

## Run site locally

For a full description of how to do changes to Baksia, please read [CONTRIBUTING.md](https://github.com/digdir/baksia/blob/main/CONTRIBUTING.md).

Requirements: [Hugo](https://gohugo.io/installation/) (extended) and [node (npm)](https://nodejs.org/en/learn/getting-started/how-to-install-nodejs)

1. Clone repo:
   ```shell
   git clone https://github.com/digdir/baksia --recurse-submodules --remote-submodules
   ```
2. Navigate to folder and run Hugo:
   ```shell
   cd baksia
   ```
3. Install requirements
   ```shell
   npm install
   ```
4. Run site locally
   ```shell
   hugo serve --navigateToChanged
   ```
5. Application available locally at: http://localhost:1313

## Theme & design

- [digdir-hugo-theme](https://github.com/felleslosninger/digdir-hugo-theme)
- [Figma design file](https://www.figma.com/file/oT5ZgqREUJGgYwXIgp3HWL/Baksia?node-id=3836%3A46985)

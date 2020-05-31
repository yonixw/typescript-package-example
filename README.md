# Guide Used:
* https://www.digitalocean.com/community/tutorials/setting-up-a-node-project-with-typescript
* https://medium.com/cameron-nokes/the-30-second-guide-to-publishing-a-typescript-package-to-npm-89d93ff7bccd

# Bugs with VSCODE extension
Looks like only (1) prior include or  (2) @types package will be loaded automatically. So we need at least 1 import before the extension will suggest other. https://github.com/microsoft/TypeScript/issues/37812
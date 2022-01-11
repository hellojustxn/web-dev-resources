# Web development resources that you might find helpful

## Tutorials
https://causeway.soe.ucsc.edu/#/select/-components

https://css-tricks.com/

https://30secondsofcode.com/

https://flexboxfroggy.com/

https://frontendmentor.com/

https://shortcuts.design/

https://dev.to/

https://www.theodinproject.com/

## Tools
https://responsively.app/

## Examples
https://codemyui.com/

## Environment Set up Snippets
### Install Brew
General package manager for macOS/Linux
```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

### Install NVM
Node version manager used to install & use specific versions of node in your projects.
```brew install nvm```

### Install a specific version of Node using NVM
```nvm install 14```

### Use a specific version of Node using NVM
```nvm use 14```

## Github Set up Snippets
### Adding/tracking a file, commit, push
```git add <filename>```

```git commit -m "Description of what you've done"```

```git push```

### Get latest branches
```git fetch```

### Changing branches
```git checkout <branch-name>```

### Branching from an existing branch
```git branch <new branch> <existing branch>```

## Angular Schematics
```ng generate @tech4good/angular-schematics:<schematic>``` 
where (schematic = module, container, component, or entity)

Note: The Angular schematic script cannot create a component when its container is nested in a subfolder. When creating a component within a container that's enclosed by a folder (e.g. activities/draw-it-out/<some dio container>, temporarily move the container into the app folder, run the angular schematics, and move the container back into the original folder.

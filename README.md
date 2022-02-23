# NodePkg-Actions
Automatically generate `package-lock.json` or `node_modules` or `yarn.lock` for people who using Vercel and etc.  
Also, you can check your dependencies security if you enabled dependabot alert or `npc` command option.

## How to use?
Just **Fork** this repo, and follow under steps!

Make directory what named your project name under root. (You should set it to your `package.json`'s `name`.) (ex. `react-tsx-website`)  
And put your `package.json` into it.  
After that, make `run.txt` into same directory. (We're going to use this file to generate)

Setting step finished!  
But you can't do anything now, so choose step from under rows!

### Generate `package-lock.json`
Add **`npm-install`** text into `run.txt`.  

### Generate `yarn.lock`
Add **`yarn-install`** text into `run.txt`.

### Update packages(npm-check-updates)
Add **`ncu`** text into `run.txt`.

## After a while, GitHub Actions will push files automatically.
If GitHub Actions doesn't work, you should check `Settings` -> `Actions` -> `General`.  
If  disabled, please enable `Allow all actions`.

# If you like this, please :star: to this repository!
Thanks for using this!

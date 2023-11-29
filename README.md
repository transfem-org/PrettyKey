<p align="center">
    <img src="https://cdn.transfem.social/files/thumbnail-2fd35c29-6b3c-44b7-87a9-045fe8dde5e7.webp" width="80" />
    <h2 align="center">Sharkey Theme Repository</h2>
</p>

<p align="center">A Repository for Sharkey, Misskey and FireFish Themes aswell as Sharkey Compatible CSS Themes</p>

## Installation of Themes

### User

1. Open Settings
2. Under `Client settings`, click `Themes`
3. Click `Install Theme`
4. Under `Theme code`, paste in the contents of the theme you want to install
5. Click `Install`
6. Go back to `Themes` page
7. Select the Theme you installed
8. Profit

### Instance admin
1. Go to Control Panel > Branding or General (if using Misskey v12 / Firefish)
2. Under "Instance-wide default light theme", paste the contents of the theme or light varient of theme you want to use
3. Under "Instance-wide default dark theme", paste the contents of the theme or dark varient of theme you want to use
    
## Repository Structure and Licensing

### Repository Structure
All themes submitted to the repository should follow this structure
```
- css
 ↪ theme name
  ↪ README.md
  ↪ themename.css (if there is multiple files include all of the needed theme files)
  ↪ LICENSE (If different from repository)
  ↪ screenshot.png (if theres multiple varients include screenshots for all)
- themes
 ↪ theme name
  ↪ README.md
  ↪ themename.json5 (if there is multiple files include all of the needed theme files)
  ↪ LICENSE (If different from repository)
  ↪ screenshot.png (if theres multiple varients include screenshots for all)
```

### Licensing
All files in this repository are licensed under Creative Commons Zero v1.0 Universal unless stated otherwise

### Adding your Theme
feel free to make a pr for adding themes, your pr should follow the repository structure and credit the theme maker aswell as have the license of the theme
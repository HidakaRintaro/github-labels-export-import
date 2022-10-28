# GitHub Labels export import
Export the Labels of a repository on GitHub and import them into another repository.

## Languages
- [English](README.md)
- [Japanese / 日本語](README-ja.md)

## Description
1. Remove all labels from the import repository
2. Get all labels from the export repository
3. Add labels retrieved from the export repository to the import repository

##  Install
```bash
git clone git@github.com:HidakaRintaro/github-labels-export-import.git
```

## Setup
```bash
npm install
```

## Usage
```bash
node index.js <exportOwner> <exportRepo> <importOwner> <importRepo> <token>
```

## LICENSE
[MIT](LICENSE)

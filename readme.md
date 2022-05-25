# Biocuration how to

A repository to guide users for community curation.

It is markdown based. You can use nested unordered lists (`* ` lists in markdown) to generated nested dropdowns. Ordered lists (`1. `, etc.)are not shown as dropdowns.

The markdown is rendered as a website, for now hosted at https://www.genestorian.org/ontology_howto/ but it can be changed in the future.



## How to edit the content in GitHub

Simply edit the `content.md` file in github, and commit your changes. They should go live immediately.

## How to edit locally

Clone the repository.

```bash
git clone https://github.com/manulera/ontology_howto
```

You can see the website by opening the file `index.html` in your browser. If you make changes to the `content.md` file, you will have to update the website to see them. If you use vscode for editing markdown, you can use [vscode live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) to see the changes live.

Make your changes locally, then commit them to the repository:

```bash
git add .
git commit -m "your message"
```

Changes commited like this should also go live immediately.
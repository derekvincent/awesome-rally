# Contribution Guidelines<!-- omit from toc -->

Thank you for your interest in making our project better. This page will provide a quick overview on how to contribute to the project and get involved. Everyone is welcome to contribute, and this guide will outline how to get the most out of helping. 

## Table of Contents<!-- omit from toc -->
- [Add or Update a site or item](#add-or-update-a-site-or-item)
- [Add or Update Categories or Labels](#add-or-update-categories-or-labels)
- [Improve Awesome List generation](#improve-awesome-list-generation)
- [Create your own Awesome List](#create-your-own-awesome-list)
- [Code of Conduct](#code-of-conduct)

## Add or Update a site or item 

If you have suggestion for a new or existing site improvements you can choose on the following ways: 

- Suggest a new site or item by opening an [add item issue](https://github.com/derekvincent/awesome-list-template/issues/new?template=01-suggest-item.yml).
- Suggest improvements to an existing site or item open an [update item issue](https://github.com/derekvincent/awesome-list-template/issues/new?template=02-update-item.yml).
- Add or update an item by modifying the [awesome-list.yaml](https://github.com/derekvincent/awesome-list-template/blob/main/awesome-list.yaml) file and submitting a pull request. This can also be done directly in the [GitHub UI](https://github.com/derekvincent/awesome-list-template/edit/main/awesome-list.yaml).


Before opening an issue or pull request please ensure you are following these guidelines: 

- Make sure the site or item is not all ready add to or suggested in the Awesome List. You can check by searching in the `awesome-list.yaml`, `README.md` or in the issues lists. There are a number of reasons that the site or item maybe included in the Awesome list but not currently being displayed in the `README.md`, if you have question please raise an issue. 
- Add sites or items in the `awesome-list.yaml` only and never in the `README.md` directly. The `README.md` is generated from the `awesome-list.yaml` and will overwrite the contents of the README. Use the yaml format and [item properties] document below: 

    ```yaml
    - link_id: https://github.com/derekvincent/awesome-list-generator
      name: Awesome List Generator
      description: Generate markdown based Awesome Lists from a yaml file. 
      labels: ["github", "documenation"]
      category: cool-tools
    ```

- Create an individual issue or pull request for each item
- For a new site or item use the following title format `[New Item]: item name`. 
- For an update to an existing site or item use the following title format `[Update Item]: item name`.
- If the item does not fit into any existing category, you can leave it plank, and it will automatically be assigned to the `Other` category, or you can suggest a new category as outlined in the [Add or Update Categories or Labels]().

## Add or Update Categories or Labels

If you would like to suggest changes or new to the list categories or labels choose the follow options: 

- Suggest a change or new category opening an [update category issue](https://github.com/derekvincent/awesome-list-template/issues/new?template=01-suggest-item.yml).
- Suggest a change or new label open an [add or update item label](https://github.com/derekvincent/awesome-list-template/issues/new?template=04-update-label.yml).
- Add or update a category or label by modifying the [awesome-list.yaml](https://github.com/derekvincent/awesome-list-template/blob/main/awesome-list.yaml) file and submitting a pull request. This can also be done directly in the [GitHub UI](https://github.com/derekvincent/awesome-list-template/edit/main/awesome-list.yaml).

Before opening an issue or pull request please ensure you are following these guidelines: 

- Make sure the category or label is not all ready add to or suggested in the Awesome List. You can check by searching in the `awesome-list.yaml`, `README.md` or in the issues lists.  
- Add categories or labels in the `awesome-list.yaml` only and never in the `README.md` directly. The `README.md` is generated from the `awesome-list.yaml` and will overwrite the contents of the README.
- Create an individual issue or pull request for each item
- For a new category or update use the following title format `[Category]: cateogry name`. 
- For a new label or update use the following title format `[Label]: label name`.

## Improve Awesome List generation
If you would like to improve list this list in ways other than described above please open an [issue](https://github.com/derekvincent/awesome-list-template/issues/new?template=05-questions.yml). If you have suggestion around rendering, metadata collections, or list generations please open an [awesome-list-generator issue](https://github.com/derekvincent/awesome-list-generator/issues/new).  

## Create your own Awesome List
If you want to create your own awesome list using the awesome-lists-generator, we recommend following [this guide](https://github.com/derekvincent/awesome-list-template/blob/main/create-my-own-awesome-lists.md). With this guide, it will only take about 3 minutes to get you started. It is already set-up to automatically run the awesome list generator via a GitHub Action and includes other useful template files.

## Code of Conduct
All members of the project community must abide by the [Contributor Covenant, version 2.0](https://github.com/derekvincent/awesome-list-template/blob/main/CODE_OF_CONDUCT.md). Only by respecting each other we can develop a productive, collaborative community. Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting a project maintainer.
# **Ritchie CLI Documentation**
This repository uses [**hugo server**](https://gohugo.io/commands/hugo_server/) and contains the [**Ritchie CLI**](https://ritchiecli.io/) official documentation. 


## **What is Ritchie?** 
### All your automations in one place

**Ritchie CLI** is an open source project that allows to **create**, **store** and **share** automations, executing them through command lines.

For more information, check out [**Ritchie's documentation**](https://docs.ritchiecli.io).

## **Requirements**
To edit, run and build this project, you will need:
* [**Yarn**](https://yarnpkg.com/)

* [**Node**](https://nodejs.org/en/)
  - To check the installation, run **`npm -v`** and **`node -v`** in your terminal.

* [**Hugo**](https://gohugo.io/getting-started/installing/)
  - To check the installation, run **`hugo version`** in your terminal.

# **Install**
Run the command below to install the dependencies: 
```bash
npm run dependencies
```

or

```bash
npm i && git submodule init && git submodule update
```

## **Build**
Run the following command to build this project: 

```
npm run build
```

And you can see the folder generated by hugo into **`./dist`** path.

## **Running**

To see this project running, use the command below: 
```bash
hugo serve
```

or

```bash
npm start
```

- Now, check if the `Web Server is available at http://localhost:1313/docs/`.

## **Running the website locally**

Once you've cloned this repo, from the `root` folder, run:

```
hugo server
```

# **How to contribute?**

You can suggest a change, a fix, or improvements to our documentation, for example: 
- Add missing information.
- Fix a grammar or code error.
- Suggest a new section.
- Translate. 

### **Open an issue**
Follow the steps below: 

**Step 1.** Access [**GitHub Issues**](https://github.com/ZupIT/docs-horusec/issues) and open an issue;
- **New contents** should be added to the [**`content` folder**](https://github.com/ZupIT/docs-ritchie/tree/main/content).

**Step 2.** Describe the issue or change you want to make; 
- **Always** base your work on the project's `main` branch, naming your new branch according to the following guide:


![git-branchs](https://user-images.githubusercontent.com/22433243/117700179-0f060780-b19c-11eb-8d03-42cfbd2de798.png)

**Examples:** `feature/name` or `fix/name`

**Step 3.** Make your changes;

**Step 4.** Open a new Pull Request for **each new content** and for **each language** and fill in the template; 

**Step 5.** Ritchie's team will check your issue, review it, and then approve your PR. 


# **Community**

If you have any questions or ideas, let's chat in our [**Zup Open Source Forum**](https://forum.zup.com.br).

**Ritchie Team**
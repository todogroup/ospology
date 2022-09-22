# Welcome to the OSPO Mind Map 🧭

The OSPO Mind Map schemes the main Open Source program Office's responsibilities, roles, behavior and team size within the Ecosystem. An interactive OSPO Mind Map version can be found at: https://ospomindmap.todogroup.org/

This folder contains the resulting mind map, and is open and available to everyone that would like to provide feedback and help to improve its content.

## 📚 About OSPO Mind Map Project

The Mind map is structured into four main areas:

* Responsibilities
* Roles
* Behavior
* Team Size
The initial [mind map](https://github.com/todogroup/ospology/discussions/75#discussion-3962305) was created using MindMup2.
However, in order to ease community contributions, a second version of this mind map was created using [Markmap](https://markmap.js.org/) that is managed as markdown that renders an interactive mind map. See Mind Map Syntax below for notes on how to use it.

## 🧩 Project Structure

This folder contains four main resources:

| Folder | Extension | Content |
| --- | --- | --- |
| Content | `.md` | Source markmap format used to generate the mindmap |
| Img | `.svg` | Rendered mindmap suitable for printing |
| Img | `.html` | Rendered interactive mindmap |
| additional-info | `*` | Initial announcement and information for the mindmap project |

## 🙋 Contributing to the project

### Content

Follow these steps to create a new version of the Mind map:

1. From `ospology/ospo-mindmap/`, run
   ```sh
   npm install
   ```
2. Make your changes to [`Content/ospomindmap.md`](Content/ospomindmap.md) (or [`Content/ospomindmap_jp.md`](Content/ospomindmap_jp.md))
3. Run `npm run dev` to see your changes live as you edit.
4. Commit your changes and [open a PR](https://github.com/todogroup/ospology/pulls)

**Markmap Syntax**

Markmap is a tool (under [MIT licence](https://github.com/gera2ld/markmap/blob/master/LICENSE)) designed by @gera2ld that parses markdown content and extract its intrinsic hierarchical structure and renders an interactive mindmap, aka markmap. Please see [markmap documentation](https://markmap.js.org/docs) for further details.

### Visualization and html generation


to visualize your mindmap localy you can use:

**VSCode integration**
[Download](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode)

**Markmap-cli**

Use markmap command-line in a local terminal.

```
$ npx markmap-cli path/to/markmap.md
```
You can also install it globally:
```
$ yarn global add markmap-cli markmap-common
$ markmap path/to/markmap.md
```
There is a watch mode so that you could edit the Markdown file and get updates on the fly:
```
$ markmap -w path/to/markmap.md
```

### Feedback and Suggestions

Do you want to improve this guide? Please open an [issue](https://github.com/todogroup/ospology/issues) with your ideas.


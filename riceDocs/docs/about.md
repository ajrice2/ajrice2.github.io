#RiceDocs - About

----------------------------------------------------------------------------

## Site Purpose

To create a centralized location for storing IT documentation and notes from classes.  Additionally, I am planning to work on projects beyond the scope of my course work and sharing it on this site.

----------------------------------------------------------------------------

## Site Projects

<table>
  <thead>
    <th>Goal</th>
    <th>Technologies</th>
    <th>Status</th>
    <th>Discussion Link</th>
  </thead>
  <tr>
    <td>Host Static Site</td>
    <td>GitHub Pages, MkDocs</td>
    <td>In-Progress</td>
    <td class="text-danger ">TODO</td>
  </tr>
</table>

----------------------------------------------------------------------------

## Reference Sites

### Markdown
- **Cheat Sheet** - [A quick reference to the Markdown syntax.](https://www.markdownguide.org/cheat-sheet/)
- **Download** - [Main web site for Markdown.](https://daringfireball.net/projects/markdown/)
- **Dingus** - [Experiment with Markdown on the web.](https://daringfireball.net/projects/markdown/dingus)
- **Table Generator** - [Generate tables in Markdown format.](https://www.tablesgenerator.com/)

### MkDocs
- **MkDocs** - [Static site generator used for this site.](https://www.mkdocs.org/)
- **Cinder** - [The MkDoc Theme used for this site.](https://sourcefoundry.org/cinder/)

### GitHub
- **Pro Git Book** - [Online Textbook for learning Git](https://git-scm.com/book/en/v2)

### Emoji's
- **Emoiji Copy** - [Add Emoji's to website.](https://www.emojicopy.com/)
- **Emojipedia** - [Add Emoji's to webiste.](https://emojipedia.org/)

### Other
- **Mike DeMaso MkDocs** - [MkDocs Setup Example](https://mikedemaso.com/tech/2019-06-20-setting-up-mkdocs/)

----------------------------------------------------------------------------

## Steps for Updating GitHub Pages

1. Make updates to your web site.
2. In the terminal, go to the folder containing mkdocs.yml and type 'mkdocs build'.
3. In the terminal, navigate to the github.io folder and add/commit/push changes to github.
  - 'git status' (confirm changes were made)
  - 'git add .' (select the files to commit)
  - 'git commit -am' (document changes that were made)
  - 'git push' (push the code to github)


----------------------------------------------------------------------------

## Random Items to Use Later


* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

        ## Site File Structure Example

        ```
        riceDocs
        │   README.md
        │   file001.txt    
        │
        └───folder1
        │   │   file011.txt
        │   │   file012.txt
        │   │
        │   └───subfolder1
        │       │   file111.txt
        │       │   file112.txt
        │       │   ...
        │   
        └───folder2
            │   file021.txt
            │   file022.txt
        index.html
        README.md
        ```

        ```
        {
        "firstName": "John",
        "lastName": "Smith",
        "age": 25
        }
        ```

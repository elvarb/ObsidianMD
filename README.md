
<img width="1531" height="420" alt="ObsidianMD Banner" src="https://github.com/user-attachments/assets/ca6cd6a3-fa05-479a-9b44-846518d0f41a" />

# ObsidianMD
Collection of ObsidianMD resources

## Repository Content

### CSS snippets/

---
#### [ObsidianMD/CSS snippets/Attachment folder.css](https://github.com/elvarb/ObsidianMD/blob/main/CSS%20snippets/Attachment%20folder.css)
Makes all folders named "_attachments" faded, the targeted folder can easily be modified.

<img width="323" height="98" alt="image" src="https://github.com/user-attachments/assets/7d518ca2-858f-419d-9cbe-9012c0915de3" />


#### [ObsidianMD/CSS snippets/Shaded folders.css](https://github.com/elvarb/ObsidianMD/blob/main/CSS%20snippets/Shaded%20folders.css)
Shades each nested folder level.

<img width="396" height="201" alt="image" src="https://github.com/user-attachments/assets/26770e81-8cd2-4b52-a576-dcb6c2888713" />


#### [ObsidianMD/CSS snippets/Stacked tabs.css](https://github.com/elvarb/ObsidianMD/blob/main/CSS%20snippets/Stacked%20tabs.css)
Modifies how tabs look and stacks them instead of showing only the first characters in the file names. 

<img width="760" height="101" alt="image" src="https://github.com/user-attachments/assets/16ed3bf7-dd1c-47ac-83e2-b409df30ad7f" />

Becomes

<img width="800" height="137" alt="image" src="https://github.com/user-attachments/assets/4f6faac5-3f6d-417f-bd96-44ae05456654" />

### Dataview/
---

#### [ObsidianMD/Dataview/Find broken frontmatter.md](https://github.com/elvarb/ObsidianMD/blob/main/Dataview/Find%20broken%20frontmatter.md)
A DataviewJS snippet that will list all notes that have broken frontmatter/properties/yaml.

<img width="737" height="161" alt="image" src="https://github.com/user-attachments/assets/9f8c71a9-bded-4c37-af49-83004de352d1" />



### Templater/

---
#### [ObsidianMD/Templater/DV inline property from another file.md](https://github.com/elvarb/ObsidianMD/blob/main/Templater/DV%20inline%20property%20from%20another%20file.md?plain=1)
Templater template that uses Dataview to display a property from another note.
- The user is prompted with with an input box to search for a note.
  - <img width="853" height="188" alt="image" src="https://github.com/user-attachments/assets/9f5d9716-b0b2-4aaa-8c7b-9b1bd5f335d9" />
- When the user has selected a note another input box shows up that will list all the available properties from that specific note.
  - <img width="851" height="252" alt="image" src="https://github.com/user-attachments/assets/eb9ae65f-5a1b-404c-a20f-21edb4b13acd" />
- After selecting a property a dataview query will be inserted in the current note.
  - `$= dv.page("2025-08-08").modified`

## Tips and tricks

### Bookmarklet
Create a custom bookmarklet in your browser that will create a markdown link of the currently opened tab.

`[GitHub](https://github.com/)`


## Other Resources

### CSS Snippets

#### [efemkay/obsidian-modular-css-layout: CSS Layout hack for Obsidian.md](https://github.com/efemkay/obsidian-modular-css-layout)
Easy to use, flexible and practical css snippets that provide a real value. 
- [obsidian-modular-css-layout/MCL Gallery Cards.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Gallery%20Cards.css)
- [obsidian-modular-css-layout/MCL Multi Column.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Multi%20Column.css)
- [obsidian-modular-css-layout/MCL Wide Views.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Wide%20Views.css)


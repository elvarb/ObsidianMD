<%*
const items = app.vault.getMarkdownFiles();
const selectedItem = await tp.system.suggester(item => item.basename, items);

if (selectedItem) {
  // Get file cache to extract frontmatter
  const fileCache = app.metadataCache.getFileCache(selectedItem);
  const frontmatter = fileCache?.frontmatter;

  if (frontmatter) {
    // Extract frontmatter keys
    const keys = Object.keys(frontmatter);
    const selectedKey = await tp.system.suggester(key => key, keys);

    if (selectedKey) {
      // Output an inline Dataview query wrapped in backticks
      tR = "`$= dv.page(\"" + selectedItem.basename + "\")." + selectedKey + "`";
    }
  } else {
    tR = "No frontmatter found in the selected file.";
  }
} else {
  tR = "No file selected.";
}
-%>

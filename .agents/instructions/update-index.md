# Update the HTML index

When asked to update the index:

1. Recursively find every `.html` file in the repository.
2. Exclude the root `index.html` file from the results.
3. Express each result as its full path relative to the repository root.
4. Sort the paths alphabetically in one flat list.
5. Update the `Index` section in `README.md` with a Markdown link for every path. Preserve unrelated README content.
6. Rebuild `index.html` as a minimal, valid HTML document containing the same paths as relative links.
7. Verify that the README and index lists match, every link points to an existing file, and no lesson HTML files were modified.

Do not add external scripts, styles, or assets to `index.html`. There's already an existing minimal styling in the page. Don't remove it either.

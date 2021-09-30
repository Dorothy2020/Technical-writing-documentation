Mkdocs syntax
 a).MkDocs pages must be authored in Markdown, a lightweight markup language which results in easy-to-read, easy-to-write plain text documents that can be converted to valid HTML documents in a predictable manner.
b).MkDocs includes support for extending the Markdown syntax with Python-Markdown extensions. 
c).One can also create multi-page documentation, by creating several Markdown files for example
mkdocs.yml
docs/
 index.md
 about.md
 License.md
 
d).The file layout you use determines the URLs that are used for the generated pages.
e).Files and directories with names which begin with a dot (for example: .foo.md or .bar/baz.md) are ignored by MkDocs, which matches the behavior of most web servers.

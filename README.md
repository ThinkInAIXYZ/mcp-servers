# Go MCP Server List

This repository provides a curated list of Model Context Protocol (MCP) servers implemented in Go. You can use these servers as references or starting points for your own AI context integration projects.

## Introduction

MCP is an open protocol that standardizes how applications provide context to LLMs. Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect your devices to various peripherals and accessories, MCP provides a standardized way to connect AI models to different data sources and tools.

## Contributing

Feel free to contribute by either:
1. Adding your server implementation directly as a package in a folder
2. Adding a link to your repository in this README

If adding a package directly, please create a `README.md` inside with author information.


## Server List

<!-- Add repository links here -->
+ [text2sql](#text2sql)
+ [dify-retriever](#dify-retriever)

### text2sql

<table>
<tr><th align="left">GitHub</th><td>https://github.com/wangle201210/mcp-server</td></tr>
<tr><th align="left">Website</th><td>/</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>stdio</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>GO</td></tr>
</table>

text2sql is a natural language to SQL query service based on the go-mcp framework, supporting the conversion of natural language questions into executable SQL statements and returning query results.

<details>
<summary>Screenshots</summary>

![](./screenshots/text2sql/res.png)

</details>

### dify-retriever

<table>
<tr><th align="left">GitHub</th><td>https://github.com/wangle201210/mcp-server</td></tr>
<tr><th align="left">Website</th><td>/</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>stdio</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>GO</td></tr>
</table>

dify-retriever-mcp, using the knowledge base to make AI answers more in line with expectations
<details>
<summary>Screenshots</summary>

![](./screenshots/dify-retriever/res.png)

</details>

## Maintenance

Each author is responsible for maintaining their own code. However, if you submit a package directly to this repository, you allow the community to fix and improve it. You can also submit pull requests to fix existing packages.

## License

Please see individual packages for license information.
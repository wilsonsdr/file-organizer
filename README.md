<h1 align="center">File Organizer</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/wilsonsdr/file-organizer?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/wilsonsdr/file-organizer?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/wilsonsdr/file-organizer?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/wilsonsdr/file-organizer?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/wilsonsdr/file-organizer?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/wilsonsdr/file-organizer?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/wilsonsdr/file-organizer?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center">
	🚧  File Organizer 🚀 Under construction...  🚧
</h4>

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/wilsonsdr" target="_blank">Author</a>
</p>

<br>

## :dart: About

File Organizer is a simple script that organizes files based on their extensions. It scans a specified source directory for files and moves them to destination folders according to their file types. The script categorizes files into groups such as documents, images, and videos, and then moves them to their respective folders. Additionally, it provides error handling to manage any issues that may arise during the organization process.

## :sparkles: Features

:heavy_check_mark: **Reading files**: The code reads files from specified `source` directory;\
:heavy_check_mark: **Filtering by Extension**: For each extension in the `extensions` object, it filters files in the `source` directory based on the extension;\
:heavy_check_mark: **Moving Files**: It moves files to different destination folders (`dest1`, `dest2`, `dest3`) based on their extension;\
:heavy_check_mark: **Error handling**: The `try...catch` block captures errors that may occur during the file moving process, providing a more robust error handling mechanism;

## :rocket: Technologies

The following tools were used in this project:

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## :white_check_mark: Requirements

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting

```bash
# Clone this project
$ git clone https://github.com/wilsonsdr/file-organizer

# Access
$ cd file-organizer

# Run the project
$ node app.js
```

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/wilsonsdr" target="_blank">wilsonsdr</a>

&#xa0;

<a href="#top">Back to top</a>

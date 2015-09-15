# Advanced Archival Description Lectures

Class lectures for Advanced Archival Description, a graduate-level class taught at NYU, presented using [reveal.js](http://lab.hakim.se/reveal-js/).

## Accessing Lectures

All lectures are written in [Github-flavored Markdown](https://help.github.com/articles/github-flavored-markdown/), and can be downloaded in bulk as a ZIP file. Better yet, you can set up [git](https://help.github.com/articles/set-up-git/) on your local machine and pull down changes as I update these files.

## Full Local Installation

If you want to view slides as they appeared in class, you'll need to clone the [slide deck repository](https://github.com/helrond/HISTGA2031SlideDeck) and follow these instructions to set up reveal.js on your local machine.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/hakimel/reveal.js.git
   ```

5. Navigate to the reveal.js folder
   ```sh
   $ cd reveal.js
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

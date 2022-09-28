# React Course with Academind

A React course with Academind in Udemy. This repo is my notes for future references.

## TOC

1. Exports and Imports
   - 2 types of Exports
     1. default for unnamed
        `export default ...;`
     2. named
        `export const specificModule = ...;`
   - corresponding Imports:
     1. for unnamed export
        `import givenNickname from './path/to/file.js';`
     2. named export
        `import { specificModule } from './path/to/file.js';`
   - these Imports can be bundled and called with .
     `import * as giveBundleAName from './path/to/file.js';`
     `giveBundleAName.specificModule`

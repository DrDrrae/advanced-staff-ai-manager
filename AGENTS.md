# AI Agent Instructions
This file provides essential information for coding agents working on this repository. Following these guidelines will minimize exploration time, reduce build failures, and improve code quality.

## Repository Summary
**DrDrrae/advanced-staff-ai-manager** is a fork of **StixsmasterHD4k/advanced-staff-ai-manager**. This is a plugin for the video game [OpenRCT2](https://github.com/OpenRCT2/OpenRCT2/tree/develop).

## High-Level Details
Scripts are written in ECMAScript 5 compatible JavaScript. OpenRCT2 currently uses the [duktape](https://duktape.org) library to execute scripts. This however does not mean you need to write your plugin in JavaScript, there are many transpilers that allow you to write in a language of your choice and then compile it to JavaScript allowing it to be executed by OpenRCT2. JavaScript or [TypeScript](https://www.typescriptlang.org) is recommended however, as that will allow you to utilise the type definition file we supply (`openrct2.d.ts`). If you would like to use ECMAScript 6 or later which contain features such as arrow functions, the `let` keyword or classes, then you will need to use a transpiler such as [Babel](https://babeljs.io) or [TypeScript](https://www.typescriptlang.org).

## Official references for writing plugins are:
* The API: `openrct2.d.ts` distributed with OpenRCT2.
* Our collection of sample scripts: [OpenRCT2/plugin-samples](https://github.com/OpenRCT2/plugin-samples)
* A TypeScript plugin comprised of multiple sources: [IntelOrca/OpenRCT2-ParkManager](https://github.com/IntelOrca/OpenRCT2-ParkManager)
  
## Further Reading
[Scripts for OpenRCT2](https://github.com/OpenRCT2/OpenRCT2/blob/develop/distribution/scripting.md)
[openrct2.d.ts](https://raw.githubusercontent.com/OpenRCT2/OpenRCT2/refs/heads/develop/distribution/openrct2.d.ts)
[OpenRCT2](https://github.com/OpenRCT2/OpenRCT2)

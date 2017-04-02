# api documentation for  [gulp-typescript (v3.1.6)](https://github.com/ivogabe/gulp-typescript)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-typescript.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-typescript)
#### A typescript compiler for gulp with incremental compilation support.

[![NPM](https://nodei.co/npm/gulp-typescript.png?downloads=true)](https://www.npmjs.com/package/gulp-typescript)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-typescript/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-typescript_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-typescript/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp-typescript/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Ivo Gabe de Wolff",
        "url": "http://ivogabe.com/"
    },
    "bugs": {
        "url": "https://github.com/ivogabe/gulp-typescript/issues"
    },
    "contributors": [
        {
            "name": "Jesper Jonsson",
            "email": "jesper.m.jonsson@gmail.com"
        },
        {
            "name": "Shogo Iwano",
            "email": "shiwano@gmail.com"
        },
        {
            "name": "Martin Poelstra",
            "email": "m.poelstra@spiritit.com"
        },
        {
            "name": "Jakub Olek",
            "email": "bukaj.kelo+github@gmail.com"
        },
        {
            "name": "Ilan Frumer",
            "email": "IlanFrumer@gmail.com"
        },
        {
            "name": "James Whitney",
            "email": "james@whitney.io"
        },
        {
            "name": "Jaroslaw Zalucki",
            "email": "mad.jaro@gmail.com"
        },
        {
            "name": "Yui Tanglertsampan",
            "email": "yuisu@microsoft.com"
        }
    ],
    "dependencies": {
        "gulp-util": "~3.0.7",
        "source-map": "~0.5.3",
        "through2": "~2.0.1",
        "vinyl-fs": "~2.4.3"
    },
    "description": "A typescript compiler for gulp with incremental compilation support.",
    "devDependencies": {
        "@types/chalk": "^0.4.31",
        "@types/gulp-util": "^3.0.29",
        "@types/node": "^6.0.46",
        "@types/source-map": "^0.1.29",
        "@types/through2": "^2.0.31",
        "@types/vinyl": "^1.2.30",
        "@types/vinyl-fs": "0.0.28",
        "gulp": "~3.9.1",
        "gulp-concat": "~2.6.0",
        "gulp-diff": "~1.0.0",
        "gulp-header": "~1.7.1",
        "gulp-plumber": "~1.1.0",
        "gulp-sourcemaps": "~1.6.0",
        "merge-stream": "~1.0.0",
        "rimraf": "~2.5.2",
        "typescript": "2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "6c67b84364cf3589a9ad6fdea2e3c0bc525c435e",
        "tarball": "https://registry.npmjs.org/gulp-typescript/-/gulp-typescript-3.1.6.tgz"
    },
    "gitHead": "44b4249741b438a60357f8d909956b62afefc9e1",
    "homepage": "https://github.com/ivogabe/gulp-typescript",
    "keywords": [
        "typescript",
        "gulpplugin",
        "incremental compilation",
        "ts",
        "tsc",
        "compile",
        "compiler",
        "transpile"
    ],
    "license": "MIT",
    "main": "release/main.js",
    "maintainers": [
        {
            "name": "ivogabe",
            "email": "ivogabe@ivogabe.nl"
        }
    ],
    "name": "gulp-typescript",
    "optionalDependencies": {},
    "peerDependencies": {
        "typescript": "~2.0.3 || >=2.0.0-dev || >=2.1.0-dev || >=2.2.0-dev || >=2.3.0-dev"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ivogabe/gulp-typescript.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "types": "release/main.d.ts",
    "typings": "release/main.d.ts",
    "version": "3.1.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-typescript](#apidoc.module.gulp-typescript)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.</span>createProject (fileNameOrSettings, settings)](#apidoc.element.gulp-typescript.createProject)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.</span>filter ()](#apidoc.element.gulp-typescript.filter)
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>compiler
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>host
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>input
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>output
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>project
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>reporter
1.  object <span class="apidocSignatureSpan">gulp-typescript.</span>utils

#### [module gulp-typescript.compiler](#apidoc.module.gulp-typescript.compiler)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.compiler.</span>FileCompiler ()](#apidoc.element.gulp-typescript.compiler.FileCompiler)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.compiler.</span>ProjectCompiler ()](#apidoc.element.gulp-typescript.compiler.ProjectCompiler)

#### [module gulp-typescript.host](#apidoc.module.gulp-typescript.host)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.host.</span>Host (typescript, currentDirectory, input, options)](#apidoc.element.gulp-typescript.host.Host)

#### [module gulp-typescript.input](#apidoc.module.gulp-typescript.input)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileCache (typescript, options)](#apidoc.element.gulp-typescript.input.FileCache)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileDictionary (typescript)](#apidoc.element.gulp-typescript.input.FileDictionary)
1.  object <span class="apidocSignatureSpan">gulp-typescript.input.</span>File
1.  object <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileChangeState
1.  object <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileKind

#### [module gulp-typescript.output](#apidoc.module.gulp-typescript.output)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.output.</span>Output (_project, streamFull, streamJs, streamDts)](#apidoc.element.gulp-typescript.output.Output)

#### [module gulp-typescript.project](#apidoc.module.gulp-typescript.project)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.project.</span>setupProject (projectDirectory, config, options, typescript)](#apidoc.element.gulp-typescript.project.setupProject)

#### [module gulp-typescript.reporter](#apidoc.module.gulp-typescript.reporter)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>defaultReporter ()](#apidoc.element.gulp-typescript.reporter.defaultReporter)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>emptyCompilationResult ()](#apidoc.element.gulp-typescript.reporter.emptyCompilationResult)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>fullReporter (fullFilename)](#apidoc.element.gulp-typescript.reporter.fullReporter)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>longReporter ()](#apidoc.element.gulp-typescript.reporter.longReporter)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>nullReporter ()](#apidoc.element.gulp-typescript.reporter.nullReporter)

#### [module gulp-typescript.utils](#apidoc.module.gulp-typescript.utils)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>deprecate (title, alternative, description)](#apidoc.element.gulp-typescript.utils.deprecate)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>forwardSlashes (fileName)](#apidoc.element.gulp-typescript.utils.forwardSlashes)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getCommonBasePath (a, b)](#apidoc.element.gulp-typescript.utils.getCommonBasePath)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getCommonBasePathOfArray (paths)](#apidoc.element.gulp-typescript.utils.getCommonBasePathOfArray)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getError (info, typescript, file)](#apidoc.element.gulp-typescript.utils.getError)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>message (title, alternative, description)](#apidoc.element.gulp-typescript.utils.message)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>normalizePath (pathString)](#apidoc.element.gulp-typescript.utils.normalizePath)
1.  [function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>splitExtension (fileName, knownExtensions)](#apidoc.element.gulp-typescript.utils.splitExtension)



# <a name="apidoc.module.gulp-typescript"></a>[module gulp-typescript](#apidoc.module.gulp-typescript)

#### <a name="apidoc.element.gulp-typescript.createProject"></a>[function <span class="apidocSignatureSpan">gulp-typescript.</span>createProject (fileNameOrSettings, settings)](#apidoc.element.gulp-typescript.createProject)
- description and source-code
```javascript
function createProject(fileNameOrSettings, settings) {
    var tsConfigFileName = undefined;
    var tsConfigContent = undefined;
    var projectDirectory = process.cwd();
    if (fileNameOrSettings !== undefined) {
        if (typeof fileNameOrSettings === 'string') {
            tsConfigFileName = path.resolve(process.cwd(), fileNameOrSettings);
            projectDirectory = path.dirname(tsConfigFileName);
            // Load file and strip BOM, since JSON.parse fails to parse if there's a BOM present
            var tsConfigText = fs.readFileSync(tsConfigFileName).toString();
            var typescript = getTypeScript(settings && settings.typescript);
            var tsConfig = typescript.parseConfigFileTextToJson(tsConfigFileName, tsConfigText);
            tsConfigContent = tsConfig.config || {};
            if (tsConfig.error) {
                console.log(tsConfig.error.messageText);
            }
            var newSettings = {};
            if (tsConfigContent.compilerOptions) {
                for (var _i = 0, _a = Object.keys(tsConfigContent.compilerOptions); _i < _a.length; _i++) {
                    var key = _a[_i];
                    newSettings[key] = tsConfigContent.compilerOptions[key];
                }
            }
            if (settings) {
                for (var _b = 0, _c = Object.keys(settings); _b < _c.length; _b++) {
                    var key = _c[_b];
                    newSettings[key] = settings[key];
                }
            }
            settings = newSettings;
        }
        else {
            settings = fileNameOrSettings;
        }
    }
    var project = _project.setupProject(projectDirectory, tsConfigContent, getCompilerOptions(settings, projectDirectory, tsConfigFileName
), getTypeScript(settings.typescript));
    return project;
}
```
- example usage
```shell
...
-----------------------
Instead of calling 'ts(options)', you can create a project first, and then call 'tsProject()'. An example:
'''javascript
var gulp = require('gulp');
var ts = require('gulp-typescript');
var merge = require('merge2');

var tsProject = ts.createProject({
declaration: true
});

gulp.task('scripts', function() {
var tsResult = gulp.src('lib/*.ts')
    .pipe(tsProject());
...
```

#### <a name="apidoc.element.gulp-typescript.filter"></a>[function <span class="apidocSignatureSpan">gulp-typescript.</span>filter ()](#apidoc.element.gulp-typescript.filter)
- description and source-code
```javascript
function filter() {
    var args = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        args[_i - 0] = arguments[_i];
    }
    utils.deprecate('ts.filter() is deprecated', 'soon you can use tsProject.resolve()', 'Filters have been removed as of gulp-typescript
 3.0.\nSoon tsProject.resolve() will be available as an alternative.\nSee https://github.com/ivogabe/gulp-typescript/issues/190.');
}
```
- example usage
```shell
...
if (!this.project.input.firstSourceFile) {
    this.project.output.finish(reporter_1.emptyCompilationResult());
    return;
}
var rootFilenames = this.project.input.getFileNames(true);
if (!this.project.singleOutput) {
    if (this.project.options.rootDir === undefined) {
        this.project.options.rootDir = utils.getCommonBasePathOfArray(rootFilenames.filter(function (fileName) { return fileName
.substr(-5) !== ".d.ts"; })
            .map(function (fileName) { return _this.project.input.getFile(fileName).gulp.base; }));
    }
}
this.project.options.sourceMap = this.hasSourceMap;
var currentDirectory = utils.getCommonBasePathOfArray(rootFilenames.map(function (fileName) { return _this.project.input.getFile
(fileName).gulp.cwd; }));
this.host = new host_1.Host(this.project.typescript, currentDirectory, this.project.input, this.project.options);
this.program = this.project.typescript.createProgram(rootFilenames, this.project.options, this.host, this.program);
...
```



# <a name="apidoc.module.gulp-typescript.compiler"></a>[module gulp-typescript.compiler](#apidoc.module.gulp-typescript.compiler)

#### <a name="apidoc.element.gulp-typescript.compiler.FileCompiler"></a>[function <span class="apidocSignatureSpan">gulp-typescript.compiler.</span>FileCompiler ()](#apidoc.element.gulp-typescript.compiler.FileCompiler)
- description and source-code
```javascript
function FileCompiler() {
    this.output = {};
    this.previousOutput = {};
    this.compilationResult = undefined;
}
```
- example usage
```shell
...
var utils = require('./utils');
var reporter_1 = require('./reporter');
var input_1 = require('./input');
var output_1 = require('./output');
var compiler_1 = require('./compiler');
function setupProject(projectDirectory, config, options, typescript) {
var input = new input_1.FileCache(typescript, options);
var compiler = options.isolatedModules ? new compiler_1.FileCompiler() : new compiler_1.ProjectCompiler();
var running = false;
if (options.isolatedModules) {
    options.newLine = typescript.NewLineKind.LineFeed;
    options.sourceMap = false;
    options.declaration = false;
    options.inlineSourceMap = true;
}
...
```

#### <a name="apidoc.element.gulp-typescript.compiler.ProjectCompiler"></a>[function <span class="apidocSignatureSpan">gulp-typescript.compiler.</span>ProjectCompiler ()](#apidoc.element.gulp-typescript.compiler.ProjectCompiler)
- description and source-code
```javascript
function ProjectCompiler() {
}
```
- example usage
```shell
...
var utils = require('./utils');
var reporter_1 = require('./reporter');
var input_1 = require('./input');
var output_1 = require('./output');
var compiler_1 = require('./compiler');
function setupProject(projectDirectory, config, options, typescript) {
var input = new input_1.FileCache(typescript, options);
var compiler = options.isolatedModules ? new compiler_1.FileCompiler() : new compiler_1.ProjectCompiler();
var running = false;
if (options.isolatedModules) {
    options.newLine = typescript.NewLineKind.LineFeed;
    options.sourceMap = false;
    options.declaration = false;
    options.inlineSourceMap = true;
}
...
```



# <a name="apidoc.module.gulp-typescript.host"></a>[module gulp-typescript.host](#apidoc.module.gulp-typescript.host)

#### <a name="apidoc.element.gulp-typescript.host.Host"></a>[function <span class="apidocSignatureSpan">gulp-typescript.host.</span>Host (typescript, currentDirectory, input, options)](#apidoc.element.gulp-typescript.host.Host)
- description and source-code
```javascript
function Host(typescript, currentDirectory, input, options) {
    var _this = this;
    this.getCurrentDirectory = function () {
        return _this.currentDirectory;
    };
    this.writeFile = function (fileName, data, writeByteOrderMark, onError) { };
    this.fileExists = function (fileName) {
        var sourceFile = _this.input.getFile(fileName);
        if (sourceFile)
            return true;
        return _this.fallback.fileExists(fileName);
    };
    this.readFile = function (fileName) {
        var sourceFile = _this.input.getFile(fileName);
        if (sourceFile)
            return sourceFile.content;
        return _this.fallback.readFile(fileName);
    };
    this.getSourceFile = function (fileName, languageVersion, onError) {
        // TODO: Cache lib.d.ts files between compilations
        var sourceFile = _this.input.getFile(fileName);
        if (sourceFile)
            return sourceFile.ts;
        return _this.fallback.getSourceFile(fileName, languageVersion, onError);
    };
    this.realpath = function (path) { return _this.fallback.realpath(path); };
    this.getDirectories = function (path) { return _this.fallback.getDirectories(path); };
    this.directoryExists = function (path) { return _this.fallback.directoryExists(path); };
    this.typescript = typescript;
    this.fallback = typescript.createCompilerHost(options);
    this.currentDirectory = currentDirectory;
    this.input = input;
}
```
- example usage
```shell
...
    if (this.project.options.rootDir === undefined) {
        this.project.options.rootDir = utils.getCommonBasePathOfArray(rootFilenames.filter(function (fileName) { return fileName
.substr(-5) !== ".d.ts"; })
            .map(function (fileName) { return _this.project.input.getFile(fileName).gulp.base; }));
    }
}
this.project.options.sourceMap = this.hasSourceMap;
var currentDirectory = utils.getCommonBasePathOfArray(rootFilenames.map(function (fileName) { return _this.project.input.getFile
(fileName).gulp.cwd; }));
this.host = new host_1.Host(this.project.typescript, currentDirectory, this.project.input, this.project.options);
this.program = this.project.typescript.createProgram(rootFilenames, this.project.options, this.host, this.program);
var result = reporter_1.emptyCompilationResult();
result.optionsErrors = this.reportDiagnostics(this.program.getOptionsDiagnostics());
result.syntaxErrors = this.reportDiagnostics(this.program.getSyntacticDiagnostics());
result.globalErrors = this.reportDiagnostics(this.program.getGlobalDiagnostics());
result.semanticErrors = this.reportDiagnostics(this.program.getSemanticDiagnostics());
if (this.project.options.declaration) {
...
```



# <a name="apidoc.module.gulp-typescript.input"></a>[module gulp-typescript.input](#apidoc.module.gulp-typescript.input)

#### <a name="apidoc.element.gulp-typescript.input.FileCache"></a>[function <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileCache (typescript, options)](#apidoc.element.gulp-typescript.input.FileCache)
- description and source-code
```javascript
function FileCache(typescript, options) {
    this.previous = undefined;
    this.noParse = false; // true when using a file based compiler.
    this.version = 0;
    this.typescript = typescript;
    this.options = options;
    this.createDictionary();
}
```
- example usage
```shell
...
var gutil = require('gulp-util');
var utils = require('./utils');
var reporter_1 = require('./reporter');
var input_1 = require('./input');
var output_1 = require('./output');
var compiler_1 = require('./compiler');
function setupProject(projectDirectory, config, options, typescript) {
var input = new input_1.FileCache(typescript, options);
var compiler = options.isolatedModules ? new compiler_1.FileCompiler() : new compiler_1.ProjectCompiler();
var running = false;
if (options.isolatedModules) {
    options.newLine = typescript.NewLineKind.LineFeed;
    options.sourceMap = false;
    options.declaration = false;
    options.inlineSourceMap = true;
...
```

#### <a name="apidoc.element.gulp-typescript.input.FileDictionary"></a>[function <span class="apidocSignatureSpan">gulp-typescript.input.</span>FileDictionary (typescript)](#apidoc.element.gulp-typescript.input.FileDictionary)
- description and source-code
```javascript
function FileDictionary(typescript) {
    this.files = {};
    this.firstSourceFile = undefined;
    this.typescript = typescript;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-typescript.output"></a>[module gulp-typescript.output](#apidoc.module.gulp-typescript.output)

#### <a name="apidoc.element.gulp-typescript.output.Output"></a>[function <span class="apidocSignatureSpan">gulp-typescript.output.</span>Output (_project, streamFull, streamJs, streamDts)](#apidoc.element.gulp-typescript.output.Output)
- description and source-code
```javascript
function Output(_project, streamFull, streamJs, streamDts) {
    this.project = _project;
    this.streamFull = streamFull;
    this.streamJs = streamJs;
    this.streamDts = streamDts;
}
```
- example usage
```shell
...
    if (running) {
        throw new Error('gulp-typescript: A project cannot be used in two compilations at the same time. Create multiple projects
 with createProject instead.');
    }
    running = true;
    input.reset();
    compiler.prepare(projectInfo);
    var stream = new CompileStream(projectInfo);
    projectInfo.output = new output_1.Output(projectInfo, stream, stream.js, stream.dts);
    projectInfo.reporter = reporter || reporter_1.defaultReporter();
    stream.on('finish', function () {
        running = false;
    });
    return stream;
};
var singleOutput = options.out !== undefined || options.outFile !== undefined;
...
```



# <a name="apidoc.module.gulp-typescript.project"></a>[module gulp-typescript.project](#apidoc.module.gulp-typescript.project)

#### <a name="apidoc.element.gulp-typescript.project.setupProject"></a>[function <span class="apidocSignatureSpan">gulp-typescript.project.</span>setupProject (projectDirectory, config, options, typescript)](#apidoc.element.gulp-typescript.project.setupProject)
- description and source-code
```javascript
function setupProject(projectDirectory, config, options, typescript) {
    var input = new input_1.FileCache(typescript, options);
    var compiler = options.isolatedModules ? new compiler_1.FileCompiler() : new compiler_1.ProjectCompiler();
    var running = false;
    if (options.isolatedModules) {
        options.newLine = typescript.NewLineKind.LineFeed;
        options.sourceMap = false;
        options.declaration = false;
        options.inlineSourceMap = true;
    }
    var project = function (reporter) {
        if (running) {
            throw new Error('gulp-typescript: A project cannot be used in two compilations at the same time. Create multiple projects
 with createProject instead.');
        }
        running = true;
        input.reset();
        compiler.prepare(projectInfo);
        var stream = new CompileStream(projectInfo);
        projectInfo.output = new output_1.Output(projectInfo, stream, stream.js, stream.dts);
        projectInfo.reporter = reporter || reporter_1.defaultReporter();
        stream.on('finish', function () {
            running = false;
        });
        return stream;
    };
    var singleOutput = options.out !== undefined || options.outFile !== undefined;
    project.src = src;
    project.typescript = typescript;
    project.projectDirectory = projectDirectory;
    project.config = config;
    project.options = options;
    var projectInfo = {
        input: input,
        singleOutput: singleOutput,
        compiler: compiler,
        options: options,
        typescript: typescript,
        directory: projectDirectory,
        // Set when 'project' is called
        output: undefined,
        reporter: undefined
    };
    return project;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-typescript.reporter"></a>[module gulp-typescript.reporter](#apidoc.module.gulp-typescript.reporter)

#### <a name="apidoc.element.gulp-typescript.reporter.defaultReporter"></a>[function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>defaultReporter ()](#apidoc.element.gulp-typescript.reporter.defaultReporter)
- description and source-code
```javascript
function defaultReporter() {
    return {
        error: function (error) {
            console.error(error.message);
        },
        finish: defaultFinishHandler
    };
}
```
- example usage
```shell
...
You can specify a custom reporter as the second argument of the main function, or as the only argument when using a 'tsProject':
'''javascript
ts(options, reporter);
tsProject(reporter);
'''
Available reporters are:
- nullReporter ('ts.reporter.nullReporter()') - Don't report errors
- defaultReporter ('ts.reporter.defaultReporter()') - Report basic errors to the console
- longReporter ('ts.reporter.longReporter()') - Extended version of default reporter, intelliJ link functionality + file watcher
 error highlighting should work using this one
- fullReporter ('ts.reporter.fullReporter(showFullFilename?: boolean)') - Show full error messages, with source.

If you want to build a custom reporter, you take a look at 'lib/reporter.ts', that file declares an interface which a reporter should
 implement.

Build gulp-typescript
------------
...
```

#### <a name="apidoc.element.gulp-typescript.reporter.emptyCompilationResult"></a>[function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>emptyCompilationResult ()](#apidoc.element.gulp-typescript.reporter.emptyCompilationResult)
- description and source-code
```javascript
function emptyCompilationResult() {
    return {
        transpileErrors: 0,
        optionsErrors: 0,
        syntaxErrors: 0,
        globalErrors: 0,
        semanticErrors: 0,
        declarationErrors: 0,
        emitErrors: 0,
        emitSkipped: false
    };
}
```
- example usage
```shell
...
ProjectCompiler.prototype.inputFile = function (file) {
    if (file.gulp.sourceMap)
        this.hasSourceMap = true;
};
ProjectCompiler.prototype.inputDone = function () {
    var _this = this;
    if (!this.project.input.firstSourceFile) {
        this.project.output.finish(reporter_1.emptyCompilationResult());
        return;
    }
    var rootFilenames = this.project.input.getFileNames(true);
    if (!this.project.singleOutput) {
        if (this.project.options.rootDir === undefined) {
            this.project.options.rootDir = utils.getCommonBasePathOfArray(rootFilenames.filter(function (fileName) { return fileName
.substr(-5) !== ".d.ts"; })
                .map(function (fileName) { return _this.project.input.getFile(fileName).gulp.base; }));
...
```

#### <a name="apidoc.element.gulp-typescript.reporter.fullReporter"></a>[function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>fullReporter (fullFilename)](#apidoc.element.gulp-typescript.reporter.fullReporter)
- description and source-code
```javascript
function fullReporter(fullFilename) {
    if (fullFilename === void 0) { fullFilename = false; }
    var typescript = require('typescript');
    return {
        error: function (error, typescript) {
            console.error('[' + gutil.colors.gray('gulp-typescript') + '] '
                + gutil.colors.bgRed(error.diagnostic.code + '')
                + ' ' + gutil.colors.red(typescript.flattenDiagnosticMessageText(error.diagnostic.messageText, '\n')));
            if (error.tsFile) {
                console.error('> ' + gutil.colors.gray('file: ') + (fullFilename ? error.fullFilename : error.relativeFilename) +
gutil.colors.gray(':'));
                var lines_1 = error.tsFile.text.split(/(?:\r\n|\r|\n)/);
                var logLine = function (lineIndex, errorStart, errorEnd) {
                    var line = lines_1[lineIndex];
                    if (errorEnd === undefined)
                        errorEnd = line.length;
                    console.error('> ' + gutil.colors.gray('[' + lineIndex + '] ')
                        + line.substring(0, errorStart)
                        + gutil.colors.red(line.substring(errorStart, errorEnd))
                        + line.substring(errorEnd));
                };
                for (var i = error.startPosition.line; i <= error.endPosition.line; i++) {
                    logLine(i, i === error.startPosition.line ? error.startPosition.character - 1 : 0, i === error.endPosition.line
 ? error.endPosition.character - 1 : undefined);
                }
            }
        },
        finish: defaultFinishHandler
    };
}
```
- example usage
```shell
...
ts(options, reporter);
tsProject(reporter);
'''
Available reporters are:
- nullReporter ('ts.reporter.nullReporter()') - Don't report errors
- defaultReporter ('ts.reporter.defaultReporter()') - Report basic errors to the console
- longReporter ('ts.reporter.longReporter()') - Extended version of default reporter, intelliJ link functionality + file watcher
 error highlighting should work using this one
- fullReporter ('ts.reporter.fullReporter(showFullFilename?: boolean)') - Show full error messages, with source.

If you want to build a custom reporter, you take a look at 'lib/reporter.ts', that file declares an interface which a reporter should
 implement.

Build gulp-typescript
------------

1. Clone this repo
...
```

#### <a name="apidoc.element.gulp-typescript.reporter.longReporter"></a>[function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>longReporter ()](#apidoc.element.gulp-typescript.reporter.longReporter)
- description and source-code
```javascript
function longReporter() {
    var typescript = require('typescript');
    return {
        error: function (error) {
            if (error.tsFile) {
                console.error('[' + gutil.colors.gray('gulp-typescript') + '] ' + gutil.colors.red(error.fullFilename
                    + '(' + error.startPosition.line + ',' + error.startPosition.character + '): ')
                    + 'error TS' + error.diagnostic.code + ' ' + typescript.flattenDiagnosticMessageText(error.diagnostic.messageText
, '\n'));
            }
            else {
                console.error(error.message);
            }
        },
        finish: defaultFinishHandler
    };
}
```
- example usage
```shell
...
'''javascript
ts(options, reporter);
tsProject(reporter);
'''
Available reporters are:
- nullReporter ('ts.reporter.nullReporter()') - Don't report errors
- defaultReporter ('ts.reporter.defaultReporter()') - Report basic errors to the console
- longReporter ('ts.reporter.longReporter()') - Extended version of default reporter, intelliJ link functionality + file watcher
 error highlighting should work using this one
- fullReporter ('ts.reporter.fullReporter(showFullFilename?: boolean)') - Show full error messages, with source.

If you want to build a custom reporter, you take a look at 'lib/reporter.ts', that file declares an interface which a reporter should
 implement.

Build gulp-typescript
------------
...
```

#### <a name="apidoc.element.gulp-typescript.reporter.nullReporter"></a>[function <span class="apidocSignatureSpan">gulp-typescript.reporter.</span>nullReporter ()](#apidoc.element.gulp-typescript.reporter.nullReporter)
- description and source-code
```javascript
function nullReporter() {
    return {};
}
```
- example usage
```shell
...
---------
You can specify a custom reporter as the second argument of the main function, or as the only argument when using a 'tsProject':
'''javascript
ts(options, reporter);
tsProject(reporter);
'''
Available reporters are:
- nullReporter ('ts.reporter.nullReporter()') - Don't report errors
- defaultReporter ('ts.reporter.defaultReporter()') - Report basic errors to the console
- longReporter ('ts.reporter.longReporter()') - Extended version of default reporter, intelliJ link functionality + file watcher
 error highlighting should work using this one
- fullReporter ('ts.reporter.fullReporter(showFullFilename?: boolean)') - Show full error messages, with source.

If you want to build a custom reporter, you take a look at 'lib/reporter.ts', that file declares an interface which a reporter should
 implement.

Build gulp-typescript
...
```



# <a name="apidoc.module.gulp-typescript.utils"></a>[module gulp-typescript.utils](#apidoc.module.gulp-typescript.utils)

#### <a name="apidoc.element.gulp-typescript.utils.deprecate"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>deprecate (title, alternative, description)](#apidoc.element.gulp-typescript.utils.deprecate)
- description and source-code
```javascript
function deprecate(title, alternative, description) {
    message(title, alternative, description);
    console.log('  ' + gutil.colors.gray('More information: ' + gutil.colors.underline('http://dev.ivogabe.com/gulp-typescript-3
/')));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-typescript.utils.forwardSlashes"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>forwardSlashes (fileName)](#apidoc.element.gulp-typescript.utils.forwardSlashes)
- description and source-code
```javascript
function forwardSlashes(fileName) {
    return fileName.replace(/\\/g, '/');
}
```
- example usage
```shell
...
var _this = this;
if (sourceMapContent === undefined)
    return undefined;
var map = JSON.parse(sourceMapContent);
var directory = path.dirname(output.path);
// gulp-sourcemaps docs:
// paths in the generated source map ('file' and 'sources') are relative to 'file.base' (e.g. use 'file.relative').
map.file = utils.forwardSlashes(output.relative);
map.sources = map.sources.map(relativeToOutput);
delete map.sourceRoot;
var generator = sourceMap.SourceMapGenerator.fromSourceMap(new sourceMap.SourceMapConsumer(map));
var sourceMapOrigins = this.project.singleOutput
    ? this.project.input.getFileNames(true).map(function (fName) { return _this.project.input.getFile(fName); })
    : [original];
for (var _i = 0, sourceMapOrigins_1 = sourceMapOrigins; _i < sourceMapOrigins_1.length; _i++) {
...
```

#### <a name="apidoc.element.gulp-typescript.utils.getCommonBasePath"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getCommonBasePath (a, b)](#apidoc.element.gulp-typescript.utils.getCommonBasePath)
- description and source-code
```javascript
function getCommonBasePath(a, b) {
    var aSplit = a.split(/\\|\//); // Split on '/' or '\'.
    var bSplit = b.split(/\\|\//);
    var commonLength = 0;
    for (var i = 0; i < aSplit.length && i < bSplit.length; i++) {
        if (aSplit[i] !== bSplit[i])
            break;
        commonLength += aSplit[i].length + 1;
    }
    return a.substr(0, commonLength);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-typescript.utils.getCommonBasePathOfArray"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getCommonBasePathOfArray (paths)](#apidoc.element.gulp-typescript.utils.getCommonBasePathOfArray)
- description and source-code
```javascript
function getCommonBasePathOfArray(paths) {
    if (paths.length === 0)
        return '';
    return paths.reduce(getCommonBasePath);
}
```
- example usage
```shell
...
if (!this.project.input.firstSourceFile) {
    this.project.output.finish(reporter_1.emptyCompilationResult());
    return;
}
var rootFilenames = this.project.input.getFileNames(true);
if (!this.project.singleOutput) {
    if (this.project.options.rootDir === undefined) {
        this.project.options.rootDir = utils.getCommonBasePathOfArray(rootFilenames.filter(function (fileName) { return fileName
.substr(-5) !== ".d.ts"; })
            .map(function (fileName) { return _this.project.input.getFile(fileName).gulp.base; }));
    }
}
this.project.options.sourceMap = this.hasSourceMap;
var currentDirectory = utils.getCommonBasePathOfArray(rootFilenames.map(function (fileName) { return _this.project.input.getFile
(fileName).gulp.cwd; }));
this.host = new host_1.Host(this.project.typescript, currentDirectory, this.project.input, this.project.options);
this.program = this.project.typescript.createProgram(rootFilenames, this.project.options, this.host, this.program);
...
```

#### <a name="apidoc.element.gulp-typescript.utils.getError"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>getError (info, typescript, file)](#apidoc.element.gulp-typescript.utils.getError)
- description and source-code
```javascript
function getError(info, typescript, file) {
    var err = new Error();
    err.name = 'TypeScript error';
    err.diagnostic = info;
    var codeAndMessageText = typescript.DiagnosticCategory[info.category].toLowerCase() +
        ' TS' +
        info.code +
        ': ' +
        typescript.flattenDiagnosticMessageText(info.messageText, '\n');
    if (!info.file) {
        err.message = codeAndMessageText;
        return err;
    }
    var fileName = info.file.fileName;
    if (file) {
        err.tsFile = file.ts;
        err.fullFilename = file.fileNameOriginal;
        if (file.gulp) {
            fileName = path.relative(file.gulp.cwd, file.fileNameOriginal);
            err.relativeFilename = fileName;
            err.file = file.gulp;
        }
        else {
            fileName = file.fileNameOriginal;
        }
    }
    else {
        err.fullFilename = info.file.fileName;
    }
    var startPos = typescript.getLineAndCharacterOfPosition(info.file, info.start);
    var endPos = typescript.getLineAndCharacterOfPosition(info.file, info.start + info.length);
    err.startPosition = {
        position: info.start,
        line: startPos.line,
        character: startPos.character
    };
    err.endPosition = {
        position: info.start + info.length - 1,
        line: endPos.line,
        character: endPos.character
    };
    err.message = gutil.colors.red(fileName + '(' + (startPos.line + 1) + ',' + (startPos.character + 1) + '): ').toString()
        + codeAndMessageText;
    return err;
}
```
- example usage
```shell
...
    this.streamFull.push(null);
    this.streamJs.push(null);
    this.streamDts.push(null);
};
Output.prototype.getError = function (info) {
    var fileName = info.file && info.file.fileName;
    var file = fileName && this.project.input.getFile(fileName);
    return utils.getError(info, this.project.typescript, file);
};
Output.prototype.diagnostic = function (info) {
    this.error(this.getError(info));
};
Output.prototype.error = function (error) {
    if (!error)
        return;
...
```

#### <a name="apidoc.element.gulp-typescript.utils.message"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>message (title, alternative, description)](#apidoc.element.gulp-typescript.utils.message)
- description and source-code
```javascript
function message(title, alternative, description) {
    console.log(gutil.colors.red('gulp-typescript').toString() +
        gutil.colors.gray(': ') +
        title +
        gutil.colors.gray(' - ') +
        alternative);
    if (description)
        console.log('  ' + gutil.colors.gray(description.replace(/\n/g, '\n  ')));
}
```
- example usage
```shell
...
    reporter: undefined
};
return project;
}
exports.setupProject = setupProject;
function src() {
if (arguments.length >= 1) {
    utils.message("tsProject.src() takes no arguments", "Use gulp.src(..) if you need to specify a glob");
}
var base;
if (this.options["rootDir"]) {
    base = path.resolve(this.projectDirectory, this.options["rootDir"]);
}
var content = {};
if (this.config.include)
...
```

#### <a name="apidoc.element.gulp-typescript.utils.normalizePath"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>normalizePath (pathString)](#apidoc.element.gulp-typescript.utils.normalizePath)
- description and source-code
```javascript
function normalizePath(pathString) {
    return path.normalize(pathString).toLowerCase();
}
```
- example usage
```shell
...
    });
    this.emitFile(output_1, currentDirectory);
}
else {
    var output_2 = {};
    var input = this.host.input.getFileNames(true);
    for (var i = 0; i < input.length; i++) {
        var fileName = utils.normalizePath(input[i]);
        var file = this.project.input.getFile(fileName);
        output_2[fileName] = { file: file };
    }
    this.emit(result, function (fileName, content, writeByteOrderMark, onError, sourceFiles) {
        if (sourceFiles.length !== 1) {
            throw new Error("Failure: sourceFiles in WriteFileCallback should have length 1, got " + sourceFiles.length);
        }
...
```

#### <a name="apidoc.element.gulp-typescript.utils.splitExtension"></a>[function <span class="apidocSignatureSpan">gulp-typescript.utils.</span>splitExtension (fileName, knownExtensions)](#apidoc.element.gulp-typescript.utils.splitExtension)
- description and source-code
```javascript
function splitExtension(fileName, knownExtensions) {
    if (knownExtensions) {
        for (var _i = 0, knownExtensions_1 = knownExtensions; _i < knownExtensions_1.length; _i++) {
            var ext_1 = knownExtensions_1[_i];
            var index_1 = fileName.length - ext_1.length - 1;
            if (fileName.substr(index_1) === '.' + ext_1) {
                return [fileName.substr(0, index_1), ext_1];
            }
        }
    }
    var ext = path.extname(fileName).toLowerCase().substr(1);
    var index = fileName.length - ext.length;
    return [fileName.substr(0, index - 1), ext];
}
```
- example usage
```shell
...
            var fileName = utils.normalizePath(input[i]);
            this.emitFile(output_2[fileName], currentDirectory);
        }
    }
    this.project.output.finish(result);
};
ProjectCompiler.prototype.attachContentToFile = function (file, fileName, content) {
    var _a = utils.splitExtension(fileName, ['d.ts']), extension = _a[1];
    switch (extension) {
        case 'js':
        case 'jsx':
            file.jsFileName = fileName;
            file.jsContent = content;
            break;
        case 'd.ts':
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

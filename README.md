# BootrapMultiselect

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.12.

* npm i -g @angular/cli@9
* ng new bootrap-multiselect
* browserlist to add IE 9-11 support
* tsconfig.json to target: es5

`npm run build`

```log
> ng build

Compiling ngx-bootrap-multiselect : module as esm5
Error: Error on worker #1: Error: getInternalNameOfClass() called on a non-ES5 class: expected MultiSelectSearchFilter to have an inner class declaration
    at Esm5ReflectionHost.getInternalNameOfClass (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/host/esm5_host.js:88:23)
    at DelegatingReflectionHost.getInternalNameOfClass (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/host/delegating_host.js:89:34)
    at PipeDecoratorHandler.analyze (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/pipe.js:60:78)
    at NgccTraitCompiler.TraitCompiler.analyzeTrait (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/src/ngtsc/transform/src/compilation.js:345:40)
    at analyze (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/src/ngtsc/transform/src/compilation.js:297:58)
    at _loop_1 (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/src/ngtsc/transform/src/compilation.js:319:21)
    at NgccTraitCompiler.TraitCompiler.analyzeClass (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/src/ngtsc/transform/src/compilation.js:325:35)
    at NgccTraitCompiler.analyzeFile (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/analysis/ngcc_trait_compiler.js:47:26)
    at DecorationAnalyzer.analyzeProgram (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/analysis/decoration_analyzer.js:134:39)
    at Transformer.analyzeProgram (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/packages/transformer.js:129:57)
    at ClusterMaster.onWorkerMessage (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:194:27)
    at /Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:54:95
    at ClusterMaster.<anonymous> (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:292:57)
    at step (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/tslib/tslib.js:141:27)
    at Object.next (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/tslib/tslib.js:122:57)
    at /Users/kbradshaw/Development/bootrap-multiselect/node_modules/tslib/tslib.js:115:75
    at new Promise (<anonymous>)
    at Object.__awaiter (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/tslib/tslib.js:111:16)
    at EventEmitter.<anonymous> (/Users/kbradshaw/Development/bootrap-multiselect/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:286:32)
    at EventEmitter.emit (events.js:315:20)
An unhandled exception occurred: NGCC failed.
See "/private/var/folders/5g/cbrr8_nx57n02r3671cp6bm40000gn/T/ng-46941z/angular-errors.log" for further details.
npm ERR! code ELIFECYCLE
npm ERR! syscall spawn
npm ERR! file sh
npm ERR! errno ENOENT
npm ERR! bootrap-multiselect@0.0.0 build: `ng build`
npm ERR! spawn ENOENT
npm ERR! 
npm ERR! Failed at the bootrap-multiselect@0.0.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/kbradshaw/.npm/_logs/2020-08-29T02_16_35_715Z-debug.log
```

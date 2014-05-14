# Scaling Angular
An in-depth demonstration of fracturing an application via multiple repositories. You can find examples below in both a CommonJS Format (Browersify) and AMD (RequireJS). Each flavor has its unique quirks and so it's recommended that you explore each approach carefully.

## CommonJS
[Parent Application](https://github.com/asilluron/ScalingDemoAngularParentApp_cjs)
[Sub Application - Business Logic](https://github.com/asilluron/ScalingDemoAngularSubApp_cjs)
[Sub Application - Model Layer - Version 1](https://github.com/asilluron/ScalingDemoAngularSubAppModel1_cjs)
[Sub Application - Model Layer - Version 2](https://github.com/asilluron/ScalingDemoAngularSubAppModel2_cjs)

## AMD
[Parent Application](https://github.com/asilluron/ScalingDemoAngularParentApp_amd)
[Sub Application - Business Logic](https://github.com/asilluron/ScalingDemoAngularSubApp_amd)
[Sub Application - Model Layer - Version 1](https://github.com/asilluron/ScalingDemoAngularSubAppModel1_amd)
[Sub Application - Model Layer - Version 2](https://github.com/asilluron/ScalingDemoAngularSubAppModel2_amd)

### Example

#### Boot Up the Parent Application - AMD Version

```
git clone https://github.com/asilluron/ScalingDemoAngularParentApp_amd.git
cd ScalingDemoAngularParentApp_amd
npm install
grunt local
```

#### Boot Up the Parent Application - AMD Version

```
git clone https://github.com/asilluron/ScalingDemoAngularParentApp_cjs.git
cd ScalingDemoAngularParentApp_cjs
npm install
gulp deploy
```

Then, open the index.html file inside of the `examples` folder

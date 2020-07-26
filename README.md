# workspace

Workspace for module development

```
git clone git@github.com:enterprise-ui/uikit-react.git packages/uikit-react
git clone git@github.com:enterprise-ui/uifactory-redux.git packages/uifactory-redux
git clone git@github.com:enterprise-ui/enterprise-ui.git packages/enterprise-ui
git clone git@github.com:enterprise-ui/enterprise-ui-boilerplate.git packages/enterprise-ui-boilerplate
yarn

// Install generator template
cd packages/enterprise-ui/packages/enterprise-ui/tools/generator-config
npm link
cd ../../../../../../

yarn platform:build
yarn boilerplate:build
yarn boilerplate:start

```

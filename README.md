# Another fork of the Create React App

Based on Create React App tag: react-scripts@4.0.1

## Usage
`
npx create-react-app --scripts-version react-scripts-more-than-less myapp
`

## Additional Features
### 1. Support Less
### 2. Enable style file extension regex customization.
```
CSS_REGEX =
CSS_MODULE_REGEX = 
SASS_REGEX = 
SASS_MODULE_REGEX =
LESS_REGEX = 
LESS_MODULE_REGEX = \.(m|module)\.less$
```

You need not put all of them in to your `.env.*`files. Configure it as you need.

### 3. `classnames-loader` 
See [classnames-loader](https://github.com/itsmepetrov/classnames-loader)

Add one line in your `.env.*`files.

```
CLASSNAMES_LOADER = true
```

The default values is `false`.

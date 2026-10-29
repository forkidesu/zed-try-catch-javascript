# Try Catch JavaScript

A Zed snippet extension.

## Install locally

1. Open Zed's Command Palette (Ctrl+Shift+P on Windows).
2. Run `zed: install dev extension`.
3. Select this folder, which contains `extension.toml`.

## Use

Open a JavaScript (`.js`) file, type `trycatch`, select **Try Catch** in
the completion menu, and accept it with Tab or Enter.

```javascript
try{

}
catch(error){

}
```

The cursor starts inside `try`. Press Tab to move inside `catch`.
Your formatter may adjust whitespace when you save.


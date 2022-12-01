# FontAwesomeLuaTable

Generates a lua table for FontAwesome4. Works with LuaJIT, Lua 5.3 and above.

## Generate

```js
npm install
npm start
```

Output files are located at `lua/`.

## Usage

```lua
IconGlyphs = require("IconsFontAwesome4")
local stringWithIcon = "Search" .. IconGlyphs.Search
```

## Type defines

To use with VSCode [sumneko.lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) extension:

https://github.com/sumneko/lua-language-server/wiki/Libraries#custom
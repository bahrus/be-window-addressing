# be-window-addressing

```html
<div be-window-addressing='{
    "target": "_self",
    "api": "appHistory",
    "on": "currentchange"
    "ifAllOf":["canTransition", "userInitiated", "hashChange", "current.selectedView"],
    "transform": {
        "span": "selectedView"
    }
}'>
    <span></span>
</div>
```
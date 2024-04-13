# marko run static $slug bug

Building this repo results in the following `dist`:

```
dist
├── $
│   └── index.html
├── 404
│   └── index.html
├── path
│   └── index.html
└── index.html
```

But it should be:

```
dist
├── 404
│   └── index.html
├── path
│   └── index.html
└── index.html
```

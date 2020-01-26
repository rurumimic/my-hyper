# my-hyper

my Hyper terminal configuration

[Hyper.is](https://hyper.is/)

## Zsh

Install [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh)

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Edit Hyper Configuration.

```js
shell: '/bin/zsh',
```

## Config

```js
config: {
    hypest: {
      darkmode: true,
      hideControls: true,
      borders: true,
    },
}
```

## Plugins

- [hypercwd](https://github.com/hharnisc/hypercwd): Opens new tabs with the same directory as the current tab in Hyper for OS X, Linux, and Windows
- [hyperborder](https://github.com/webmatze/hyperborder): adds a gradient border to the Hyper terminal
- [hyper-blink](https://github.com/amio/hyper-blink): A living cursor blinks
- [hyperterm-cursor](https://github.com/alvaropinot/hyperterm-cursor): hyperterm-cursor a color difference cursor (at the moment)
- [hyper-pane](https://github.com/chabou/hyper-pane): Extension for Hyper.app to enhance pane navigation. Navigate through panes with arrows, jump directly to a specific pane with digit, change focus on mouse hover or temporarily maximize a pane
- [hyper-active-tab](https://github.com/lucleray/hyper-active-tab): Add a symbol to the ▲ active tab in your hyper terminal
- [hyper-broadcast](https://github.com/chabou/hyper-broadcast): Extension for Hyper.app to broadcast user inputs to multiple terms
- ~~[hyper-tabs-enhanced](https://github.com/henrikdahl/hyper-tabs-enhanced): Enhanced Tabs Plugin for Hyper. Matches any theme.~~
- [hyper-highlight-active-pane](https://hyper.is/plugins/hyper-highlight-active-pane): Highlight the currently active pane in Hyper
- [hyper-search](https://github.com/jaanauati/hyper-search): Extension for Hyper that allows you to search text in your terminal.
- [hyper-statusline](https://github.com/henrikdahl/hyper-statusline): Status Line Plugin for Hyper. Shows clickable & useful information. Matches any theme.
- [hyper-tab-icons-plus](https://github.com/sangdth/hyper-tab-icons-plus): Improved forked version of Hyper Tab Icons from Dylan Frankland, displays icons in the header tabs for the current running process in Hyper terminal.
- [hyper-hypest](https://github.com/dizzyup/hyper-hypest): A beautiful and minimal macOS theme with vibrancy

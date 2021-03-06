# react-crontab-input

a crontab.guru/ replica as a react component, with i18n support

![demo](./demo.gif)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FKevinWang15%2Freact-crontab-input.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FKevinWang15%2Freact-crontab-input?ref=badge_shield)

## Online DEMO

http://kewang-cron-input.surge.sh/

## Installation

```
npm i https://github.com/KevinWang15/react-crontab-input
```

## Usage
In your jsx code:

```jsx
import CrontabInput from "react-crontab-input";

...
        <CrontabInput locale="zh_CN" onChange={value => this.setState({ value })} value={this.state.value}/>
...
```

In your css code:

```less
@import "../node_modules/react-crontab-input/lib/default-style.css";
```

## Special Thanks

* [bradymholt/cRonstrue](https://github.com/bradymholt/cRonstrue)
* [roccivic/cron-converter](https://github.com/roccivic/cron-converter)
* [crontab.guru](https://crontab.guru/)

## License

MIT

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FKevinWang15%2Freact-crontab-input.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FKevinWang15%2Freact-crontab-input?ref=badge_large)
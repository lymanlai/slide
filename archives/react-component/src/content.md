# Component-based UI

- tile based rendering
- [normal-flow](https://www.w3.org/TR/2011/REC-CSS2-20110607/visuren.html#normal-flow)

- - -

# Components

[WebComponents](http://w3c.github.io/webcomponents)

- - -

![](http://ww3.sinaimg.cn/large/6d308bd9gw1f345kcfv4jj20kb0flwew.jpg)

<img src="http://ww2.sinaimg.cn/large/6d308bd9gw1f347cizzetj21kw0a4wg2.jpg" width="600"/>

- - -

# [autoresponsive-react](https://github.com/xudafeng/autoresponsive-react)

- - -

```javascript
...
render() {
  return (
    <AutoResponsive>
    	<Something />
    </AutoResponsive>
  );
}
...
```

- - -

[![](http://ww4.sinaimg.cn/large/6d308bd9gw1ettap20q1cg20b80dc7pv.gif)](http://xudafeng.github.io/autoresponsive-react)

- - -

[![](http://ww4.sinaimg.cn/bmiddle/6d308bd9gw1ettap4hkvxg20a209de2d.gif)](http://xudafeng.github.io/autoresponsive-react)

- - -

# [Isomorphic](http://isomorphic.net)

- - -

![](http://ww4.sinaimg.cn/large/6d308bd9gw1f34arplhhfj208t082glq.jpg)

- - -

### e.g.

- [director](https://github.com/flatiron/director)
- [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch)
- rendering

- - -

# Native

```bash
$ react run app.js
```

- - -

<img src="http://ww4.sinaimg.cn/mw1024/6d308bd9gw1ex2ywhirakj21cd1t97ko.jpg" width="600" />

- - -

<a href="https://github.com/xudafeng/autoresponsive_react_native_sample">
  <img src="http://ww2.sinaimg.cn/large/6d308bd9gw1f0ndw34ikkj20u01hc0vd.jpg" height="600" />
</a>
<span style="color: grey;">Android&nbsp;&nbsp;&nbsp;&nbsp;iOS</span>
<a href="https://github.com/xudafeng/autoresponsive_react_native_sample">
  <img src="http://ww1.sinaimg.cn/large/6d308bd9gw1ettap705b7g207g0dckah.gif" height="600" />
</a>

- - -

## learn once >> write once

- - -

![weex](http://ww2.sinaimg.cn/large/6d308bd9gw1f34c8di6c3j20jh0c0t9q.jpg)

- - -

[![](http://ww1.sinaimg.cn/large/6d308bd9gw1f36bsmuzf3j20sz0kdgpd.jpg)](https://github.com/xudafeng/autoresponsive-react/issues/33)

- - -

![](http://ww2.sinaimg.cn/large/6d308bd9gw1f36bsl1crij20ll0j1q5u.jpg)

- - -

## Improvement plan

- infinite scroll support
- offline rendering with visual dom intergration
- mixed typesetting practice
- extendible & configurable

- - -

# Testing

- - -

![](http://ww3.sinaimg.cn/large/6d308bd9gw1f2xmott0jyj20fv0dujs5.jpg)

- - -

### E2E

```javascript


describe('test/example.test.js', () => {
  describe('page func testing', () => {
    before(() => {
      return driver
        .initWindow({
          width: 375,
          height: 667,
          deviceScaleFactor: 2
        });
    });

    afterEach(function () {
      return driver
        .coverage()
        .saveScreenshots(this);
    });

    after(() => {
      return driver
        .openReporter(false)
        .quit();
    });

    it('page render should be ok', () => {
      return driver
        .getUrl(`${BASE_URL}/examples`)
        .setWindowSize(800, 600)
        .sleep(1000);
    });
  });
});

```

- - -

### Unit

- - -

## Coverage

- [macaca-coverage](//github.com/macacajs/macaca-coverage)

- - -

### More Samples

- [react-sample](//github.com/macaca-sample/react-sample) - Macaca test sample for browser React
- [vue-sample](//github.com/macaca-sample/vue-sample) - Macaca test sample for browser framework Vue.js
- [coverage-sample](//github.com/macaca-sample/coverage-sample) - Coverage sample
- [awesome-macaca](//github.com/macacajs/awesome-macaca) List of awesome things regarding Macaca.

- - -

# END

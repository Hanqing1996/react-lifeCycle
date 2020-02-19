#### demo1
* 生命周期函数共9个
1. constructor
2. componentWillMount
3. render
4. componentDidMount
5. componentWillUpdate
6. shouldComponentUpdate
7. componentDidUpdate
8. componentWillUnmount
9. componentWillReceiveProps
* setState 不能放在与 updata 相关的函数里面，也不能放到 render 里面。
* 数据请求（ajax）应该放到 componentDidMount 里面。
* 与 setState 相关的生命周期
```
shouldComponentUpdate->componentWillUpdate->render->componentDidUpdate
```
# REACT

### 创建项目并本地运行
  ```
  $ npx create-react-app *****
  $ cd *****
  $ npm start
  ```

#### 基本概念
  + state/setState
  + props
  + onClick
  + bind(this, ...)
  + () => {} - class fields
  + 函数式组件和类组件
  + 状态提升***

#### 受控组件 - Formik[https://jaredpalmer.com/formik]
#### 非受控组件
  + <input type="file"/>
#### 状态提升

#### 生命周期 （删除的生命周期：componentWillMount，componentWillReceiveProps ， componentWillUpdate）
+ getDerivedStateFromProps
+ shouldComponentUpdate
+ getSnapshotBeforeUpdate
+ render
+ componentDidMount
+ render
+ componnetDidUpdate
+ componentWillUnmount

#### 常用插件
+ react-router-dom
+ formik + yup
+ 

#### Important!!!
+ $$typeof - 防止XSS攻击

## React项目的组成
  + 表单: formik + yup 
  + *** - 表格
  + react hooks
    + useState
    + useEffect
    + useContext
    + 自定义hook
    + ...
  + React.lazy(() => import('./component)) - 动态加载组件
  + react-router-dom/react-router/react-router-native
  + redux + reduxjs/toolkit + react-redux
    *** state + view + actions ***
    1. 创建store - crateStore()
  + axios
  + mobx ？？？？？

## Hook
  + useState
  + useEffect
  + useContext
  + useReducer
  + useCallback
  + useMemo
  + useRef
  + useImperativeHandle
  + useLayoutEffect
  + useDebugValue
  + 自定义hook

## 内部组件
+ Suspense
+ Fragment
+ <> - 短标签

## 高阶组件
+ React.memo
+ 

## Examples:
### 九宫格数独

## 其他
+ http://httpbin.org/ - 测试axios请求


## 补充
+ redux
  1. immutability
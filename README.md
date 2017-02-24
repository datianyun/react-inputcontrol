
# react-inputcontrol

inputControl组件

 基于bootstrap样式

### Installation
``` sh
npm install reactui-inputcontrol
```

### API

### props

|name|type|default| description|
|-----|---|--------|----|
|config| object |- | 配置|
|inputChange| func |- | 变更触发函数|
### Demo

``` sh
npm run start
```

http://localhost:8888/example/

### Usage
``` javascript
import Input from 'reactui-Input'
const parentConfig = {
    title : '母帐号',
    type  : 'noempty',
    tipInfo : '说明：只可填写政府类帐号',
    placeholder : '请输入母账号id或注册邮箱',
    errorInfo : '母帐号不能为空'
}
return (
    <form className="form-horizontal">
        <div className="control-group">
            <label className="control-label">母帐号：</label>
            <Input inputChange={this.handleText.bind(this)} config={parentConfig}></Input>
        </div>
    </form>
)
```

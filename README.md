# demo
 // Using @Library annotation (for global variables and classes)
 ```groovy
@Library[('mySharedLibrary')] _
def useSomeLib(helper) { // dynamic: cannot declare as Helper
    helper.prepare()
    return helper.count()
}
```

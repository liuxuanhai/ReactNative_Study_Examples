#### 关于StackNavigator、TabNavigator、DrawerNavigator三个同时使用注意事项： 
* 嵌套顺序为

* DrawerNavigator -> StackNavigator -> TabNavigator

#### DrawerNavigator跳转的页面 须要在StackNavigator这里注册
  
  ```
    Wallet: {
            screen: Wallet,
        },
        CardCoupons: {
            screen: CardCoupons,
        },
        Invite: {
            screen: Invite,
        },
  ```
    
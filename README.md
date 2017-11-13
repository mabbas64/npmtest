# npmtest
test NPM

;; Start Powershell as Admin, then type:
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force   
```npm install -g npm-windows-upgrade```
 
;;now always use below command to update npm:   
```npm-windows-upgrade -p -v latest```

A list of versions matched between NPM and NODE (https://nodejs.org/en/download/releases/) - but you will need to download NODE INSTALLER and run that to update node (https://nodejs.org/en/)

;; continuing in powershell:

```
npm install -g create-react-native-app
```
; Lets create our project. I'm naming mine 'SmoothTodo'
```
create-react-native-app SmoothTodo
```

;; after the project is created:
```
cd SmoothTodo
yarn start
```

**Navigation between screens**

;;install the react-navigation library
```npm install --save react-navigation```

Then use StackNavigator to create the screens like:
```
const App = StackNavigator({
  Home: { screen: HomeScreen },
  Profile: { screen: ProfileScreen },
});
```

# Ionic MS Tabs Module
###### Tabs module for [Ionic module structure app](https://github.com/DabitNG/ionic-ms-starter)

### Features
This is a module for Ionic MS Starter that provides tab navigation to your app

### Installing module
1. `git clone https://github.com/DabitNG/ionic-ms-tabs-module.git`
2. Extract and place menu folder into www/modules.
3. Go to module-injector.js file under www/modules/main and add `tabs` dependency.
4. (If not ussing Gulp) Add `<script src="modules/tabs/module.js"></script>` to your index.html after module-injector.
5. Remove `<ion-pane>` from index.html and add the following code to your index.html body tag:
```
<ion-nav-bar class="bar-stable">
   <ion-nav-back-button>
   </ion-nav-back-button>
</ion-nav-bar>
<ion-nav-view></ion-nav-view> 
```

### Support or Contact
Having trouble with this module? Contact with [autor](https://github.com/DabitNG)




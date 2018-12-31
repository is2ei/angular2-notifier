# Angular2 notifier 
## Welcome to the angular-notifier wiki!

![Angular Notifier](https://woorklab.com/images/notifier2.png)

## Demo link

[Angular web notifier demo page](https://augustpi.github.io/angular-dart-notifier/) (dart version)


## How to use

* First step import `notifier.ts` file in the **/src/** directory
* and import notifier.css file 


```
  sendNotifier(String type, String title, String content, int duration): void{
    Notifier(type, title, content, duration).show();
 }
```


```
Notifier('info', 'title', 'content here', 1000).show();
```

* **type** -> 'success', 'info', 'todo', 'reminder', 'warning' and 'danger' select one of them, 
* **duration** int **milliseconds**

![Angular dart notifier example](https://woorklab.com/images/notifier2.png)

## Angular.io

For Angular [Angular](http://angulardart.io)

## Dartlang and AngularDart

For Dartlang please visit [Dartlang](https://www.dartlang.org) and [Github repo](https://github.com/dart-lang),
For AngularDart [AngularDart](http://angulardart.org) and [Github](https://github.com/dart-lang/angular)

## Contribute
Our project is, without any discrimination, open to anyone who is willing to make a contribution!

## License
Our project is licensed under MIT license.

# FlashChat

## Final Product
<img src="https://github.com/adbht/FlashChat/blob/master/Updated%20FlashChat%20Cropped%20Video.mov" width="900" />

## About
FlashChat is a live messaging application for iOS using Swift and Google’s Firebase database service for backend support on securely saving user accounts and their personal chats. So reinstallation or any future updates will result in no user data loss. To keep a clear structure on all the files, this application was designed and developed by implementing the Model View Controller (MVC) design pattern. 

## Cocoapods
This application was developed with the following 5 Cocoapods: 
   - Firebase
   - Firebase/Auth
   - Firebase/Database
   - SVProgressHUD
   - ChameleonFramework

## MVC Design Pattern
   - Model
     - [Message.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Model/Message.swift)
   - View
     - [Main.storyboard](https://github.com/adbht/FlashChat/blob/master/FlashChat/View/Main.storyboard)
     - [LaunchScreen.storyboard](https://github.com/adbht/FlashChat/blob/master/FlashChat/View/LaunchScreen.storyboard)
     - CustomCell
       - CustomMessageCell.swift
       - MessageCell.xib
   - Controller
     - [AppDelegate.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Controller/AppDelegate.swift)
     - [ChatViewController.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Controller/ChatViewController.swift)
     - [LogInViewController.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Controller/LogInViewController.swift)
     - [RegisterViewController.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Controller/RegisterViewController.swift)
     - [WelcomeViewController.swift](https://github.com/adbht/FlashChat/blob/master/FlashChat/Controller/WelcomeViewController.swift)

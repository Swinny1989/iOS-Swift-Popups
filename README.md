 
# Swift-Popups
Swift-Popups is a small convienience class to show modal popups from anywhere in your project
## Installation
To install, simply copy the Popups.swift file into your project!
## Usage
To show a popup with one button:

```
Popups.SharedInstance.ShowPopup("Title goes here", message: "Message goes here.")
```

To show a popup with multiple buttons:
```
Popups.SharedInstance.ShowAlert(self, title: "Title goes here", message: "Messages goes here", buttons: ["button one" , "button two"]) { (buttonPressed) -> Void in
            if buttonPressed == "button one" { 
              //Code here
            } else if buttonPressed == "button two" {
            // Code here
            }
        }
```
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D 

## Credits
Tom Swindell
## License
MIT license


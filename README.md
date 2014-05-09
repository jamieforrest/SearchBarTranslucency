SearchBarTranslucency
=====================
### Summary:
I am trying to set the barTintColor of a UISearchBar without translucency. However, setting the translucent property doesn't seem to do anything. I have reproduced the issue in a bare-bones Xcode project here.


### Steps to Reproduce:
1. Create a new iOS "Single View" app
2. Add a UITableView to the UIViewController in the storyboard
3. Add a UISearchBar & UISearchDisplayController to the UITableView in Interface Builder
4. In ViewController.m's viewDidLoad, set the translucency of the searchDisplayController's searchBar to NO, and set the barTintColor of the same searchBar to any color. 

### Expected Results:
The searchBar's barTintColor should be a solid color with no translucency.

### Actual Results:
The searchBar's barTintColor still has translucency.

### Version:
7.0, 7.1

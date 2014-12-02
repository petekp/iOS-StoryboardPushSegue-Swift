Very basic Push segue between two scenes using the Storyboard interface. The unwind/back action requires this code in the initial ViewController:

```swift
@IBAction func unwindSegue(segue: UIStoryboardSegue) {
      
}
```
This will now be accessible in the Exit dialog (right click the Exit icon on the Storyboard panel) which can be connected (cmd-drag) to a button in the scene.

![example movie](http://cl.ly/430J3V3x232K/Screen%20Recording%202014-12-01%20at%2004.19%20PM.mov)

Very basic Push segue between two scenes using the Storyboard interface. The unwind/back action requires this IBAction in the root ViewController class:

```swift
@IBAction func unwindSegue(segue: UIStoryboardSegue) {
      
}
```
In Storyboard, add a button to the destination scene and cmd-drag from it to the Exit icon on the top bar. When prompted, select 'unwindSegue'.

![example movie](http://cl.ly/image/0D3A1S2j3Q43/pushsegueexample.gif)

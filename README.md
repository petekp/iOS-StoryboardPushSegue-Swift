This is an example of a basic Push segue between two scenes using Storyboard and Swift. The title bar has been removed from the Navigation Controller to provide a full canvas for static comps. Useful for quick flow prototyping.

## How it works

Enabling the unwind/back function requires this IBAction be placed in the root ViewController class:

```swift
@IBAction func unwindSegue(segue: UIStoryboardSegue) {

}
```
In Storyboard, add a button to the destination scene and ctrl-drag it to the Exit icon in the scene's control bar. When prompted to select an Action Segue, select 'unwindSegue'.

![example movie](http://cl.ly/image/0D3A1S2j3Q43/pushsegueexample.gif)
# MKOutlinedLabelNode
Draw outlined text in SpriteKit. Currently only SKLabelHorizontalAlignmentMode.Center is supported. But it shouldn't be too hard to support all alignment modes. We just have to position the border depending on the alignment mode.

Usage
-----
```swift
let textNode = MKOutlinedLabelNode(fontNamed: "Helvetica", fontSize: 32)
textNode.borderColor = UIColor.blackColor()
textNode.horizontalAlignmentMode = SKLabelHorizontalAlignmentMode.Center
textNode.fontColor = UIColor.blueColor()
textNode.outlinedText = "Test"
```

Screenshot
----------

![Screenshot](https://raw.githubusercontent.com/marioklaver/MKOutlinedLabelNode/master/OutlinedText.png)

License
-------
[MIT](https://github.com/marioklaver/MKOutlinedLabelNode/blob/master/LICENSE)

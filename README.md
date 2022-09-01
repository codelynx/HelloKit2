#  xcframework

This project demonstrate how to provide xcframework for both simulator and iphoneos.
You may select target 'xcframework' to produce xcframework under build folder.
Be aware all in build folder will be deleted before producing building xcframework

This HelloKit provides very minimal functionality in HelloKit2 as follows.  So when client app implemented this feature and
"Hello form Swift" was printed on thier console then that's it... nothing more, nothing less.

```.swift
open class SwiftyHello {
	public init() {
	}
    public func hello() {
		print("Hello from Swift")
    }
}
```


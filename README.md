# swift_pretty_print_json

```swift
            let json = try? JSONSerialization.jsonObject(with: data!)
            let jsonData = try? JSONSerialization.data(withJSONObject: json, options: .prettyPrinted)
            print("JSON Pretty Printed: ", String(decoding: jsonData!, as: UTF8.self))
```

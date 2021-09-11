# Blog title
This is a *test* blog
Below is a **test code**
```swift
var body: some View {
        ZStack(alignment: .center) {
            Image("EmptyListBackground")
                .opacity(0.4)
            
            VStack(alignment: .center, spacing: 20) {
                Text("Welcome to SafeBox!")
                    .font(.title)
                Text("Add your first record")
                    .font(.title2)
            }//: VSTACK
            .padding(.horizontal)
        }//: ZSTACK
    }
```

# swift-ui-can-you-help-me-with-my-code-
import SwiftUI  struct ContentView: View {     @State var countNumber = 0     @State var Test = "hi"               var body: some View {         VStack {                          Text (String(countNumber))             .font(.largeTitle)                          Text(String(Test))                          if countNumber > 34 {                                  Test = "bye"                              }                                                    Button("Click") {                                  countNumber += 1                              }                                                }     } }

### Hi there, I'm Xavier Camps 👋

[![Linkedin: xaviercampsnovi](https://img.shields.io/badge/-xaviercampsnovi-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/xaviercampsnovi/)](https://www.linkedin.com/in/xaviercampsnovi/)
[![GitHub xaviercamps](https://img.shields.io/github/followers/xaviercamps?label=follow&style=social)](https://github.com/xaviercamps)

```swift
struct ImDeveloper {
    let name: String
    let birthdate: Int
    let role: String
    let location: String
    let knowleadges: [String]
    
    func simpleDescription() -> String {
        let description = """
            My name is \(name). I was born in \(location) in \(birthdate).
            I'm an \(role) and my knowleadges developing apps are:
            \(knowleadges).
        """
        return description
    }
}

let xavier = ImDeveloper(name: "Xavier",
                         birthdate: 1988,
                         role: "iOS Developer",
                         location: "Barcelona",
                         knowleadges: ["Swift, Objective-C, UIKit, SwiftUI, Combine"])

print(xavier.simpleDescription())
```


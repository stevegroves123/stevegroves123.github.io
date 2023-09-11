## Welcome to Stevegroves123

You can use the [editor on GitHub](https://github.com/stevegroves123/stevegroves123.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

Click on [here](https://github.com/stevegroves123/stevegroves123.github.io/blob/main/json/tesco.json)

### About Me

> I am an old, daft and slightly mad guy who like to be creative, 
> either using electronics to create silly gadets or software to create Apple IOS or WatchIOS apps.

An example of one silly creation is [Water app for Apple Watch](https://github.com/stevegroves123/WaterLog)

For playing with virtual electronics I use TinkerCad.[stevegroves123](https://www.tinkercad.com/login)

```swift
import UIKit

enum Result {
    case Success(score: Int)
    case Failure(score: Int)
}

let scored = 1

switch scored {
case 0..<75:
    let examResult = Result.Failure(score: scored)
    print(examResult)
case 75...100:
    let examResult = Result.Success(score: scored)
    print(examResult)
default:
    let examResult = "Unknown score"
    print(examResult)
}
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

# TicTacToe
## Installation

To install this package, import 'https://github.com/diasyerlan/TicTacToe' in SPM.

## Usage example

```swift

import UIKit
import CurrentCity

class ViewController: UIViewController {
    
    override func viewDidLoad() {
        super.viewDidLoad()

        // Initialize the LocationViewController
        let vc = TicTacToeViewController()

        // Add it as a child view controller
        addChild(vc)
        vc.view.frame = view.bounds
        view.addSubview(vc.view)
        vc.didMove(toParent: self)
    }
}

```

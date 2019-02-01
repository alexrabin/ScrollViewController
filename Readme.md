# ScrollViewController

ScrollViewController allows you to easily create a UIViewController with a scrollview that moves the content of the scrollview when the keyboard shows up.

## How To Use
Create a ViewController of Subclass ScrollViewController and thats it.
 ```
 class ViewController : ScrollViewController{
    
    override func viewDidLoad() {
        super.viewDidLoad()
        
        //Change attributes of the scrollview here
        self.scrollView.backgroundColor = .blue
        
        
    }
    override func viewWillAppear(_ animated: Bool) {
        super.viewWillAppear(animated)
    }
    override func viewWillDisappear(_ animated: Bool) {
        super.viewWillDisappear(animated)
    }
}
 ```

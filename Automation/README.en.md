# LowCode
Software to automate tasks, configurable in a "no code" way. Created to make it easy to add new features. <br>
I created this software to have an easy way to create automations without having to create a new program each time. <br>

What it does:
* You can place as much nodes as yout want, they will run one after the other
* Nodes are:
   * Wait: wait for a certain amount of time (in seconds) or a specific hour
   * Keyboard: simulate a key tap/press/release (or multiple keys)
   * Mouse: simulate a mouse move/click/scoll
   * Clipboard: copy something to the clipboard
   * Url: open a web page
   * Clicker: use image recognition to locate an element on the page, and click on it
   * If-Input: wait for a specific input from the user to continue running the nodes, can wait:
        * only the first time this node is encounter
        * each time the node is encounter
        * only the first time, until the input is detected again, and so on
* Nodes can be dragged and dropped easier use
* You can activate the writing of the node in the logs (if you want to store it later)
* The succession of nodes can be stored in a file to be loaded later
* In case of emergency, you can press a key three times (fast) to trigger the end of the loop (escape by default)
<br>

![LowCode](sources/Low-Code.gif)

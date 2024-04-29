<h1>DragList SwiftUI</h1>

<p>This repository showcases a generic drag list implemented in SwiftUI for iOS. The drag list allows users to reorder list items by dragging and dropping them into the desired position. This implementation leverages the powerful features of SwiftUI, enabling easy customization and integration into iOS apps.</p>

<h2>Key Features:</h2>
<ul>
  <li><strong>Intuitive Reordering:</strong> Users can intuitively reorder list items by dragging them with a drag gesture.</li>
  <li><strong>Simple Customization:</strong> The list is designed to be highly customizable, allowing developers to specify the content of list items through a closure.</li>
  <li><strong>SwiftUI Compatibility:</strong> It harnesses SwiftUI features for an efficient and modern implementation.</li>
</ul>

<h2>Project Structure:</h2>
<ul>
  <li><strong>DragList.swift:</strong> The main component implementing the generic drag list.</li>
  <li><strong>DropViewDelegate.swift:</strong> A SwiftUI drop delegate that handles drop operations, proposing a move operation when a drop enters, performing the drop action by swapping items, and animating the rearrangement of items in the drop target.</li>
</ul>

<h2>How to Use:</h2>
<p>To integrate the generic drag list into your SwiftUI iOS projects, follow these steps:</p>
<ol>
  <li>Add the <strong>DragList.swift</strong> file to your project.</li>
  <li>Define the model for list items by extending <strong>DragListItem</strong>.</li>
  <li>Use <strong>DragList</strong> in your SwiftUI view, passing the list of items and a closure to determine the content of each item.</li>
</ol>
<pre><code>
DragList(items: myItems) { item in
    // Customize the content of the item here
}
</code></pre>

<h2>Contribution:</h2>
<p>We welcome contributions and enhancements! If you have ideas on how to make this drag list even more powerful or if you encounter any bugs, feel free to submit a pull request or open an issue.</p>

<p>We hope this generic drag list proves useful in your SwiftUI projects!</p>

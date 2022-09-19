# UnityDrag3DObject
 
![ezgif-3-6694da71a1](https://user-images.githubusercontent.com/10281005/191072185-2f624b2e-c101-4369-9733-28cda87a8445.gif)

## Version

2021.3.9f1

## Explanation

You can see entire logic in Draggable.cs

OnMouseDown - Create a new GameObject DragAnchor and set the coordinates to raycastHit coordinates. Set the parent of the clicked object to DragAnchor.

OnMouseUp - Nullify parent and destroy DragAnchor

OnMouseDrag - Use ternary search to move the DragAnchor to the dragged position.

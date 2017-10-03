## Intention

I was looking for a box for playing cards (for Settlers of Catan), but didn't find what I was looking for. So I thought, this would be a good reason to lean OpenSCAD and make a customizable box.

## The Result

The OpenSCAD design let you create a box and a cover. You can customize the box size by the inner dimensions of the box. The cover can be flipped around the box to create a stand for the cards or whatever you put in.

Further you can create boxes with more than one tray. If you select more than one for `pocketCount` a wider box with additional space is created. I uploaded an example STL file for this.

The wall width can also be modified, but the default of 1.5mm is a good value for most smaller boxes.
 
## Examples

The pictures show my example prints. The black, small one was the first prototype for SD cards. The white one is an business card box. The red one is a single card box for cards of "Settlers of Catan".  

The provided JSON file contains parameters for the boxes in the photos. Please keep in mind, that the business card box are for german business cards. You may use other dimensions in other countries.

## Issues

If you create a very thin box (which means the hight of the box is less than 10mm), the half round cuts in the cover become very small. This leads to a cover that it's tricky to open. I think I will modify this in the next version.

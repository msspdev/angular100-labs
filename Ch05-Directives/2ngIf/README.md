# Chapter 5 Directives: ngIf

## Objectives

- Use ngIf to display a For Sale message if the album is on sale

## Steps

1. Copy the sale icon image form this folder to your projects assets folder

2. In your albumCard template, use ngIf to display the onsale image if on_sale == true

   ```html
   <img
     *ngIf="album.on_sale"
     src="assets/img/sale.png"
     style="width:40px;height:40px;"
   />
   ```

3. Compare the data against what is on the screen. Which items are on sale, is there an image for the sale appearing?

4. Once you have this working, mark your work as complete.
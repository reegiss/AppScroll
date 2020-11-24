# AppScroll
Exemplo scrollview


1 - Add UIScrollView and pin it 0,0,0,0 to superview (or your desired size)

2 - Add UIView in ScrollView, pin it 0,0,0,0 to all 4 sides and center it horizontally and vertically.

3 - In size inspector, change bottom and align center Y priority to 250. (for horizontal scroll change trailing and align center X)

4 - Add all views that you need into this view. Don't forget to set the bottom constraint on the lowest view.

5 - Select the UIScrollView, select the size inspector and deselect Content Layout Guides.

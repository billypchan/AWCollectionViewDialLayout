AWCollectionViewDialLayout
==========================

UICollectionViewLayout for displaying cells in a semi-circle with a height visual display. Also suitable for distance or strength visualization for large amount of data.

Very handy for quickly browsing items with your left thumb without having some of the content hidden behind your finger while you scroll.

* * *
Usage:
* * *
```
// Radius : The radius of your circle
// Angular spacing: Angle between items (deg)
// Cell Size: Size of your cell
// Alignment: Supports 2 Types: WHEELALIGNMENTLEFT and WHEELALIGNMENTCENTER
// X-Offset: To translate the circle along the x-axis

AWCollectionViewDialLayout *dialLayout = [[AWCollectionViewDialLayout alloc] initWithRadius:300.0  andAngularSpacing:18.0 andCellSize:CGSizeMake(240, 100) andAlignment:WHEELALIGNMENTCENTER andItemHeight:100  andXOffset:70];
```

* * *
Screenshots:
* * *
![Screenshot 1](https://github.com/billypchan/AWCollectionViewDialLayout/blob/master/AWCollectionViewDialLayoutDemo/awcollectionviewdiallayout_Height.png =320x)


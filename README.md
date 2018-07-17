### UITableView Infinite Scrolling

![Poster](https://koenig-media.raywenderlich.com/uploads/2018/04/UITableViewInfiniteScrolling-feature.png)

Infinite scrolling allows users to load content continuously, eliminating the need for pagination. The app loads some initial data and then adds the rest of the information when the user reaches the bottom of the visible content.

Social media companies like Twitter and Facebook have made this technique popular over the years. If you look at their mobile applications, you can see infinite scrolling in action.


To improve the app experience, you’ll use the Prefetching API introduced by Apple in iOS 10 for both UITableView and UICollectionView. 
This is an adaptive technology that performs optimizations targeted to improve scrolling performances. Data source prefetching provides a mechanism to prepare data before you need to display it. 
For large data sources where fetching the information takes time, implementing this technology can have a dramatic impact on user experience.

From [UITableView Infinite Scrolling](https://www.raywenderlich.com/187041/uitableview-infinite-scrolling-tutorial)
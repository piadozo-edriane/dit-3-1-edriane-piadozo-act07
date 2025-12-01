## What did you learn about using fragments and navigation components
 - Navigation Graph (nav_graph.xml) acts as the central hub defining all possible navigation paths
 - Fragments have their own lifecycle separate from Activity

## How much did you make your UI adaptive to screen size orientation
- Resource Qualifiers (layout-sw600dp)
- Created separate layouts for tablets (600dp+ smallest width)
- Phone layouts: 16-24dp padding, 16-32sp text sizes
- Tablet layouts: 48dp padding, 24-48sp text sizes
- Automatically switches based on device screen size

## What challenges did you face when combining Bottom Navigation and Tabs
- ProfileFragment contains ViewPager2 which hosts other fragments (InfoTab, GalleryTab)
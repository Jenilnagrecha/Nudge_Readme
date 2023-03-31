## Libraries
Standard Flutter libraries
  * Use showDialog() from flutter to display banner<br/>
  * Proivder(For Future Expansion)
  * If It  was mentioned to not to use  showDaialog then I would have Used Provier with change notifiers and Stack to adding a banner
 
## Repo link
  [Repo](https://github.com/Jenilnagrecha/nudge_task/)
  
## Video
https://user-images.githubusercontent.com/75077531/229159279-6d330bfd-fe84-4107-947d-bd006f958408.mp4

## More Description

About Single funiction:

As Mentioned in question 2 Screen and a single resuable componenet
Single Reusable class:PopUpandNavigation

How to use:
PopUpandNavigation popnav = PopUpandNavigation();
    popnav.goToNewPage(context, NexPage),
    popnav.showPopupBanner(context,width,RequiredBannerWidget,)

This could be rendered anywhere in project and to prove it i've added it to new page's center text<br />
Implemented it in home page as per requirement 
<br />
<br />

About Code:

Used ShowDialog() to show baner onclick
and Navigatior for changing page

If it was asked to implement it without usng ShowDialog then I would havee implemented it with Adding that banner in stack and using Provider State controller and Change notifier kind of class.

Have standard contant resusabe widgits in seperate file

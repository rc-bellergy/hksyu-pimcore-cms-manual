# Interface of the CMS 

- [Sidebar](#sidebar)
    - [Quick Open Document / Asset / Data Object](#quick-open-document-asset-data-object)
    - [Translation](#translation)
    - [Recycle bin](#recycle-bin)
    - [Search Engine Optimization](#search-engine-optimization)
    - [Cache](#cache)
    - [Search](#search)
- [Panel Tree](#panel-tree)
- [Toolbar](#toolbar)
- [Tabbar](#tabbar)

![](images/b01-1.png)  

Introducing most commonly feature in each of these areas.




## Sidebar

There are six areas that you use commonly in sidebar.
(File, Tools, Marketing, Settings, Search, Logout)


![](images/b02.png ':size=150x')



### Quick Open Document / Asset / Data Object

![](images/b03.png)

The editor can enter the file’s ID or the path (also full path) to open the file(Document / Assets / URL).


| ![](images/b04.png) 	| ![](images/b05.png) 	|
|:-------------------:	|:-------------------:	|

> How to find the file’s ID, please [click here](#LINK_TO)  

> To search by keywords, please [click here](#search)


### Translation

If your website supports multi-languages, Pimcore provides an easy way for editors to edit commonly used translation terms across the application, such as non-article,  which can be found here:  

`Tools` > `Translations` > `Shared Translations`.

![](images/b06.png)

![](images/b07.png)

(Available languages are defined within the system languages)

> How to translate the article, please [click here](data-objects)



### Recycle bin

All the files were sent to recycle bin when they were deleted.

![](images/b08.png)

> How to detele the file, please [click here](#LINK_TO)  

> For more information on operation in recycle bin, please [click here](basic/recycle-bin)



### Search Engine Optimization

![](images/b12.1.png)

SEO stands for "Search Engine Optimization". It repetitive process used to send signals to search engines that your website is worth being listed in Google's index.

The editor can make further SEO relevant settings for each Pimcore document. 

Two places that the editor can make SEO setting:

- **For Global Pimcore Document in the sidebar**  
`Tools` > `Search Engine Optimiztion` > `SEO Document Editor`

![](images/b10.png)

Double click the document.

![](images/b11.png)

Edit the "Title" and "Description" and click the "Save" button

![](images/b12.png)

- **For Each Pimcore Ddocument in the panel tree**   
`Open the desired document` > `navigate to the "SEO & Settings" tab`

![](images/b12.2.png)

At the top of this tab is the "Title & Description" section. Title and description must always be filled in, whereby HTML tags are to be regarded as optional. The title describes the page in one or a few words and the description summarizes the content of the page briefly and concisely. The title should not exceed a character length of 60 characters and the character length of the description should not pass the mark 170.

**About Pretty URL** 

The Pretty URL setting overrides a document's full path only for the purpose of routing. This is useful for when you would like to create shorter paths or friendly URLs for sharing. A Pretty URL does not redirect to the original URL.

Here is example.  
Original URL: https://demo.com/about/our-story/aticle/123

Fill the "our-story-123" in pretty url field.

Pretty URL: https://demo.com/our-story-123

### Cache

Pimcore uses extensively caches for differently types of data. The primary cache is a pure object cache where every element (document, asset, object) in Pimcore is cached as it is (serialized objects). Every cache item is tagged with dependencies so the system is able to evict dependent objects if a referenced object changes.


![](images/b13.png)

> For more information on operation in cache section, please [click here](basic/cache)

### Search

The editor can search by Quick Search (All) / Document / Assets / Data Object

Quick Search(All)

![](images/b16.png)

![](images/b17.png)

Search Document / Assets / Data Object

![](images/b18.png)

![](images/b19.png)

> For more information on operation in search, please [click here](basic/search)

## Panel Tree




## Toolbar

There are highlight features in the Toolbar.




### Tabbar

There are highlight features in the Tabbar.
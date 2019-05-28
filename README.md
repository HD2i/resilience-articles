# resilience-articles

This is the repository for articles for the Resilience iOS app. Adding, updating, and modifying articles is done within Articles.json and should be self explanatory. 

When adding a new article, add it to the top and follow the format of previous articles. 

Below are numbered labels to illustrtate what each key-value corresponds to in an article:

```
 {
            "title"       : 1 (Title of article),
            "abstract"    : 2 (Abstract of article),
            "imageNames"  : 3 (Name of image used on Resilience website),
            "imageIsLight": 4 (Color of X- 0 is black and 1 is white),
            "date"        : 5 (Date of article of form JAN 1, 2000),
            "url"         : 6 (URL of article on website),
            "storyType"   : 7 (Story type, for example: Resilience Story, Learn, etc.),
            "moreTitle"   : 8 (Text for "Read More"),
            "sections"    : [
                                   {
                                   "imageNames"         : 9 (Name of the image used on the Resilience website),
                                   "imageText"          : 10 (Name of the image, overlaid on the image),
                                   "text"               : 11 (Text for this section),
                                   "embeddedTextLinks"  : [
                                                           {
                                                           "linkText": 12 (Text you want to have hyperlinked),
                                                           "linkUrlString": (Enter the url for the link)
                                                           }
                                                           ]
                                   },
                                   {
                                   "text"               : 13 (Text for this section),
                                   "showTopRule"       : 1
                                   },
                                   {
                                   "title"              : 14 (Enter text associated with button),
                                   "titleAlignment"     : (0 for left aligned, 1 for center aligned and 2 for right aligned, if this key-value is not defined the default is center aligned),
                                   "buttonTitle"        : 15 (Enter text in button),
                                   "actionType"         : (Should only be "link", other action types will need changes to iOS app),
                                   "actionValue"        : (URL of link),
                                   "showTopRule"        : 1
                                   },
                                   {
                                   "text"               : 16 (Text for this section),
                                   "showTopRule"        : 1
                                   },
                                   {
                                   "title"              : 17 (Enter text associated with button),
                                   "buttonTitle"        : 18 (Enter text in button),
                                   "actionType"         : (Should only be "link", other action types will need changes to iOS app),
                                   "actionValue"        : (URL of link),
                                   "showTopRule"        : 1
                                   },
                                   {
                                   "text"   : 19 (Text for section),
                                   "showTopRule"    : 1
                                   },
                                   {
                                   "type"              : 20 (Type of section, in this case: "references"),
                                   "title"             : 21 (Title of section),
                                   "titleAlignment"    : (0 for left aligned, 1 for center aligned and 2 for right aligned, if this key-value is not defined the default is center aligned),
                                   "text"              : 22 (Text of references, each reference seperated by two line breaks),
                                   "showTopRule"       : 1,
                                   "embeddedTextLinks" : [
                                                          {
                                                          "linkText": 23 (Text you want to have hyperlinked),
                                                          "linkUrlString": (URL of hyperlink)
                                                          },
                                                          {
                                                          "linkText": 24 (Text you want to have hyperlinked),
                                                          "linkUrlString": (URL of hyperlink)
                                                          },
                                                          {
                                                          "linkText": 25 (Text you want to have hyperlinked),
                                                          "linkUrlString": (URL of hyperlink)
                                                          }
                                                          ]
                                   },
                                   {
                                   "type"              : 26 (Type of section, in this case: "photoCredit"),
                                   "title"             : 27 (Title of section),
                                   "titleAlignment"    : (0 for left aligned, 1 for center aligned and 2 for right aligned, if this key-value is not defined the default is center aligned),
                                   "text"              : 28 (Text of Photo Credit, each credit seperated by two line breaks),
                                   "embeddedTextLinks" : [
                                                          {
                                                          "linkText": 30 (Text you want to have hyperlinked),
                                                          "linkUrlString": (URL of hyperlink)
                                                          }
                                                          ]
                                   }
                                   ]
                  }
```

